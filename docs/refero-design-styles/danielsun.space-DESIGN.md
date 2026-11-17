# Daniel Sun — sunlit drafting table

## Overview

An editorial portfolio sensibility pairs elegant, tightly set serif statements with miniature tactile controls and a faint drafting grid. The default is white and black with a sunny yellow glow, while saturated color lives mainly inside framed illustrations and product imagery. Spacious introductions give way to dense visual galleries, and a playful botanical ending makes the technical craft feel personal. It suits design-led products, creative services and visual case studies.

### Essentials

- Statements feel like personal introductions rather than advertising billboards: regular serif at 64px/72px with -3px tracking, broken into broad, deliberate lines.
- The opening is a sunlit drafting table: a 700px scene within a 1200px frame, faint square grid and fine construction lines, a yellow glow overhead and the message anchored low on the left.
- Actions look like tiny physical keys: black 28px-high header buttons with 8px corners, layered inset highlights and downward shadows; larger contact keys are 40px high with 10px corners.
- Color is an exhibit, not a navigation system: white canvas and black text dominate the framework; yellow light occupies the opening's upper region, while vivid purple, green and blue remain bounded by media frames.
- Work is presented as collectible objects: two staggered columns, 12px gaps, 12px image corners and a 6px white rim with layered shadows; use a composed interface or simple dimensional diagram when photography is unavailable.
- The technical frame ends with organic life: a two-column contact strip, 40px square social keys, then a 160px botanical border of yellow flowers and green stems; recreate with a repeating illustrated plant field rather than substituting a conventional footer. Small corner handles and fine rules keep the whole page feeling like a design workspace.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Yellow light | `#fff443` | `--color-sunlight` | accent, background | Warm luminous upper field, fading into white rather than a solid yellow section. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Headlines, body and black action keys; full canvas inversion only for personal or company-story pages. |
| Charcoal tag | `#303030` | `--color-tag` | surface | Dark category labels over gallery artwork. |
| Secondary gray | `#666666` | `--color-muted` | text | Supporting lines and footer labels; black at 60% over white. |
| Construction edge | `#cccccc` | `--color-rule` | border | Thin grid-cell dividers and label edges. |
| Control tray | `#f2f2f2` | `--color-tray` | surface | Black at 5% over white for the segmented navigation tray. |
| Soft key shade | `#f5f5f5` | `--color-key-shade` | surface | Social-key gradients and the visible black-at-4% metadata wash. |
| Pearl key | `#f7f7f7` | `--color-key-light` | surface | Light contact-key gradient endpoints. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, white rims and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| personal or company-story pages | Inverse divider | `#545454` | `--color-dark-rule` | border | Structural dividers on black. |
| personal or company-story pages | Inverse secondary | `#a6a6a6` | `--color-inverse-muted` | text | White at 65% over black, used for reflective italic labels and supporting copy. |
| personal or company-story pages | Silver key | `#c2c2c2` | `--color-silver` | action, surface | Raised download action on the inverse story theme. |

## Typography

- **LT Superior Serif** — Display statements, section titles and capability names. Fine, high-contrast editorial serif with compact spacing and an unforced regular weight. If unavailable, use **Instrument Serif**. 400; retain the tight spacing and tune line breaks to match the broad text silhouette. Font stack: "LT Superior Serif", "Instrument Serif", Georgia, serif.
- **Inter Display** — Body copy, controls, captions and small identity text. Clean neo-grotesk; regular weight throughout. Font stack: "Inter Display", Inter, Arial, sans-serif.
- **EB Garamond** (only for personal or company-story pages) — Reflective section labels. Small literary italic contrasting with utilitarian body copy. Font stack: "EB Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | LT Superior Serif | 400 | 64px | 1.125 | -0.0469em | Opening statement, major section lead and expressive closing line. |
| heading | LT Superior Serif | 400 | 30px | 40px | -0.0167em | Capability names, narrative subheads and metadata-group headings. |
| identity | Inter Display | 400 | 21px | 20px | -0.024em | Centered text identity in the header. |
| body | Inter Display | 400 | 16px | 1.625 | 0.006em | Explanations and narrative paragraphs. |
| support | Inter Display | 400 | 16px | 1.5 | 0.006em | Short supporting lines and contact text. |
| label | Inter Display | 400 | 14px | 20px | normal | Buttons, category chips and compact navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| personal or company-story pages | reflective-label | EB Garamond | 400 italic | 20px | 1 | -0.025em | Small narrative labels above biographical paragraphs. |

