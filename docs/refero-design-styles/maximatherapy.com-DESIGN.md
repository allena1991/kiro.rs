# Maxima Therapy — a world of play

## Overview

An exuberant, human-centered style that treats a service as a colorful world to explore. Cream and butter-yellow grounds meet primary blue, orange-red and lively green, with tightly packed condensed display lettering and friendly rounded sans-serif text. Natural, warmly lit photography mingles with flat geometric characters, clouds and oversized letterforms; immersive illustration chapters alternate with spacious, practical white panels.

### Essentials

- Headlines behave like soft-edged poster lettering: Robuck Rounded uppercase at 214.3px/0.8, normal tracking, with short lines stacked into tall blocks; explanatory headings switch to rounded sans at 33.3px/1.05 and -0.02em.
- The opening is an illustrated world rather than a conventional text-and-image split: a full-width stage, floating white navigation at 55.2px tall, a small separate identity mark, circular controls and a centered orange-red introduction card about 435px wide.
- Color occupies whole chapters, not little decorative accents: butter yellow #fff2b7 backs the long interactive introduction, cream #f3efe0 backs the editorial middle, white contains practical information, and green #00b351 carries the default closing world.
- Actions look like rounded toy pieces: 55.2px-high pill buttons, 26.7px horizontal padding, 47.6px corners, with blue conversion actions and a separate orange-red navigation action.
- Real life and imagination share the same plane: full-width natural-light photographs receive opaque flat-color clouds, plants, creatures and architectural forms; use a geometric illustration world as the equivalent when photography is unavailable.
- Letterforms become scenery: include a giant blue rounded word sculpture at 575.2px/1 with -0.02em tracking, plus a monumental closing identity treatment inside a white 9.5px-radius footer panel. Adapt the words and identity to the new product.
- Feature explanations feel like a shuffled deck: centered 23.8px-radius colored cards, 57.1px by 47.6px padding, a title above a geometric emblem and compact centered copy, with contrasting rotations and overlaps.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Play blue | `#2668fd` | `--color-blue` | text, action, accent, surface | Giant word sculpture, conversion pills, icons and feature cards. |
| Orange red | `#fd4401` | `--color-orange` | text, action, surface, accent | Default poster headlines, introduction card, selected feature cards and navigation action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sun yellow | `#fdcb40` | `--color-yellow` | surface, accent, text | Illustration shapes, selected feature cards and warm secondary actions; also the background of the company-story opening and ending. |
| Grass green | `#00b351` | `--color-green` | background, surface, text | Default closing chapter and green themed capability cards and poster headings. |
| Light green | `#a7eb98` | `--color-mint` | text, background | Pale closing headline on green; alternate introduction ground for a later-stage offering. |
| Butter yellow | `#fff2b7` | `--color-butter` | background, text | Default immersive introduction ground and pale lettering on orange-red cards. |
| Social pink | `#ffcccd` | `--color-salmon` | surface | Small circular social actions, not the main page ground. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black text | `#000000` | `--color-ink` | text | Body copy and practical headings on light panels. |
| Cream | `#f3efe0` | `--color-canvas` | background | Editorial middle chapters and open space around photos and white panels. |
| White | `#ffffff` | `--color-white` | surface, text, background | Navigation, practical panels, clouds and reverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruiting and adjacent-offering pages | Bright pink | `#f780d4` | `--color-pink` | background | Closing world for recruiting and adjacent-offering pages. |
| recruiting pages | Pink lettering | `#ffa8e5` | `--color-rose` | text | Oversized lettering against a blue opening. |
| adjacent-offering pages | Lilac lettering | `#f5cbff` | `--color-lilac` | text | Oversized next-offering title against the pink closing world. |

## Typography

