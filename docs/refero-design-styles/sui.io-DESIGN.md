# Sui — electric machine horizons

## Overview

A cinematic infrastructure style that alternates black technical stages with stark white editorial fields. Regular grotesk typography feels unusually tightly fitted, while small monospaced markings, dotted rules and square blue controls give the page an engineered character. Blue-lit abstract geometry and grainy light horizons supply spectacle without making the information panels decorative or dense. It suits ambitious platforms and technical products that need both an expansive promise and concrete explanations.

### Essentials

- A tunnel-sized promise rather than a dashboard hero: a full-width 900px dark stage, centered 90px/1 regular headline with -0.065em tracking, a 20px support line and two adjacent 48px rectangular actions near the bottom.
- Headlines feel fitted together, not heavy: weight 400 throughout, 90px/1 with -0.06em tracking for chapter displays and 78px/1.1 with -0.05em tracking for a full-width editorial statement.
- Color behaves like machine illumination: black and white occupy the major page fields; #298dff is concentrated into 12px markers, square arrows, compact actions and atmospheric blue light rather than repeated full-color sections.
- Controls and panels have cut-square geometry: 0px corners, 8px or 16px grid gutters, 16px card padding and no drop shadows. Primary actions are blue rectangles; a paired secondary action is white with black text.
- Technical markings bind the storytelling: 12px monospaced label strips, dotted dividers and short elbow connectors appear alongside large human-readable text. Carry these devices into every new page, even when the product is not developer-facing.
- The page ends in light, not just links: a four-column black directory leads into a full-bleed 520px grainy blue-to-white horizon divided into stepped vertical bays. Recreate the light field with gradients and noise when custom artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#298dff` | `--color-blue` | accent, action, link | Primary actions, square markers, arrow controls and illuminated artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black stage | `#000000` | `--color-black` | background, text | Dark chapters, hero negative space, footer and text on white. |
| Charcoal panel | `#131518` | `--color-panel` | surface, background, border | Navigation and dark cards; matching card borders disappear into the panel. |
| Control edge | `#343940` | `--color-edge` | border, surface | Square icon backings and fine dark control outlines. |
| Technical gray | `#6c7584` | `--color-muted` | text, surface | Secondary descriptions, footer links and square social controls. |
| Silver support | `#d4d4d4` | `--color-hero-support` | text | Support line on the cinematic opening. |
| Label strip | `#e0e2e6` | `--color-label` | surface | Small monospaced labels on the white editorial field. |
| Mist panel | `#f4f5f7` | `--color-light-panel` | surface | Benefit strips and information cards on white sections. |
| White field | `#ffffff` | `--color-white` | background, text, action | Editorial sections, text on dark fields and the inverse secondary action. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| resource and trust pages | Resource gray | `#67707e` | `--color-resource-gray` | text, surface | Large utility link labels and verification tags. |
| topic landing pages | Topic strip | `#c2c6cd` | `--color-topic-label` | surface | Uppercase category labels above product-topic chapters. |

## Typography

