# Wispr Flow — words in motion

## Overview

An expressive editorial style for approachable productivity and AI products, balancing bookish serif headlines with direct, friendly sans-serif explanations. Butter-cream pages open into forest-green and near-black chapters, punctuated by lilac controls and bright proof cards. Winding text graphics, loosely drawn illustrations and cinematic motion-blurred photography make otherwise spacious layouts feel alive.

### Essentials

- Bookish headlines sound conversational rather than institutional: EB Garamond 400 at 96px/0.95 in the opening, 75px/1 in section leads and 120px/0.85 in the closing call, all with -0.03em tracking; italicize the phrase that turns the thought.
- The opening is a centered promise inside a moving sentence: a 992px headline container, 480px support column and compact lilac action sit above looping text paths that run beyond both viewport edges.
- Color changes by chapter, not by decoration: #ffffeb is the reading canvas; #034f46 and #1a1a1a take whole proof chapters, while #f0d7ff anchors actions. Orange and coral concentrate in illustrations, small labels and isolated testimonial cards, not the general canvas.
- Buttons feel like tactile little controls, not lozenges: lilac fill, dark 2px outline, approximately 52px height, 8px corners and Figtree 16px/1 at weight 600, with an icon before the label when useful.
- Human movement replaces sterile software wallpaper: stage a large, rounded photographic scene with warm amber light, blue-green shadows and directional blur; use a photographed everyday activity when bespoke product footage is unavailable.
- Carry three recognizable devices into a new design: a winding SVG sentence ribbon, a monumental rounded photographic closing call and an oversized black brand lockup in the cream footer. The lockup spans the 1240px content width; an original typographic wordmark is the fallback.
- Small interface-like proofs sit inside expansive editorial space: 32px-radius panels, 16px grid gutters, 112–128px chapter breathing room and a two-column question-and-answer console with a forest-green question pane.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest green | `#034f46` | `--color-forest` | background, surface, link | Large demonstration chapters, question panes and link hover. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lilac | `#f0d7ff` | `--color-lavender` | action, surface, accent | Main conversion control, selected billing tab, product art backing and selected proof cards. |
| Apricot | `#ffa946` | `--color-orange` | accent, surface | Contained testimonial surfaces, drawn details and small announcement badges. |
| Coral | `#ff6c4c` | `--color-coral` | accent, surface, text | Contained proof cards, pricing stickers and correction marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter paper | `#ffffeb` | `--color-canvas` | background, text | Default reading canvas and reversed text on dark chapters. |
| Answer paper | `#f5f4f0` | `--color-bubble` | surface | Light chat-style answer bubble inside the question console. |
| Warm stone | `#e4e4d0` | `--color-stone` | surface, border, text | Inset informational bands, footer product cards, quiet borders and subdued reversed copy. |
| Tertiary ink | `#8d8d83` | `--color-faint` | text | Small category headings; visible result of ink at 50% opacity on butter paper. |
| Secondary ink | `#5f5f59` | `--color-muted` | text | Secondary copy; visible result of ink at 70% opacity on butter paper. |
| Soft black | `#1a1a1a` | `--color-ink` | text, background, border, action | Primary text, linework and full-width dark proof chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| value calculators | Deep forest | `#07352f` | `--color-calculator-dark` | surface | Inner calculator panel, darker than its surrounding green chapter. |
| value calculators | Raised forest | `#1a5e54` | `--color-calculator-result` | surface | Result strip within the dark calculator panel. |
| value calculators | Input edge | `#e4e3de` | `--color-input-edge` | border | Subtle outline around cream calculator inputs. |

## Typography