**Notes:**

- Keep the main serif regular, not bold. Its -3px tracking is considerably tighter than the -0.5px used at 30px.
- Body and controls are sans-serif; do not carry the display serif into navigation.
- Display lines are intentionally much broader than the 400px capability-copy measure. Use the same 64px recipe for opening and major chapter headings rather than inventing a different scale for every section.

## Layout

**Density:** Airy introductions and chapter breaks contrast with closely packed media and miniature controls.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight gaps between overlaid media tags. |
| 8px | Capability title to paragraph and wrapped metadata rows. |
| 12px | Gallery columns, image rows and social-key gaps. |
| 16px | Narrative paragraph separation and outer page safety inset. |
| 24px | Content-cell padding and footer label-to-action separation. |
| 32px | Separation of narrative metadata groups. |
| 48px | Case-study cover to narrative subhead. |
| 120px | Top breathing room before case-study chapter headings. |
| 200px | Case-study introduction top padding and spacious centered section lead. |

### Containers and grids

- **Main frame**: max width 1200px · side padding 16px. Centered structural frame with continuous vertical rules; at 1440px it leaves 120px outer margins.
- **Gallery**: 2 columns · gap 12px · side padding 24px. Two independent vertical stacks inside the main frame, producing a staggered image-led composition rather than aligned text-card rows.
- **Capability matrix**: 2 columns · gap 0px. 600px-wide cells share hairline dividers. Each cell is 310px high with 24px padding.
- **Body measure**: max width 400px. Capability paragraphs remain narrow inside the broader cell.
- **Proof matrix**: 5 columns · gap 0px. Monochrome marks centered within 240px by 104px cells.
- **Case introduction** (only for case-study pages): max width 670px · side padding 24px. Left-aligned title and one short paragraph above a wide cover.
- **Case narrative** (only for case-study pages): 2 columns · gap 0px. A 720px narrative column beside a 480px metadata column inside the main frame; both use 24px inset.
- **Case media** (only for case-study pages): max width 1152px · gap 12px. Full-width 1152px by 671px presentation panels alternate with pairs of 570px by 572px panels.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Header keys | 8px |
|  | Contact keys | 10px |
|  | Gallery image | 12px |
|  | Gallery tags | 7px |
| case-study pages | Media panels | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Gallery rim | `0px 0px 0px 6px #ffffff, 0px 6px 16px 0px rgba(0,0,0,0.2), 0px 1px 3px 6px rgba(0,0,0,0.15), 0px 0px 8px 0px rgba(0,0,0,0.25), 0px 0px 0px 7px rgba(0,0,0,0.06)` | White framed gallery artwork. |
| Black key | `0px -1px 1px 0px rgba(0,0,0,0.4) inset, 0px -3px 5px 0px rgba(255,255,255,0.25) inset, 0px -5px 5px 0px rgba(255,255,255,0.25) inset, 0px 3px 5px -1px rgba(0,0,0,0.35), 0px 6px 10px -1px rgba(0,0,0,0.15)` | Small black header action and active navigation key. |

### Surfaces

#### Drafting canvas · level 0

**Use:** Default white page with a subtle technical field.

**CSS:** `background-color: #ffffff; color: #000000`

**Observed:** A very faint square grid is visible behind open text areas and outside the main frame; solid white cells interrupt it. Fine vertical rails and tiny square corner handles suggest an artboard.

**Transfer:** Recreate the grid and handles as decoration behind content, not as functional editing UI.

#### Sunlit field · level 0

**Use:** Atmosphere above the opening statement.

**CSS:** `background-image: radial-gradient(ellipse at 50% 0%, rgba(255,244,67,0.9) 0%, rgba(255,244,67,0) 70%)`

**Observed:** A broad yellow glow is strongest along the top and dissolves before the headline; subtle grain keeps it from feeling like a slick flat banner.

**Transfer:** Match the soft glow; exact stops are not essential.

#### White structural cell · level 1

**Use:** Capability cells, proof grid and contact strip.