- **ABC Diatype Rounded Plus** — Body, navigation, buttons, compact headings and tags. Friendly rounded grotesk with tight spacing and substantial medium and bold weights. If unavailable, use **Nunito Sans**. Use 500 and 700; retain tight tracking and compact line heights. Font stack: "ABC Diatype Rounded Plus", "Nunito Sans", Arial, sans-serif.
- **Robuck Rounded** — Poster headlines, manifestos, quotations and introduction-card titles. Very condensed, heavy-looking uppercase with softly rounded ends; its regular cut supplies the display weight. If unavailable, use **Barlow Condensed**. Use 900 to approximate the narrow heavy silhouette; soften corners in custom outlined lettering. Font stack: "Robuck Rounded", "Barlow Condensed", Impact, sans-serif.
- **ABC Diatype Rounded** — Oversized blue word sculpture. Extra-heavy rounded sans whose open counters and broad lowercase forms act as objects. If unavailable, use **Nunito**. Use 900 with -0.02em tracking. Font stack: "ABC Diatype Rounded", "Nunito", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | ABC Diatype Rounded | 900 | 575.2px | 1 | -0.02em | Blue oversized letterforms crossing the width and bleeding into the following scene. |
| display | Robuck Rounded | 400 | 214.3px | 0.8 | normal, uppercase | Monumental editorial stacks and closing destination headlines. |
| manifesto | Robuck Rounded | 400 | 61.9px | 0.8 | normal, uppercase | Centered belief statements, introduction-card titles and large testimonial text. |
| heading | ABC Diatype Rounded Plus | 700 | 33.3px | 1.05 | -0.02em | Practical-panel lead and feature-card headings. |
| heading-small | ABC Diatype Rounded Plus | 700 | 23.8px | 1.05 | -0.02em | Short section lead-ins, small card titles and closing prefaces. |
| body | ABC Diatype Rounded Plus | 500 | 19px | 1.2 | -0.02em | Paragraphs, captions and footer navigation. |
| action | ABC Diatype Rounded Plus | 500 | 19px | 2.9 | -0.02em | Single-line pill labels and navigation labels. |
| eyebrow | ABC Diatype Rounded Plus | 500 | 13.7px | 1.2 | normal, uppercase | Compact section categories and small white tags. |

**Notes:**

- Condensed display text is heavy in appearance even though the declared font weight is 400. Do not replace it with medium-weight wide sans.
- Rounded sans uses -0.02em tracking throughout its main roles; display capitals retain normal tracking and a compressed 0.8 line height.
- The root size follows 1.0582vw on desktop, so rem-based typography and spacing grow together. Preserve relative proportions rather than independently enlarging headings.
- Poster statements are line-broken for silhouette; isolated words and letters can tilt or stretch as art, while explanatory text remains upright.

## Layout

**Density:** Airy in the landscape and editorial chapters, compact within cards and practical information groups.

### Spacing

| Value | Use |
| --- | --- |
| 19px | Main grid gutters. |
| 26.7px | Pill-button horizontal padding. |
| 28.6px | Small section inset above a practical panel. |
| 38.1px | Practical heading-to-action separation. |
| 47.6px | Desktop page margins, footer inset and card horizontal padding. |
| 57.1px | Feature-card vertical padding and larger component separation. |
| 76.2px | Closing preface-to-title spacing. |
| 119px | White practical-panel vertical padding. |

### Containers and grids

- **page-grid**: 12 columns · gap 19px · side padding 47.6px. Full-width desktop structure. Editorial headline occupies about five columns starting one column in; a much smaller paragraph sits toward the far right.
- **practical-panel**: 2 columns · side padding 47.6px. A white panel spanning the inset page width. Left column holds a narrow lead and button; right column holds repeated explanatory rows.
- **statement**: max width 895px. Centered condensed manifesto, broken into a few dense lines.
- **opportunity-grid** (only for recruiting or directory pages): 3 columns · gap 19px. White linked tiles beneath a monumental title, wrapping to a second row.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 47.6px |
| feature-cards | 23.8px |
| practical-panels | 9.5px |
| tags | 4.8px |
| icon-buttons | 50% |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Editorial chapters.

**CSS:** `background: #f3efe0`

**Observed:** Flat, opaque and untextured; illustrations and photographs overlap its boundaries.

**Transfer:** Let spacious cream intervals separate highly colored worlds.

#### Butter stage · level 0

**Use:** Default immersive introduction and feature-card deck.

**CSS:** `background: #fff2b7; overflow-x: clip`

**Observed:** Full-bleed color with white cloud silhouettes and strongly contrasting cards.

**Transfer:** Use one dominant pale chapter color, not alternating tiny tinted boxes.

#### White information panel · level 1

**Use:** Practical information, team invitation and footer.

