# Craft — torn paper possibilities

## Overview

A light, tactile editorial style that makes capable software feel personal and creative. Bookish serif headlines meet unassuming grotesk text on warm paper, with sky blue, mint, butter yellow and periwinkle staged in rounded panels. Torn-paper collage, halftone clouds, friendly portraits and layered interface scenes bring a handmade feeling to spacious product storytelling.

### Essentials

- Book typography meets everyday software: regular serif headlines at 66px/1 with -0.03em tracking, section titles at 54px/1.1 with -0.02em, and compact 16px/1.4 sans paragraphs.
- The opening is a scrapbook sky, not an empty billboard: a 1400px-wide, 828px-high rounded stage inside 20px margins, a centered two-line promise and glass pill above a large interface rising through torn paper.
- Actions feel like polished little objects: fully rounded 48px pills with 32px horizontal padding, translucent white layers and a low, soft shadow; the compact navigation action is black and 36px high.
- Color belongs to tactile stages: warm #fcf9f7 remains the continuous reading ground, while #b8caf5, #9bd8a9 and #fde99b fill bounded 1080px feature panels. Black is concentrated in actions, the premium offer and the inset footer rather than whole dark chapters.
- Give digital content physical depth: overlap rounded interface sheets over irregular paper edges, add fine grain and broad low-opacity shadows, and punctuate open space with softly halftoned clouds. When finished media is unavailable, use two believable interface fragments on an SVG paper collage rather than generic abstract blobs.
- Human warmth interrupts feature density: italic serif quotes at 32px/1.5 sit beside 54px portraits and a fine horizontal rule; portrait showcases use cutout people on colored paper backings with sans identity captions and italic use-case lines.
- Carry the handmade material into the ending: a textured black footer with 24px corners, inset 16px from the page, white grouped links and faint rules. Landing-page conversion bands add mint brushwork, a 56px italic invitation and a 36px serif reassurance.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#9ed4ef` | `--color-sky` | background, accent | Upper color of sky-stage gradient. |
| Pale sky | `#d1eef9` | `--color-sky-light` | background | Lower color of sky-stage gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter paper | `#fde99b` | `--color-butter` | surface, accent | Feature stage and lined-paper collage. |
| Mint paper | `#9bd8a9` | `--color-mint` | surface, background, accent | Feature stages, brushwork band and category-page opening. |
| Periwinkle paper | `#b8caf5` | `--color-periwinkle` | surface, accent | Feature stage and torn-paper collage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#030302` | `--color-ink` | text, action, background | Headings, navigation, dark actions, premium offer and footer. |
| Soft ink | `#41413f` | `--color-body-ink` | text | Supporting text; rgba(3,3,2,0.75) over warm paper. |
| Secondary ink | `#5a5958` | `--color-muted-ink` | text | Section support; rgba(3,3,2,0.65) over warm paper. |
| Faded ink | `#807e7d` | `--color-caption-ink` | text | Quiet captions; rgba(3,3,2,0.5) over warm paper. |
| Layer edge | `#dedbda` | `--color-strong-edge` | border | Slightly stronger panel edges; rgba(3,3,2,0.12) over warm paper. |
| Paper edge | `#e6e3e1` | `--color-edge` | border | Card outlines and FAQ rules; rgba(3,3,2,0.09) over warm paper. |
| Gray torn paper | `#e4e4e7` | `--color-paper-gray` | surface | Collage layer behind white deckled edges. |
| Off-white sheet | `#f7f7f7` | `--color-sheet-gray` | surface | Torn notebook paper in collages. |
| Warm paper | `#fcf9f7` | `--color-canvas` | background, surface | Continuous reading ground and pricing offer surfaces. |
| White sheet | `#ffffff` | `--color-white` | surface, text | Interface sheets, cards, inverse text and translucent glass layers. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| community workflow galleries | Award label yellow | `#fff085` | `--color-award-yellow` | surface | Raised award strip over gallery media. |
| community workflow galleries | Award brown | `#733e0a` | `--color-award-ink` | text | Text and trophy on award strips. |
| audience landing pages | Pale mint | `#d5f0db` | `--color-mint-light` | surface, background | Audience proof panel and lower mint hero gradient. |
| workflow galleries | Lilac media backing | `#ede8f1` | `--color-lilac-well` | surface | Colored media well behind overlapping workflow sheets. |
| workflow galleries | Cool media backing | `#f5f5f7` | `--color-media-gray` | surface | Inset media wells in workflow galleries. |

## Typography