**CSS:** `background: #ffffff; padding: 24px; box-shadow: 1px 0px 0px 0px rgba(0,0,0,0.15)`

**Observed:** Rectangular, flush-edged cells share thin rules rather than floating individually.

**Transfer:** Use shared borders for text-led content; reserve rounded rims for imagery.

#### Inverse drafting canvas · level 0

**Only for:** personal or company-story pages

**Use:** A more intimate story-led presentation.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The same faint grid and frame remain, with pale lavender light overhead, silver controls and white text.

**Transfer:** Invert the entire scene coherently rather than inserting random black feature cards.

## Components

### Fixed navigation

**Use:** Persistent orientation and contact action.

**CSS:** `position: fixed; height: 52px; background: #ffffff; z-index: 9; padding: 0px 16px`

**Text style:** `identity` — Inter Display 400 · 21px/20px · tracking -0.024em

**Observed:** A centered identity sits independently of the left segmented page selector and right Black action key. The content aligns to the 1200px main frame. Case studies replace the selector with a small Back key.

**Transfer:** Keep the identity visually centered even when side controls differ in width.

### Segmented selector

**Use:** Switch between work-led and story-led presentations.

**CSS:** `display: flex; height: 28px; width: 149px; background: rgba(0,0,0,0.05); border-radius: 8px; box-shadow: 0px -1px 0px 0px rgba(0,0,0,0.1) inset, 0px 1.5px 1px 0px rgba(255,255,255,0.65) inset, 0px 0px 0px 1px rgba(0,0,0,0.15) inset`

**Text style:** `label` — Inter Display 400 · 14px/20px

**Observed:** Two adjacent choices sit in one shallow molded tray; the active choice is a black glossy key. Sun and moon icons reinforce the light and dark page themes.

### Black action key

**Use:** Compact primary contact action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 28px; padding: 0px 8px; background: #000000; color: #ffffff; border-radius: 8px; box-shadow: 0px -1px 1px 0px rgba(0,0,0,0.4) inset, 0px -3px 5px 0px rgba(255,255,255,0.25) inset, 0px -5px 5px 0px rgba(255,255,255,0.25) inset, 0px 3px 5px -1px rgba(0,0,0,0.35), 0px 6px 10px -1px rgba(0,0,0,0.15)`

**Text style:** `label` — Inter Display 400 · 14px/20px

**Observed:** A separate translucent highlight layer shines across the upper half. The hero uses a broader, taller version with a right-pointing arrow; the inverse theme uses silver instead of black.

### Framed media card

**Use:** Image-led proof and related-work navigation.

**CSS:** `border-radius: 12px; overflow: hidden; box-shadow: 0px 0px 0px 6px #ffffff, 0px 6px 16px 0px rgba(0,0,0,0.2), 0px 1px 3px 6px rgba(0,0,0,0.15), 0px 0px 8px 0px rgba(0,0,0,0.25), 0px 0px 0px 7px rgba(0,0,0,0.06)`

**Observed:** Artwork fills the frame. A compact caption row overlays the lower-left edge with a white identity chip followed by charcoal category chips; card heights vary by artwork.

**Transfer:** Let the image do the selling; keep explanatory prose outside the frame.

### Overlay category chip

**Use:** Categorize gallery work without adding a text block.

**CSS:** `background: #303030; color: #ffffff; border-radius: 7px; height: 24px; padding: 7px 9px; backdrop-filter: blur(8px); display: flex; align-items: center`

**Text style:** `label` — Inter Display 400 · 14px/20px

**Observed:** Several chips sit together in a row inset 10px from the artwork edge, separated by 4px. The first identity chip is white with black text.

### Capability cell

**Use:** Explain a capability through one small object and a short paragraph.

**CSS:** `height: 310px; padding: 24px; display: flex; flex-direction: column; box-shadow: 1px 0px 0px 0px rgba(0,0,0,0.15)`

**Text style:** `heading` — LT Superior Serif 400 · 30px/40px · tracking -0.0167em

**Observed:** A small dimensional icon sits near the upper-left; a title and body paragraph sit lower in the cell, with an 8px title-to-copy gap and 400px text measure.

**Transfer:** Use a concrete tool-like icon rather than a large decorative feature illustration.