- **TWK Everett** — All display, headings, descriptions and action labels. Regular neo-grotesk with open counters and tightly joined headline spacing. If unavailable, use **Inter**. Use weight 400 and retain tight tracking; check headline wrapping. Font stack: "TWK Everett", "Inter", Arial, sans-serif.
- **TWK Everett Mono** — Technical markings, label strips, diagram captions and footer directory. Small mechanical monospace, usually regular and compact. If unavailable, use **IBM Plex Mono**. Use weight 400; preserve small label sizes. Font stack: "TWK Everett Mono", "IBM Plex Mono", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | TWK Everett | 400 | 90px | 1 | -0.065em | Default cinematic opening headline. |
| display | TWK Everett | 400 | 90px | 1 | -0.06em | Major chapter statements and centered closing editorial headline; also topic-page hero headings. |
| editorial | TWK Everett | 400 | 78px | 1.1 | -0.05em | Large flowing argument on white; also centered instructional statements. |
| stat | TWK Everett | 400 | 69px | 1.1 | -0.0431em | Prominent single metric in the editorial mosaic. |
| heading-lg | TWK Everett | 400 | 60px | 1.1 | -0.05em | Chapter headings and action-path titles. |
| heading | TWK Everett | 400 | 44px | 1.1 | -0.05em | Paired audience or comparison headings. |
| hero-support | TWK Everett | 400 | 20px | 1.4 | -0.02em | Single centered explanatory line beneath the default hero. |
| body | TWK Everett | 400 | 18px | 1.4 | -0.02em | Benefit copy, main paragraphs and resource-card titles. |
| wide-action | TWK Everett | 400 | 18px | 0.95 | -0.02em | Labels in wide action-path bars. |
| mosaic-title | TWK Everett | 400 | 15px | 1.4 | -0.01875em | Compact linked story titles beside thumbnails. |
| action | TWK Everett | 400 | 14px | 1.25 | -0.005em | Compact opening actions and card links. |
| footer-label | TWK Everett Mono | 400 | 14px | 1.1 | 0.0175em, uppercase | Directory group headings; accompanying links use muted mixed-case mono treatment. |
| diagram-caption | TWK Everett Mono | 400 | 14px | 1.4 | -0.02em | Numbered technical diagram annotations. |
| label | TWK Everett Mono | 400 | 12px | 1 | -0.03em | Sentence-case editorial label strips. |
| micro-label | TWK Everett Mono | 400 | 10px | 1.2 | -0.00625em, uppercase | Metric qualifiers and compact mosaic labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| topic and trust landing pages | topic-display | TWK Everett | 400 | 80px | 1.1 | -0.05em | Broad left-aligned chapter statements on white. |
| resource and trust pages | resource-link | TWK Everett | 400 | 24px | 0.8 | -0.015em | Large utility links preceded by elbow connectors. |
| topic landing pages | topic-detail | TWK Everett | 400 | 15px | 1.4 | -0.005em | Dense feature descriptions beneath compact titles. |
| topic and trust landing pages | topic-label | TWK Everett Mono | 400 | 12px | 1.25 | normal, uppercase | Small category chips above topic chapters. |

**Notes:**

- Keep the display family at regular weight: size, line breaks and unusually negative spacing provide authority without bold cuts.
- Use 90px for major centered statements, 78px for continuous editorial argument, 60px for section navigation and 44px for paired headings. Do not flatten these into one heading size.
- Mono labels are tiny counterweights to the oversized grotesk. They should look like attached markings, not competing headlines.

## Layout

**Density:** Airy between chapters, compact inside the information machinery: expansive black stages and 128px–210px section offsets surround cards with narrow gutters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight repeated-row and three-column card gutters. |
| 10px | Blue marker to benefit text. |
| 16px | Default card padding and two-column grid gap. |
| 20px | Desktop outer gutter and footer column gap. |
| 24px | Internal card groups and arrow-to-copy clusters. |
| 30px | Editorial label to large argument. |
| 32px | Opening headline group spacing and benefit-strip vertical padding. |
| 40px | Action-path copy to action bar. |
| 64px | Closing heading to editorial mosaic. |
| 112px | Footer directory to social cluster. |
| 128px | Trust chapter top padding and major closing separation. |
| 140px | Topic chapter top padding. |
| 160px | Major chapter heading-to-content separation. |
| 184px | Editorial mosaic chapter top and bottom padding. |
| 210px | Default white editorial argument top offset. |

### Containers and grids

- **main container**: max width 1400px · side padding 20px. Centered near-edge desktop content; at 1440px the usable field is 1400px wide.
- **paired grid**: 2 columns · gap 16px. Audience comparisons, capability panels and action pathways; equal desktop columns.
- **compact grid**: 3 columns · gap 8px. Feature, directory and report cards.
- **editorial mosaic**: max width 940px · gap 8px. Centered closing cluster of articles, portrait-format media, one wide metric and social tiles.
- **footer directory**: 4 columns · gap 20px. Broad directory columns across the main container.
- **technical grid** (only for platform architecture chapters): 4 columns · gap 16px. Equal-width illustrated module cards.
- **resource rail** (only for resource chapters): gap 8px. 338px-wide cards in a horizontal rail with a partial next card visible; 230px card height.