- **UntitledSerifFont** — Headlines, editorial card titles, prices and italic testimonials. Bookish, gently contrasting serif with broad lowercase forms; regular rather than assertively bold. OpenType features: "liga". If unavailable, use **Source Serif 4**. Use 400 roman and italic; retain tight tracking and test line breaks. Font stack: "UntitledSerifFont", "Source Serif 4", ui-serif, Georgia, serif.
- **UntitledSansFont** — Navigation, body copy, actions and uppercase category labels. Plain, warm grotesk with compact spacing and modest medium weights. OpenType features: "liga". If unavailable, use **Inter**. Use 400–500 for most text; avoid increasing weight to compensate for size. Font stack: "UntitledSansFont", "Inter", system-ui, "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | UntitledSerifFont | 400 | 66px | 1 | -0.03em | Default landing-page promise; centered across a 666px text measure. |
| closing-heading | UntitledSerifFont | 400 italic | 56px | 1.1 | -0.03em | Invitation in the mint conversion band. |
| heading-lg | UntitledSerifFont | 400 | 54px | 1.1 | -0.02em | Primary section titles; also the compact hero for pricing and ecosystem pages. |
| heading | UntitledSerifFont | 400 | 46px | 1.22 | -0.03em | Editorial statement and plan titles. |
| heading-emphasis | UntitledSerifFont | 400 italic | 46px | 1.22 | -0.03em | One emphasized word within an editorial statement. |
| feature-heading | UntitledSerifFont | 400 | 36px | 1.22 | -0.03em | Headings within pastel feature stages. |
| closing-support | UntitledSerifFont | 400 | 36px | 40px | -0.04em | Serif reassurance beneath the closing invitation. |
| quote | UntitledSerifFont | 400 italic | 32px | 1.5 | -0.04em | Open testimonial interludes with hanging quotation marks. |
| plan-description | UntitledSerifFont | 400 | 30px | 1 | -0.03em | Compact two-line value proposition in paired plan cards. |
| tile-heading | UntitledSerifFont | 400 | 28px | 1.2 | -0.02em | Centered titles on three-up illustrated capability tiles. |
| support | UntitledSansFont | 400 | 18px | 1.4 | -0.02em | Centered section support and detailed offer copy. |
| eyebrow | UntitledSansFont | 500 | 16px | 1.5 | 0.01em, uppercase | Category labels above feature and section titles. |
| body | UntitledSansFont | 400 | 16px | 1.4 | -0.02em | Feature explanations, navigation links and captions. |
| action | UntitledSansFont | 500 | 16px | 1.5 | normal | Pill actions and selected controls. |
| footer-label | UntitledSansFont | 500 | 14px | 1.5 | 0.01em, uppercase | Footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience landing pages | offer-display | UntitledSerifFont | 400 | 70px | 1 | -0.03em | Large free-offer value at the bottom of audience plan cards. |
| pricing comparisons | comparison-price | UntitledSerifFont | 400 | 60px | 1.1 | -0.02em | Oversized total against smaller alternative prices. |
| audience landing pages | audience-heading | UntitledSerifFont | 400 | 52px | 1.1 | -0.025em | Centered audience-benefit and comparison headings. |
| capability detail pages | feature-detail-heading | UntitledSerifFont | 400 | 46px | 1.2 | -0.03em | Left-aligned alternating feature chapters. |
| audience landing pages | audience-support | UntitledSansFont | 400 | 20px | 1.625 | -0.025em | Longer audience-specific hero explanation. |
| audience landing pages | audience-body | UntitledSansFont | 400 | 18px | 1.625 | -0.025em | Benefit narratives beside a product demonstration. |
| workflow galleries | small-action | UntitledSansFont | 500 | 14px | 20px | normal | Award strips and small resource actions. |

**Notes:**

- Regular serif type carries authority; do not replace it with a bold sans display. Use roman for most promises, italic selectively for personal emphasis and invitations.
- The largest promise uses -0.03em tracking and a solid line height of 1; section titles loosen to 1.1. Body sans stays compact at -0.02em.
- Keep interface typography inside media subordinate to the marketing hierarchy; it is not an additional marketing font family.

## Layout

**Density:** Airy outside, compact inside: 120px between major blocks contrasts with 16px text stacks and densely layered product scenes.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tile title-to-caption gap and compact navigation spacing. |
| 12px | Gallery card insets and compact list gaps. |
| 16px | Eyebrow, title and body stacks; offer copy stacks. |
| 20px | Desktop page inset around the opening. |
| 24px | Three-column gutters and small card padding. |
| 32px | Plan-card interior and pill horizontal padding. |
| 40px | Feature-column and paired-plan gutters; opening title-to-action gap. |
| 48px | Pastel stage padding and conversion-band inset. |
| 60px | Section padding and heading-to-grid spacing. |
| 96px | Footer separation from preceding content. |
| 120px | Major section-to-section rhythm. |

### Containers and grids

