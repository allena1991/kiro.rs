# Replit — warm tools, vivid possibilities

## Overview

An approachable software style that makes powerful tools feel immediately usable. Warm ivory, charcoal and red-orange frame tightly tracked grotesk headlines, small practical controls and colorful demonstrations. Spacious openings give way to dense galleries and rounded capability cards, with natural photography adding a human counterpoint to diagrammatic product art.

### Essentials

- An invitation sits above a tool, not a billboard: a centered 64px/1 regular headline with -0.06em tracking, a 14px support line and a 650×86px composer occupy the middle of a spacious ivory first screen.
- Soft containers surround crisp actions: 20–24px card corners contrast with 8px orange button corners; reserve pills for 36px category filters rather than primary conversions.
- Color arrives in contained chapters: keep the long canvas warm ivory #faf6f1, with peach #f9aa8b, salmon #ffb199 and coral #ff764d inside demonstration cards; vivid #ff3c00 is the small action and occasional headline-word accent.
- Capabilities are tangible mini-scenes: use a 2-column set of 666×320px demonstrations and tall 320×604px diagram cards, with clipped artwork, compact text and no heavy card shadows. When product media is unavailable, construct simplified line diagrams and real output previews.
- Technical labels punctuate conversational headings: 13px medium monospace capitals at 0.12em tracking sit above 36px/1 regular card titles; the main narrative remains sans-serif.
- Include warm optical artwork as a signature counterpoint to functional UI: coral radial-gradient folds within a rounded card, backed by otherwise flat surfaces. A CSS construction of overlapping gradient strips is sufficient.
- The final invitation returns to openness: a centered 56px/1 question, 16px/1.7 reassurance and a 52px orange action lead into a pale, spacious footer with a brand summary and four compact link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#ff3c00` | `--color-accent` | action, accent, link, border | Conversions, selected accents, short links and highlighted plan outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Optical coral | `#ff764c` | `--color-optical` | accent, surface | Radial-gradient folded artwork in capability demonstrations. |
| Coral | `#ff764d` | `--color-coral` | surface | Strongest flat capability-card fill. |
| Peach | `#f9aa8b` | `--color-peach` | surface | Broad demonstration-card fill. |
| Salmon | `#ffb199` | `--color-salmon` | surface, accent | Capability cards, quote marks and portrait-tile backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate ink | `#111827` | `--color-footer-heading` | text | Footer column titles; also the source hue of 10% alpha separators. |
| Deep ink | `#191818` | `--color-strong` | text, border | Closing headlines, prices and fine diagram outlines. |
| Warm heading ink | `#312e2e` | `--color-ink` | text | Default section and card heading text. |
| Deep olive | `#2c3328` | `--color-olive` | surface | Backing for the dark photographic demonstration. |
| Soft charcoal | `#37383c` | `--color-hero-ink` | text | Hero headline and navigation. |
| Support grey | `#4b4d53` | `--color-support` | text | Small opening support line and attribution. |
| Slate grey | `#4b5563` | `--color-footer-text` | text, link | Footer prose, links and social icons. |
| Warm secondary ink | `#6f6c6a` | `--color-muted` | text | Descriptions, plan labels and reassurance. |
| Warm stone | `#dbd4cf` | `--color-stone` | surface | One tone in the tall capability-card family. |
| Filter edge | `#d8d5cf` | `--color-filter-edge` | border | Unselected category controls. |
| Composer edge | `#dfddd8` | `--color-edge` | border | Fine outline on the main composer. |
| Light grey | `#ededed` | `--color-cool-card` | surface | Neutral demonstration card alongside warmer cards. |
| Gallery stone | `#f3f2ee` | `--color-gallery` | background | Full-width output gallery band and its lower fade. |
| Composer grey | `#f3f3f1` | `--color-panel` | surface | Main input backing and compact utility circles. |
| Preview ground | `#f6f5f4` | `--color-preview` | surface | Output thumbnail framing. |
| Footer cream | `#faf5f0` | `--color-footer` | background | Shared footer; subtly warmer than the main canvas. |
| Warm ivory | `#faf6f1` | `--color-canvas` | background | Default marketing canvas and navigation backing. |
| White | `#ffffff` | `--color-white` | surface, text, background | Pricing and quotation cards, inverted type, and the company-story canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and people pages | Blue charcoal | `#1b2333` | `--color-company-ink` | text | Company narrative typography. |