## Corner radius

| Element | Radius |
| --- | --- |
| panels and controls | 0px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default hero, technical narrative chapters and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black fields make room for luminous geometry; not every dark section contains artwork.

**Transfer:** Use black as both negative space and the backing for explanatory diagrams.

#### White editorial field · level 0

**Use:** Large arguments and benefit chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** A hard full-width switch from black, not a floating light card.

**Transfer:** Change the whole field when the narrative moves from spectacle to explanation.

#### Dark panel · level 1

**Use:** Information cards and editorial tiles on black.

**CSS:** `background: #131518; border-radius: 0px; box-shadow: none`

**Observed:** Separation comes from a slightly raised neutral value and narrow black gutters, not shadows.

**Transfer:** Keep technical content flat and strongly grouped.

#### Light panel · level 1

**Use:** Repeated benefit and feature cards on white.

**CSS:** `background: #f4f5f7; border-radius: 0px; box-shadow: none`

**Observed:** Very pale neutral fill; dotted interior separators create the information structure.

**Transfer:** Use as a quiet backing for text and marker-based headers.

#### Dotted technical rule

**Use:** Chapter boundaries, card headers and comparison frames.

**CSS:** `height: 1px; background-image: radial-gradient(circle, rgba(108,117,132,0.7) 0.7px, transparent 0.8px); background-size: 10px 1px`

**Observed:** Sparse dots rather than continuous solid rules; vertical variants frame comparison columns.

**Transfer:** Apply as SVG or CSS dot rows, leaving generous space around major chapter boundaries.

## Components

### Floating navigation

**Use:** Persistent global navigation above both light and dark fields.

**CSS:** `background: #131518; backdrop-filter: blur(12px); height: 64px; padding: 11.5px 16.5px; display: flex; justify-content: space-between; align-items: center; gap: 32px; border-radius: 0px`

**Text style:** `action` — TWK Everett 400 · 14px/1.25 · tracking -0.005em

**Observed:** Brand mark left, compact centered navigation with square plus or pictogram controls, blue conversion action right. The bar is fixed 8px below the top with 20px side gutters.

**Transfer:** Use a restrained number of categories; preserve the squared icon companions rather than chevrons in pills.

### Opening action pair

**Use:** Primary and secondary routes at the base of the cinematic opening.

**CSS:** `display: flex; height: 48px; border-radius: 0px; color: #ffffff`

**Text style:** `action` — TWK Everett 400 · 14px/1.25 · tracking -0.005em

**Observed:** Two touching rectangles, blue then white with black text, form a centered cluster about 267px wide. Labels sit centered; neither is pill-shaped.

**Transfer:** Give each action similar visual width and keep the pair well below the headline group.

### Editorial label strip

**Use:** Small thematic marker above a broad editorial statement.

**CSS:** `background: #e0e2e6; color: #000000; padding: 6px; border-radius: 0px`

**Text style:** `label` — TWK Everett Mono 400 · 12px/1 · tracking -0.03em

**Observed:** A close-fitting gray strip, aligned to the left content edge rather than centered over the paragraph.

**Transfer:** Use one short explanatory phrase, not a promotional badge.

### Benefit strip

**Use:** One concise outcome in a paired benefit chapter.

**CSS:** `background: #f4f5f7; display: flex; align-items: center; gap: 10px; padding: 32px 0px 32px 24px; border-radius: 0px`

**Text style:** `body` — TWK Everett 400 · 18px/1.4 · tracking -0.02em

**Observed:** A 12px blue square precedes one line of dark copy. Repeated strips are 86px tall at desktop and separated by 8px.

**Transfer:** Keep benefits parallel and short enough to preserve the compact row.

### Capability panel

**Use:** Dark category card containing concrete capabilities and a destination link.

**CSS:** `background: #131518; padding: 16px; display: flex; flex-direction: column; justify-content: space-between; gap: 80px; border-radius: 0px`

**Text style:** `body` — TWK Everett 400 · 18px/1.4 · tracking -0.02em

**Observed:** Header pairs a category icon and title with a small logo group. A dotted rule separates the header from a short outcome list with blue elbow-line connectors. Desktop panels occupy a two-column grid and are about 692px by 418px.