- **reading container**: max width 1080px · side padding 0px. Default centered content spine; 180px side margins at a 1440px viewport.
- **wide detail container**: max width 1160px · side padding 24px. Alternating feature chapters and footer content.
- **navigation**: max width 920px. Floating, centered capsule, independent of the wider hero.
- **section introduction**: max width 720px. Centered title and restrained one- or two-line support.
- **feature tiles**: 3 columns · gap 24px. Three equal 344px-wide illustrated capability cards inside the reading container.
- **plan pair**: max width 920px · 2 columns · gap 40px. Equal 440px-wide light and dark plan cards.
- **faq**: max width 1000px. Single uninterrupted list of ruled questions and explanatory answers.
- **resource list** (only for ecosystem resource pages): 2 columns · gap 12px. Compact 534px-wide horizontal template rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | hero and gallery cards | 24px |
|  | feature stages | 32px |
|  | plan cards | 16px |
|  | quote avatars | 50% |
| workflow galleries | media wells | 10px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| paper stack | `rgba(0, 0, 0, 0.01) 0px 50px 40px 0px, rgba(0, 0, 0, 0.02) 0px 50px 40px 0px, rgba(0, 0, 0, 0.05) 0px 20px 40px 0px, rgba(0, 0, 0, 0.08) 0px 3px 10px 0px` | Major stages, plan cards and raised gallery shells. |
| glass pill | `rgba(0, 0, 0, 0.1) 0px 12px 12px 2px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px` | Floating navigation and translucent actions. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #fcf9f7`

#### Sky stage · level 1

**Use:** Default large opening backdrop.

**CSS:** `background: linear-gradient(in oklab, #9ed4ef 0px, #d1eef9 100%); border-radius: 24px; overflow: hidden`

**Observed:** Fine paper grain overlays the blue; a faint white fade softens the lower field. Clouds and collage are separate layers.

**Transfer:** Keep the airy blue stage and paper texture; introduce product-specific media in front.

#### Pastel feature stage · level 1

**Use:** Bounded product storytelling surface.

**CSS:** `background: #b8caf5; border-radius: 32px; padding: 48px; box-shadow: rgba(0, 0, 0, 0.01) 0px 50px 40px 0px, rgba(0, 0, 0, 0.02) 0px 50px 40px 0px, rgba(0, 0, 0, 0.05) 0px 20px 40px 0px, rgba(0, 0, 0, 0.08) 0px 3px 10px 0px`

**Observed:** Periwinkle, mint and butter variants share the same soft grain, subtle highlights and substantial rounded silhouette.

**Transfer:** Assign one pastel to each capability; preserve the white gaps between colored blocks.

#### Raised sheet · level 2

**Use:** Gallery and explanatory card shells.

**CSS:** `background: #ffffff; border: 1px solid rgba(3, 3, 2, 0.09); border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.01) 0px 50px 40px 0px, rgba(0, 0, 0, 0.02) 0px 50px 40px 0px, rgba(0, 0, 0, 0.05) 0px 20px 40px 0px, rgba(0, 0, 0, 0.08) 0px 3px 10px 0px`

**Observed:** White on warm paper is separated by both an almost invisible edge and a wide soft shadow.

**Transfer:** Use depth instead of a strong outline.

#### Charcoal paper · level 1

**Use:** Site-ending footer and dark premium offer.

**CSS:** `background: #030302; border-radius: 24px; color: #ffffff`

**Observed:** Black paper grain remains visible instead of a perfectly flat digital black.

**Transfer:** Use a low-opacity screened monochrome fiber texture; keep text contrast high.

#### Mint audience proof · level 1

**Only for:** audience landing pages

**Use:** Large proof panel with a statement and nested quote sheet.

**CSS:** `background: #d5f0db; border: 1px solid rgba(3, 3, 2, 0.09); border-radius: 24px; padding: 24px`

**Observed:** Two columns; the right side is a translucent white document containing gray quote boxes and small reaction chips.

**Transfer:** Pair a short, tall statement with authentic audience comments.

## Components

### Floating navigation

**Use:** Persistent primary navigation.

**CSS:** `position: fixed; top: 32px; max-width: 920px; height: 52px; border-radius: 26px; background: linear-gradient(rgba(255, 255, 255, 0.4) 10%, rgba(255, 255, 255, 0.8)); backdrop-filter: blur(4px); box-shadow: rgba(0, 0, 0, 0.1) 0px 12px 12px 2px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px; z-index: 50`

**Text style:** `body` — UntitledSansFont 400 · 16px/1.4 · tracking -0.02em

**Observed:** Centered capsule with a compact identity at left, short links through the middle and login plus a dark action at right. A fine luminous rim highlights the glass; it floats above every stage.

**Transfer:** Keep the menu concise and separate its width from the main container.

### Glass action

**Use:** Default hero and feature action.