## Typography

- **Replit Diatype** — All marketing headings, body copy and controls. Compact contemporary grotesk with open, matter-of-fact forms; regular-weight display text carries unusually tight spacing. If unavailable, use **Inter**. Use 400 for display; retain negative tracking and check line breaks. Font stack: "Replit Diatype", "Inter", Arial, sans-serif.
- **Replit Diatype Mono** — Short technical labels on demonstration cards. Even-width utilitarian lettering, widely tracked in uppercase. If unavailable, use **IBM Plex Mono**. Font stack: "Replit Diatype Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| intro-heading | Replit Diatype | 400 | 68.9px | 1 | -0.06em | Centered product introduction with a single orange word. |
| display | Replit Diatype | 400 | 64px | 1 | -0.06em | Opening question and major pricing headline. |
| closing-heading | Replit Diatype | 400 | 56px | 1 | -0.04em | Final marketing invitation. |
| heading | Replit Diatype | 400 | 48px | 1 | -0.06em | Centered section headlines above capability groups. |
| card-heading | Replit Diatype | 400 | 36px | 1 | -0.03em | Wide demonstration-card benefit titles. |
| capability-heading | Replit Diatype | 400 | 32px | 1 | -0.04em, capitalize | Tall capability-card titles. |
| gallery-heading | Replit Diatype | 460 | 32px | 1.25 | normal | Left-aligned gallery section title. |
| body-compact | Replit Diatype | 400 | 16px | 1.1 | -0.02em | Short descriptions anchored at the bottom of tall cards. |
| body | Replit Diatype | 400 | 16px | 1.7 | normal | Relaxed support and reassurance in the final invitation. |
| action | Replit Diatype | 400 | 15px | 1 | -0.03em | Closing primary action. |
| support | Replit Diatype | 400 | 14px | 1.6 | normal | Opening support line and small attribution. |
| footer-copy | Replit Diatype | 400 | 14px | 24px | normal | Footer prose and text links. |
| footer-title | Replit Diatype | 600 | 14px | 24px | normal | Footer link-group titles. |
| navigation | Replit Diatype | 460 | 14px | 20px | normal | Desktop navigation links. |
| header-action | Replit Diatype | 500 | 14px | 20px | -0.02em | Compact account-creation action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and people pages | company-display | Replit Diatype | 400 | 72px | 1 | -0.0467em | Centered multi-line mission headline. |
| pricing sections | price | Replit Diatype | 400 | 40px | 1.1 | -0.03em | Pricing amounts and custom-plan word labels. |
| company and people pages | people-heading | Replit Diatype | 512 | 36px | 42px | -0.02em | Centered people-grid heading. |
| company and people pages | company-closing | Replit Diatype | 512 | 30px | 35px | normal | Compact centered mission invitation. |
| testimonial sections | quotation | Replit Diatype | 400 | 26px | 1.2 | -0.03em | Long proof quotations. |
| company and people pages | company-body | Replit Diatype | 400 | 20.1px | 28px | 0.0026em | Company narrative paragraphs and portrait names. |
| company and people pages | company-link | Replit Diatype | 700 | 20.1px | 28px | 0.0026em | Bold orange text action and narrative subheads. |

**Notes:**

- Display hierarchy depends on regular weight and tight tracking, not bold weight. The 48–69px marketing headlines share -0.06em spacing; smaller card titles relax to -0.03em or -0.04em.
- Keep the large marketing promise brief enough for one line at desktop. Company storytelling instead uses a narrow three-line display and larger paragraph text.
- Technical mono is a label accent rather than a competing headline or body family. The 18px semibold labels in tall capability cards are sans-serif, not the uppercase mono label system.

## Layout