**CSS:** `background: #ffffff; border-radius: 9.5px; box-shadow: none`

**Observed:** Inset against the canvas or a saturated closing chapter; separation comes from fill, not an outline.

**Transfer:** Reserve white containers for moments when the reader needs to understand or act.

#### Green closing world · level 0

**Use:** Default related destination and footer surround.

**CSS:** `background: #00b351`

**Observed:** Pale green monumental lettering, white clouds, a large character and a white footer panel form one continuous scene.

**Transfer:** Give the closing destination the scale of a fresh illustrated chapter.

#### Blue recruiting world · level 0

**Only for:** recruiting pages

**Use:** Culture-led opening.

**CSS:** `background: #2668fd; clip-path: polygon(0% 0%, 0% 100%, 100% 85%, 100% 0%)`

**Observed:** Pink display text and large flat character art, with white supporting copy; the bottom edge cuts diagonally.

**Transfer:** Keep this saturated opening distinct from the pale default stage.

#### Pink closing world · level 0

**Only for:** recruiting and adjacent-offering pages

**Use:** Alternate footer surround and next-destination scene.

**CSS:** `background: #f780d4`

**Observed:** White cloud silhouettes and the same inset white footer; adjacent-offering version adds lilac display text.

**Transfer:** Change the world color to distinguish an audience or destination, preserving component construction.

## Components

### Floating navigation

**Use:** Persistent compact navigation above illustrated and photographic scenes.

**CSS:** `display: flex; background: #ffffff; border-radius: 47.6px; height: 55.2px`

**Text style:** `action` — ABC Diatype Rounded Plus 500 · 19px/2.9 · tracking -0.02em

**Observed:** Separate small identity mark at the left; right-aligned white link capsule, orange-red action pill and independent round envelope control. Two dropdown labels carry tiny blue downward triangles.

**Transfer:** Keep navigation compact enough to float over artwork instead of creating a full-width white bar.

### Primary button

**Use:** Conversion within practical panels and footer.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #2668fd; color: #ffffff; height: 55.2px; padding: 0px 26.7px; border-radius: 47.6px`

**Text style:** `action` — ABC Diatype Rounded Plus 500 · 19px/2.9 · tracking -0.02em

**Observed:** Single-line label, without a trailing arrow. Secondary contextual pills can use yellow or a darker tone belonging to the illustrated chapter.

**Transfer:** Use concise verbs and retain the soft horizontal capsule.

### Navigation action

**Use:** Distinct high-visibility action beside the navigation capsule.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #fd4401; color: #ffffff; height: 55.2px; padding: 0px 26.7px; border-radius: 47.6px`

**Text style:** `action` — ABC Diatype Rounded Plus 500 · 19px/2.9 · tracking -0.02em

**Observed:** Independent from the white navigation capsule and the envelope circle.

### Feature deck card

**Use:** Explain one capability at a time in the immersive introduction.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: space-between; background: #fd4401; border-radius: 23.8px; padding: 57.1px 47.6px; text-align: center`

**Text style:** `heading` — ABC Diatype Rounded Plus 700 · 33.3px/1.05 · tracking -0.02em

**Observed:** Title, flat geometric emblem and body paragraph in that order. Orange-red, blue, white and yellow cards overlap with different tilts; white cards use black copy, dark saturated cards use white copy. The heading color can contrast independently from the paragraph.

**Transfer:** Use a recognizable simple emblem per capability; keep each card readable as a complete object.

### Introduction card

**Use:** Name the selected world and summarize its benefit.

**CSS:** `background: #fd4401; border-radius: 23.8px; width: 435px; text-align: center; padding: 42.7px 47.6px`

**Text style:** `manifesto` — Robuck Rounded 400 · 61.9px/0.8 · uppercase

**Observed:** Centered condensed pale-yellow title, white category tag, two-line white support copy, and an outlined circular downward control. Sits below the illustrated scene between distant circular carousel controls.

**Transfer:** Make this an invitation into the next chapter, not a dense conversion form.

### Category tag

**Use:** Short audience or category qualifier.

**CSS:** `background: #ffffff; color: #000000; border-radius: 4.8px; padding: 6.7px 6.7px 4.2px`

**Text style:** `eyebrow` — ABC Diatype Rounded Plus 500 · 13.7px/1.2 · uppercase