**CSS:** `height: 48px; padding: 16px 32px; border-radius: 9999px; color: #030302; background: linear-gradient(rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.59) 25%, rgba(255, 255, 255, 0.6) 50%, rgba(255, 255, 255, 0.84) 75%); box-shadow: rgba(0, 0, 0, 0.1) 0px 12px 12px 2px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px`

**Text style:** `action` — UntitledSansFont 500 · 16px/1.5

**Observed:** Translucent light layers with a shiny rim sit above colored stages; text remains centered and on one line. The closing web action is 56px high with 24px corners.

**States:** Declared: hover color rgba(3,3,2,0.9) and the same glass-pill shadow.

### Dark action

**Use:** Navigation conversion and light plan-card conversion.

**CSS:** `background: #030302; color: #ffffff; height: 48px; padding: 16px 32px; border-radius: 9999px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

**Text style:** `action` — UntitledSansFont 500 · 16px/1.5

**Observed:** The compact navigation variant is 36px high with 8px 14px padding. On the dark offer, reverse the action to white. The platform-download variant is a wider 56px-high lozenge with platform mark.

**States:** Declared: hover background rgba(3,3,2,0.75); hover color rgba(3,3,2,0.9).

### Feature panel

**Use:** One capability explained through copy and staged interfaces.

**CSS:** `max-width: 1080px; padding: 48px; gap: 40px; border-radius: 32px; overflow: hidden`

**Text style:** `feature-heading` — UntitledSerifFont 400 · 36px/1.22 · tracking -0.03em

**Observed:** Uses Pastel feature stage. One narrower text column holds category, serif title, short explanation, Glass action and occasional icon links. The larger media column contains layered sheets; its side alternates.

**Transfer:** Show an actual input-to-output relationship rather than a generic device mockup.

### Open testimonial

**Use:** Breathing-space proof between feature blocks.

**CSS:** `max-width: 1080px; padding: 0px 48px; display: flex; gap: 40px; align-items: flex-start`

**Text style:** `quote` — UntitledSerifFont 400 italic · 32px/1.5 · tracking -0.04em

**Observed:** An italic quote spans roughly two thirds of the row. A circular portrait, plain sans name and thin gray rule occupy the remaining side; the side reverses between quotes. No enclosing card.

**Transfer:** Use one specific personal experience in place of a general endorsement.

### Plan card

**Use:** Compact offer pair on landing and capability pages.

**CSS:** `width: 440px; min-height: 422px; background: #ffffff; border: 1px solid rgba(3, 3, 2, 0.09); border-radius: 16px; overflow: hidden`

**Text style:** `plan-description` — UntitledSerifFont 400 · 30px/1 · tracking -0.03em

**Observed:** Interior is 32px. Title and two-line serif description sit at top; large serif price and action anchor the bottom. The second offer has black textured fill, inverse text and white action; leave a substantial open middle.

**Transfer:** Contrast usage patterns, not a long checklist of nearly identical features.

### Inset footer

**Use:** Consistent ending across page types.

**CSS:** `background: #030302; color: #ffffff; border-radius: 24px; padding: 0px 24px; margin: 96px 16px 16px; overflow: hidden`

**Text style:** `footer-label` — UntitledSansFont 500 · 14px/1.5 · tracking 0.01em · uppercase

**Observed:** Textured black paper, 1160px inner width and a six-track grid with 40px gaps. Five visible groups leave one breathing column before downloads. White uppercase group labels sit over fine rules and 14px/21px links; a lower rule separates copyright, language and outlined social squares.

**Transfer:** Preserve the inset dark slab and the deliberate gap between link groups, adjusting labels to the new product.

### Workflow gallery card

**Only for:** ecosystem and workflow galleries

**Use:** Real examples and community-made workflows.

**CSS:** `background: #ffffff; border: 1px solid rgba(3, 3, 2, 0.09); border-radius: 24px; padding: 12px; gap: 16px; overflow: hidden`

**Text style:** `eyebrow` — UntitledSansFont 500 · 16px/1.5 · tracking 0.01em · uppercase

**Observed:** Inset rounded media well above a title, byline, short description and faint arrow link. Three-up cards use 24px gutters; lead examples can span two columns with media beside a 46px serif title. Sheets overlap and tilt within muted colored wells.

**Transfer:** Use actual workflows with one visible result per example.

### Award strip

**Only for:** community workflow galleries

**Use:** Highlight a selected example without changing its card shell.

**CSS:** `background: #fff085; color: #733e0a; border-radius: 8px; padding: 4px 8px; gap: 4px; box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px`

**Text style:** `small-action` — UntitledSansFont 500 · 14px/20px

**Observed:** Small trophy and short season/category label pinned over the upper-left media corner. It resembles a raised yellow annotation, not an uppercase status chip.

### Question row

**Only for:** pricing and audience pages

**Use:** Resolve practical objections.