**Density:** Airy overall, with a deliberately open first screen and tightly packed card interiors and footer lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon/text gaps and eyebrow-to-title separation. |
| 12px | Tall capability-card gutters and compact header-action gaps. |
| 16px | Demonstration and pricing gutters; internal text stacks. |
| 24px | Tall card padding, support spacing and common component grouping. |
| 32px | Wide section side padding and footer column gutters. |
| 40px | Wide demonstration-card padding. |
| 48px | Quote-card padding and spacing from support groups to actions. |
| 64px | Pricing section vertical padding and broad footer group gaps. |
| 80px | Closing section top padding and header height. |
| 112px | Product-introduction top spacing and gallery bottom padding. |
| 120px | Gallery top padding and closing bottom padding. |

### Containers and grids

- **marketing container**: max width 1380px · side padding 16px. Centered wide demonstration and gallery content; at desktop the usable width is 1348px.
- **navigation container**: max width 1280px. Centered header grid with logo, compact link cluster and separate right-side actions.
- **demonstration grid**: 2 columns · gap 16px. Equal-width horizontal cards, 666×320px at desktop; copy generally occupies the left 45%.
- **capability grid**: 4 columns · gap 12px. Equal tall cards, 320×604px, arranged as an increasing warm-color sequence.
- **footer container**: max width 1280px · side padding 32px. Brand-summary column beside a four-column navigation group; content width 1216px with a 64px major gutter.
- **pricing grid** (only for pricing sections): max width 1390px · 4 columns · gap 16px · side padding 32px. Wide left-aligned plan comparison with billing controls at the heading's right.
- **company text** (only for company and people pages): max width 618px. Centered mission paragraphs, with a narrower display line measure.
- **portrait grid** (only for company and people pages): 3 columns · gap 24px. Centered portrait wall of roughly 263px square images and left-aligned captions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | composer and tall cards | 20px |
|  | demonstration and pricing cards | 24px |
|  | gallery previews | 16px |
|  | category filters | 9999px (pill) |
| testimonial sections | quotation card | 60px |
| testimonial sections | portrait proof tiles | 70px |

## Surfaces and depth

### Surfaces

#### Ivory canvas · level 0

**Use:** Default marketing page ground.

**CSS:** `background: #faf6f1`

**Observed:** Continuous warm backing across the opening, capabilities, proof, plans and closing.

**Transfer:** Let whitespace carry the structure; contain stronger colors in scenes.

#### Gallery band · level 0

**Use:** Output-discovery chapter.

**CSS:** `background: #f3f2ee; padding: 120px 0 112px`

**Observed:** A subtle tonal change rather than a hard color break; the bottom of the thumbnail grid fades into the band.

**Transfer:** Use for a selection of actual outputs or customer artifacts.

#### Flat demonstration card · level 1

**Use:** Wide benefit demonstrations.

**CSS:** `background: #f9aa8b; border-radius: 24px; padding: 40px; overflow: hidden`

**Observed:** Equal cards vary between peach, light grey, photographic olive and optical coral art. Flat fill and clipping do more work than elevation.

**Transfer:** Give each benefit its own visual mechanism while holding the outer geometry constant.

#### Photographic overlay · level 1

**Use:** Readable copy over a human-use demonstration.

**CSS:** `background: linear-gradient(100deg, rgba(29,34,27,0.8) 0%, rgba(29,34,27,0.45) 50%, rgba(29,34,27,0.2) 100%); border-radius: 24px`

**Observed:** Darkens the left side most strongly, preserving the outdoor scene to the right.

**Transfer:** Place over an authentic product-in-use photograph, with white type and sparse translucent messages.

#### Footer cream · level 0

**Use:** Shared site ending.

**CSS:** `background: #faf5f0`

**Observed:** A slightly deeper cream area bounded by subtle rules; generous space above the navigation columns.

**Transfer:** Keep it low-contrast and text-led.

#### Company white · level 0

**Only for:** company and people pages

**Use:** Editorial storytelling ground.

**CSS:** `background: #ffffff; color: #1b2333`

**Observed:** Pure white replaces the warm marketing canvas, without changing the brand's orange links.

**Transfer:** Use this cleaner variant for long-form mission and people content.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `height: 80px; position: sticky; top: 0px; background: #faf6f1; z-index: 1002`