- **Eb garamond** — Editorial headlines, feature names, quotations and prices. High-contrast old-style serif with expressive italic forms; light visual weight and closely fitted display settings. Font stack: "Eb garamond", Georgia, serif.
- **Figtree** — Navigation, actions, explanatory copy, labels and bold quantified proof. Friendly contemporary sans with open forms and a substantial medium weight. Font stack: "Figtree", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental | Eb garamond | 400 | 120px | 0.85 | -0.03em | Closing photographic call and especially expansive editorial leads. |
| monumental-italic | Eb garamond | 400 italic | 120px | 0.85 | -0.03em | Emphasized words inside the monumental closing line. |
| hero | Eb garamond | 400 | 96px | 0.95 | -0.03em | Default centered first-screen headline. |
| hero-italic | Eb garamond | 400 italic | 96px | 0.95 | -0.03em | Second phrase of the opening promise. |
| section-lead | Eb garamond | 400 | 75px | 1 | -0.03em | Main chapter headings on light and dark surfaces. |
| section-italic | Eb garamond | 400 italic | 75px | 1 | -0.03em | Integrated italic phrase within a section lead. |
| heading | Eb garamond | 400 | 64px | 0.95 | -0.03em | Secondary editorial statements and demonstration headings. |
| feature-heading | Eb garamond | 400 | 48px | 0.95 | -0.03em | Feature chapters and inset information-band titles. |
| card-heading | Eb garamond | 400 | 32px | 0.95 | -0.03em | Quotations, proof-card headings and smaller capability titles. |
| support | Figtree | 500 | 20px | 1.3 | normal | Hero support lines, larger introductory paragraphs and accordion questions. |
| console-heading | Eb garamond | 400 | 20px | 0.95 | normal | Questions and Answer headings inside the console. |
| body | Figtree | 500 | 16px | 1.3 | normal | Feature explanations and product-card descriptions. |
| body-regular | Figtree | 400 | 16px | 1.3 | normal | Longer expanded answers and people lists. |
| action | Figtree | 600 | 16px | 1 | normal | Main button and compact navigation control labels. |
| caption | Figtree | 500 | 14px | 1.3 | normal | Footer links, console questions and small explanatory text. |
| eyebrow | Figtree | 500 | 14px | 1.3 | 0.08em, uppercase | Chapter categories and product labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling pages | company-hero | Eb garamond | 400 | 120px | 0.85 | -0.05em | Three-line organization statement over cinematic photography. |
| pricing pages | pricing-hero | Eb garamond | 400 | 96px | 0.95 | -0.05em | Compact centered pricing title. |
| quantified comparison sections | stat | Figtree | 700 | 80px | 0.95 | -0.03em | Dominant quantitative comparison, contrasted with small supporting bars. |
| comparison landing pages | comparison-hero | Eb garamond | 400 | 75px | 1 | -0.05em | Left-aligned two-line promise opposite a large device composition. |
| pricing pages | price | Eb garamond | 400 | 40px | 0.95 | -0.03em | Plan price and billing interval kept in one flowing line. |
| company storytelling pages | manifesto | Eb garamond | 400 | 32px | 1.3 | -0.03em | Extended organization narrative with one lilac-highlighted mission sentence. |
| pricing pages | plan-label | Figtree | 600 | 18px | 1.3 | normal | Rotated plan-name stickers. |

**Notes:**

- Serif tracking normally holds at -0.03em while line height compresses from 1 at 75px to 0.85 at 120px. The tighter -0.05em openings belong to specific page types, not the default.
- Italic emphasis is part of the sentence, not a separate decorative subtitle. Preserve mixed roman/italic reading order when wrapping new copy.
- Sans text uses normal tracking except for uppercase labels. Medium body weight keeps small explanations legible against the creamy surfaces.
- The huge footer lettering is brand artwork rather than a heading font recipe; scale the new product's original lockup as a graphic.

## Layout

**Density:** Airy editorial chapters surround compact controls and information panels; large narrative pauses contrast with tight small-text groups.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Main vertical gaps and section padding; smaller control details use their own measured values.

| Value | Use |
| --- | --- |
| 8px | Tight component gaps and console grid gutter. |
| 16px | Card-grid gutters, inner inset and footer heading separation. |
| 24px | Hero support-to-action gap and grouped panel details. |
| 32px | Feature title-to-copy gap, card padding and calculator group spacing. |
| 40px | Global minimum desktop side padding. |
| 48px | Information-band horizontal inset. |
| 64px | Information-band vertical padding and major internal group gaps. |
| 80px | Footer top padding and larger media separation. |
| 96px | Chapter separation around comparison and pricing content. |
| 112px | Proof and calculator chapter vertical inset. |
| 128px | Large editorial chapter inset. |
| 160px | Extra-large section padding and feature-story cadence. |

### Containers and grids

- **main container**: max width 1240px · side padding 40px. Centered desktop content; at 1440px the content edges fall 100px from the viewport sides.
- **opening title**: max width 992px. Centered headline group with abundant cream space on both sides.
- **opening support**: max width 480px. Balanced two-line support below the first headline.
- **editorial column**: max width 768px. Centered explanatory statements and video-scale content.
- **console and calculator**: max width 816px. Contained interactive proof within the wider chapter.
- **paired product cards**: 2 columns · gap 16px. Two equal product-discovery cards above footer links.
- **four-column grid**: 4 columns · gap 16px. Footer navigation; the same desktop geometry holds four plan cards on pricing pages.
- **feature split** (only for comparison landing pages): 2 columns · gap 80px. Editorial intro at left and stacked capability cards at right.
- **process steps** (only for trust and process explanations): 4 columns · gap 64px. Numbered lifecycle explanation connected by a dotted line.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 8px |
|  | product discovery cards | 12px |
|  | console question pane | 16px |
|  | information panels | 32px |
|  | testimonial cards | 48px |
|  | full-width chapters | 80px |
| pricing pages | plan stickers | 100px |
| comparison landing pages | accordion cards | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | plan sticker | `1.1px 1.1px 1.1px 0px rgba(0, 0, 0, 0.3)` | Small paper-like lift on rotated pricing labels only. |