**Observed:** Small uppercase label centered between title and support copy in the introduction card.

### Social circle

**Use:** Footer social links.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffcccd; border-radius: 50%; width: 55px; height: 55px`

**Observed:** Three nearly touching pink circles with blue social glyphs sit beside the blue conversion pill.

### Footer panel

**Use:** Monumental identity-led ending.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 19px; background: #ffffff; border-radius: 9.5px; padding: 47.6px 0px`

**Text style:** `body` — ABC Diatype Rounded Plus 500 · 19px/1.2 · tracking -0.02em

**Observed:** Two compact link columns at upper left; social actions and conversion pill at upper right. Large open middle. Oversized illustrated lowercase identity spans the lower left, while tiny underlined utilities sit at lower right. It is inset 47.6px from the colored world and is about 700px tall on desktop.

**Transfer:** Create a new oversized identity with small friendly geometric figures perched on its letters; keep the bottom a designed scene rather than a generic legal strip.

### Footer text link

**Use:** Compact navigation within the white footer panel.

**CSS:** `position: relative; color: #000000; text-decoration: none`

**Text style:** `body` — ABC Diatype Rounded Plus 500 · 19px/1.2 · tracking -0.02em

**Observed:** Stacked into short columns; a black pseudo-element supports link decoration. Small utility links use underlining instead.

## Imagery and graphics

### Geometric play world

**Use:** Opening landscape, oversized chapter breaks and closing character scenes.

**Observed:** Opaque flat-vector forms: arched buildings, stacked oval trees, triangular roofs and kites, simplified people, flowers and smiling creatures. Primary blue, orange-red, yellow and green dominate; white cloud clusters float across generous light grounds. No lighting, shading, grain or dimensional rendering.

**Transfer:** Make a new world around the product's benefit using the same circles, arches, triangles and rounded bars. A coherent arrangement of a few large geometric forms is the minimum, rather than a collage of stock icons.

**Build:** Use layered SVG groups: a broad arch behind the scene, two or three stacked ellipses for foliage, rectangular trunks, triangular accents and small black circular eyes with a short curved smile. Place clusters of three to five overlapping white circles at different edge heights. Scale the main composition nearly to page width and let parts exit the viewport. Use flat palette fills without outlines; reserve thin curves for strings, stems and smiles.

### Illustrated real-life panorama

**Use:** Wide emotional proof between manifesto and editorial chapters.

**Observed:** Natural-light photos of people engaged in real activities fill the width and most of a viewport. Domestic and work settings keep their warm neutral color. Flat clouds, plants, fantastical objects and characters sit in front of and around people without tinting the photo. Top and bottom boundaries can be gently diagonal.

**Transfer:** Photograph the human outcome of a product rather than a person pointing at a screen. Overlay custom geometric motifs, keeping faces and important actions clear. If no appropriate photo exists, extend the geometric play world into a full-width outcome scene.

**Build:** Place an object-fit: cover photograph in a wide clipped band; add absolutely positioned SVG layers at the side edges and corners. Put one large solid-color arch or sweep behind the visual subject and several smaller vector objects in the foreground. Keep photographic shadows intact and illustration fills completely opaque.

### Photo fragments

**Use:** Editorial support beside giant headline stacks and in company-story chapters.

**Observed:** Warm candid photos split into offset rectangular pieces or paired like slightly rotated prints, with modestly rounded corners on the cream ground. The pieces overlap or interlock without a visible frame or shadow.

**Transfer:** Use one coherent scene divided into two offset panels, not unrelated photo thumbnails.

### Word sculpture

**Use:** A signature bridge from manifesto into photographic scenery.

**Observed:** Enormous blue lowercase rounded letters tip and drift across the width. They overflow the viewport and overlap the next scene instead of sitting neatly on a typographic baseline.

**Transfer:** Use a few short action words meaningful to the new product and treat them as objects, preserving broad counters and a playful silhouette.

**Build:** Render individual letters or words as heavy rounded SVG text paths or positioned text spans using the word-sculpture recipe. Offset their baselines and rotate selected groups. Clip horizontal overflow in the parent; let the lower letter shapes overlap the following panorama. Use solid blue with no shadow.

### Poster stickers

**Use:** Punctuation for towering editorial headline stacks.

