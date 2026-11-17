# Suno — creative heat after dark

## Overview

A dark, expressive style that feels more like a creative instrument than enterprise software. Warm ivory grotesk typography, fine charcoal panels and grainy amber-to-magenta light make vivid artwork and product demonstrations feel luminous. Slender editorial serifs bring a more personal register to company stories and specialist product launches; the overall pace is spacious, with concentrated pockets of detail.

### Essentials

- An invitation sits inside a creative atmosphere, not beside a dashboard: a centered 72px/72px medium grotesk headline above a 760px-wide translucent action panel, flanked by tilted output artwork.
- Headlines sound big without becoming heavy: 500-weight sans at 72px/64px for chapter leads and 140px/0.87 for a monumental proof statement; the editorial variant uses 300-weight serif at 96px/104px.
- Heat is concentrated against charcoal: #101012 dominates the page, with amber, red and magenta atmosphere in the opening and a major proof stage; feature illustrations carry most other color. Pink #fd429c is a tiny promotional accent, not the page fill.
- Actions are smooth capsules: 40px compact and 56px major buttons, 9999px radii, ivory utility conversions and an orange-pink aura for the central creative action.
- The product is treated as creative output: richly colored portrait artwork rails and miniature interface compositions sit in 24px-radius dark cards with 32px padding. Include an output-art rail; when no native artwork exists, use art-directed examples of the product's results.
- A luminous proof stage punctuates the dark scroll: a full-width grainy warm aura backs an oversized headline and paired 330px-wide translucent proof panels. Recreate the light field and meaningful proof even without photographic media.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Promotional pink | `#fd429c` | `--color-pink` | accent, surface | Small recommended-plan badges and pink emphasis within the warm aura. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright white | `#ffffff` | `--color-white` | text, action | Opening headline and bright specialist-product actions. |
| Chalk highlight | `#fcfbf9` | `--color-hover` | text, link | Footer column headings and link hover highlights. |
| Warm ivory | `#f7f4ef` | `--color-foreground` | text, action, background | Primary marketing text and filled buttons; also the inverted culture-story canvas. |
| Silver | `#c2c2c1` | `--color-link` | text, link | Footer and secondary navigation links. |
| Soft white | `#b7b7b8` | `--color-support` | text | Supporting marketing copy: white at 70% over charcoal. |
| Book gray | `#a3a3a3` | `--color-muted` | text | Editorial paragraphs and secondary descriptions. |
| Proof edge | `#404041` | `--color-proof-edge` | border | White at 20% over charcoal; translucent proof-panel edges vary visibly over colored atmosphere. |
| Footer edge | `#343436` | `--color-footer-edge` | border | White at 15% over charcoal for footer rules and social outlines. |
| Fine edge | `#28282a` | `--color-edge` | border, surface | White at 10% over charcoal for card edges and accordion rules. |
| Raised charcoal | `#252529` | `--color-panel` | surface | Solid editorial cards, statistics and demo frames. |
| Media smoke | `#1c1c1f` | `--color-media` | surface | Media backing and 40%-alpha proof-panel fill. |
| Ivory fog | `#1c1b1d` | `--color-plan` | surface | Ivory at 5% over charcoal for plan cards. |
| Fog card | `#1a1a1b` | `--color-feature` | surface | White at 4% over charcoal, used for feature cards. |
| Charcoal canvas | `#101012` | `--color-canvas` | background, text | Dominant page ground and inverse text on ivory actions. |
| Media black | `#000000` | `--color-black` | surface, background | Deep media stages and the base beneath aura-button artwork. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture and recruiting stories | Paper text gray | `#7d7c83` | `--color-paper-muted` | text | Secondary text on the ivory culture band. |
| culture and recruiting stories | Warm stone | `#e0deda` | `--color-quote` | surface | Quote cards on the inverted story band. |
| in-application pricing pages | Warm near black | `#0e0808` | `--color-pricing-ground` | background | Scrollable plan-detail canvas inside the application shell. |

## Typography