### Surfaces

#### Butter canvas · level 0

**Use:** Default page foundation.

**CSS:** `background-color: #ffffeb; color: #1a1a1a`

#### Dark proof chapter · level 0

**Use:** An immersive zone for social or comparative proof.

**CSS:** `background-color: #1a1a1a; color: #ffffeb; border-radius: 80px`

**Observed:** Broad edge-to-edge rounded chapter; the main social-proof chapter uses asymmetric top and bottom corners during its transition.

**Transfer:** Group several related proofs into one coherent dark scene rather than alternating each card's background.

#### Forest chapter · level 0

**Use:** Demonstrations and value-focused chapters.

**CSS:** `background-color: #034f46; color: #ffffeb; border-radius: 80px`

**Observed:** Solid opaque color without texture or gradients; reversed serif titles retain the same light weight.

**Transfer:** Use as a substantial field supporting one dominant idea.

#### Stone inset · level 1

**Use:** Information bands, console backing and product discovery.

**CSS:** `background-color: #e4e4d0; border-radius: 32px; box-shadow: none`

**Observed:** Flat, low-contrast material with no floating shadow.

**Transfer:** Use a clear inset to collect denser practical details.

#### Lilac enterprise callout · level 1

**Only for:** trust and enterprise pages

**Use:** A high-visibility invitation within a dark technical chapter.

**CSS:** `background-color: #f0d7ff; color: #1a1a1a; border-radius: 24px; padding: 40px 104px`

**Observed:** Wide two-column panel pairs a serif proposition and short explanation with a checklist.

**Transfer:** Keep the tint as one contained block rather than recoloring the whole technical page.

## Components

### Floating navigation

**Use:** Persistent compact navigation across light, dark and photographic chapters.

**CSS:** `position: fixed; z-index: 999; background-color: #ffffeb; color: #1a1a1a; border: 2px solid #e4e4d0; border-radius: 8px`

**Text style:** `action` — Figtree 600 · 16px/1

**Observed:** A centered narrow horizontal bar, visually about 912px wide at desktop, contains the brand, a two-option product switch, a few text links and the primary action. The header layer is 85px tall; it does not become a full-width opaque masthead.

**Transfer:** Keep the navigation compact and cream-backed even over photography.

### Primary button

**Use:** Default conversion action in the opening and closing scenes.

**CSS:** `background-color: #f0d7ff; color: #1a1a1a; border: 2px solid #1a1a1a; border-radius: 8px; padding: 16px 24px; min-height: 52px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — Figtree 600 · 16px/1

**Observed:** Small icon precedes a practical action label. The outlined secondary control uses the cream canvas; paid-plan actions and trust-center actions use ink fill with cream text.

**Transfer:** Name the next step, adding platform specificity only when necessary.

### Text link

**Use:** Footer lists and secondary resource navigation.

**CSS:** `color: #1a1a1a; display: flex; align-items: center; gap: 8px; transition: color 0.3s ease`

**Text style:** `caption` — Figtree 500 · 14px/1.3

**Observed:** Short unboxed labels form compact vertical lists; arrows can sit beside action-oriented links.

**States:** Declared: hover color #034f46 and outline 0px; active outline 0px.

### Question console

**Use:** Default objection-handling component.

**CSS:** `background-color: #e4e4d0; border-radius: 32px; max-width: 816px; display: grid; grid-template-columns: 1fr 1fr; gap: 8px; overflow: hidden`

**Text style:** `console-heading` — Eb garamond 400 · 20px/0.95

**Observed:** Left pane is forest green with 16px corners and a 16px outer inset; right pane is an answer conversation on the stone backing. Small serif labels head each pane. Question rows use the caption recipe, 16px padding and a subtly lighter active fill; the left list fades into forest at its bottom.

**Transfer:** Use real buying questions and show one focused answer at a time.

### Answer bubble

**Use:** Focused explanation in the question console.

**CSS:** `background-color: #f5f4f0; border-radius: 12px 12px 12px 0.3px; padding: 12px 16px; transition: height 0.2s`

**Text style:** `caption` — Figtree 500 · 14px/1.3

**Observed:** The selected question is repeated above, right-aligned in secondary ink; its answer appears beneath in a pale bubble with a tiny product mark below.

**Transfer:** Keep the answer concise enough to read like a helpful response, not a documentation article.

### Product discovery card

**Use:** Compact product re-entry point above the footer navigation.