**States:** Declared: hover background-color #222529 and color white; focus-visible not specified. Active outline 0px.

**Transfer:** Use a small coherent capability family per panel instead of a dense inventory.

### Wide action bar

**Use:** Destination under each large action-path title and support paragraph.

**CSS:** `background: #298dff; color: #ffffff; height: 40px; padding: 8px 7.5px 8px 8px; display: flex; align-items: center; gap: 12px; border-radius: 0px`

**Text style:** `wide-action` — TWK Everett 400 · 18px/0.95 · tracking -0.02em

**Observed:** A 24px square arrow leads the label; the bar spans its full half-column. It belongs beneath the right-hand explanatory copy opposite a 60px title.

**Transfer:** Use the complete rectangular footprint for the destination, not a small pill.

### Resource card

**Use:** Editorial resources in a horizontal rail.

**CSS:** `background: #f4f5f7; color: #000000; padding: 16px; max-width: 338px; height: 230px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px; border-radius: 0px`

**Text style:** `body` — TWK Everett 400 · 18px/1.4 · tracking -0.02em

**Observed:** Small source icon at top, dotted divider, generous middle space, title and short blue text link below. Dark chapters use the Dark panel surface instead.

**States:** Declared: hover background-color rgb(41, 141, 255) and color rgb(255, 255, 255); focus-visible not specified. Transition background-color and color 0.3s cubic-bezier(0.215, 0.61, 0.355, 1).

**Transfer:** Keep titles readable and use the available space as hierarchy rather than filling every card with an image.

### Metric tile

**Use:** One large live-looking proof point inside the closing editorial mosaic.

**CSS:** `background: #131518; padding: 8px; display: flex; flex-direction: column; gap: 18px; border-radius: 0px`

**Text style:** `stat` — TWK Everett 400 · 69px/1.1 · tracking -0.0431em

**Observed:** A tiny uppercase mono qualifier sits above an oversized unbolded number; the tile is wide and shallow, about 650px by 122px.

**Transfer:** Use a relevant substantiated metric, with its unit or definition in the micro-label.

### Social square

**Use:** Footer social destinations.

**CSS:** `background: #6c7584; color: #000000; width: 32px; height: 32px; padding: 7px; display: flex; justify-content: center; align-items: center; border-radius: 0px`

**Observed:** Solid platform glyphs sit in a left-aligned row with 8px gaps, above the small copyright line.

**States:** Declared: hover background-color #298dff and color white; focus-visible not specified. Transition background-color and color 0.2s cubic-bezier(0.645, 0.045, 0.355, 1).

**Transfer:** Use only actual community destinations.

### Elbow resource row

**Only for:** resource and trust pages

**Use:** Utility destinations in instructional and participation closings.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; padding: 8px 9px 8px 16px; height: 56px; color: #67707e; border-radius: 0px`

**Text style:** `resource-link` — TWK Everett 400 · 24px/0.8 · tracking -0.015em

**Observed:** An understated 32px by 8px elbow connector precedes a gray title, with no filled button backing. Rows stack without a gutter.

**Transfer:** Use a short list of practical next steps when conversion is participation rather than purchase.

## Imagery and graphics

### Radial machine-light stage

**Use:** Signature cinematic opening artwork.

**Observed:** Blue, silver and white rectangular beams radiate outward from a black central void. Length and thickness vary; close beams are broad and softly lit, distant beams thin. The scene fills the viewport while the center remains readable for white text.

**Transfer:** Represent the product's momentum with abstract illuminated structure rather than literal themed clip art. A static layered SVG tunnel with a dark center is the minimum acceptable equivalent.

**Build:** On black, distribute 70–100 tapered rectangular planes around a central elliptical void. Rotate each toward a shared vanishing point; vary length from 70px to 440px and thickness from 3px to 55px on a 1440px stage. Fill planes with gradients between rgba(41,141,255,0.75), rgba(255,255,255,0.65) and transparent; keep many planes dim. Layer a black elliptical mask over the center and a light grain texture above the art, below text.

### Stepped light horizon