**CSS:** `max-width: 1000px; padding: 16px 0px; border-bottom: 1px solid rgba(3, 3, 2, 0.09)`

**Text style:** `support` — UntitledSansFont 400 · 18px/1.4 · tracking -0.02em

**Observed:** Question uses medium 18px sans, with a 22px outline chevron at right; answer uses regular 18px sans. Pricing opens one answer while audience guidance exposes many answers. The final row drops its rule.

**States:** Declared: hover text-decoration-line none; focus-visible border-color rgba(3,3,2,0.12) with no box-shadow.

## Imagery and graphics

### Torn-paper collage

**Use:** Signature framing in the opening and a later personalization or showcase moment.

**Observed:** Huge irregular scraps of white notebook paper, periwinkle fiber paper, pale gray paper and yellow ruled paper overlap. Torn edges have white fiber lips; some scraps show grids, dots or notebook perforations. Product media remains in front and the text stays on a clean patch.

**Transfer:** Use a real product result or a carefully built interface fragment in place of the original media; keep paper construction tangible rather than using smooth vector blobs.

**Build:** Draw 3–5 oversized irregular SVG polygons with short uneven edge segments. Back a gray or colored polygon with a slightly larger white silhouette to suggest a torn lip. Fill one scrap with a 40px square grid of 1px rgba(3,3,2,0.2) lines, another with sparse horizontal lines over butter, and one with periwinkle. Rotate scraps slightly in opposite directions; layer subtle SVG feTurbulence grain at 0.1–0.2 opacity and position the group across the lower half of a rounded stage.

### Halftone cloud

**Use:** Atmospheric punctuation at hero edges and around open section transitions.

**Observed:** Soft blue-white cloud puffs have blurred edges and a visible fine dot screen. They drift partly outside the container; the cloud is lighter and less defined than the foreground sheets.

**Transfer:** Retain the cloud as a paper-print atmosphere even for a non-document product.

**Build:** Combine 5 overlapping SVG ellipses into an irregular cloud silhouette around 480px by 247px. Use pale sky and white fills, blur the outer edge by 10–18px, and mask a 3px-spaced dot pattern through it at low opacity. Keep the center white and the lower edge softly blue; place behind text and cards, never across letterforms.

### Layered product sheets

**Use:** Hero object, feature stages and example cards.

**Observed:** Light interface windows with delicate borders, rounded corners and broad shadows overlap frontally or at small opposing rotations. Some feature panels use two-by-two white utility cards; detail chapters also use a hand interacting with a real phone inside a mint frame.

**Transfer:** Show two recognizable states or outputs from the new product, with real content density and a restrained palette. A minimum version is two legible, purpose-built interface sheets, not a generic chart dashboard.

### Paper-backed portraits

**Use:** Human proof showcase.

**Observed:** Friendly close-up people are cut out cleanly and placed on individual collaged colored backings. Tall rounded portrait cards sit in a wide row with soft shadows, uppercase sans identity captions and separate centered italic serif descriptions beneath.

**Transfer:** Use permissioned portraits of actual users, keep faces prominent and lighting natural, and give each a distinct paper backing. When portraits are unavailable, use photographed hands or tools from genuine use contexts with the same collage backing.

**Build:** Mask a portrait subject over a 24px-rounded vertical card. Place two torn SVG scraps behind it in mint, butter or periwinkle and white; add a sparse ruled or graph-paper pattern, then low-opacity monochrome grain. Keep the face unobstructed and the decorative layers behind the shoulders.

### Personalized object parade

**Use:** A full-bleed expression of personal choice.

**Observed:** A row of vividly varied document covers extends past both page edges over a torn-paper collage. Each cover is framed as a small rounded physical object with an inner bevel, contrasting edge and soft shadow; the section title remains calm above the row.

**Transfer:** Present the product's customizable outputs, themes or meaningful artifacts as a family of tactile objects. If the product has no themes, use varied finished outputs rather than inventing settings.

**Build:** Create 6–8 cover-like rectangular cards with 24px outer corners and inset 12px inner sheets. Vary muted paper fills and one photographic band per selected cover; use thin translucent inset highlights and low shadows to imply a raised frame. Run the row beyond the viewport and center a multi-scrap collage behind it.

### Brushwork and fiber

**Use:** Conversion band and material continuity across colored panels and footer.

**Observed:** Mint conversion surface carries broad pale brush sweeps; other panels have subtle grain and screened light texture. The footer is black with faint gray fibers, not a smooth gradient.

**Transfer:** Keep texture subordinate to readability and repeat it at two scales: coarse hand movement in a band, fine grain on panels.

**Build:** For brushwork, draw 2–3 long irregular SVG strokes diagonally upward across the mint panel in white at 0.2–0.3 opacity with round but slightly uneven ends. Overlay monochrome feTurbulence at low opacity with mix-blend-mode overlay. On black, screen the same grain at 0.4 opacity but reduce its image contrast so fibers remain faint.