**CSS:** `background-color: #e4e4d0; border: 2px solid rgba(0, 0, 0, 0); border-radius: 12px; padding: 8px 32px 8px 8px; display: flex; align-items: center; gap: 32px; transition: border-color 0.25s`

**Text style:** `body` — Figtree 500 · 16px/1.3

**Observed:** A 150px square artwork tile with 6px corners precedes a product name, short muted description and action. Paired cards are 612px by 170px on desktop. One uses lilac art backing, the other forest green.

**Transfer:** Summarize two genuine products or two distinct entry paths without inflating these into large feature sections.

### Testimonial card

**Use:** Vivid human proof inside a dark chapter.

**CSS:** `background-color: #f0d7ff; color: #1a1a1a; border-radius: 48px; padding: 16px; display: grid; grid-template-columns: 1.1fr 1fr; gap: 32px; overflow: clip`

**Text style:** `card-heading` — Eb garamond 400 · 32px/0.95 · tracking -0.03em

**Observed:** A large quotation and compact attribution occupy the left; a tall rounded portrait fills the right. Cards form a staged stack with changing angle and scale. Lilac, orange and coral surfaces keep the enclosing chapter visually alive.

**Transfer:** Use authentic portraits and a specific human observation; a single static card retains the same editorial split.

### Plan card

**Only for:** pricing pages

**Use:** Comparable plan propositions.

**CSS:** `background-color: #ffffeb; border: 2px solid #e4e4d0; border-radius: 32px; padding: 32px 30.4px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `price` — Eb garamond 400 · 40px/0.95 · tracking -0.03em

**Observed:** Four equal cards align their audience labels, prices, actions and checklists. A Plan sticker straddles each top border. The entry plan has a stone outline and cream action; paid plans have ink outlines and ink actions. The featured plan adds a lilac tab below its bottom edge.

**Transfer:** Distinguish the commercial emphasis with border and action treatment, not a dramatically taller card.

### Plan sticker

**Only for:** pricing pages

**Use:** Playful label attached to each plan's top edge.

**CSS:** `background-color: #ff6c4c; color: #1a1a1a; border: 2.5px solid #ffffeb; border-radius: 100px; padding: 5px 9.5px; box-shadow: 1.1px 1.1px 1.1px 0px rgba(0, 0, 0, 0.3); transform: rotate(-7.7deg)`

**Text style:** `plan-label` — Figtree 600 · 18px/1.3

**Observed:** Small tilted label has a cream cutout edge. The plan series changes through coral, lilac, orange and deep wine; labels remain small relative to the card.

**Transfer:** Treat this as a paper sticker rather than a flat status badge.

### Value calculator

**Only for:** value calculators

**Use:** Translate a benefit into a reader-specific number.

**CSS:** `background-color: #07352f; color: #ffffeb; border-radius: 32px; padding: 32px; max-width: 816px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `body` — Figtree 500 · 16px/1.3

**Observed:** Two cream inputs sit in a 16px-gutter row, with 8px corners, 1px pale edges and 12px by 16px padding. A lighter green 16px-radius result strip below contains three columns with 24px padding; the most valuable result is a larger serif number. A centered text action finishes the panel.

**Transfer:** Use transparent assumptions and only inputs the reader can readily answer.

### Stacked capability card

**Only for:** comparison landing pages

**Use:** Explain concrete differences beside a sticky editorial introduction.

**CSS:** `background-color: #034f46; color: #e4e4d0; border: 2px solid rgba(26, 26, 26, 0.5); border-radius: 32px; padding: 32px; display: flex; flex-direction: column; align-items: flex-start; gap: 18px; position: sticky`

**Text style:** `card-heading` — Eb garamond 400 · 32px/0.95 · tracking -0.03em

**Observed:** A 48px line illustration leads a serif title and short sans explanation. Cards rise into a rounded stack as the story advances.

**Transfer:** Give every card one observable behavior rather than a broad category name.

### Accordion card

**Only for:** comparison landing pages

**Use:** Compact alternative to the question console.

**CSS:** `border: 2px solid #1a1a1a; border-radius: 24px; overflow: hidden`

**Text style:** `support` — Figtree 500 · 20px/1.3

**Observed:** Two-column grid with 16px gutters. Each trigger has 32px padding, a 20px question and a 24px chevron; answer text uses the regular body recipe.

**Transfer:** Use for independent questions when the paired conversation format would be too elaborate.

## Imagery and graphics

### Winding sentence ribbon

**Use:** Signature graphic in the opening and product demonstrations.

**Observed:** Faint grey sentences loop from outside the left edge into the lower opening. They become a dark ribbon with cream text near a capsule-shaped waveform control. Letter fragments near the capsule introduce small orange highlights; the graphic crosses the page without enclosing the main headline.