### Contact key

**Use:** Final direct-contact action.

**CSS:** `height: 40px; width: 239px; display: flex; align-items: center; justify-content: center; border-radius: 10px; background-image: linear-gradient(120deg, #f7f7f7 -53%, #ffffff -43%, #ffffff -21%, #f7f7f7 -12%); box-shadow: 0px -1px 0px 0px rgba(0,0,0,0.1) inset, 0px 1.5px 1px 0px rgba(255,255,255,0.65) inset, 0px 4px 2px 0px rgba(0,0,0,0.03) inset, 0px -8px 8px 0px rgba(255,255,255,0.7) inset, 0px 0px 0px 1px rgba(0,0,0,0.15) inset, 0px 3px 3px 0px rgba(0,0,0,0.04)`

**Text style:** `support` — Inter Display 400 · 16px/1.5 · tracking 0.006em

**Observed:** The address fills the broad left portion and a copy glyph occupies the square right end. It sits below a muted availability line.

### Social key

**Use:** Compact social links in the closing strip.

**CSS:** `width: 40px; height: 40px; border-radius: 10px; background-image: linear-gradient(120deg, #f5f5f5 -82%, #ffffff -68%, #ffffff -21.8055%, #f5f5f5 -4%); box-shadow: 0px -1px 1px 0px rgba(0,0,0,0.1) inset, 0px 1.5px 1px 0px rgba(255,255,255,0.65) inset, 0px 4px 2px 0px rgba(0,0,0,0.03) inset, 0px -8px 8px 0px rgba(255,255,255,0.7) inset, 0px 0px 0px 1px rgba(0,0,0,0.15) inset, 0px 3px 3px 0px rgba(0,0,0,0.04)`

**Observed:** A gray platform mark is centered on each key; six keys form a horizontal row with 12px gaps. Inverse versions use translucent dark glass and pale edge highlights.

### Proof cell

**Use:** Monochrome social proof.

**CSS:** `height: 104px; display: flex; align-items: center; justify-content: center; box-shadow: 1px 1px 0px 0px #cccccc`

**Observed:** Marks are centered in a flush five-column matrix beneath a small left-aligned introduction. This is a ruled table rather than a floating logo cloud.

### Metadata chip

**Only for:** case-study pages

**Use:** List services and tools beside a narrative.

**CSS:** `background: rgba(0,0,0,0.04); border-radius: 8px; height: 24px; padding: 4px 8px 5px 8px; box-shadow: 0px -1px 0px 0px rgba(0,0,0,0.15) inset`

**Text style:** `label` — Inter Display 400 · 14px/20px

**Observed:** Low-contrast chips wrap into compact rows below a serif group heading; these are smaller supporting annotations, not conversion actions.

## Imagery and graphics

### Drafting grid and handles

**Use:** Technical visual skeleton across open sections.

**Observed:** Tiny low-contrast squares continue outside the central frame. Fine rails outline the artboard and small hollow squares mark section intersections.

**Transfer:** Maintain the impression of a working design surface while keeping all decoration subordinate to text.

**Build:** Use two linear-gradients, one horizontal and one vertical, with rgba(0,0,0,0.025) 1px lines on an 8px repeat over white. Draw the central rails with 1px rgba(0,0,0,0.15) borders; add 6px hollow square pseudo-elements at major intersections. On black, use white lines at similarly low alpha.

### Overhead sunlight

**Use:** Signature opening atmosphere.

**Observed:** A wide soft yellow cloud hangs above the serif statement; its middle is warm and bright and its sides dissolve toward white. Fine grain overlays the glow.

**Transfer:** Use the same light as an abstract product atmosphere even when no hero photography exists.

**Build:** Place a broad elliptical radial gradient at the top center of the main frame using rgba(255,244,67,0.9), fading to transparent by 70%. Keep it behind the grid and fade it before the text. Add a low-opacity SVG turbulence layer for fine grain, not large visible speckles.

### Collectible product exhibits

**Use:** Main proof gallery and exploration strip.

**Observed:** Laptop and tablet mockups, dimensional line illustrations, dark halftone graphics and translucent cards fill white-rimmed frames. Each artwork owns its own palette. The exploration strip uses slightly tilted frames and clips neighboring pieces at its edges.