### Icons

**Observed:** Small functional icons are mostly black outline SVGs: 16px with 2px round strokes for arrows and small actions, 22px chevrons for questions. Feature symbols are larger and lightly hand-drawn in feeling; partner marks retain their own colors inside rounded icon tiles.

**Transfer:** Choose simple outline icons with rounded stroke ends; reserve solid or multicolor marks for genuine platform identities.

## Section recipes

How recurring sections are built.

### First screen: Scrapbook sky opening

**Observed:** A sky stage begins 20px from the edges and occupies 828px of the first 900px. Floating navigation sits near the top, above a centered 666px-wide, two-line 66px serif promise in the upper-middle. A Glass action follows with 40px separation; there is no separate support paragraph in the default opening. Behind the words are blue paper grain, pale halftone clouds at both edges and extremely faint oversized outline identity artwork. Across the lower half, irregular torn notebook, periwinkle, gray and yellow papers form a foreground shelf. A large light interface window rises centrally through the collage, roughly two thirds of the stage width, with its bottom clipped by the stage. The first viewport contains navigation, full promise, action and upper product scene; detailed explanation begins below the fold.

**Transfer:** Use a concise human benefit, a single invitation and a believable product result rising from a new paper collage. Without supplied product media, compose two interface sheets containing the new product's actual inputs and outputs. Pricing opens with a smaller 54px headline above offer panels; capability pages use a mint stage, pale brush sweeps and a bottom category switcher; audience pages use a mint gradient, support, two actions and a device; ecosystem pages use a 54px promise with one italic word and a small orbit of platform tiles around two sheets.

**Avoid:** Do not convert the scene into a split-screen SaaS hero with a small laptop on the right, or add a paragraph that pushes the object entirely below the fold.

**Text style:** `display` — UntitledSerifFont 400 · 66px/1 · tracking -0.03em

### Editorial heading pair

**Observed:** Centered uppercase Eyebrow, heading-lg and Support are stacked with 16px gaps inside a 720px measure; 60px separates the introduction from the main grid.

**Transfer:** Name the next outcome plainly, then offer one sentence of explanation.

**Text style:** `heading-lg` — UntitledSerifFont 400 · 54px/1.1 · tracking -0.02em

### Pastel capability stage

**Observed:** Feature panel uses Pastel feature stage with 48px padding and a 40px gap. A 36px title, compact paragraph and Glass action occupy one side; layered product sheets occupy more space on the other. A small two-by-two icon-link group can sit below the copy.

**Transfer:** Turn one important capability into a scene with visible inputs and results; alternate media orientation across chapters.

**Text style:** `feature-heading` — UntitledSerifFont 400 · 36px/1.22 · tracking -0.03em

### Illustrated capability triptych

**Observed:** Editorial heading pair introduces three equal 344px-wide, 380px-high cards with 24px gaps. A 28px serif title and short muted caption sit near the top; product fragments rise from below, sometimes tilted, against distinct pastel photographic or paper backings.

**Transfer:** Compare three complementary ways to work, not three repetitive feature descriptions.

**Text style:** `tile-heading` — UntitledSerifFont 400 · 28px/1.2 · tracking -0.02em

### Human proof interlude

**Observed:** Open testimonial sits alone on warm paper between substantial stages. The quote is italic 32px with 48px line height, flanked by a name, tiny portrait and a horizontal rule. A wider portrait showcase uses a row of cutout people on collage backings with centered identity and use-case captions.

**Transfer:** Use the quote form for personal experience and the portrait row for breadth of users.

**Text style:** `quote` — UntitledSerifFont 400 italic · 32px/1.5 · tracking -0.04em

### Paired offer close

**Observed:** Centered heading and support lead into two Plan cards separated by 40px. The light offer and black premium offer share dimensions and bottom-anchored price/actions; a single understated group-discount link sits below.

**Transfer:** Make the choice about intensity or frequency of use; keep dense comparison tables in a separate pricing treatment.

**Text style:** `heading-lg` — UntitledSerifFont 400 · 54px/1.1 · tracking -0.02em

### Mint conversion invitation

**Observed:** A 1080px by 230px mint band has 32px corners, 48px padding and brushwork. The 56px italic invitation and 36px serif reassurance form the left block; web and platform actions form a compact right stack. Inset footer follows with substantial separation.

**Transfer:** Keep the large friendly invitation and the tactile band, adapting reassurance and platform choices to the product.

**Text style:** `closing-heading` — UntitledSerifFont 400 italic · 56px/1.1 · tracking -0.03em

### Pricing decision and comparison

**Only for:** pricing pages