**Transfer:** Thread an original sentence expressing the new product's workflow through the scene. Keep the headline and button perfectly still and readable.

**Build:** Use a wide SVG with a viewBox extending beyond the viewport. Draw a cubic Bézier path with one loose loop at the left and a shallow rising sweep across the bottom. Put Figtree text on textPath; use ink at roughly 25% opacity for the incoming phrase. Duplicate the final sweep as a thick ink stroke behind cream text. Place a cream capsule with a 2px ink outline at the transition and fill it with variable-height round-ended vertical bars. Preserve the loose curve rather than fitting it to a rigid sine wave.

### Cinematic human scene

**Use:** Required major photographic closing call; also backs demonstrations.

**Observed:** People move through landscapes, shared interiors and transit. Amber highlights, teal-blue surroundings and deep shadows mingle in directional motion blur; the central person stays more recognizable than the peripheral scene. Photography fills the rounded chapter rather than appearing as a small thumbnail, with cream display text and a lilac action over it.

**Transfer:** Photograph the human outcome of using a different product. Minimum version: a real activity photograph with duplicated, horizontally blurred background layers, a legible central subject and a restrained dark scrim.

**Build:** Make an 80px-radius overflow-hidden full-width scene. Set a cover image as the base; duplicate it as a blurred background layer with a horizontal scale stretch, then mask a clearer central subject above it. Add an ink-to-transparent scrim only where the cream copy needs contrast. Center a maximum 1024px headline group over the photograph.

### Loose editorial illustration

**Use:** Inset informational bands and playful proof accents.

**Observed:** Flat cream, lilac and apricot shapes have irregular dark outlines: laptops, phones, speech bubbles and casually drawn people. Illustrations are modest supporting objects, sometimes overlapping a panel's top edge, not polished 3D models.

**Transfer:** Draw a few recognizable objects from the new workflow with imperfect outlines and limited flat fills. Keep the image less prominent than the serif message.

**Build:** Use SVG paths with rounded joins, approximately 3px ink outlines, cream device shapes, lilac clothing or keys and apricot callouts. Combine two or three slightly rotated objects; avoid gradients and dimensional shadows.

### Monumental footer lockup

**Use:** Required brand-scale ending after navigation links.

**Observed:** A black waveform-like symbol and heavy wordmark span the cream content width. The symbol occupies roughly 344px by 337px, the lettering 756px by 264px, with a 140px gap. Fine legal links and small social icons sit beneath.

**Transfer:** Create an original oversized lockup for the new brand. If no symbol exists, use an oversized custom-set wordmark spanning the same width and retain the small legal baseline.

**Build:** Place original black SVG brand artwork in a two-part grid within 1240px. Balance the symbol's height with the wordmark's visual mass and reserve 40px below it for the legal line; never render this as a normal heading.

### Device result scene

**Only for:** comparison landing pages

**Use:** Concrete right-hand hero demonstration.

**Observed:** A large laptop and overlapping phone extend toward and beyond the right edge, showing dark messaging interfaces over scenic wallpaper. A small floating result bubble bridges the devices; the surrounding page remains cream.

**Transfer:** Show one credible before-to-result workflow in devices appropriate to the new product. Keep UI detail inside the devices rather than borrowing its font and color system for the marketing page.

### Company atmosphere

**Only for:** company storytelling pages

**Use:** Immersive organization opening.

**Observed:** Full-bleed motion-blurred people in a shared room, purple-blue backdrop, warm amber figures and green foreground. Cream sentence paths arc near the outer edges around a three-line centered serif statement.

**Transfer:** Use a genuine environment with people at work or in conversation, keeping faces secondary to the shared atmosphere.

### Icons

**Observed:** Utility icons are generally 24px, simple monochrome forms; outlined examples use 1.5px round strokes. Pricing checklist marks are 15px by 12px. Larger capability illustrations are 48px and intentionally more hand-drawn.

**Transfer:** Separate crisp small utility symbols from loose editorial illustrations. Match ink or cream to the surface, and use filled platform symbols only when they clarify an action.

## Section recipes

How recurring sections are built.

### First screen: Centered promise in a sentence ribbon

**Observed:** Butter canvas behind a compact Floating navigation and a narrow green announcement strip. The central eyebrow starts the content around 259px down the first screen; a two-line 96px roman-and-italic promise sits inside a 992px group. A 480px support column follows, then a Primary button separated by 24px and a small platform note. A faint looping sentence enters from the left, curves underneath the copy and becomes a dark text ribbon at the lower right; the capsule-shaped waveform sits on this lower path. Within 900px, navigation, complete headline, support, action, note and the main ribbon are visible. The first substantial proof chapter falls below this opening.