**Transfer:** Compose a realistic interface on a neutral backing, or a crisp dimensional metaphor with a few product colors. Keep each exhibit self-contained rather than bleeding its palette into the surrounding page.

**Build:** For a minimum dimensional exhibit, draw a product-relevant SVG object with a white front face, thin dark outline and offset extruded side face. Shade the side with a restrained two-color gradient, then place it on a pale neutral field within the Framed media card.

### Botanical closing border

**Use:** Signature end of every page.

**Observed:** A dense row of photoreal yellow sunflowers with dark brown centers and green leaves grows from the bottom edge. Stems and flower heights vary; the field spans the 1200px frame and occupies the final 160px beneath the contact strip.

**Transfer:** Create an original botanical border with the same yellow-and-green warmth. If photographic cutouts are unavailable, use detailed SVG flowers rather than leaving the ending typographic.

**Build:** Create 5–7 transparent flower sprites or SVG symbols with narrow green stems, paired pointed leaves, dark textured circular centers and radial yellow petals. Repeat them across the width at varied scale and height, overlap leaves, and clip their stems at the bottom of a 160px-high frame. Avoid a visible rectangular image backing.

### Case-study presentation boards

**Only for:** case-study pages

**Use:** Large visual chapters after the narrative.

**Observed:** Rounded full-width boards alternate with near-square pairs. Interfaces are inset onto gray or deep violet backings; illustrations sit on pale gray fields. Some boards deliberately crop a larger interface or assemble several marketing tiles.

**Transfer:** Show the product at useful scale with backing margins, then follow with closer details. Keep typography within the presented product distinct from the surrounding editorial page.

### Personal paper collage

**Only for:** personal or company-story pages

**Use:** Human context and expressive closing scene.

**Observed:** Overlapping white-bordered instant photos, a curled yellow handwritten checklist and a tilted red name sticker sit against the dark drafting grid. The closing serif line occupies the lower-left while the collage fills the right half.

**Transfer:** Use original team or maker photos and tactile paper objects to convey personality without turning the main product page into a scrapbook.

**Build:** Layer a white photo rectangle with a wider bottom margin, a pale-yellow lined note with a subtly curved lower corner, and a contrasting name-label shape. Rotate each independently and use small contact shadows. Handwritten marks belong only inside these paper objects.

### Icons

**Observed:** Small sun and moon symbols distinguish navigation themes; arrows and copy glyphs sit within actions. Footer social marks are gray, while capability icons are small dimensional objects with highlights and shadows. Image-based icon assets include 14px, 16px and 20px action sizes and 40px square footer slots.

**Transfer:** Use simple monochrome utility glyphs for actions and a consistent family of crafted dimensional objects for capabilities; do not substitute colorful emoji.

## Section recipes

How recurring sections are built.

### First screen: Sunlit editorial opening

**Observed:** A 52px Fixed navigation caps a 700px opening scene. Behind it, Drafting canvas and Overhead sunlight create a broad empty upper field. The three-line regular serif statement is anchored toward the lower-left, spans roughly three quarters of the inner width and uses display typography. A glossy arrow-ended action sits beneath it. Within the first 900px the entire statement and action are visible, followed by a 72px supporting strip and the top of the two-column gallery; there is no dominant product object in the opening itself.

**Transfer:** Write a direct product promise with a similarly broad sentence silhouette and let the light carry the upper half. Without hero media, retain the luminous grid instead of inserting stock photography. Case-study openings use a compact title and paragraph with 200px top padding, then a wide cover; story-led openings invert the canvas and glow.

**Avoid:** Do not center a short SaaS slogan above a giant dashboard or crowd the upper light field with badges and secondary actions.

**Text style:** `display` — LT Superior Serif 400 · 64px/1.125 · tracking -0.0469em

### Staggered visual proof

**Observed:** The Gallery begins below the support strip. Two stacks of Framed media cards sit inside 24px inset with 12px gutters; varied artwork heights create a masonry rhythm. Overlay category chips sit at the lower-left of each exhibit.

**Transfer:** Use varied but purposeful image ratios to present product outcomes, interaction details and visual metaphors. The gallery can appear wherever the narrative needs tangible proof.

### Ruled proof matrix