- **Neue Montreal** — Marketing headings, actions, navigation and paragraphs; the Book cut supplies lighter editorial body text. Compact contemporary grotesk, open and direct, with restrained medium-weight headings. If unavailable, use **Inter**. Use 300–500 weights; retain tight display tracking and check headline wrapping. Font stack: "Neue Montreal", "Inter", system-ui, -apple-system, sans-serif.
- **Editorial New** — Editorial and specialist-product displays, plan names and company statistics. Tall, narrow, high-contrast editorial serif with fine hairlines and a light, elegant voice. If unavailable, use **Instrument Serif**. Use its regular cut and tune width to preserve the narrow display silhouette. Font stack: "Editorial New", "Instrument Serif", Georgia, Cambria, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental | Neue Montreal | 500 | 140px | 0.87 | -0.0263em | Major proof statement on the luminous stage. |
| display | Neue Montreal | 500 | 72px | 1 | -0.0133em | Centered opening promise, normally split into two balanced lines. |
| heading | Neue Montreal | 500 | 72px | 64px | normal | Default chapter titles, centered or left aligned according to the content. |
| rating | Neue Montreal | 400 | 40px | 1 | normal | Rating numerals inside proof panels. |
| plan-name | Editorial New | 300 | 24px | 1.5 | normal | Plan titles in pricing cards. |
| card-heading | Neue Montreal | 500 | 20px | 1.2 | normal | Feature-card titles. |
| question | Neue Montreal | 500 | 20px | 1.5 | normal | Default accordion questions. |
| support | Neue Montreal | 400 | 18px | 24px | normal | Centered section support, usually no more than two lines. |
| button | Neue Montreal | 500 | 17px | 24px | normal | Major conversion labels. |
| hero-support | Neue Montreal | 300 | 16px | 1.5 | normal | Short, narrow support beneath the opening headline. |
| card-body | Neue Montreal | 500 | 16px | 1.5 | normal | Feature-card descriptions. |
| navigation | Neue Montreal | 500 | 15px | 24px | normal | Navigation and compact action labels. |
| footer-link | Neue Montreal | 400 | 14px | 1.5 | normal | Footer links. |
| badge | Neue Montreal | 500 | 10px | 1.5 | normal, uppercase | Short promotional badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| culture and recruiting stories | word-sculpture | Editorial New | 300 | 180px | 1 | -0.03em | Single conceptual words on the ivory story band. |
| editorial company stories and specialist-product launches | editorial-display | Editorial New | 300 | 96px | 104px | -0.03em | Company-story and specialist-product opening headlines. |
| company and recruiting stories | story-heading | Neue Montreal | 500 | 64px | 1 | -0.01em | Company-story section leads. |
| company proof grids | stat | Editorial New | 300 | 64px | 1 | normal | Centered statistical figures. |
| specialist-product launches | editorial-heading | Editorial New | 300 | 54px | 58px | -0.03em | Specialist-product chapters and closing invitation. |
| in-application pricing pages | pricing-display | Editorial New | 300 | 40px | 1.2 | normal | Compact headline above plans inside an application shell. |
| culture and recruiting stories | word-completion | Neue Montreal | 400 | 32px | 1 | -0.01em | Book-cut short sentence completion beneath a monumental word. |
| company and recruiting stories | story-body | Neue Montreal | 400 | 18px | 28px | -0.01em | Book-cut editorial prose. |
| company proof grids | stat-caption | Neue Montreal | 400 | 16px | 1.5 | normal | Book-cut explanation immediately below a statistic. |

**Notes:**

- The default marketing voice is medium-weight grotesk, not serif. Editorial displays are a scoped alternative rather than a second font mixed into every headline.
- Headline lines are intentionally close: the 72px chapter lead uses 64px leading, and the monumental proof statement uses 0.87. Give the surrounding block room rather than loosening those lines.
- Neue Montreal Book is the lighter text cut within the sans family; use it for story prose and stat captions, not the medium feature descriptions.

## Layout

**Density:** Airy between chapters, concentrated within cards and plan comparisons.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon spacing, small caption gaps and stacked feature-list gaps. |
| 12px | Footer link gaps and closely paired proof panels. |
| 16px | Default title-to-support gap and feature title-to-copy gap. |
| 20px | Container side padding. |
| 24px | Plan and editorial-card padding; editorial text/action gaps. |
| 32px | Feature-card padding and horizontal gaps. |
| 40px | Internal plan group spacing and footer block separation. |
| 48px | Feature-row separation and space above footer legal strip. |
| 60px | Heading group to output-art rail; FAQ link to closing action. |
| 80px | Navigation height and culture section padding. |
| 96px | Editorial opening top padding below the header. |
| 120px | Breathing room between closing action and footer. |
| 160px | Large separation before objection handling. |
| 240px | Bottom spacing of specialist-product and company chapters. |