**Transfer:** Keep the center as a short contrastive promise and turn a relevant workflow sentence into the surrounding ribbon. No bespoke media is needed: the SVG text path and capsule provide the main object. Pricing opens with a centered title, support and billing switch above cards; trust pages use a centered two-line promise and practical paired actions; comparison pages use a left promise opposite a device scene; organization pages use a full photographic opening.

**Avoid:** Do not replace this opening with a dashboard grid, a giant floating app window in the center or multiple competing calls to action.

**Text style:** `hero` — Eb garamond 400 · 96px/0.95 · tracking -0.03em

### Editorial heading pair

**Observed:** Eyebrow above a centered section-lead title, with one italic phrase integrated into the headline. The feature introduction adds a slim lilac hand-drawn underline beneath its emphasized phrase. Light chapters use ink; dark chapters reverse to cream.

**Transfer:** Emphasize the human turning point in the sentence rather than coloring individual product keywords.

**Text style:** `section-lead` — Eb garamond 400 · 75px/1 · tracking -0.03em

### Speed or outcome stage

**Observed:** Forest chapter holds a large roman-and-italic promise and short support above an asymmetric comparison: a narrow outlined baseline panel and a much larger photographic demonstration. Serif 48px numerals or rates sit over each side; a curved sentence and small waveform capsule cross the demonstration.

**Transfer:** Compare the old and new experiences using a relevant, substantiated measure. Make the improved experience visually broader than the baseline, while keeping the visual comparison honest.

### Alternating feature narrative

**Observed:** On cream, a compact illustrated interface motif occupies the left while successive 48px feature titles and 16px explanations occupy the right. Text groups are separated by 160px; active material is emphasized while neighboring material recedes.

**Transfer:** Pair each new capability with a small understandable transformation rather than a full app screen.

**Text style:** `feature-heading` — Eb garamond 400 · 48px/0.95 · tracking -0.03em

### Practical information band

**Observed:** Stone inset spans 1240px with 32px corners, 64px vertical and 48px horizontal padding. Three columns hold a 48px serif proposition, a compact explanation with a text link, and an illustration or fine-line trust seals.

**Transfer:** Use for practical reassurance such as compatibility, ownership or support; preserve the small art-to-copy ratio.

### Human proof theater

**Observed:** Dark proof chapter begins with a centered eyebrow and 75px roman/italic heading, then stages bright Testimonial cards against abundant dark space. Large portraits and tightly set serif quotes share each card.

**Transfer:** Use authentic qualitative proof as a human pause between denser product explanations, with one dominant card visible at a time.

### Conversation-based objections

**Observed:** A short centered heading and eyebrow lead into Question console. The console is only 816px wide inside the 1240px page grid, leaving clear cream margins.

**Transfer:** Make the section feel like a useful conversation; select questions that block a purchase, not broad marketing talking points.

### Photo closing and oversized footer

**Observed:** Cinematic human scene occupies an almost viewport-height 789–865px rounded band. A centered 120px cream headline, selective italic emphasis, compact support and Primary button form the foreground. The cream footer follows with 80px top padding, paired Product discovery cards, four link columns with 16px gutters, then Monumental footer lockup and a fine legal/social baseline. This ending is consistent across the page family; one trust closing uses the smaller 96px title.

**Transfer:** Close with the human benefit, not another feature list. Retain the photographic scale and oversized original brand art even when the new page is short.

**Text style:** `monumental` — Eb garamond 400 · 120px/0.85 · tracking -0.03em

### Pricing and practical comparison

**Only for:** pricing pages

**Observed:** Centered pricing-hero and short support sit above a bordered billing switch with lilac active tab. Four Plan cards begin in the first screen, over a faint oversized looping stroke. A later comparison repeats plan names and prices in a compact cream header with 12px corners; feature groups use 1px stone bottom rules and roughly 70px rows.

**Transfer:** Keep the purchase decision visible early and the detailed feature matrix separate; do not turn the whole page into a table.

**Text style:** `pricing-hero` — Eb garamond 400 · 96px/0.95 · tracking -0.05em

### Value calculation chapter

**Only for:** value calculators

**Observed:** Forest chapter with 80px corners and 112px top inset holds a centered section-lead with italic second line and Value calculator below. Deep forest and lighter result green create depth without shadows.

**Transfer:** Put one measurable economic outcome behind a small number of understandable inputs.

**Text style:** `section-lead` — Eb garamond 400 · 75px/1 · tracking -0.03em

### Trust through controls and process

**Only for:** trust and process explanations

**Observed:** Left 75px editorial title and right support/actions introduce a controls section; an accordion-like list sits opposite a small cream settings panel over blurred human photography. A four-step explanation follows with 80px numbered lilac circles and a fine dotted connector. A dark technical chapter has three ruled columns, then Lilac enterprise callout. Three audit-seal columns return to cream.