**Text style:** `navigation` — Replit Diatype 460 · 14px/20px

**Observed:** Small logo at left, short navigation labels with tiny dropdown chevrons, then sales link, outlined login and filled account action at right. Content is centered inside Navigation container.

### Primary button

**Use:** Main conversion, especially the closing invitation.

**CSS:** `background: #ff3c00; color: #ffffff; border-radius: 8px; padding: 0px 24px; height: 52px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — Replit Diatype 400 · 15px/1 · tracking -0.03em

**Observed:** Text followed by a small right arrow; width fits the label rather than stretching across the section.

**States:** Declared: hover opacity 0.9.

### Header action

**Use:** Compact high-priority account action.

**CSS:** `background: #ff3c00; color: #ffffff; border-radius: 8px; padding: 8px 12px; height: 38px; border: 1px solid transparent`

**Text style:** `header-action` — Replit Diatype 500 · 14px/20px · tracking -0.02em

**Observed:** Fits into the navigation's right-hand control cluster beside a neutral outlined login.

**States:** Declared: hover opacity 0.75.

### Outline action

**Use:** Secondary conversion under demonstrations and inside paid plans.

**CSS:** `color: #ff3c00; border: 1.5px solid #ff3c00; border-radius: 8px; padding: 12px 24px`

**Observed:** The marketing demonstration action is label-width; pricing actions span the card's inner width. Gallery browse uses the more compact 10px 20px padding variant.

**States:** Declared: hover background-color #ff3c00 and color #ffffff.

### Prompt composer

**Use:** Make the product's starting action the opening's main object.

**CSS:** `width: 650px; height: 86px; background: #f3f3f1; border: 1px solid #dfddd8; border-radius: 20px`

**Observed:** A short editable prompt above an attachment plus at lower left and a circular orange submit arrow at lower right. A faint peach halo sits behind the container. Category choices and small example-prompt chips follow beneath.

**Transfer:** Use a genuinely relevant first action: search, request, upload or configure; preserve the low, wide tool-like shape.

### Category filter

**Use:** Output-gallery navigation.

**CSS:** `height: 36px; padding: 0px 17px; border: 1px solid #d8d5cf; border-radius: 9999px`

**Observed:** A horizontal category row aligns beside the gallery heading. The selected category is near-black with white text; others remain transparent with warm-grey labels.

**States:** Declared: hover border-color #a8a49d; focus-visible outline-offset 2px.

### Demonstration card

**Use:** Explain one benefit through a small scene.

**CSS:** `background: #f9aa8b; border-radius: 24px; padding: 40px; height: 320px; overflow: hidden; display: flex; gap: 24px`

**Text style:** `card-heading` — Replit Diatype 400 · 36px/1 · tracking -0.03em

**Observed:** Upper-left mono label, benefit title and short paragraph; a large graphic occupies the other side and can bleed into the outer clipping. Dark photo variants invert text. Light grey and optical-art variants keep dark text.

### Capability card

**Use:** Make platform breadth scannable.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 24px; height: 604px; display: flex; flex-direction: column; justify-content: space-between; overflow: clip`

**Text style:** `capability-heading` — Replit Diatype 400 · 32px/1 · tracking -0.04em · capitalize

**Observed:** Small semibold category, a short multi-line title, a centered line-art diagram and a compact bottom paragraph. Repeated cards progress from white through stone and salmon to coral.

### Footer link

**Use:** Dense site navigation at the ending.

**CSS:** `color: #4b5563; line-height: 24px; font-size: 14px; text-decoration: none`

**Text style:** `footer-copy` — Replit Diatype 400 · 14px/24px

**Observed:** Each link belongs to a titled vertical group; the left summary and social row are visually separate from the four navigation columns.

**States:** Declared: hover color #111827; focus-visible outline 2px solid #111827 with outline-offset 2px.

### Quote card

**Only for:** testimonial sections

**Use:** Substantial named third-party proof.