### Containers and grids

- **public container**: max width 1240px · side padding 20px. Centered border-box container; 1200px of usable content at desktop.
- **feature rows**: 3 columns · gap 32px. Three 376px-wide feature cards across the public container.
- **plan grid**: 3 columns · gap 24px. Equal-width pricing plans with aligned actions and feature lists.
- **reading column**: max width 800px · side padding 20px. 760px inner width for prompt panel and default FAQ.
- **editorial reading** (only for company and recruiting stories): max width 782px. Company-story paragraphs, narrower than the full media container.
- **stat grid** (only for company proof grids): 3 columns · gap 24px. Centered 384px-wide statistical cards in a two-row desktop arrangement.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 9999px (pill) |
| cards and video | 24px |
| glass panels | 20px |
| editorial thumbnails | 16px |
| badges | 12px |
| engagement counters | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| prompt aura | `-5.3px 0px 40px rgba(255,176,3,0.067), 5.3px 0px 40px rgba(254,60,125,0.067)` | Subtle amber and pink edge light around the creative prompt. |
| floating artwork | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Depth under tilted opening output artwork. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #101012; color: #f7f4ef`

**Observed:** Long unbroken charcoal sections make colored media feel bright.

**Transfer:** Keep the neutral ground continuous through most of a landing page.

#### Feature fog · level 1

**Use:** Feature cards.

**CSS:** `background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.1); border-radius: 24px`

**Observed:** Low-contrast outlines distinguish panels without lifted shadows.

**Transfer:** Use for text-plus-image capabilities rather than an opaque light card.

#### Plan fog · level 1

**Use:** Pricing cards.

**CSS:** `background: rgba(247,244,239,0.05); border: 1px solid rgba(255,255,255,0.1); border-radius: 24px`

**Observed:** A warmer wash than feature cards; the recommended plan gets a pink edge.

**Transfer:** Separate price, action and feature list into legible groups.

#### Header glass · level 2

**Use:** Navigation backing.

**CSS:** `background: rgba(16,16,18,0.6); backdrop-filter: blur(24px) saturate(1.5)`

**Observed:** A fixed 80px bar allows the atmosphere to show through; editorial variants are sticky.

**Transfer:** Preserve translucency above imagery and solidity by appearance over charcoal.

#### Prompt glass · level 1

**Use:** Creative-action panel in the opening.

**CSS:** `background: rgba(16,16,18,0.1); border: 0.5px solid rgba(255,255,255,0.1); border-radius: 20px; backdrop-filter: blur(18.8px)`

**Observed:** A shallow glass rectangle over the warm field, with prompt aura shadow.

**Transfer:** Keep this as a real action surface: a prompt, search or compact task launcher.

#### Proof glass · level 1

**Use:** Ratings and conversion panels on the luminous proof stage.

**CSS:** `background: rgba(28,28,31,0.4); border: 1px solid rgba(255,255,255,0.2); border-radius: 20px; padding: 24px`

**Observed:** Atmosphere remains visible through two adjacent panels.

**Transfer:** Use for two comparable proof points and their relevant actions.

#### Solid editorial panel · level 1

**Use:** Statistics, editorial product cards and video containers.

**CSS:** `background: #252529; border-radius: 24px`

**Observed:** More opaque and visibly lighter than feature fog.

**Transfer:** Use when a scoped editorial section needs a stronger grouped surface.

#### Ivory story band · level 0

**Only for:** culture and recruiting stories

**Use:** Long inverted narrative chapter.

**CSS:** `background: #f7f4ef; color: #101012`

**Observed:** An extended light stretch contains place photography, monumental words and warm-stone quote cards.

**Transfer:** Treat it as an editorial change of register, not alternating light and dark stripes.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `height: 80px; display: flex; align-items: center; justify-content: space-between; padding: 20px`

**Text style:** `navigation` — Neue Montreal 500 · 15px/24px

**Observed:** Wordmark and four compact navigation choices sit left; outlined login and ivory signup capsules sit right. The public container aligns the bar with content. Menu labels have small downward chevrons.

**States:** Declared: hover unspecified; focus-visible 2px solid ivory outline on navigation actions.

**Transfer:** Keep product navigation short and reserve the far right for account actions.

### Ivory button

**Use:** Primary utility conversion and secondary major conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f7f4ef; color: #101012; border-radius: 9999px; height: 56px; padding: 16px 32px`