**Observed:** A small muted introduction precedes flush rows of Proof cells. Five centered marks per row are separated by thin gray rules.

**Transfer:** Use credible partner, integration or customer marks with comparable visual weight, preserving the table-like treatment.

### Editorial capability matrix

**Observed:** A centered display lead sits in a tall grid-backed heading region with 200px top padding and 24px bottom padding. Beneath it, a two-by-two Capability matrix uses White structural cells, tool-like icons, 30px serif titles and short sans paragraphs.

**Transfer:** Group a few capabilities into succinct cells, balancing the large editorial introduction against compact practical explanations.

**Text style:** `display` — LT Superior Serif 400 · 64px/1.125 · tracking -0.0469em

### Exploration and closing contact

**Observed:** A large left-aligned serif statement introduces a clipped horizontal strip of collectible product exhibits. Beneath it, the contact strip divides into equal 600px cells: muted availability and Contact key on the left, social label and Social keys on the right, each inset 24px. Botanical closing border forms the actual bottom edge.

**Transfer:** Offer a final glimpse of range or future possibility, then make contact easy. Case studies can go directly from final artwork or related work to the same contact-and-botanical ending.

### Case narrative and chapters

**Only for:** case-study pages

**Observed:** A wide cover is followed after 48px by a left narrative headed in 30px serif and a right metadata column. Chapter leads use 64px display type with 120px top and 24px bottom padding; alternating full-width and paired Case-study presentation boards carry the detailed proof.

**Transfer:** Use the narrative to explain the constraint and decision before showing the resulting system. Preserve the distinction between editorial headings and product typography.

**Text style:** `heading` — LT Superior Serif 400 · 30px/40px · tracking -0.0167em

### Inverse personal ending

**Only for:** personal or company-story pages

**Observed:** A 498px black drafting-grid scene pairs a low-left 64px serif closing line with Personal paper collage on the right. Silver and dark-glass controls carry the contact strip below it, followed by the same yellow botanical border.

**Transfer:** Use this variant for human stories and culture, not as the default product landing-page ending.

**Text style:** `display` — LT Superior Serif 400 · 64px/1.125 · tracking -0.0469em

## Page flow

**Storyline:** Personal promise → tangible visual proof → context and capability → expressive final glimpse → direct contact → botanical sign-off.

### Introduce a design-led offering through its work and personality

1. **Promise** — Sunlit editorial statement and a direct project action.
2. **Proof** — Supporting credibility line, staggered media gallery and ruled logo matrix.
3. **Capabilities** — Centered serif lead above practical service cells.
4. **Range** — Expressive statement and clipped exploration gallery.
5. **Closing call** — Two-column contact strip and botanical border.

**Transfer:** Make visual results the main argument while keeping the action human and direct.

### Explain the people, experience and approach behind an offering

1. **Positioning** — Inverse editorial statement beneath a pale overhead glow.
2. **Human context** — Biographical paragraphs paired with overlapping photographs.
3. **Credibility** — Ruled experience rows beside a statement of approach and a silver download key.
4. **Closing call** — Large future-facing line and paper collage, then inverse contact strip and flowers.

**Transfer:** Use the inverse theme to distinguish a personal or culture narrative from product proof.

### Explain a visual-system project through constraints, decisions and applications

1. **Introduction** — Compact title and summary above a wide brand cover.
2. **Context** — Narrative explanation beside service and tool chips.
3. **System proof** — Branding chapter with alternating boards and paired dimensional illustrations.
4. **Application proof** — Web-design chapter with framed interfaces and detail panels.
5. **Closing call** — Direct contact strip and botanical ending after the final application.

**Transfer:** Organize by system and application rather than making every artifact a separate text section.

### Demonstrate breadth within a long-running product engagement

1. **Introduction** — Title and role summary above a device-based cover.
2. **Context** — Long-form narrative and compact metadata sidebar.
3. **Capability chapters** — Large serif dividers separate web, campaign and physical applications; boards carry the detail.
4. **Further exploration** — Related-work masonry gallery.
5. **Closing call** — Shared contact strip and botanical bottom edge.

**Transfer:** Let chapters carry a broad body of work without adopting the typography or palette of the interfaces shown inside them.

## Writing