**CSS:** `background: #ffffff; border-radius: 60px; padding: 48px; height: 518px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `quotation` — Replit Diatype 400 · 26px/1.2 · tracking -0.03em

**Observed:** An oversized salmon quotation mark precedes several lines of regular text and a named attribution. The carousel composition combines a large white quote panel with square portrait and trust-label tiles.

**Transfer:** Use a specific, permissioned quote; keep the generous shape rather than shrinking it to a conventional review chip.

### Pricing card

**Only for:** pricing sections

**Use:** Compare entry, paid and custom offers.

**CSS:** `background: #ffffff; border: 1px solid #ff3c00; border-radius: 24px; padding: 28px 24px; height: 465px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `price` — Replit Diatype 400 · 40px/1.1 · tracking -0.03em

**Observed:** Default highlighted entry card: muted plan label, large price, tiny billing qualifier, audience description, checkmarked feature list and bottom-aligned orange action. Paid and custom cards remove the colored outline and use outlined actions. Discounts use a small pale salmon badge rather than a giant sale heading.

### Company text action

**Only for:** company and people pages

**Use:** Mission-aligned invitation without a filled conversion button.

**CSS:** `color: #ff3c00; font-weight: 700`

**Text style:** `company-link` — Replit Diatype 700 · 20.1px/28px · tracking 0.0026em

**Observed:** Centered bold text with an inline right arrow beneath the final heading. The surrounding paragraph gives it 0.8 effective opacity.

## Imagery and graphics

### Optical coral folds

**Use:** Signature artwork inside a wide demonstration card.

**Observed:** A broad coral field resolves into repeated vertical curved folds, brightest and palest near the right edges. It is soft and luminous, not a hard-striped gradient or glossy 3D object; dark copy remains on the left.

**Transfer:** Retain this warm optical counterpoint even for a product with little visual UI. It can illustrate layers, choices or increasing capability without literal product artwork.

**Build:** Clip to a 24px rounded 666×320px card. Layer three full-height strips aligned to the right, roughly 418px, 168px and 89px wide. Use left-centered elliptical radial gradients in #ff764c, holding solid coral through 72%, 45% and 30% respectively, then tapering alpha toward the far edge (0.42, 0.45 and 0.35). Let the warm white ground show through the taper; do not add a drop shadow.

### Miniature product diagrams

**Use:** Centerpieces of tall capability cards.

**Observed:** Fine outlines, dashed orbital paths, stacked rounded rectangles and small floating service tiles communicate workflows. Monochrome structures sit on white or warm fills, with restrained orange action accents; each diagram has ample empty space above its bottom paragraph.

**Transfer:** Reduce the new product to a few linked steps, modules or safeguards. A clean SVG diagram is the minimum equivalent; avoid putting an unreadable full dashboard in every card.

**Build:** Within a roughly 272px-wide illustration area, use 1–1.5px dark or white strokes, 6–8px rounded nodes and orange dashed circles. Place three or four short labels in nodes, link them with thin paths, and anchor one orange action tile as the focal point.

### Output gallery

**Use:** Broad evidence of what the tool enables.

**Observed:** A four-column grid of approximately 325×230px previews mixes richly designed posters, sites, dashboards and editorial compositions. Thumbnails have 16px corners and fine outlines; a bottom fade dissolves the lower rows into the stone band.

**Transfer:** Show diverse, believable outputs from the new product, keeping each preview fully art-directed. Preserve the mix of dark, cream and vivid compositions instead of tinting all examples orange.

### Human use photography

**Use:** One dark wide demonstration among flat graphic cards.

**Observed:** An outdoor close view of a person using a phone is darkened olive; white headline and translucent horizontal message strips sit over it. Photography fills the card rather than appearing as a tiny inset.

**Transfer:** Use a candid task-focused photograph with natural green or muted surroundings; reserve the strongest dark overlay for the text side.

### Composer halo

**Use:** Soft focal warmth beneath the first-screen tool.

**Observed:** A very low-contrast peach glow surrounds the wide input, visible mainly at its lower and side edges against ivory.

**Transfer:** Keep the main tool tactile without making it appear elevated or neon-lit.

**Build:** Position a broad elliptical pseudo-element behind the composer, extending about 80px beyond it. Use a radial rgba(255,177,153,0.15) center fading to transparent and a 32px blur. Match the soft glow; exact stops are not essential.