**Text style:** `button` — Neue Montreal 500 · 17px/24px

**Observed:** The compact header variant is 40px high with 8px 16px padding and navigation typography; major plans can use full-width buttons.

**States:** Declared: hover unspecified; focus-visible 2px solid #f7f4ef outline with 1px offset.

### Aura button

**Use:** Central creative action and final invitation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background-color: #000000; color: #ffffff; border-radius: 9999px; height: 40px; padding: 8px 16px`

**Text style:** `navigation` — Neue Montreal 500 · 15px/24px

**Observed:** A warm orange, red and magenta image fills the capsule. A small creative glyph precedes the label. The closing version is 56px high with 16px 78px padding and button typography.

**States:** Declared: hover unspecified; focus-visible 2px solid #f7f4ef outline with 1px offset.

**Transfer:** Apply the warm aura treatment described under imagery as a background layer; keep the label white.

### Prompt composer

**Use:** An immediate way to try the core task.

**CSS:** `display: flex; flex-direction: column; gap: 8px; width: 760px; max-width: 100%; min-height: 113px; border-radius: 20px; background: rgba(16,16,18,0.1); border: 0.5px solid rgba(255,255,255,0.1); backdrop-filter: blur(18.8px)`

**Observed:** A prompt field spans the first row. The second row places an add control and advanced-options chip left, a randomization control and Aura button right. Inner horizontal spacing is 20px, with 16px top and bottom insets.

**Transfer:** For a non-generative product use a short task input with one decisive action; do not substitute a dense form.

### Feature card

**Use:** Capability explanation with a visual payoff.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; width: 376px; min-height: 460px; padding: 32px; background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.1); border-radius: 24px`

**Text style:** `card-heading` — Neue Montreal 500 · 20px/1.2

**Observed:** Title then description at a 16px gap. Art is centered in the lower half, commonly 310px by 208px, with enough space to keep the upper text visually separate.

**States:** Declared: hover background white at 10%; focus-visible outline-style none.

**Transfer:** Use card-body for the description and one focused visual, not a miniature page.

### Plan card

**Use:** Compare subscription tiers.

**CSS:** `display: flex; flex-direction: column; gap: 40px; padding: 24px; background: rgba(247,244,239,0.05); border: 1px solid rgba(255,255,255,0.1); border-radius: 24px`

**Text style:** `plan-name` — Editorial New 300 · 24px/1.5

**Observed:** Serif name and short description above compact price and billing notes; full-width capsule action precedes a dense checked feature list. Default tier uses a translucent gray action, recommended tier an aura action and pink outline, top tier ivory.

**Transfer:** Emphasize one plan without brightening the whole card.

### Promotion badge

**Use:** Small pricing emphasis.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding: 2px 8px; border-radius: 12px; background: #fd429c; color: #fcfbf9`

**Text style:** `badge` — Neue Montreal 500 · 10px/1.5 · uppercase

**Observed:** Tiny capsule aligned opposite the plan title, with a small white glyph. Best-value and savings variants are neutral washes.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 24px 0px; border-bottom: 1px solid rgba(255,255,255,0.1); color: #f7f4ef`

**Text style:** `question` — Neue Montreal 500 · 20px/1.5

**Observed:** A plain question fills the left; a plus sits right. Default rows are about 81px tall within a 760px reading width. Specialist-product FAQs use a two-column layout with a serif heading left and smaller questions right.

**States:** Declared: hover row border white at 25%; focus-visible 2px solid ivory outline on the question button.

### Social circle

**Use:** Footer social destinations.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 50%; border: 1px solid rgba(255,255,255,0.15); color: #fcfbf9`

**Observed:** Monochrome 20px social glyph, one per circle; the row uses an 8px gap.

**States:** Declared: hover border white at 10%; focus-visible 2px solid ivory outline.

### Footer link

**Use:** Low-emphasis grouped site navigation.

**CSS:** `color: #c2c2c1`

**Text style:** `footer-link` — Neue Montreal 400 · 14px/1.5

**Observed:** Links stack with 12px gaps below a brighter medium-weight column heading. External destinations append a small northeast arrow.

**States:** Declared: hover color #fcfbf9; focus-visible 2px solid ivory outline.

### Stat tile

**Only for:** company proof grids

**Use:** Quantified company proof.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; height: 180px; padding: 24px; background: #252529; border-radius: 24px`

**Text style:** `stat` — Editorial New 300 · 64px/1