**Use:** Signature full-width ending beneath the footer directory.

**Observed:** A luminous blue-to-white base rises into black through seven broad vertical bays. Their light climbs highest near the center, creating a stepped hill profile; dotted vertical seams and fine grain reveal the structure. The art is 1440px by 520px and touches both page edges.

**Transfer:** Retain this ending device with new content: it needs no product artwork or logo. Match the soft glow; exact stops are not essential.

**Build:** Use a 520px black field divided into seven equal-width SVG or CSS bays. Fill each from white at the bottom through #298dff to transparent black, with taller gradient extents in the central bay and progressively shorter extents toward the edges. Add 1px dotted vertical separators in rgba(255,255,255,0.4). Overlay procedural SVG turbulence at opacity 0.5 with soft-light blending.

### Editorial and partner media

**Use:** Proof rails and the closing mosaic.

**Observed:** Partner identities use flat saturated or black image panels, while event clips and urban photography remain naturally colored and rectangular. Small article thumbnails appear beside compact text in the mosaic; media stays inside square-edged layouts.

**Transfer:** Use authentic partner or product images for proof and real-world photographs for community activity; keep them subordinate to the larger monochrome page structure.

### Wireframe module diagrams

**Only for:** platform architecture chapters

**Use:** Explanatory artwork for linked technical modules.

**Observed:** Fine gray and blue isometric cubes, stacked planes and hourglass-like data geometry sit centered on charcoal rectangles. Sparse blue nodes, tiny labels and dotted projection grids suggest system architecture rather than shiny rendered objects. Each graphic occupies roughly a 336px by 277px field beneath its title and description.

**Transfer:** Map real functional relationships to simple wireframe forms. A crisp SVG of two or three related planes is preferable to a generic glossy 3D object.

**Build:** Draw an isometric grid with 1px rgba(108,117,132,0.5) strokes on #131518. Add a cube or stacked parallelograms using the same gray, then pick only several edges and nodes in rgba(41,141,255,0.8). Leave generous dark margins and use small mono annotations sparingly.

### Topic atmosphere

**Only for:** topic and trust openings

**Use:** Focused product-topic hero variants.

**Observed:** One variant frames black negative space with vertical blue-white light columns and a faint dotted grid; another centers a dim particle-like circular field behind the heading. Both keep the headline white and the support copy low on the stage.

**Transfer:** Use the column treatment for broad platform topics and restrained particles for assurance-focused narratives.

**Build:** For columns, alternate narrow vertical linear gradients fading from white through #298dff into transparent against black, mirrored at the top and bottom. Add a faint radial dot grid in rgba(108,117,132,0.2). For the circular variant, mask the same dot grid into a large soft-edged disk centered behind the text.

### Icons

**Observed:** Square-backed functional symbols dominate: 26px navigation pictograms, 24px action arrows, 32px module controls and 48px category icons. Line connectors use 2px butt-ended strokes; blue marks active destinations while white and gray handle structure.

**Transfer:** Choose geometric arrows, outlined category symbols and simple solid utility glyphs. Pair them with square backings or elbow connectors, not circular icon bubbles.

## Section recipes

How recurring sections are built.

### First screen: Cinematic tunnel opening

**Observed:** The first 900px is one edge-to-edge dark media stage, behind a floating navigation bar. Back to front: black void, radial blue/silver beam artwork, centered white headline and silver support line, then a touching blue-and-white Opening action pair near the lower edge. The 90px headline is one line spanning about half the viewport width; its text group sits slightly above the vertical midpoint. The support line follows with 32px group spacing. The 48px action pair sits roughly 63px above the stage bottom. Navigation, headline, support, actions and the full tunnel field are visible in the first screen; partner proof begins below the stage and a 128px white transition.

**Transfer:** Make the opening a single strong spatial metaphor around a readable central void. Without custom media, use the Radial machine-light stage SVG recipe. Topic openings retain the 90px centered statement but use Topic atmosphere, typically two headline lines and a lower two-line 18px support block rather than forcing the default action pair.

**Avoid:** Do not replace the immersive stage with a left-copy/right-screenshot split, a boxed illustration or a gradient-filled headline.