**Observed:** A small smiling sun, dotted butterfly, pencil or book crosses the edge of huge display words. Stickers have vivid flat fills and a white silhouette rim rather than a drop shadow.

**Transfer:** Use two relevant symbols to punctuate a large stack, keeping the letter silhouette dominant.

**Build:** Create two small SVG symbols from circles, petals, rounded rectangles or triangles. Add a thicker white copy of the outer silhouette behind each symbol as a sticker rim. Rotate the groups in opposite directions and position them across different edges of the headline block.

### Portrait quotation

**Only for:** testimonial sections

**Use:** Human attribution beside an expressive quotation.

**Observed:** Circular photographic portrait at left, oversized orange-red opening quotation marks overlapping its upper edge, and a tall condensed blue quote to the right. Attribution is small black rounded sans below.

**Transfer:** Use a real speaker and a compact benefit-centered quote; preserve the portrait/typographic scale contrast.

### Icons

**Observed:** Small solid blue arrows and triangles, simple envelope outline and blue social glyphs. Dropdown triangles are about 10px by 9px; carousel arrows about 27px by 16px sit in white circular controls; social glyphs range from 12px to 25px wide.

**Transfer:** Use chunky, friendly directional marks rather than a thin technical line-icon library; place standalone actions inside circles.

## Section recipes

How recurring sections are built.

### First screen: Illustrated world opening

**Observed:** The opening is a full-width illustrated carousel stage about 990px tall at the desktop viewport. A small identity mark floats at upper left and Floating navigation occupies the upper right, inset 47.6px. Large geometric scenery is the main object and fills the upper screen; an Introduction card is centered beneath it and distant white circular previous/next controls bracket the stage. The introductory title uses manifesto lettering, not the monumental editorial stack. Within a 900px first screen, prioritize the navigation, central illustration and beginning of the introduction card; the full support line and downward invitation can continue below the fold. Behind the card is the Butter stage, with white clouds at the edges; feature-deck detail belongs below the opening.

**Transfer:** For a different product, compose a large benefit-world from simple SVG shapes and use the Introduction card to name the promise. Where no equivalent media exists, geometric architecture, a character and two symbolic objects still provide a strong main object. Recruiting and company-story pages instead use an enormous display promise over a blue or yellow diagonal-ended illustrated field, with a compact supporting paragraph offset to the right.

**Avoid:** Do not substitute a small photograph next to a conventional medium headline, or let decorative layers cover the title or navigation.

**Text style:** `manifesto` — Robuck Rounded 400 · 61.9px/0.8 · uppercase

### Shuffled capability deck

**Observed:** Feature deck cards occupy the center of a pale full-width world. Several differently colored and rotated cards are visible as a stack, while one title/emblem/paragraph face is dominant. White clouds balance the open side areas.

**Transfer:** Map one capability to one card and use overlap to communicate a family of offerings without requiring a long ordinary grid.

### Manifesto and letter landscape

**Observed:** A centered manifesto spans about 895px, set in orange-red on butter or green on mint, with a yellow contextual pill beneath. The Word sculpture follows as a visual landscape that bridges into the Illustrated real-life panorama.

**Transfer:** Use one compact belief statement and a few short active words; let the letter landscape provide the spectacular proof of personality.

**Text style:** `manifesto` — Robuck Rounded 400 · 61.9px/0.8 · uppercase

### Towering editorial argument

**Observed:** On Cream canvas, a five-column stack of display words starts one grid column in. Poster stickers cross its edges. A narrow body paragraph and Primary button sit far to the right, with Photo fragments extending beneath them. The headline, not the paragraph, determines the section height.

**Transfer:** State one strategic benefit in short stackable words, then give the substantive explanation in the smaller side column.

**Text style:** `display` — Robuck Rounded 400 · 214.3px/0.8 · uppercase

### Practical reassurance panel

**Observed:** White information panel is inset 47.6px and has 119px vertical padding. Left column has a narrow heading and Primary button; the right holds three vertically spaced steps with colorful face emblems, short bold titles and compact descriptions. Recruiting uses the same split layout for six benefits with pink circular check marks.

**Transfer:** Explain the next steps or reduce an adoption concern in plain language; use the split panel for information that must be scanned rather than admired.