**Observed:** One large light-serif figure above a Book-cut caption at an 8px gap, centered in equal-sized tiles.

## Imagery and graphics

### Grainy warm aura

**Use:** Signature opening and monumental proof backgrounds; capsule conversion artwork.

**Observed:** Clouds of mustard amber, burnt orange, deep red and wine-magenta diffuse into charcoal. Fine granular noise breaks the smooth gradients. The opening is lit across its upper field and fades to darkness below; the proof scene is vignetted on every edge. Capsule art is a much more saturated slice of the same heat.

**Transfer:** Include this atmospheric light device in a new landing page. Match the glow and grain rather than relying on exact color stops; it should illuminate the stage without tinting body text.

**Build:** Layer broad radial ellipses: amber rgba(255,176,3,0.45) around 20% 35%, deep red rgba(215,45,20,0.45) around 55% 25%, and pink rgba(253,66,156,0.28) around 72% 20%. Use 300px–700px fields with roughly 80px blur. Add a monochrome SVG feTurbulence texture with low opacity, then a charcoal vertical fade and radial edge vignette above it. For the capsule, shrink the fields to the button bounds and raise saturation; keep the text layer above the noise.

### Output artwork rail

**Use:** Creative proof after an invitation or launch statement.

**Observed:** Five richly varied portrait covers, 228px by 311px, separated by 38px. The subjects range from blurred portraits to collage, paper objects and stark graphic symbols. Small play glyphs sit at top left; dark glass engagement counters overlap the bottom, with title and creator below.

**Transfer:** Make a rail of polished outputs from the new product. If the product has no visual output, art-direct five use cases as portrait cover compositions rather than substituting stock software logos.

### Tilted opening covers

**Use:** Peripheral depth in the creative opening.

**Observed:** Two roughly 280px by 385px portrait cards tilt in opposite directions, partly outside the viewport. They are darker and softer than the central message, with large play circles, bottom captions and deep shadows.

**Transfer:** Use two result compositions or artifacts as peripheral objects; keep the center free for the promise and action.

**Build:** Place portrait image cards at the lateral edges of the stage; rotate approximately -10deg and 10deg, clip the outer edges, apply brightness(0.5), blur(1.1px) and a deep 25px-offset shadow. Add a bottom charcoal-to-transparent gradient for captions.

### Feature visual miniatures

**Use:** Lower half of capability cards.

**Observed:** A mixture of obliquely framed interface details, glossy orange-magenta type sculpture, sticker-like collage and isolated symbolic objects. Each is a compact, composed scene with rounded clipping rather than a full-screen app view.

**Transfer:** Alternate tightly edited product views with one or two tactile abstract objects. Minimum version: a clean interface detail on black, one warm glow and a strong crop; do not depend on elaborate 3D rendering.

### Vertical creator films

**Use:** Social proof rail.

**Observed:** Five 234px by 415px portrait videos sit side by side with 21px gaps and small creator handles beneath. Frames feel candid and varied, including faces, equipment and personal commentary.

**Transfer:** Use credible people demonstrating outcomes in their own environments; retain portrait framing and understated captions.

### Product demonstrations

**Only for:** specialist-product launches

**Use:** Large hero film, alternating feature scenes and tutorial thumbnails.

**Observed:** A 1200px by 675px opening film shows an angled close-up of a dark creative interface with luminous tracks. Feature media is 793px by 446px; three smaller workflow cards use 387px by 290px views. Tutorials form a compact four-column wall of 288px by 162px images with white circular play controls.

**Transfer:** Show real workflows, enlarged enough to read the main gesture; contain UI color inside the media stage. A static, carefully composed workflow view is the minimum alternative to film.

### People and place photography

**Only for:** company and recruiting stories

**Use:** Human narrative, wide media bands and editorial splits.

**Observed:** Warm natural-light scenes of people actively creating, candid group portraits, city locations and a full-width collage of expressive people. Images have rounded framing, believable color and little ornamental overlay. One split pairs a nearly square 568px by 565px scene with a short text column.

**Transfer:** Photograph the activity and setting of the new audience; prioritize hands, tools, collaboration and genuine enjoyment over headshot grids.

### Icons

**Observed:** Small monochrome filled utility glyphs, typically 12px–20px, sit beside labels or within circular controls. Play triangles mark output media. Recruiting arrows are 12px with 2px round strokes; specialist carousel chevrons use 16px icons and 1.5px round strokes. Culture benefit cards use distinct colorful miniature illustrations rather than ordinary utility glyphs.