### Company editorial photography

**Only for:** company and people pages

**Use:** Alternate mission explanations and human proof.

**Observed:** Narrative imagery includes a silhouetted person and monitor against saturated red-orange light, framed with rounded corners beside a narrow text column. The people wall uses square, naturally colored portraits with varied settings, subtle rounded corners, names and smaller roles underneath.

**Transfer:** Choose real work environments and human faces rather than abstract orange stock art. Keep the three-column portrait rhythm and straightforward captions; use warm dramatic light only in the narrative imagery.

### Icons

**Observed:** Utility icons are compact and restrained: chiefly 16px controls and chevrons, 24px social or proof marks, with thin line work for actions and simple filled brand symbols. The composer has a plus and right arrow; capability diagrams use small rounded nodes.

**Transfer:** Choose one simple icon family with modest stroke weight. Keep icons secondary to labels and reserve orange for meaningful focal controls rather than coloring every symbol.

## Section recipes

How recurring sections are built.

### First screen: Tool invitation opening

**Observed:** An 80px ivory Navigation tops a spacious, centered composition. The single-line display question spans about one third of the viewport width and begins well below the header, with roughly 273px of open space above it inside the hero. A small support line follows after about 18px. Below is the 650×86px Prompt composer on its faint Composer halo; its attachment and submit controls are embedded rather than presented as a separate CTA pair. A carousel-like row of category icons, a small prompt suggestion label and three example chips complete the tool. In the first 900px the entire headline, support, tool and suggestions are visible; the product introduction starts below the fold. Layers are ivory ground, soft halo, input and utility controls, then foreground text. There is no giant illustration competing with the tool.

**Transfer:** Make a new product's smallest meaningful task the focal object, keeping the center-weighted question and compact support. If there is no interactive interface, create a faithful simplified task preview with a single clear start action. Company-story openings use the white variant: a narrow 72px three-line mission heading near the top, a wider 20.1px paragraph below, then the first editorial image.

**Avoid:** Do not replace the working-tool composition with a full-width dashboard, split-screen hero or a huge orange conversion slab. Do not magnify the faint halo into a saturated aurora.

**Text style:** `display` — Replit Diatype 400 · 64px/1 · tracking -0.06em

### Introduction and demonstration set

**Observed:** Centered intro-heading joins a dark introductory word to an orange product word. A muted short subline precedes the Demonstration grid. Each Demonstration card combines Eyebrow, card-heading, short support and a different visual mechanism. Paired actions sit beneath the set.

**Transfer:** Use an introduction to frame a small set of benefits, making each one visually different while preserving card geometry.

**Text style:** `intro-heading` — Replit Diatype 400 · 68.9px/1 · tracking -0.06em

### Output discovery band

**Observed:** Gallery band contains a left-aligned gallery-heading and a right-aligned Category filter row, followed after 24px by four-column Output gallery imagery with 16px gutters. The lower previews fade into the band; a centered Outline action remains clear beneath them.

**Transfer:** Use examples to let the reader recognize their own use case; let the outputs supply more visual variety than the page chrome.

**Text style:** `gallery-heading` — Replit Diatype 460 · 32px/1.25

### Capability chapter

**Observed:** A centered heading is followed after 48px by Capability grid. Cards use white, stone, salmon and coral, each with its title at top, a small diagram in the center and bottom-aligned body-compact explanation.

**Transfer:** Explain the product's foundation or breadth through small, concrete diagrams rather than four generic icons.

**Text style:** `heading` — Replit Diatype 400 · 48px/1 · tracking -0.06em

### Logo ribbon

**Observed:** A low-height proof band contains repeated monochrome logos about 110×48px with 80px gaps. Two repeated tracks support continuous horizontal movement.

**Transfer:** Use genuine partner or customer marks at balanced visual weights. A static row can preserve the same sparse ribbon composition when motion is reduced.

### Closing invitation and footer

**Observed:** A centered closing-heading, 24px gap to a body support line capped at 560px, then 48px to Primary button. The section uses 80px top and 120px bottom padding. Footer cream follows: brand mark, concise description and social row at left, four compact link columns at right, with 128px top padding and a lower hairline above copyright.