Warm, direct and craft-aware, with confidence grounded in concrete work rather than grandiose positioning. A conversational first-person voice explains choices, trade-offs and practical outcomes.

**Do not copy:** Do not reuse the designer's name, client names, email, project artwork, personal history, experience numbers, customer claims or project results. Source quotations illustrate tone only.

- **Addressing the reader:** The maker speaks as I and addresses the reader as you or your; a product team can use we while preserving the directness.
- **Rhythm:** Long, flowing serif statements contrast with brief labels. Supporting copy uses plain sentences and concrete verbs; case narratives can be several paragraphs, while action labels remain conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Introduce the maker or offering and connect the craft to a reader benefit. | About 15–25 words | “Hey! I'm [Brand], a designer who brings trusted clarity into your web and brand experiences” |
| Capability lead | Frame the offering around what the reader's product needs. | About 8–12 words | “Everything your product needs to be taken seriously” |
| Narrative subhead | Use a familiar spoken phrase to introduce substantial context. | 3–5 words | “Long story short” |
| Supporting explanation | Describe the actual work with verbs, constraints and sequence rather than vague benefits. | One or two sentences | “I build what I design in Framer or Webflow, down to the smallest interactions that make a site feel alive without ever pulling focus.” |
| Primary action | A low-pressure invitation to a real conversation. | 2–6 words | “Let's chat”<br>“Start a project with me” |
| Closing line | A short forward-looking personal statement. | 5–8 words | “Ready for the next adventures”<br>“Pushing my limits through curiosity” |

**Words and phrasing to use:** clarity; your product; from scratch; shape; build; smallest interactions; voice; curiosity; Long story short

**Avoid:** revolutionary platform; unparalleled innovation; unlock limitless potential; enterprise synergies; disrupt everything

**Rules:**

- Explain what was done and why before claiming impact.
- Keep metadata labels lowercase or sentence case, not all-capital technical eyebrows.
- Let a small personal aside or colloquial phrase soften longer narrative copy.
- Use concrete constraints and outcomes in case narratives; keep gallery annotations minimal.

## Do's and Don'ts

### Do

- Keep the main serif at 64px/72px, weight 400 and -3px tracking.
- Anchor the opening statement low in its 700px scene and preserve the overhead light field.
- Use 24px cell insets and 12px media gaps within the 1200px frame.
- Give artwork a 6px white rim and 12px rounded image corners.
- Keep practical copy at 16px/26px and capability paragraphs within 400px.
- Use 28px glossy keys for compact header actions and 40px contact keys in the ending.
- Carry the faint drafting grid, corner handles and organic botanical sign-off into new pages.
- Keep saturated product palettes inside their own media frames.

### Don't

- Do not turn the 28px header key into a giant pill-shaped conversion button.
- Do not make all capability cells rounded floating cards; their shared 1px rules are important.
- Do not bold the 64px serif headlines or replace them with geometric sans display type.
- Do not tint the entire page to match a colorful exhibit.
- Do not use huge all-caps eyebrows above every heading; the label system is compact 14px sentence-case sans.
- Do not let 16px body copy span the full 1152px media width.
- Do not substitute a multi-column sitemap for the compact contact strip and botanical edge.
- Do not apply the paper collage and italic story labels indiscriminately to ordinary product features.

## Motion and responsive

### Motion

**Observed:**

- Opacity transitions of 0.9s are declared on a small set of surfaces or actions; no action-specific hover, focus-visible or active declarations are established.

**Transfer:**

- Keep interaction changes subordinate to the tactile key construction; do not make hover motion the primary source of visual character.

**Unknown:**

- The exact animation behavior of the botanical canvas and interactive artwork is not established.
- Timing and easing for any gallery tilt or scroll reveal are unknown.

### Responsive

**Observed:**

- Styles declare width boundaries around 640px, 992px and 1200px; the described composition is the 1440px desktop layout.

**Transfer:**

- As a design adaptation, collapse the two media stacks and capability columns into one while retaining thin rails and white rims.
- Keep the overhead glow separate from the text; shorten line lengths instead of placing the headline over the brightest light.
- Stack the two contact cells on narrow screens and retain the clipped botanical border.

**Unknown:**

- Exact mobile type sizes, spacing, navigation arrangements and media ratios are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