**Observed:** The blue paper sky carries a 54px centered title above a narrow entry offer and a wide premium-family panel. The wide panel has a glass yearly/monthly segmented switch and three internal price columns. Below, a white rounded comparison sheet sits over large torn periwinkle and warm paper scraps; three columns compare feature label and two plans with dashed horizontal rules. A separate cost contrast makes the product total 60px serif while alternatives remain small. Question rows, a four-item award row and Inset footer finish the page.

**Transfer:** Use a clear default billing choice, aligned bottom actions and plain comparison facts. Let typography create the price contrast rather than oversized discount badges.

**Text style:** `heading-lg` — UntitledSerifFont 400 · 54px/1.1 · tracking -0.02em

### Workflow gallery and resources

**Only for:** ecosystem pages

**Observed:** A three-column gallery mixes two-column lead examples and single-column cards, then a consistent three-up community grid. Workflow gallery cards can carry Award strips. Lower sections switch to a two-column template list, then six-column grids of 80px partner icon tiles with centered names and uppercase protocol labels. A centered documentation invitation and outlined pill precede Inset footer.

**Transfer:** Move from inspiration to ready-made starting points to independent implementation; avoid repeating a broad trial pitch at every step.

**Text style:** `heading-lg` — UntitledSerifFont 400 · 54px/1.1 · tracking -0.02em

### Audience benefits and proof

**Only for:** audience landing pages

**Observed:** A centered 52px title introduces an alternating benefit carousel with a numbered uppercase label, 30px serif benefit, relaxed 18px paragraph, framed product media and mint arrows with elongated pagination marks. Mint audience proof pairs a large statement and bottom action with nested quote boxes and reaction chips. Two white offer cards use 70px serif values; comparison pills and a long ruled FAQ precede Inset footer.

**Transfer:** Show the audience's actual setting and practical constraints, then explain access and eligibility without cluttering the opening.

**Text style:** `audience-heading` — UntitledSerifFont 400 · 52px/1.1 · tracking -0.025em

## Page flow

**Storyline:** Personal promise → tangible product or people proof → capability stories → practical choice or starting point → objections and a context-appropriate ending.

### Broad product landing page

1. **promise** — Scrapbook sky opening and short personal-use statement.
2. **social proof** — Paper-backed portrait showcase.
3. **capability chapters** — Pastel feature scenes punctuated by open italic testimonials and a compact awards row.
4. **personal expression** — Illustrated capability triptych and full-width personalized object parade.
5. **community** — Four tactile community destination tiles with cloud punctuation.
6. **pricing** — Paired light and dark offers.
7. **closing call** — Mint conversion invitation and inset charcoal footer.

**Transfer:** Use product objects and human evidence in alternation so an expansive product still feels approachable.

### Plan decision page

1. **pricing** — Sky-backed entry offer beside a wide multi-plan premium sheet and billing switch.
2. **comparison** — Large white ruled comparison sheet over torn paper.
3. **quantified proof** — Small alternative prices contrast with a large serif combined value.
4. **objection handling** — Compact question list.
5. **trust and ending** — Four award objects with captions, then inset charcoal footer; no extra mint conversion band.

**Transfer:** Put the decision first and supporting rationale after it.

### Capability detail page

1. **promise** — Mint paper opening with brush sweeps and category switcher.
2. **demonstration** — Alternating copy and mint-framed product examples, including a six-card block anatomy scene.
3. **social proof** — Open italic testimonials between deeper feature explanations.
4. **pricing** — Shared paired-offer module.
5. **closing call** — Mint conversion invitation and inset footer.

**Transfer:** Use one color to unify the capability chapter while varying the media arrangement.

### Ecosystem and inspiration page

1. **promise** — Sky, clouds and orbiting partner tiles around a product result.
2. **inspiration** — Mixed-span example gallery followed by community gallery with annotation-like awards.
3. **starting points** — Two-column template list.
4. **implementation guidance** — Partner icon directory grouped by connection method.
5. **closing call** — Documentation invitation and outlined resource action, then inset footer.

**Transfer:** Move the reader from what is possible to something they can start or build; keep the ending technical rather than a generic sales banner.

### Audience-specific offer page

1. **promise** — Mint hero with device, graph-paper tear, two actions and a compact trust line.
2. **benefits** — Numbered benefit carousel beside a product document.
3. **social proof** — Mint proof panel with document-like quotes and reaction chips.
4. **offer** — Two detailed white access cards with oversized serif values.
5. **comparison** — Small comparison pills.
6. **objection handling and ending** — Long expanded practical FAQ, followed directly by inset footer after an airy gap.

**Transfer:** Tailor the use context, proof and access details while retaining the same paper materials and serif hierarchy.

## Writing

Warm, personal and gently confident. The product is presented as a place for thinking rather than machinery; concrete everyday actions keep the emotional language credible.