**Transfer:** Keep navigation and actions monochrome and compact. Reserve colorful object-like icons for the scoped culture-card treatment.

## Section recipes

How recurring sections are built.

### First screen: Creative atmosphere opening

**Observed:** A 900px-tall stage has Header glass across its top 80px. Back to front: a full-width grainy warm aura fading into Canvas, two dark tilted opening covers clipped at the lateral edges, and a centered text/action stack. The display headline occupies about three fifths of the width and wraps into two lines. A narrow 410px hero-support block sits below; the 760px by 113px Prompt composer follows at a 24px gap. All of the headline, support and action panel are visible in the first 900px; a dim monochrome publication-logo rail occupies the lower edge. The next section title falls below the fold.

**Transfer:** Default to this participatory, warm-atmosphere opening for a new marketing page. Without native artwork, compose two result artifacts and keep the live task launcher central. Editorial company openings instead use editorial-display on plain charcoal with support and an ivory action; specialist-product launches add a wide demonstration film below the serif stack. Application pricing opens directly with plans inside a sidebar shell.

**Avoid:** Do not turn the first screen into a left-copy/right-dashboard split, a giant serif poster by default, or a gallery whose bright peripheral cards compete with the central action.

**Text style:** `display` — Neue Montreal 500 · 72px/1 · tracking -0.0133em

### Heading and output proof

**Observed:** A centered heading, 16px support gap and a narrow support block lead into Output artwork rail after 60px. The chapter title uses heading; specialist launches substitute editorial-heading and a 24px support gap.

**Transfer:** Use to establish quality through actual results rather than a list of adjectives.

**Text style:** `heading` — Neue Montreal 500 · 72px/64px

### Capability collection

**Observed:** A left-aligned two-line chapter lead spans roughly 760px. Feature rows begin 72px below it, with Feature cards in three columns, 32px horizontal gaps and 48px between rows.

**Transfer:** Choose the capabilities needed for the new story; preserve the compact text-over-art card construction rather than copying a section count.

**Text style:** `heading` — Neue Montreal 500 · 72px/64px

### Plan comparison

**Observed:** A centered title/support pair leads to a monthly/yearly choice and three Plan cards at 24px gaps. Serif plan names contrast with compact sans prices. Only the recommended plan receives a pink edge and aura action.

**Transfer:** Keep the choice understandable at a glance, then let detailed feature lists serve careful comparison.

### Monumental luminous proof

**Observed:** A full-width 900px atmosphere stage centers a two-line monumental headline, support text and two Proof glass panels in a 672px-wide group with a 12px gap. Each panel combines a 40px rating, small review caption and a white download capsule.

**Transfer:** Use a real major proof point and paired destinations or outcomes. Preserve the dramatic scale and warm vignette, even if the metric is not an app rating.

**Text style:** `monumental` — Neue Montreal 500 · 140px/0.87 · tracking -0.0263em

### Objections and final invitation

**Observed:** The default ending uses a centered heading/support pair over a 760px FAQ column, five ruled FAQ rows, a dim full-FAQ text link, then a centered Aura button. The final action has 60px space above and 120px below before the footer. The specialist variant uses a split serif FAQ, then a centered editorial-heading invitation and white capsule separated from the footer by 240px.

**Transfer:** Resolve the page's main adoption objections and end with one clear invitation; the closing action does not need a new promotional card.

**Text style:** `heading` — Neue Montreal 500 · 72px/64px

### Open footer

**Observed:** A 1200px-wide dark footer pairs a small wordmark and Social circle row on the left with three link columns on the right. Columns are 176px wide with 48px gaps. A legal strip sits 48px below, separated by a white-at-15% hairline and 24px vertical padding; a small outlined language capsule aligns right.

**Transfer:** Close with an orderly, low-contrast directory rather than another hero. Company stories can arrive here after news or a long actionable listing.

### Editorial product chapters

**Only for:** specialist-product launches

**Observed:** A narrow editorial-heading and Book-cut support pair sit beside a wider 793px by 446px product demonstration. Subsequent chapters reverse the balance; 240px bottom space lets each scene stand independently. Later workflow and tutorial rails tighten the pace.

**Transfer:** Give each workflow one visible gesture and one benefit; use the serif voice consistently across this page type.