**Transfer:** Return from detailed proof to a simple invitation and one action; end with useful site navigation rather than another giant branded artwork.

**Text style:** `closing-heading` — Replit Diatype 400 · 56px/1 · tracking -0.04em

### Quotation mosaic

**Only for:** testimonial sections

**Observed:** A horizontal proof composition combines a 585×518px Quote card with 253px square portrait and outlined trust tiles. White quote panels have 60px corners, portrait backing is salmon, and the small trust tile has a 40px radius and fine grey outline.

**Transfer:** Maintain the contrast between a substantial readable quote and compact human-proof tiles. Use only as much carousel content as real proof supports.

**Text style:** `quotation` — Replit Diatype 400 · 26px/1.2 · tracking -0.03em

### Plan comparison

**Only for:** pricing sections

**Observed:** A left-aligned display headline and short muted paragraph share the section top with a compact monthly/yearly switch. Four equal Pricing cards follow, with 40px prices, short qualifiers, checkmarked feature lists and baseline-aligned actions. The entry plan receives the orange border and solid action; paid plans are not oversized.

**Transfer:** Use a calm comparison, not a loud promotional pricing table. Preserve equal card heights and differentiate through outlines and button fill.

**Text style:** `display` — Replit Diatype 400 · 64px/1 · tracking -0.06em

### Company narrative and people

**Only for:** company and people pages

**Observed:** White-ground narrative pairs use alternating large photographs and narrow text columns with bold 20.1px subheads, paragraphs and short lists. The centered people-heading introduces a three-column portrait wall with about 38px to the first images, small name-to-role spacing and generous row gaps. The ending is a 30px centered company-closing plus bold orange text action, followed by the shared cream footer.

**Transfer:** Use this editorial variant for purpose and people, with real photography and restrained captions instead of the landing page's colored capability panels.

**Text style:** `people-heading` — Replit Diatype 512 · 36px/42px · tracking -0.02em

## Page flow

**Storyline:** Invite participation → make benefits tangible → show believable outcomes and foundations → establish trust → lower commitment barriers → invite the next step → useful navigation.

### Product marketing and self-serve conversion

1. **Promise and first action** — Spacious question-led opening centered on a live task composer.
2. **Capability demonstration** — A product introduction above warm mixed-media benefit cards.
3. **Outcome proof** — Filterable output gallery on a stone band.
4. **Foundation** — Tall colored diagram cards explain platform breadth.
5. **Social proof** — Quote and portrait mosaic.
6. **Commitment** — Equal-height plan cards and compact billing selector.
7. **Trust reinforcement** — Monochrome moving logo ribbon.
8. **Closing call** — Open centered invitation, one orange button and structured cream footer.

**Transfer:** Adapt the order to the reader's questions. Preserve the participatory opening, tangible visual benefits and uncluttered return to action rather than requiring every block.

### Company narrative, people and recruitment

1. **Purpose** — Narrow multi-line mission display on white with a substantial centered paragraph.
2. **Belief and approach** — Alternating photography and explanation pairs.
3. **Human credibility** — Three-column named portrait wall.
4. **Closing call** — Modest mission invitation and bold orange arrow link.
5. **Navigation** — Shared cream footer and social links.

**Transfer:** Use for a story-oriented page that earns trust through the people and approach behind a product; replace the story's specifics rather than forcing a sales comparison into it.

## Writing

Inviting, plainspoken and optimistic about what the reader can make. Benefits lead; technical substance appears as practical capabilities rather than grandiose futurism.