**Text style:** `hero` — TWK Everett 400 · 90px/1 · tracking -0.065em

### Editorial argument

**Observed:** White editorial field, 20px side gutters, close-fitting Editorial label strip and a 30px gap to a 78px continuous paragraph spanning the 1400px container. The statement behaves as a large piece of reading, not a stack of marketing cards.

**Transfer:** Explain the change in the reader's world in a short forceful argument. Preserve full-width wrapping and regular weight.

**Text style:** `editorial` — TWK Everett 400 · 78px/1.1 · tracking -0.05em

### Marked capability list

**Observed:** On a pale full-width field, an offset column carries 44px capability lines separated by dotted rules. Blue square icon blocks sit at the far right; a tiny bracketed arrow and mono label establish the technical frame.

**Transfer:** Use for a concise set of foundational properties. Keep the row language parallel and the artwork as secondary indexing.

### Technical spine

**Observed:** A centered 90px chapter title introduces a long black stage. Numbered Diagram-caption annotations alternate around a dotted vertical spine, with dark outlined mini-panels and small square nodes. The composition isolates one concept at a time rather than crowding a diagram into a conventional card.

**Transfer:** Present a small set of related system layers along a central spine; shorten the physical scroll length to suit the amount of real explanation.

**Text style:** `display` — TWK Everett 400 · 90px/1 · tracking -0.06em

### Paired benefit frame

**Observed:** Two equal white columns with dotted perimeter framing, centered 44px headings and four Benefit strips per column. The 16px column gap and 8px row gaps keep the machinery close while the title area remains tall.

**Transfer:** Compare two audiences or two sides of a workflow with equal emphasis; do not force an artificial winner.

**Text style:** `heading` — TWK Everett 400 · 44px/1.1 · tracking -0.05em

### Capability chapter and action paths

**Observed:** A centered two-line 90px chapter statement on black leads to two-column Capability panels. Below, action-path rows pair a 60px title on the left with 18px muted support and a Wide action bar on the right.

**Transfer:** Move from product possibilities to clear routes for different reader intentions. Adapt the number and placement of panels to the story.

**Text style:** `heading-lg` — TWK Everett 400 · 60px/1.1 · tracking -0.05em

### Editorial mosaic closing

**Observed:** A centered 940px content cluster on black has a 90px closing headline, short support and 64px space to an 8px-gutter mosaic. Three thumbnail story rows share the upper area with two portrait media tiles; below, a wide Metric tile sits beside two square social destinations. The chapter has 184px vertical padding.

**Transfer:** Assemble useful current resources, authentic media and one meaningful proof point into an editorial closing instead of another generic conversion banner.

**Text style:** `display` — TWK Everett 400 · 90px/1 · tracking -0.06em

### Directory and luminous ending

**Observed:** A dotted top boundary and small brand symbol introduce four directory columns on black. Uppercase mono group headings precede gray mixed-case links with elbow connectors. Social squares and copyright sit below, followed by the edge-to-edge Stepped light horizon. This is the final visual event, not a conventional white legal strip.

**Transfer:** Group the new product's information architecture into a few broad columns, then preserve the luminous ending independently of directory length.

**Text style:** `footer-label` — TWK Everett Mono 400 · 14px/1.1 · tracking 0.0175em · uppercase

### Topic feature field

**Only for:** topic landing pages

**Observed:** On white, a small uppercase chip leads to an 80px left-aligned chapter statement. A 160px chapter gap separates the statement from a three-column 8px-gutter field of pale cards with 16px padding, blue square title markers and descriptions anchored low in each card.

**Transfer:** Use for concrete applications of a focused product capability, with one readable outcome per card.

**Text style:** `topic-display` — TWK Everett 400 · 80px/1.1 · tracking -0.05em

### Resource rail

**Only for:** topic and trust pages

**Observed:** A 60px or 44px heading sits above a dotted rail with a short blue progress segment and square directional controls. Resource cards run horizontally with 8px gaps and a partial next card showing. White chapters use pale cards; black chapters use charcoal.

**Transfer:** Use a browsable set of deeper resources as a bridge into the directory, without requiring a separate conversion banner.