**Text style:** `editorial-heading` — Editorial New 300 · 54px/58px · tracking -0.03em

### Inverted conceptual words

**Only for:** culture and recruiting stories

**Observed:** Ivory story band supports an introductory story-heading followed by two-column rows. The left holds a 180px light-serif word and 32px sentence completion; the right holds a short gray explanation. Hairline black-at-10% rules, 40px bottom padding and 40px row gaps provide rhythm.

**Transfer:** Use a few defining product or organizational principles as visual language, not a prescribed list of company values.

**Text style:** `word-sculpture` — Editorial New 300 · 180px/1 · tracking -0.03em

### Company proof and editorial cards

**Only for:** company stories

**Observed:** A centered story-heading leads to a three-column, two-row Stat tile grid. Product cards elsewhere use four columns, imagery above the text and solid editorial panels. A later program block uses three open text columns with 64px gaps.

**Transfer:** Mix quantified proof, concrete offerings and participation opportunities without treating every section as the same card grid.

**Text style:** `story-heading` — Neue Montreal 500 · 64px/1 · tracking -0.01em

## Page flow

**Storyline:** Invitation → visible results → capability detail → credible proof and choice → objections → focused invitation or actionable directory → restrained footer.

### Broad product marketing and immediate trial

1. **promise and participation** — Atmospheric opening with a task launcher and floating result artwork.
2. **quality proof** — Output rail beneath a bold chapter title.
3. **capability chapters** — Three-column feature-card collection.
4. **choice** — Plan comparison with one aura-highlighted action.
5. **quantified and social proof** — Monumental luminous stage followed by portrait creator films.
6. **objection handling and closing call** — Ruled FAQ, small continuation link, isolated aura conversion, open footer.

**Transfer:** Use the participatory opening and luminous proof as signature devices; adapt the amount and order of detail to the product.

### Detailed subscription decision inside an application

1. **choice** — Compact serif title, billing switch and plans within a persistent sidebar and bottom player shell.
2. **objection handling** — Stacked FAQ panels below billing details.
3. **detailed comparison** — A ruled multi-column feature table with grouped category bands, checks and locks; the table ends the scroll without a marketing footer.

**Transfer:** Use the app shell only when the page belongs inside a product; borrow the plan treatment for an ordinary marketing page without importing the sidebar or player.

### Attract candidates and make the opportunity concrete

1. **shared purpose** — Serif invitation, two paragraphs, ivory action and wide candid group photograph.
2. **culture proof** — Activity photography and compact profile cards.
3. **editorial differentiation** — Long ivory band with place photography, monumental conceptual words and sideways quote cards.
4. **practical reassurance** — Dark benefit grid, hiring accordions and compensation prose.
5. **actionable directory** — Search/filter controls and fine-ruled role listings, ending directly in the shared footer.

**Transfer:** Use the dark-to-ivory-to-dark editorial change for a rich people story; replace the directory with the relevant actionable opportunities.

### Launch a specialist creative tool through workflows

1. **promise** — Two-line light-serif display, concise support, white action and large angled demonstration film.
2. **result proof** — Portrait output rail.
3. **workflow chapters** — Alternating text/media demonstrations, then smaller workflow cards.
4. **education and objection handling** — Tutorial thumbnail wall and split-column FAQ.
5. **closing call** — Centered serif invitation, white capsule and large dark breathing space before the shared footer.

**Transfer:** Choose this serif-led variant for a focused professional tool, retaining warm creative output rather than enterprise dashboard imagery.

### Explain the organization through people, product and scale

1. **identity** — Serif statement, short paragraph, ivory action and large expressive photo collage.
2. **origin and offering** — Editorial image/text split, product cards and backing statement.
3. **quantified proof** — Light-serif figures in a dark stat grid.
4. **participation and currency** — Three open program columns, then a hairline-separated three-card news row.
5. **ending** — News leads directly into the shared directory footer without an extra closing conversion banner.

**Transfer:** Use the editorial variant to connect human purpose to tangible offerings and current activity.

## Writing

Inviting, direct and creatively confident. Concrete verbs and everyday situations make ambitious technology feel playable, while specialist copy is comfortable naming actual controls and workflows.