**Transfer:** Show actual controls, the path a user's material takes and independently verifiable assurances. Adapt the step count to the real process.

### Organization story and press

**Only for:** company storytelling pages

**Observed:** Company atmosphere opening leads into a dark 32px serif manifesto with a lilac mission phrase. Cream chapters use monumental headings, a centered rounded 832px video and a recruiting invitation. A green rounded support chapter combines an overlapping illustration and large left title with logos and two columns of names at right. Press coverage uses three columns of 403px entries, 16px gutters and thin lilac top rules.

**Transfer:** Tell an origin story and demonstrate external credibility without forcing company content into ordinary product landing pages.

**Text style:** `company-hero` — Eb garamond 400 · 120px/0.85 · tracking -0.05em

### Comparative proof and bold stat

**Only for:** comparison landing pages

**Observed:** Dark chapter presents two equal rounded cream/lilac evidence cards with loose illustrated corner accents. Corrections in the baseline result are coral. Beneath, one 80px bold sans percentage dominates beside tiny comparison bars and a muted citation. A later video sits in another dark rounded chapter; Accordion cards handle remaining objections.

**Transfer:** Show an inspectable comparison first, then a clearly qualified statistic. Keep the bold sans numeral exceptional among serif headlines.

**Text style:** `stat` — Figtree 700 · 80px/0.95 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible outcome → capability explanation → trust and human proof → objections → human-scale closing call → product discovery and monumental brand ending.

### Introduce a product through its felt benefit and breadth

1. **Promise** — Centered roman/italic headline surrounded by flowing sentence art.
2. **Product demonstration** — Large green comparison and cinematic workflow stage.
3. **Capabilities** — Small illustrative motifs beside successive editorial feature statements.
4. **Reassurance** — Three-part stone inset with practical assurance.
5. **Human proof** — Dark scene containing bright portrait-and-quote cards.
6. **Objection handling** — Two-pane question console on cream.
7. **Closing call and orientation** — Rounded human photograph with oversized serif promise; product cards, link columns and giant brand artwork follow.

**Transfer:** Move between emotional promise, visible mechanism and believable proof; use the shared ending to restore a simple next step.

### Explain the organization behind a product

1. **Identity** — Immersive human scene with a three-line monumental statement and perimeter text paths.
2. **Belief** — Dark serif narrative, highlighted mission and illustrated values.
3. **Origin and invitation** — Cream editorial headings around founder video and recruiting action.
4. **External validation** — Green support panel with logos and named backers, then cream press grid.
5. **Closing call and orientation** — Photographic invitation followed by the shared product cards, footer columns and huge lockup.

**Transfer:** Use an organization-specific narrative and external credibility instead of substituting generic feature lists.

### Make an informed commercial decision easy

1. **Offer** — Centered title, billing selector and four aligned plan cards with tilted labels.
2. **Practical fit** — Stone compatibility band.
3. **Detailed comparison** — Repeated compact plan header above grouped ruled rows.
4. **Trust and proof** — Stone reassurance band and logo strip.
5. **Quantified value** — Green calculator chapter with dark nested panel.
6. **Objection handling** — Question console.
7. **Closing call and orientation** — Warm blurred photograph, brief action, shared product cards and monumental footer.

**Transfer:** Lead with understandable choices and progressively disclose detail before the economic case.

### Turn trust promises into inspectable decisions

1. **Promise** — Cream centered headline, concrete support, paired actions and small audit proof.
2. **Control** — Settings explanation and visible control interface.
3. **Process transparency** — Connected numbered lifecycle steps.
4. **Safeguards** — Dark technical columns and lilac enterprise callout.
5. **Verification** — Cream three-column independent audit and compliance proof.
6. **Objection handling** — Question console.
7. **Closing call and orientation** — Human photographic call, shared product discovery and oversized footer artwork.

**Transfer:** Explain what a reader can control before naming standards and verification.

### Explain why a new approach differs from an established alternative

1. **Contrastive promise** — Left editorial headline and paired actions, right oversized devices.
2. **Credibility** — Compact press quotation.
3. **Inspectible comparison** — Dark result comparison with cream/lilac cards, coral corrections and a bold dominant statistic.
4. **Mechanism** — Sticky introduction beside stacking green capability cards.
5. **Demonstration** — Dark video chapter.
6. **Objection handling** — Two-column outlined accordion grid.
7. **Closing call and orientation** — Blurred human photographic call followed by the same product cards and monumental footer.

**Transfer:** Make the distinction visible in outputs, then explain the mechanism and answer switching concerns.

## Writing

Confident, conversational and slightly playful. Emotional promises are short; explanations become concrete immediately and technical trust copy is matter-of-fact.