**Do not copy:** Do not reuse Craft's name, logo, product-specific terminology, partner relationships, named users, testimonials, awards, prices, audience counts or performance and access claims. Examples illustrate phrasing, not facts for a new product.

- **Addressing the reader:** Speak directly to you and your work; mention the product by name sparingly. Use we mainly for practical explanations and support.
- **Rhythm:** Short conversational titles, often 4–9 words, followed by a one- or two-sentence explanation. Pair clipped assurances with a longer explanatory sentence; contractions and em dashes are natural.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Possessive invitation plus concrete things the reader makes or does. | 8–12 words | “Your space for notes, tasks, and big ideas” |
| Feature title | Everyday action or contrast with a satisfying human outcome. | 5–9 words | “From first thought to final form”<br>“Write first. Structure later.”<br>“Save it before it slips away” |
| Section invitation | Personal agency, not a technical feature inventory. | 4–7 words | “Make it unmistakably yours”<br>“Some Ideas to Get You Started” |
| Supporting line | Explain freedom of use in plain words, often with a balanced pair. | 10–25 words | “Use it now and then, or integrate it into your daily flow.” |
| Action | Simple verb and low-pressure next step. | 2–4 words | “Try [Brand] Free”<br>“Learn more”<br>“Browse app templates” |
| Closing reassurance | Two short practical assurances, without hype. | 6–10 words | “Start for free. No credit card required.” |

**Words and phrasing to use:** your; space; thinking; ideas; make it yours; flow; start; together; when you're ready

**Avoid:** revolutionize; 10x; supercharge; enterprise-grade everything; disrupt; unleash your potential

**Rules:**

- State a recognizable human outcome before naming the mechanism.
- Use specific everyday examples to explain breadth; do not stack abstract benefit nouns.
- Keep action labels short and calm; place eligibility and billing details in explanatory sections.
- Use sentence case as the default for new copy, with uppercase reserved for category and utility labels.

## Do's and Don'ts

### Do

- Keep the main serif promise at 66px, weight 400 and line height 1 on desktop.
- Use 1080px as the core storytelling width and 120px between major blocks.
- Maintain 32px corners and 48px inner padding on large pastel feature panels.
- Keep 16px/1.4 sans feature paragraphs smaller than the 36px serif feature title.
- Use both a faint 1px edge and a broad low-opacity shadow to separate white cards from paper.
- Preserve irregular paper edges, subtle grain and at least one halftone cloud treatment.
- Use one italic 32px testimonial as an open interlude rather than boxing every proof item.
- Finish with the inset black textured footer and its 24px corners.

### Don't

- Do not turn regular serif titles into heavy bold display text.
- Do not apply pastel colors to every reading section; keep the warm paper gaps continuous.
- Do not use rectangular primary buttons or colored brand-action fills; the action language is glass, black and white pills.
- Do not replace broad translucent shadows with crisp high-opacity drop shadows.
- Do not use glossy 3D device sculptures as the dominant visual language; sheets and handmade paper carry the depth.
- Do not give the default landing hero several equal-weight conversion actions; the two-action pattern belongs to the audience variant.
- Do not make the footer edge-to-edge or flatten its fiber texture into a solid dark band.
- Do not bring partner logos, code fonts or colorful interface status tokens into the marketing type and palette system.

## Motion and responsive

### Motion

**Observed:**

- Glass action declares all 0.5s cubic-bezier(0,0,.2,1); dark action declares all 0.2s cubic-bezier(.4,0,.2,1).
- Navigation backdrop-filter declares 0.1s cubic-bezier(.4,0,.2,1).
- Question rows declare opacity 0.3s cubic-bezier(.4,0,.2,1); common color transitions declare 0.2s cubic-bezier(.4,0,.2,1).

**Transfer:**

- Let material shifts such as translucency and shadow carry action feedback; do not introduce unrelated bouncy motion.
- Keep the persistent floating navigation visually independent of scrolling paper scenes.

**Unknown:**

- Runtime choreography of collage, cover parade and partner orbit; no precise entrance timeline is established.

### Responsive

**Observed:**

- Styles include breakpoints at 640px, 768px, 1024px, 1280px and 1536px among additional widths.
- Declared classes change the illustrated triptych and plan pair from columns to a single stack, reduce outer section gaps from 120px to 80px, and hide desktop navigation links below the medium breakpoint.
- Declared closing title sizes are 40px then 56px; open testimonial text is 24px then 32px.

**Transfer:**

- On narrow layouts, stack copy above media while keeping torn-paper layers behind the object; preserve an uncluttered headline patch.
- Keep a visible portion of the product result in the opening instead of shrinking the entire desktop collage into an unreadable miniature.
- Reduce the portrait showcase to an overflow row or stacked cards while retaining readable identity captions.

**Unknown:**

- Exact mobile viewport compositions, mobile navigation interaction and final breakpoint-specific media positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