**Do not copy:** Do not reuse Suno names, marks, cover art, creator identities, quotations, pricing, rankings, funding, review totals or other product-specific claims; replace them with substantiated material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you and your work; use we for the people building the product, not an impersonal corporation.
- **Rhythm:** Brief sentence-case headlines alternate with one- or two-sentence explanations. Action labels are short verbs; longer editorial paragraphs are broken into distinct ideas.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct creative invitation, expressed as something the reader can make. | 5–10 words | “Make any song you can imagine” |
| Chapter lead | Plain-language benefit, often using your to give the reader agency. | 4–11 words | “Everything you need to make music your way”<br>“Play it how you mean it.” |
| Supporting line | Name a low-friction entry point and a tangible result. | One or two sentences | “Start with a simple prompt or dive into our pro editing tools, your next track is just a step away.” |
| Feature description | Start with a concrete verb, then say what can be changed or controlled. | 18–35 words | “Pull any song apart into clean, time-aligned stems and carry them into the DAW you already use.” |
| Action | Short verb plus a destination or immediacy cue. | 1–4 words | “Try it now”<br>“See open positions” |
| Closing invitation | Repeat the page's playful central phrase and make the next step explicit. | 6–10 words | “Be a control freak. Try Studio now.” |

**Words and phrasing to use:** make; your way; start; play; shape; own; explore; every detail; start fresh

**Avoid:** synergize; enterprise-grade transformation; seamless solutions; unlock unparalleled efficiency; revolutionary ecosystem

**Rules:**

- Lead with what a person can do, then explain the technology supporting it.
- Connect professional depth to an accessible entry point instead of choosing only beginner or expert language.
- Use playful specificity sparingly; let feature descriptions remain concrete.
- Only make superlative or quantified claims when they can be substantiated for the new product.

## Do's and Don'ts

### Do

- Keep the default page predominantly #101012, with #f7f4ef text and localized warm atmosphere.
- Preserve the 72px/64px medium chapter recipe rather than replacing it with bold type.
- Give feature cards 32px padding and 24px corners.
- Keep major actions 56px high and compact navigation actions 40px high.
- Use 20px side padding inside the centered 1240px public container.
- Include portrait output proof and a luminous monumental proof stage, adapted to the new product.
- Keep FAQ content within a 760px inner reading width.
- Let editorial chapters breathe with up to 240px bottom spacing.

### Don't

- Do not paint ordinary section backgrounds pink; #fd429c is a small emphasis color outside media.
- Do not make all panels #252529; default feature panels use a much subtler 4% white fog.
- Do not use squared or modestly rounded main actions; the capsule silhouette is essential.
- Do not apply the 180px serif word treatment to an ordinary capability grid; it belongs to the inverted editorial band.
- Do not give feature cards raised white shadows; separation comes from a faint 1px edge.
- Do not turn all body copy into 18px editorial prose; feature descriptions stay 16px/24px at weight 500.
- Do not enlarge footer headings into another content chapter; their 14px scale is deliberately restrained.
- Do not spread app-interface accent colors into the surrounding marketing controls.

## Motion and responsive

### Motion

**Observed:**

- Most navigation and card colors transition over 0.15s with cubic-bezier(.4, 0, .2, 1); button color/opacity declarations also use 75ms.
- Header-glass opacity uses 0.2s cubic-bezier(0.33, 1, 0.68, 1).
- Marquee declarations include 30s linear infinite and 10s linear infinite.
- Specialist-product white actions declare hover scale 1.02; creator handles underline on hover.

**Transfer:**

- Keep hover feedback focused on color and subtle scale; preserve the sense of drifting creative media without animating every text block.

**Unknown:**

- Exact background-video behavior, typing cadence, scroll choreography and marquee membership are not established.

### Responsive

**Observed:**

- CSS includes 640px, 768px, 1024px and 1280px breakpoints among others.
- Opening display classes specify 48px/44px before the desktop 72px recipe; chapter leads specify 35px/35px before desktop 72px/64px.
- Editorial display classes specify 48px/52px before desktop 96px/104px; the serif specialist heading specifies 36px/40px before 54px/58px.
- Feature rows declare horizontal overflow and scroll snapping, with cards constrained to 90vw; desktop navigation is hidden below its large-screen layout.

**Transfer:**

- On narrow screens preserve the central task and balanced headline before peripheral artwork. Keep output rails horizontally browsable and allow feature rows to snap rather than compressing three cards into unreadable columns.
- Use the declared smaller display recipes and reduce editorial chapter breathing space before reducing paragraph legibility.

**Unknown:**

- Exact mobile header menu, device-specific artwork positions and all breakpoint-to-layout assignments remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