**Text style:** `heading-lg` — TWK Everett 400 · 60px/1.1 · tracking -0.05em

### Trust directory and participation closing

**Only for:** resource and trust pages

**Observed:** Dark chapters pair 60px left headings with support copy on the right, then three-column charcoal directory or report cards with 8px gutters. Cards contain compact identity headers, dotted rules, gray explanations, tags or dates and square arrow controls. The final participation block places a 60px heading left and four Elbow resource rows right, above the common directory footer.

**Transfer:** Make assurance tangible with actual partners, reports and practical contact routes. A utility-link ending is appropriate when readers need several different next steps.

**Text style:** `heading-lg` — TWK Everett 400 · 60px/1.1 · tracking -0.05em

### Light-to-dark horizon transition

**Only for:** resource and trust pages

**Observed:** A white instructional chapter uses a centered 78px heading, a large empty interval, dotted full-width divider and right-half explanatory copy with Elbow resource rows. A 450px white-to-blue-to-black gradient merges the bottom into the next dark chapter.

**Transfer:** Use a luminous horizon to shift from guidance into detailed technical proof, keeping the upper section readable and white.

**Text style:** `editorial` — TWK Everett 400 · 78px/1.1 · tracking -0.05em

## Page flow

**Storyline:** Immersive promise → explain the change → reveal the system → translate into outcomes → offer evidence and next steps → directory and luminous horizon.

### Broad platform marketing landing page

1. **Promise** — Full-screen radial stage, concise centered statement and paired actions.
2. **Social proof** — Compact partner identities on white.
3. **Argument** — Oversized editorial paragraph followed by a marked property list.
4. **System explanation** — Large centered title and a numbered technical spine on black.
5. **Benefits** — Equal paired audience frames on white.
6. **Applications and activation** — Dark capability panels followed by broad title-and-action rows.
7. **Ongoing proof** — Centered editorial mosaic with media, stories and a wide metric.
8. **Ending** — Four-column directory, social squares and stepped luminous horizon.

**Transfer:** Use the contrast between cinematic ambition and very plain explanations as the organizing principle; adjust the amount and order of proof to the product.

### Focused product-topic landing page

1. **Promise** — Blue-column atmospheric opening with centered two-line statement.
2. **Problem and resolution** — Large thematic title followed by equal challenge-and-solution columns with dark repeated cards.
3. **System explanation** — Four illustrated module columns with wireframe artwork.
4. **Applications** — White chapter with large statement and compact three-column cards.
5. **Proof** — Horizontal partner case-study rail.
6. **Further reading** — Light resource rail, immediately followed by the shared directory and light horizon.

**Transfer:** Keep a focused argument and use the illustrated system plus application cards to explain how the capability becomes useful; do not add a fictitious final CTA when resources are the useful next step.

### Trust and technical assurance landing page

1. **Promise** — Dark particle-field opening with a centered assurance statement and low support copy.
2. **Foundational proof** — White design-principle chapter with paired pale cards.
3. **Guidance** — White instructional statement, practical links and blue-to-black horizon transition.
4. **Technical detail** — Dark split-heading chapter and three linked explanatory cards.
5. **Independent proof** — Partner directory and recent report grids.
6. **Further reading** — Dark resource rail.
7. **Participation** — Split heading and elbow-link list before the shared directory and light horizon.

**Transfer:** Replace broad promotional claims with concrete mechanisms, independent verification and practical routes to help or participate.

## Writing

Confident, infrastructural and direct. The language presents ambitious change in plain words, then earns it through mechanisms, outcomes and practical resources rather than exuberant adjectives.

**Do not copy:** Do not reuse Sui names, logos, product marks, partner identities, financial values, technical guarantees, report titles, quotations or ecosystem claims. Source examples illustrate voice only; replace them with substantiated content for the new product.