**Do not copy:** Do not reuse Replit names, logos, product-mode names, customer or partner marks, personnel, quotations, adoption claims, performance savings or pricing. Replace all brand-specific assets and claims with truthful equivalents. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you; describe the product by name when explaining work it performs. Use we for mission and company commitments.
- **Rhythm:** Short questions and compact benefit phrases alternate with single-sentence support. Parallel verbs and paired short sentences keep technical subjects approachable; longer mission paragraphs belong to the company variant.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A direct question that hands agency to the visitor. | 4–6 words | “What will you build?” |
| Opening support | Outcome plus speed, followed by a plain-language barrier remover. | One compact line | “Turn ideas into apps in minutes — no coding needed” |
| Benefit heading | Verb-led result, or two short parallel clauses. | 2–7 words | “Describe it. Publish it.”<br>“Start Small. Scale Fast.” |
| Primary action | A direct start verb with low-commitment reassurance. | 3–5 words | “Get started for free” |
| Closing headline | A friendly question, then practical reassurance below. | 5–7 words | “What are you waiting for?” |
| Company mission | An active purpose expressed through who gains access. | One short statement | “Empowering the next billion software creators” |

**Words and phrasing to use:** create; build; ideas; start; describe; publish; scale; bring to life; in one place

**Avoid:** revolutionary paradigm; next-gen synergy; disrupt everything; unparalleled magic; enterprise-grade excellence without explanation

**Rules:**

- Lead with a reader outcome, then explain the mechanism.
- Name technical capabilities only where they help a visitor understand a concrete task.
- Use quantified proof only when substantiated; keep claims out of ornamental labels.
- Write short parallel headings that can carry regular-weight type without needing bold emphasis.
- Make the final support line answer a practical hesitation, such as setup effort or payment commitment.

## Do's and Don'ts

### Do

- Keep 64px display text regular with -0.06em tracking, letting line breaks and space supply emphasis.
- Use the 650×86px tool as the opening focal object, with small controls and suggestions beneath.
- Keep wide demonstration cards at 24px corners and 40px padding, with artwork clipped at their edges.
- Pair ivory surroundings with contained peach, salmon and coral scenes rather than tinting every section.
- Use 13px uppercase mono labels with 0.12em tracking to distinguish technical chapter labels.
- Align tall-card descriptions and plan actions toward common bottom baselines.
- Finish with the 56px invitation and the four-column cream footer; keep orange action areas compact.
- Use the white, larger-body editorial variant for company and people storytelling.

### Don't

- Do not make display headlines semibold or bold; 400 is the main marketing display weight.
- Do not turn all controls into pills: primary buttons have 8px corners, category filters are the pill exception.
- Do not add floating drop shadows to all cards; flat fills, clipping and fine edges define the material.
- Do not impose a universal 24px gutter: wide cards use 16px and tall capability cards use 12px.
- Do not use monospace for long body paragraphs or entire headlines; its role is short technical labels.
- Do not treat the company page's 20.1px body copy as the default for compact marketing cards.
- Do not enlarge pricing figures into giant display statistics; the measured price scale is 40px/1.1.
- Do not put white text indiscriminately on peach or salmon; dark type is the normal pairing, with white reserved for dark scenes and vivid actions.

## Motion and responsive

### Motion

**Observed:**

- Logo tracks declare 40s linear infinite horizontal scrolling.
- The navigation declares a transform transition of 0.4s ease-out.
- Closing action opacity declares 0.1s ease-out; compact header action colors declare 0.15s ease.
- Outline actions declare orange fill and white text on hover; filters declare border changes.
- A small diagram cursor declares a 1s step-end repeating blink.

**Transfer:**

- Keep motion functional and localized: a slow proof ribbon and small demo activity, rather than moving the whole layout.
- Preserve the static two-track ribbon composition when suppressing movement.

**Unknown:**

- Scroll-trigger timing, playback behavior and reduced-motion handling are not established.

### Responsive

**Observed:**

- Closing headline declares 40px at widths up to 768px.
- Plan-grid classes specify one column, then two, then four; footer link columns specify two before four at 768px.
- Footer outer layout changes at 1280px; desktop uses a separate summary block beside the link groups.

**Transfer:**

- On narrow screens, let the composer shrink within the available width and keep its attachment and submit controls inside the same rounded object.
- Stack wide demonstrations while preserving the copy/art relationship; reduce the tall-card column count without collapsing diagrams into tiny icons.
- Keep company paragraphs narrower than their imagery, and preserve readable portrait captions when reducing columns.

**Unknown:**

- Exact mobile first-screen spacing, navigation menu behavior and all breakpoint-to-layout mappings are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