**Text style:** `heading` — ABC Diatype Rounded Plus 700 · 33.3px/1.05 · tracking -0.02em

### Human quotation

**Observed:** Portrait quotation pairs a circular portrait at left with a condensed blue quote at right, roughly 626px to 662px wide. Orange-red quote marks punctuate the portrait; a body-size attribution completes the text block. Cream remains open around both halves.

**Transfer:** Insert personal proof without converting it into a conventional testimonial card grid.

**Text style:** `manifesto` — Robuck Rounded 400 · 61.9px/0.8 · uppercase

### Next world and monumental footer

**Observed:** Green closing world carries a white heading-small preface, a pale-green display destination, a centered action and a large character rising behind the Footer panel. White clouds drift around the title. The panel preserves a broad empty middle and oversized identity at the bottom. Recruiting ends in a pink cloud world without a destination headline; company-story ends in yellow; adjacent-offering pages use pink with lilac display text.

**Transfer:** Turn the next relevant destination into a colorful invitation, then finish with the identity-led Footer panel. Every new page needs the monumental closing identity; the destination subject and its position can change.

**Text style:** `display` — Robuck Rounded 400 · 214.3px/0.8 · uppercase

### Recruiting directory

**Only for:** recruiting or directory pages

**Observed:** A two-line orange-red display title precedes a three-column array of small white rounded linked tiles, with blue bold titles and cream circular arrow controls. A separate open-application invitation and blue button appear below.

**Transfer:** Use for a finite set of opportunities or locations, not for the default immersive capability introduction.

**Text style:** `display` — Robuck Rounded 400 · 214.3px/0.8 · uppercase

## Page flow

**Storyline:** immersive invitation → tangible capabilities → belief and human outcome → deeper benefit → practical reassurance or personal proof → next destination and identity-led ending

### Broad marketing introduction to a family of offerings

1. **Invitation** — Illustrated carousel world and introduction card.
2. **Capabilities** — Colored shuffled feature deck in an extended pale world.
3. **Belief and outcome** — Centered manifesto, giant blue letter landscape and illustrated photography.
4. **Deeper benefit** — Monumental word stack with compact explanation, stickers and photo fragments.
5. **Reassurance** — Large geometric scene followed by a white split-panel process.
6. **Next destination and ending** — Green illustrated destination chapter and monumental white footer.

**Transfer:** Use the expansive visual journey for a broad audience; adapt the capability count and editorial depth to the product.

### Recruiting and culture-led conversion

1. **Promise** — Blue diagonal-ended illustrated world with monumental pink display statement.
2. **Human context** — Offset warm photo fragments.
3. **Practical value** — White split benefits panel.
4. **Social proof** — Circular portrait and condensed blue quotation.
5. **Outcome** — Full-width activity photo mixed with vector scenery.
6. **Conversion** — Monumental opportunity title, three-column linked tiles and a separate open invitation.
7. **Ending** — Pink clouds and the shared monumental white footer.

**Transfer:** Use culture, practical value and opportunities as separate registers rather than forcing everything into the product-story deck.

### Company-story and values-led trust

1. **Promise** — Yellow diagonal-ended illustrated opening with orange-red display statement and supporting narrative.
2. **Belief** — Photo fragments followed by a small blue lead and centered orange-red manifesto.
3. **Human outcome** — Full-width photography layered with imaginative flat forms.
4. **Personal proof** — Portrait quotation on cream.
5. **Invitation** — White two-column panel with concise text, blue action and warm team photo.
6. **Ending** — Yellow world and shared monumental white footer.

**Transfer:** Favor a coherent belief and human story over an exhaustive chronology.

### Focused offering landing page within a larger family

1. **Invitation and capabilities** — Mint world, selected introduction card and colored feature deck.
2. **Belief and outcome** — Green manifesto, blue letter sculpture and illustrated human panorama.
3. **Deeper benefit** — Green towering display stack, stickers, supporting paragraph and photo fragments.
4. **Reassurance** — Large geometric scene and white three-step panel.
5. **Next destination** — Pink world with lilac monumental title and a new character.
6. **Ending** — Shared white identity-led footer on the same pink ground.

**Transfer:** Keep the family structure while changing the pale introduction color, emblem set and adjacent destination.

## Writing