- **Addressing the reader:** Use direct imperatives for actions and occasional you/your for reader outcomes. The product is named in declarative statements rather than narrated through a chatty first-person company voice.
- **Rhythm:** Short display statements contrast with occasional long editorial arguments. Supporting copy is usually one or two sentences; action labels are compact and literal. Parallel verbs make dense capability lists easy to scan.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short declarative location or future-facing statement. | 3–9 words | “Where AI transacts”<br>“Creating a trusted, verifiable AI future” |
| Support | Name the product's role and the practical kind of work it enables. | 9–18 words | “[Brand] is the infrastructure for trusted autonomous execution”<br>“Build private, autonomous, and economically coordinated AI without opaque intermediaries.” |
| Benefit | Verb-led concrete outcome, sometimes followed by a constraint. | 5–12 words | “Settle transactions without manual reconciliation.”<br>“Define policy once, enforced automatically wherever assets move.” |
| Chapter heading | Imperative plus a practical object or an assurance phrased as a property. | 3–9 words | “Build secure from your first line of code”<br>“Get audited and verified” |
| Action | Literal verb plus destination or task. | 2–4 words | “Go to docs”<br>“Read launch playbook”<br>“Read article” |

**Words and phrasing to use:** build; run; coordinate; define; control; verify; protect; private; trusted; resources; from the ground up

**Avoid:** magical; revolutionary; game-changing; effortless everything; unlimited guarantees; hype without a mechanism

**Rules:**

- State the benefit, then explain the enforcing mechanism in the next level of copy.
- Use oppositions sparingly to sharpen an argument: opaque versus verifiable, supervision versus policy.
- Use exact technical nouns when they help comprehension, but keep opening copy understandable without a glossary.
- Make resource and community actions sound useful, not like a sales funnel.

## Do's and Don'ts

### Do

- Keep hero and chapter display type at weight 400 with the appropriate -0.065em or -0.06em tracking.
- Use a 1400px main container and 20px desktop side gutters.
- Keep the hero actions rectangular and 48px tall, with blue primary and white secondary fills.
- Place 12px blue square markers alongside short benefit copy.
- Use 8px gutters for compact three-column grids and 16px for paired panels.
- Preserve dotted rules and small mono markings as recurring structural devices.
- Give major chapters 128px–210px breathing room while retaining 16px card padding.
- Finish with the 520px stepped blue light horizon under a black directory.

### Don't

- Do not use bold display cuts to compensate for smaller headlines; the 90px regular face is the intended authority.
- Do not round cards or controls into 12px-radius SaaS tiles or pill buttons.
- Do not add soft drop shadows to charcoal or pale cards; their fills establish the hierarchy.
- Do not tint every content chapter blue; keep the large fields black or white.
- Do not turn the 12px mono labels into large centered badge headlines.
- Do not add glossy solid 3D renders to the wireframe technical modules.
- Do not force all content into a narrow centered reading column; editorial arguments span the main field.
- Do not replace the editorial mosaic with a uniform row of identical blog cards.

## Motion and responsive

### Motion

**Observed:**

- Declared social-control transitions animate background-color and color over 0.2s cubic-bezier(0.645, 0.045, 0.355, 1).
- Declared resource cards animate background-color and color over 0.3s cubic-bezier(0.215, 0.61, 0.355, 1).
- Capability panels declare a 0.2s transition and a lighter charcoal hover surface. The opening uses moving media, and technical content is staged through scroll progression.

**Transfer:**

- Carry the blue hover fill into resource browsing and social controls; keep the signature light artwork behind stable readable copy.
- Treat the technical spine as progressive explanation, not an excuse for long stretches without information.

**Unknown:**

- Exact media playback, scroll choreography and easing of the large narrative scenes are not specified.
- No focus-visible visual treatment is established; supply an accessible treatment consistent with the square geometry.

### Responsive

**Observed:**

- Styles declare width breakpoints including 479px, 767px, 991px, 1200px, 1280px and 1920px.
- A 12px mobile global gutter is declared.

**Transfer:**

- On narrow screens, retain the dark central void around the hero copy; reduce beam density rather than placing text over bright edges.
- Stack paired benefit and action-path columns, keeping markers, mono labels and dotted boundaries attached to their content.
- Preserve the full-bleed horizon and compress its bay widths; keep resource rails horizontally browsable rather than shrinking titles into unreadable columns.

**Unknown:**

- Exact small-screen type sizes, navigation transformation and mobile section heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