**Do not copy:** Do not reuse the brand names, logos, proprietary artwork, customer identities, quotations, platform availability, benchmark numbers, pricing, certifications or product claims. Source examples illustrate cadence only; new claims require the new product's own substantiation.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for responsibility and beliefs. Name the product naturally in explanatory copy rather than repeating it in every heading.
- **Rhythm:** Short paired headline clauses, often 3–9 words, contrast with one or two clear support sentences. Periods and commas supply the rhythm; italic emphasis provides a spoken inflection rather than extra punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Replace an old behavior with an easier new one in two short clauses. | 4–8 words | “Don’t type, just speak.” |
| Section lead | A conversational sentence with an italic turning phrase. | 4–12 words | “Built around how you work, not how we think you should.”<br>“You might be wondering.” |
| Support | Name the category, transformation and place of use in one plain sentence. | 12–24 words | “The voice-to-text AI that turns speech into clear, polished writing in every app.” |
| Action | Direct verb and concrete next step, with platform when useful. | 2–5 words | “Get started on macOS”<br>“View compliance report” |
| Feature explanation | Explain the behavior with familiar examples rather than vague intelligence claims. | 1–3 sentences | “Create snippets for the things you type all the time, like emails, links, addresses, and bios. Speak the shortcut, and Flow expands it instantly.” |
| Reassurance | State the user's choice or protection before the technical qualification. | 1–3 short sentences | “Your data is never sold. You choose whether data is used to help improve Flow.” |
| Closing line | Return to the human outcome with a memorable spoken cadence. | 4–12 words | “Speak naturally, send without fixing.” |

**Words and phrasing to use:** you choose; naturally; effortless; ready to send; works where you work; clear; polished; your own

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; enterprise-grade magic; unqualified superlatives; dense acronym-led headlines

**Rules:**

- Name the behavior before describing its technical mechanism.
- Turn category headings into small spoken promises.
- Use real examples of work to clarify breadth.
- Trust copy should state the default, the user's choice and any important condition.
- End with a simple invitation instead of introducing a new feature.

## Do's and Don'ts

### Do

- Keep the default first headline at 96px/0.95, weight 400, with a meaningful italic second phrase.
- Let a sentence ribbon travel beyond the viewport edges while the 480px support column stays centered.
- Use 1240px desktop containers and 16px gutters for repeatable grids.
- Keep practical inset bands flat, stone-colored and 32px-rounded.
- Make a full human photographic closing scene with 80px corners rather than a tiny decorative portrait.
- Reserve the 80px bold sans stat for one exceptional quantitative proof.
- Place paired 150px artwork tiles in compact footer product cards before the link columns.
- Give the brand lockup a full 1240px-wide final stage on cream.

### Don't

- Do not turn the primary action into a pill; the 8px rectangular control is distinct from round stickers.
- Do not replace butter paper with pure white throughout; #ffffeb is a major part of the warmth.
- Do not use bright coral or orange as the general page background; contain them in proof surfaces and illustration details.
- Do not apply the pricing sticker's drop shadow to information cards; stone panels stay flat.
- Do not use heavy sans headlines for ordinary chapters; weight-400 serif is the main voice.
- Do not apply -0.05em tracking to every heading; the core display setting is -0.03em.
- Do not make the footer a dark utility bar; its oversized black artwork belongs on cream.
- Do not make technical proof a wall of badges; use ruled columns, small seals and compact readable explanations.

## Motion and responsive

### Motion

**Observed:**

- Text links declare color 0.3s ease; product cards declare border-color 0.25s; answer bubbles declare height 0.2s.
- Logo tickers declare a 40s linear infinite animation.
- Feature and testimonial stories use sticky scenes and transformed cards; the sentence graphics and waveform motifs support a sense of continuous flow.

**Transfer:**

- Let the story progress through a stable stage while cards or sentence paths change, rather than animating every paragraph independently.
- Keep the logo ticker unhurried and continuous; use the declared small state transitions for supporting controls.

**Unknown:**

- Exact scroll choreography, timelines and easing for the major scenes are not specified.
- Primary-button hover and focus treatments are not established.

### Responsive

**Observed:**

- Styles define width breakpoints around 479/480px, 767/768px and 991/992px, with additional desktop-specific thresholds.

**Transfer:**

- On narrow screens, preserve the headline's roman/italic relationship and let the sentence path run off-screen rather than shrinking its text into illegibility.
- Stack paired cards and console panes in reading order; let the oversized wordmark fit the available width while retaining its role as the final visual event.
- Reduce the device scene before compressing support copy; keep the primary action close to the promise.

**Unknown:**

- Exact mobile sizes, menu behavior, card stacking and scene-height rules are not established; these transfer rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