Warm, direct and optimistic without talking down to the reader. Emotional promises are paired with concrete descriptions of what support or participation actually involves.

**Do not copy:** Do not reuse Maxima names, logos, signature characters, program names, age bands, professional claims or testimonial quotations as claims for another product. Source examples illustrate voice only.

- **Addressing the reader:** Use we for the organization and you or your for the reader; describe the people benefiting in respectful, everyday language.
- **Rhythm:** Short poster-like headlines contrast with fuller explanatory paragraphs. Practical rows use a brief action-oriented title and one or two sentences; calls to action stay compact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Display promise | Make an empathetic promise in a few common words, suitable for stacking. | 4–10 words | “support that grows with you”<br>“The First Years Matter Most” |
| Belief statement | A collective we statement joins a human value to a concrete outcome. | 15–30 words | “We bring fun and curiosity to therapy, supporting each child’s unique path to growth.” |
| Practical lead | Acknowledge hesitation before explaining that the process is manageable. | 15–25 words | “We understand this can be a big step, but we made the process as quick, easy, and stress-free as possible.” |
| Capability support | Name what the service does and the human result in plain language. | 10–40 words | “Nurturing growth through play, therapy, and parent support.” |
| Action | A plain verb with a short destination or outcome. | 2–3 words | “Get started”<br>“Apply Now”<br>“Explore Careers” |

**Words and phrasing to use:** support; grow; together; every step; understand; confidence; care; learn; your own steps

**Avoid:** disrupt; dominate; unlock limitless potential; revolutionary solution; clinical jargon without explanation

**Rules:**

- Make warmth specific by describing actions and everyday outcomes.
- Use playful visual presentation without babyish language.
- Follow a broad emotional promise with a useful explanation.
- Treat people's differences with dignity; avoid deficit-based persuasion.
- Use restrained punctuation; typography carries the enthusiasm.

## Do's and Don'ts

### Do

- Pair 214.3px condensed poster lettering with 19px rounded supporting text.
- Keep desktop page margins at 47.6px and principal grid gutters at 19px.
- Use complete full-bleed color chapters with white practical panels inside them.
- Maintain blue conversion pills at 55.2px high with 26.7px horizontal padding.
- Make white clouds and flat geometric scenery part of the visual language, including when photography is unavailable.
- Use naturally lit human activity photos with opaque vector foregrounds.
- Give feature-deck cards 23.8px corners and practical panels 9.5px corners.
- Include a giant blue word landscape and an oversized illustrated closing identity.

### Don't

- Do not replace the condensed display face with a wide geometric headline font.
- Do not add gray hairline borders or elevated box shadows to the white panels; the design separates flat fills.
- Do not turn the entire site into a dense multicolor card dashboard; editorial cream intervals are essential.
- Do not apply the blue recruiting opening or pink closing theme indiscriminately to the default introduction.
- Do not make the geometric art volumetric, airbrushed or photorealistic; its contrast with real photography matters.
- Do not tint photos with blue overlays or cover faces with headline lettering.
- Do not use square conversion buttons or turn the compact floating navigation into a full-width opaque header.
- Do not shrink the closing identity into a small conventional footer logo.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares color-related transitions of .15s cubic-bezier(.4,0,.2,1).
- The carousel background declares a 1s ease-in-out transition.
- Feature cards use perspective, rotation and sticky staging; individual headline words and letters are transformed independently.
- Cloud-across keyframes are declared.

**Transfer:**

- Preserve the deck-like movement and changing illustrated world rather than applying one uniform fade to all sections.
- Keep a complete readable card face as the resting state; maintain artwork layering when transforms are disabled.

**Unknown:**

- Exact scroll choreography, letter trajectories, cloud speed and action hover/focus appearance are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1025px, 1280px and 1536px.
- Desktop root sizing is viewport-relative at 1.0582vw.
- Layout declarations include single-column narrow-screen variants and smaller side insets.

**Transfer:**

- On narrow screens, stack explanatory text beneath its display headline and retain the distinction between condensed poster type and rounded practical type.
- Keep the illustrated world edge-to-edge and scale its main character or object independently so the central card remains readable.
- Let word-sculpture letters bleed horizontally, but keep text and controls within the content width.

**Unknown:**

- Exact mobile font sizes, navigation transformation and final narrow-screen illustration arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
