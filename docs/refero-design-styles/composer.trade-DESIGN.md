# Composer — modular color, monumental type

## Overview

A technical yet playful marketing style that makes sophisticated software feel tactile and approachable. Light grey fields and black grotesk typography are interrupted by bright modular blocks, saturated blue chapters and forest-green proof panels. Product interfaces float like physical objects, while aerial landscapes and geometric overlays give specialist pages an expansive, experimental mood. The pacing is spacious at the chapter level and compact inside demonstrations and comparison cards.

### Essentials

- Make the product name a typographic object: a 244px/1, weight-700 grotesk word spans most of the opening width, paired with a 64px introduction and 36px supporting copy.
- Use a gridded playground rather than a conventional centered hero: a #ecedee canvas has 240px grid squares, with hard-edged green, pink, cyan-looking blue and yellow blocks passing behind oversized black letters.
- Actions are long capsules with a directional tail: 9999px radii, 16px vertical padding, 36px horizontal padding and right arrows; the opening action uses 36px text while chapter actions use 20px.
- Keep most reading areas neutral; concentrate color into discrete events: small rectangular opening accents, one #1871da capability band, a #31805a proof panel and #1c372a footer rather than tinting every card.
- Stage real product artifacts at architectural scale: 6px corners, fine outlines and layered directional shadows; pair wide interface views with smaller explanatory fragments and ruled two- or three-column cells.
- Include an expressive word-block proof device: 64px green words on individually staggered #ffb4ed rectangles inside a 12px-radius green panel. Use a short verified benefit statement in the same treatment when quotations are unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof green | `#31805a` | `--color-proof-green` | surface, text, accent | Proof panel, its reversed word-block letters and navigation sign-up hover. |
| Forest | `#1c372a` | `--color-forest` | background, surface, action | Default footer and photographic closing-call panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm yellow | `#ffbb38` | `--color-yellow` | accent, text | Small geometric blocks and announcement emphasis. |
| Chapter blue | `#1871da` | `--color-blue` | background, accent | Capability band, gradient-heading start and hard-light opening blocks. |
| Block green | `#1ec072` | `--color-block-green` | accent | Multiply-blended opening rectangles and geometric art. |
| Block pink | `#f6609f` | `--color-hot-pink` | accent | Hard-light modular art and final heading-gradient stop; blending makes the opening blocks appear lighter. |
| Gradient violet | `#ba84ff` | `--color-purple` | accent | Middle stop of the selective blue-to-pink heading gradient. |
| Light pink | `#ffb4ed` | `--color-pink` | surface, text, action, accent | Highlighted word rectangles, dark-chapter buttons and short decorative accents. |
| Warm sand | `#e3bc99` | `--color-sand` | text | Headings on near-black specialist chapters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Primary typography, black capsules and the company-story band. |
| Near-black green | `#101516` | `--color-dark` | background, text, action | Announcement strip and dark specialist sections. |
| Muted grey text | `#666666` | `--color-muted` | text | Visible black at 60% over white; supporting copy also uses black at 60% over the grey canvas. |
| FAQ edge | `#bfbfbf` | `--color-faq-rule` | border | Visible black at 25% over white for question-row separators. |
| Cool ruled edge | `#bec6cc` | `--color-rule` | border | Default fine dividers between feature cells and chapter bands. |
| Cool grey canvas | `#ecedee` | `--color-canvas` | background, surface | Default marketing background and outlined-action fill. |
| White | `#ffffff` | `--color-white` | text, surface, background | Proof strips, FAQ fields, interface cards and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| AI feature landing pages | Trial orange | `#fc6821` | `--color-orange` | action, accent | Closing trial capsule and square ornament. |
| AI feature landing pages | Hatched lavender | `#d39fff` | `--color-hatch-purple` | accent | Diagonal hatch ornament attached to a closing panel. |
| business and AI feature landing pages | Rock brown | `#402622` | `--color-brown` | background | Photographic proof and closing bands. |
| business landing pages | Business footer charcoal | `#1e1e1e` | `--color-charcoal` | background | Alternative footer background. |
| AI feature landing pages | Atmospheric slate | `#2e3740` | `--color-slate` | background | Landscape-backed long-form capability chapters. |
| AI feature landing pages | Blue grey paper | `#eceef0` | `--color-ai-canvas` | background | Cooler feature-landing canvas. |
| retirement-style specialist pages | Ivory paper | `#f5f3eb` | `--color-retirement-canvas` | background | Long-form explanatory sections between dark opening and closing bands. |
| business landing pages | Warm business paper | `#f7f5f0` | `--color-business-canvas` | background | Warm alternative to the default cool grey. |

## Typography

- **neue-haas-grotesk-display** — All marketing typography, from monumental names to compact navigation. A close-set neo-grotesk with a high x-height, compact proportions and direct, unornamented letterforms. If unavailable, use **Inter**. Use weights 400–700; preserve normal display tracking and tune name width before changing size. Font stack: "neue-haas-grotesk-display", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | neue-haas-grotesk-display | 700 | 244px | 1 | normal | fixed | Monumental single-word product introduction. |
| intro-kicker | neue-haas-grotesk-display | 700 | 64px | 0.5 | normal | fixed | Short introductory word above the monumental name; not a general eyebrow. |
| heading-lg | neue-haas-grotesk-display | 600 | 64px | 1 | normal | fixed | Major chapter headings, FAQ title and word-block proof title. |
| hero-support | neue-haas-grotesk-display | 400 | 36px | 1.2 | 0.01em | fixed | Opening description, including a separately spaced short payoff. |
| heading | neue-haas-grotesk-display | 600 | 36px | 40px | normal | fixed | Feature chapter lead and selective gradient headline. |
| hero-action | neue-haas-grotesk-display | 400 | 36px | 1 | normal | fixed | Opening action and wide proof-panel signup capsule. |
| stat | neue-haas-grotesk-display | 600 | 36px | 1 | normal | fixed | Compact numerical proof. |
| chapter-support | neue-haas-grotesk-display | 400 | 32px | 1.2 | 0.02em | fixed | Large two-column explanatory paragraphs in the blue chapter. |
| card-heading | neue-haas-grotesk-display | 600 | 24px | 32px | normal | fixed | Centered feature-cell headings. |
| question | neue-haas-grotesk-display | 400 | 24px | 1 | 0.025em | fixed | FAQ question triggers. |
| stat-label | neue-haas-grotesk-display | 400 | 24px | 1.5 | 0.02em | fixed | Muted label directly below each stat. |
| body | neue-haas-grotesk-display | 400 | 20px | 1.4 | 0.025em | fixed | Default feature support and list copy. |
| body-compact | neue-haas-grotesk-display | 400 | 20px | 1.3 | 0.02em | fixed | Detailed product explanations under interface fragments. |
| quote | neue-haas-grotesk-display | 400 | 20px | 1.2 | 0.02em | fixed | Short statements within the proof panel. |
| action | neue-haas-grotesk-display | 500 | 20px | 1 | normal | fixed | Chapter-level filled or outlined action. |
| nav | neue-haas-grotesk-display | 500 | 14px | 20px | normal | fixed | Navigation text links. |
| nav-action | neue-haas-grotesk-display | 600 | 14px | 20px | normal | fixed | Compact navigation signup capsule. |
| small | neue-haas-grotesk-display | 400 | 14px | 20px | 0.025em | fixed | Announcement copy and compact utility text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AI feature landing pages | feature-display | neue-haas-grotesk-display | 500 | 64px | 1 | normal | fixed | Concise promise beside a tall photographic composite. |
| business landing pages | business-display | neue-haas-grotesk-display | 500 | 60px | 1 | normal | fixed | Multi-line audience-oriented promise. |
| retirement-style specialist pages | specialist-display | neue-haas-grotesk-display | 700 | 60px | 1 | normal | fixed | Sand-colored promise on a dark opening. |
| pricing pages | pricing-display | neue-haas-grotesk-display | 400 | 60px | 1 | normal | size clamp(48px, 16vw, 60px) | Restrained page title over a dotted field. |
| AI feature landing pages | chapter-value | neue-haas-grotesk-display | 600 | 60px | 1.5 | normal | fixed | Single-word capability headings in the narrow atmospheric column. |
| business landing pages | closing-business | neue-haas-grotesk-display | 500 | 36px | 1.2 | 0.025em | fixed | Pink closing headline over a brown panel. |
| AI feature landing pages | closing-feature | neue-haas-grotesk-display | 600 | 32px | 1.3 | normal | fixed | Compact promise inside the forest-green closing square. |
| pricing pages | plan-heading | neue-haas-grotesk-display | 700 | 24px | 29px | normal | fixed | Plan names. |
| pricing pages | plan-price | neue-haas-grotesk-display | 500 | 24px | 29px | normal | fixed | Price lines immediately below plan names. |
| pricing pages | plan-body | neue-haas-grotesk-display | 400 | 16px | 1.25 | normal | fixed | Plan descriptions and checked feature lists. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display and major headings use normal tracking rather than fashionable negative tracking. Body and compact utility copy gain slight positive tracking, usually 0.02em–0.025em.
- The exceptional intro-kicker line height belongs only to the interlocked name composition; ordinary headings use a full line box.
- Treat the enormous name as live typography, not a logo image. For longer product names, break or resize intentionally while preserving dominance.
- Interface artwork can use Inter internally; it is not a second marketing voice.

## Layout

**Density:** Airy between chapters, tightly fitted within product fragments; the large display and ruled cells create density without crowding support copy.

### Spacing

**Spacing system:**

- **grid** 8px — Main spacing rhythm; 4px serves small heading gaps and 36px capsule insets are a distinct component exception.

| Value | Use |
| --- | --- |
| 8px | Chapter heading to support line. |
| 16px | Compact list gaps, pricing-grid gutters and vertical capsule padding. |
| 24px | Plan-card internal padding and compact block separation. |
| 32px | Page side insets, chapter action separation and proof-panel gutters. |
| 40px | Feature-cell padding and proof-panel inset. |
| 48px | Stat-strip padding and loose feature-composition gaps. |
| 56px | Footer padding and feature-cell bottom breathing room. |
| 64px | Split-section gaps and capability chapter spacing. |
| 80px | Large product comparison row padding. |
| 96px | Blue chapter top padding and separation before detailed product fragments. |
| 160px | Major dark/light chapter padding and FAQ breathing room. |

### Containers and grids

- **main-container**: max width 1600px · side padding 32px. Centered wide marketing field; 1376px usable width at a 1440px viewport.
- **editorial-container**: max width 1200px · side padding 0px. Inset chapter copy, large editor artwork and pricing comparisons; center within the main field.
- **split-feature**: 2 columns · gap 64px. Text and substantial media in balanced halves, with the image allowed to lead or overlap the next band.
- **ruled-feature-grid**: 3 columns · gap 0px. Contiguous feature cells separated by fine edges rather than floating rounded cards.
- **faq-column**: max width 803px. Question stack occupies the right seven-twelfths of the wide container; headline stays at the left.
- **pricing-grid** (only for pricing pages): max width 1200px · 3 columns · gap 16px. Equal-height plans above a full-width business option.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-capsules | 9999px (pill) |
|  | product-panels | 6px |
|  | proof-panel | 12px |
| pricing pages | plan-cards | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product-depth | `0px 52.9px 20.7px 0px rgba(0,0,0,0.01), 0px 29.3px 17.9px 0px rgba(0,0,0,0.03), 0px 12.9px 12.9px 0px rgba(0,0,0,0.05), 0px 3.6px 7.2px 0px rgba(0,0,0,0.06)` | Layered soft lift beneath product artwork, not beneath every text cell. |
| pricing pages | plan-lift | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | White pricing cards. |

### Surfaces

#### Grid canvas · level 0

**Use:** Default opening field.

**CSS:** `background-color: #ecedee; background-image: linear-gradient(rgba(0,0,0,0.16) 0.5px, rgba(0,0,0,0) 0.5px), linear-gradient(to right, rgba(0,0,0,0.16) 0.5px, rgba(0,0,0,0) 0.5px); background-size: 240px 240px`

**Observed:** Large, very fine squares continue behind the opening name and color blocks; later opaque bands cover the grid.

**Transfer:** Use the grid to ground modular artwork, not as a texture over every paragraph.

#### Neutral chapter · level 0

**Use:** Main product explanations.

**CSS:** `background-color: #ecedee; color: #000000`

#### White proof field · level 0

**Use:** Stats, publication marks and questions.

**CSS:** `background-color: #ffffff; color: #000000`

#### Dotted product stage · level 0

**Use:** Technical demonstration backing.

**CSS:** `background-image: linear-gradient(90deg, #ecedee 0%, rgba(0,0,0,0) 100%), radial-gradient(rgba(0,0,0,0.2) 1px, rgba(0,0,0,0) 1px); background-size: 100% 100%, 16px 16px; border-bottom: 1px solid #bec6cc`

**Observed:** Dots become apparent toward the media side; copy remains on a calmer grey field.

**Transfer:** Fade the dot grid away beneath the reading column.

#### Dark specialist band · level 0

**Use:** An alternate-product chapter with landscape media.

**CSS:** `background-color: #101516; color: #ffffff`

**Observed:** Sand headings and pink capsule actions sit beside green landscape artwork.

#### Blue capability band · level 0

**Use:** A strong transition into deeper product capabilities.

**CSS:** `background-color: #1871da; color: #ffffff; padding: 96px 0px 136px`

**Observed:** A fine inverse rule separates the title from two large support columns; a wide interface object overlaps the band’s lower edge.

#### Green proof panel · level 1

**Use:** Expressive proof statements and conversion.

**CSS:** `background-color: #31805a; border-radius: 12px; padding: 40px; color: #ffffff`

**Observed:** Inset 32px from the wide page edge, with an irregularly composed word-block title and surrounding quotes.

#### Forest footer · level 0

**Use:** Final brand and utility information.

**CSS:** `background-color: #1c372a; color: #ffffff; padding: 56px 0px`

**Observed:** Business variants use charcoal instead. The legal content is visually subordinate to the upper brand/contact row.

#### Warm paper · level 0

**Only for:** business landing pages

**Use:** Audience-specific business narrative.

**CSS:** `background-color: #f7f5f0; color: #000000`

#### Ivory explanation field · level 0

**Only for:** retirement-style specialist pages

**Use:** Long-form specialist explanations.

**CSS:** `background-color: #f5f3eb; color: #000000`

#### Slate landscape field · level 0

**Only for:** AI feature landing pages

**Use:** Immersive capability narrative.

**CSS:** `background-color: #2e3740; color: #ffffff; padding: 104px 0px`

**Observed:** Dark aerial terrain occupies the inset field, fading into the solid slate below.

#### Brown closing band · level 0

**Only for:** business and AI feature landing pages

**Use:** Warm photographic closing composition.

**CSS:** `background-color: #402622`

**Observed:** Business uses pink type and two narrow vertical photo strips; the feature variant places a green square over a much larger rock image.

## Components

### Navigation links

**Use:** Compact desktop site navigation.

**CSS:** `padding: 2px 8px; border-radius: 9999px; color: #000000`

**Text style:** `nav` — neue-haas-grotesk-display 500 · 14px/20px

**Observed:** Small links sit in a right-aligned row opposite a compact brand mark. A resource label includes a small chevron; dark specialist openings invert link text.

**States:** Declared: hover background-color rgba(0,0,0,0.1).

### Navigation signup

**Use:** Persistent high-intent action in the navigation.

**CSS:** `background-color: #000000; color: #ffffff; padding: 2px 8px; border-radius: 9999px; height: 24px`

**Text style:** `nav-action` — neue-haas-grotesk-display 600 · 14px/20px

**Observed:** Visually much smaller than chapter actions; the dark-opening variant uses a white fill and black text.

**States:** Declared: hover background-color #31805a.

### Primary button

**Use:** Main opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background-color: #000000; color: #ffffff; border-radius: 9999px; padding: 16px 36px; height: 68px`

**Text style:** `hero-action` — neue-haas-grotesk-display 400 · 36px/1

**Observed:** Text leads and a simple right arrow sits in a generous trailing area. The opening capsule has a thin black outer wrapper; specialist openings use smaller 20px action text.

**Transfer:** Keep one clear action and a strong directional tail rather than a paired button cluster.

### Pink chapter button

**Use:** Conversion or exploration within dark product chapters.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background-color: #ffb4ed; color: #000000; border-radius: 9999px; padding: 16px 36px; height: 52px`

**Text style:** `action` — neue-haas-grotesk-display 500 · 20px/1

**Observed:** Short label and right arrow; business closing variant substitutes a small conversation icon.

### Outlined button

**Use:** Lower-pressure pricing or detail navigation.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background-color: #ecedee; color: #000000; border: 1px solid #000000; border-radius: 9999px; padding: 16px 36px; height: 54px`

**Text style:** `action` — neue-haas-grotesk-display 500 · 20px/1

**Observed:** Placed beneath supporting details, not styled like a filled primary action.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 0px; border-bottom: 1px solid rgba(0,0,0,0.25); color: #000000`

**Text style:** `question` — neue-haas-grotesk-display 400 · 24px/1 · tracking 0.025em

**Observed:** Each row is a full-width text trigger with a muted 24px chevron at the far right; adjoining rows form a continuous stack rather than separate cards.

### Stat block

**Use:** Quantified proof in a white strip.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; color: #000000`

**Text style:** `stat` — neue-haas-grotesk-display 600 · 36px/1

**Observed:** Bold number sits directly above a stat-label line at 60% black. Three blocks share a 48px-gap strip with dotted vertical dividers; publication marks sit below.

**Transfer:** Use short defensible numbers, keeping labels visually secondary.

### Ruled feature cell

**Use:** Explain individual product mechanisms.

**CSS:** `padding: 40px; border-right: 1px solid #bec6cc; display: flex; flex-direction: column; align-items: center; gap: 16px`

**Text style:** `card-heading` — neue-haas-grotesk-display 600 · 24px/32px

**Observed:** Product fragment above compact heading and support. Cells share the page canvas; final cells omit the outer edge. Some paired feature cells use taller artwork stages and 56px bottom padding.

### Word block

**Use:** The expressive title device within the proof panel.

**CSS:** `background-color: #ffb4ed; color: #31805a; padding: 0px 6px 6px`

**Text style:** `heading-lg` — neue-haas-grotesk-display 600 · 64px/1

**Observed:** Each word has its own tight rectangular backing, staggered horizontally and slightly overlapped vertically. Fine outlined quotation marks frame the group.

**Transfer:** Use two to four short words; retain the irregular staircase rather than placing one flat highlight behind a whole sentence.

### Wide proof signup

**Use:** Conversion at the base of the proof panel.

**CSS:** `background-color: #000000; color: #ffffff; border-radius: 100px; padding: 16px 32px; display: flex; justify-content: space-between; align-items: center; height: 68px`

**Text style:** `hero-action` — neue-haas-grotesk-display 400 · 36px/1

**Observed:** Spans the middle two columns of the four-column proof grid, 632px wide at desktop; a short qualification sits below.

**States:** Declared: hover color #ffb4ed.

### Footer band

**Use:** Final utility and trust layer.

**CSS:** `background-color: #1c372a; color: #ffffff; padding: 56px 0px`

**Text style:** `small` — neue-haas-grotesk-display 400 · 14px/20px · tracking 0.025em

**Observed:** Compact brand mark left, social icons and contact right. A 56px gap leads into full-width paragraphs with 16px separation and subdued white at 40%; privacy utility closes the band. Business uses charcoal.

**Transfer:** Preserve the restrained brand/contact row and subordinate utility hierarchy; match the amount of disclosure to the new product’s actual obligations.

### Plan card

**Only for:** pricing pages

**Use:** Compare tier benefits without a decorative featured-plan hierarchy.

**CSS:** `background-color: #ffffff; border-radius: 6px; overflow: hidden; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Text style:** `plan-body` — neue-haas-grotesk-display 400 · 16px/1.25

**Observed:** Header and feature body each have 24px insets, separated by a 1px black-at-15% rule. Plan-heading, plan-price and a full-width black arrow capsule precede green circular checks. Equal-height columns keep corresponding benefit rows aligned; a full-width business card sits underneath.

## Imagery and graphics

### Modular block field

**Use:** Signature opening artwork and small recurring chapter accents.

**Observed:** Flat, hard-edged rectangles in green, pink, yellow and cyan-looking blended blue step diagonally across the grey grid. Some blocks have tiny dot patterns; blocks overlap letters and page edges without becoming rounded stickers.

**Transfer:** Construct equivalent modules around the new product name. This is the fallback artwork when no product photography exists.

**Build:** Use an overflow-hidden absolute layer behind live text. Arrange 50px-high rectangular units and 100px/200px-tall groups, including a broad 500px by 200px green zone above the name’s left side and smaller 125px-wide steps toward the lower right. Use #1ec072 with multiply, #f6609f and #1871da with hard-light, and #ffbb38 with multiply. Overlay 1px dots at 20px intervals on selected rectangles. Keep corners square and preserve a clear support-copy area.

### Floating product artifacts

**Use:** Primary demonstrations and feature grids.

**Observed:** Black chart panels, white conversational cards and small logic fragments overlap one another on pale dotted fields. The biggest editor view is about 1200px wide; other compositions juxtapose an 860px graph with a 400px explanation column and smaller secondary chart. Fine outlines and multi-layer shadows give the flat UI physical depth.

**Transfer:** Use genuine, readable interface excerpts from the new product; minimum version is one complete panel plus one meaningful detail, with working content rather than a skeleton. Keep surrounding artwork sparse.

**Build:** Layer a 6px-radius black or white product panel over the Dotted product stage. Add one smaller white card offset over its top-left edge, then a soft product-depth shadow. Keep diagrams aligned to the underlying ruled cells and use real product colors only within the interface.

### Landscape with geometric intervention

**Use:** Specialist product chapters and audience landings.

**Observed:** Green aerial hills or weathered rock faces fill crisp rectangular windows occupying about half a split composition. A white pixel-diamond or fine concentric line figure is centered over the terrain; muted natural texture contrasts with small sharp colored modules.

**Transfer:** Choose expansive, detailed natural terrain with an uncluttered focal area; add an original geometric system mark, not a literal illustration of the feature.

**Build:** Cover a rectangular image frame with aerial landscape photography. Add a centered SVG of repeated 12px–20px squares rotated 45deg, or two sets of thin concentric circles with a small horizontal offset. Use white at partial opacity and a few pink, green or yellow squares; no enclosing badge.

### Tactile access object

**Use:** Pricing invitation or upgrade section.

**Observed:** A dark forest-toned card floats at a slight counterclockwise angle on the light canvas. Fine contour lines, subtle serial markings and low-contrast gold details make it feel engraved; a long soft shadow anchors it beside the copy.

**Transfer:** Represent access with a relevant pass, tool plaque or compact physical token. Maintain the dark material and understated engraving rather than substituting a bright payment-card mockup.

**Build:** Create a roughly 417px by 247px, 6px-radius dark rectangular SVG, rotate it slightly counterclockwise and apply a multi-layer down-right shadow. Draw dense fine contour lines in white at 8%–15% opacity and a few restrained sand-colored markings.

### Handheld luminous composite

**Only for:** AI feature landing pages

**Use:** Feature-specific hero media.

**Observed:** A photographed hand holds an iridescent orb against blue sky and white clouds. Thin orbit paths and tiny interface-like tags surround the orb; a fading grid bridges the art into the pale reading column. The image occupies about three-fifths of the opening.

**Transfer:** Make an original human-scale product metaphor that combines photography with a single luminous object. Minimum version is a well-lit hand/object photograph plus a modest colored halo and a few SVG orbit lines.

**Build:** Mask a hand photograph over a cloud image. Place a circular radial-gradient object above the palm with pink, blue and yellow-green lobes, a bright rim and a blurred glow behind it. Draw two tilted thin white SVG ellipses and several small white pill tags. Fade the grid toward the copy side.

### Atmospheric terrain chapter

**Only for:** AI feature landing pages

**Use:** Long-form capability storytelling.

**Observed:** Dark blue-grey aerial terrain spans the inset field behind a narrow centered text column and fades into slate near the lower feature row. White words and fine horizontal rules sit directly over the image.

**Transfer:** Use a textured natural or material image that reads at low contrast. Preserve legibility and the transition into the solid lower field.

**Build:** Place a cover photograph inside 32px side insets. Add a dark translucent slate overlay and a bottom gradient from transparent to #2e3740, beginning near 47% and reaching solid near 81%. Center a 400px copy column above it.

### Photographic closing square

**Only for:** AI feature landing pages

**Use:** Final conversion before the footer.

**Observed:** A large rotated-feeling rock formation fills a 720px-high band. A 500px forest-green square sits left of center, carrying white copy and an orange action; an orange square and lavender hatch square protrude from its upper right edge.

**Transfer:** Use original material photography and a solid square message panel, with a short outcome statement and one action.

**Build:** Cover the full band with rock or material photography, lightly darkened. Position a 500px square #1c372a panel with 40px horizontal and 60px vertical padding. Attach two 75px squares to its right edge: solid #fc6821 above a repeating -45deg #d39fff 1px line/4px interval hatch.

### Pathway diagram

**Only for:** retirement-style specialist pages

**Use:** Closing illustration beside the final promise.

**Observed:** Four slender pastel paths descend from outlined circular nodes, then bend toward different arrow destinations over a faint dotted grid on near-black. The graphic occupies the right half of a 617px-tall band.

**Transfer:** Represent alternate paths or flexible outcomes with simple routed lines rather than reusing the original financial symbolism.

**Build:** Use a 600px-wide SVG on #101516. Draw four 2px paths with rounded quarter-circle bends in pink, green, cyan and yellow; start each at a small outlined node and end with three repeated chevrons. Put a low-opacity dotted grid behind the routes.

### Name-tile wall

**Only for:** company-story sections

**Use:** Humanize the company without portrait photography.

**Observed:** A five-column checker-like wall of small saturated rectangular name cards sits on black, alternating occupied cells with negative space. Cards use compact black name and role text; the other half contains mission copy and white supporter marks.

**Transfer:** Use real people or contributors; maintain the graphic tile rhythm rather than introducing circular headshots.

**Build:** Make a five-column CSS grid of approximately 146px by 75px cells with 1px gaps. Populate staggered cells with green, blue, pink and yellow name cards using 16px by 12px padding. Let unoccupied cells show the black background.

### Icons

**Observed:** Small monochrome arrows and chevrons support navigation, not decorative icon packs. Action arrows are typically 16px–20px; FAQ chevrons occupy 24px. Circular check marks precede short benefit lists; feature illustrations use larger diagrammatic forms.

**Transfer:** Choose simple line arrows, compact filled checks and recognizable utility silhouettes. Keep their color tied to text or the proof green; do not copy an apparent 16px SVG stroke width as a CSS stroke rule.

## Section recipes

How recurring sections are built.

### First screen: Monumental modular opening

**Observed:** A 50px near-black announcement strip sits above compact navigation with 32px side insets. The opening is a 896px-tall grey gridded stage below the navigation. Back-to-front layers are the fine square grid, stepped colorful block artwork, black live headline, then support and action. The headline begins well below navigation: a short 64px intro word sits over a 244px product name spanning about four-fifths of the viewport. Support is left aligned under the name in a roughly 583px column, with a separate short payoff and 56px separation before the Primary button. Within the first 900px, navigation, the entire headline, colored blocks and supporting copy are visible; the action starts near the bottom and continues below the fold. The numerical proof strip follows below the opening.

**Transfer:** Use a short product name or an equally compact category phrase as the monumental object; construct the Modular block field without relying on proprietary artwork. Business variants open with a 60px audience promise in the left half and tall terrain on the right; feature variants use a 64px concise promise beside the Handheld luminous composite. Specialist dark openings use sand 60px type and pink actions; pricing uses a restrained title over dots rather than the name sculpture.

**Avoid:** Do not replace the composition with a centered 64px slogan over a generic dashboard, or put the blocks in front of essential support text.

**Text style:** `display` — neue-haas-grotesk-display 700 · 244px/1

### Compact proof strip

**Observed:** White proof field contains three Stat blocks with 48px gaps and dotted separators, then a small centered publication-mark row.

**Transfer:** Use verified short numbers and relevant third-party proof; keep the number/label scale relationship rather than making giant financial-style counters.

**Text style:** `stat` — neue-haas-grotesk-display 600 · 36px/1

### Asymmetric product demonstration

**Observed:** A 36px gradient heading and muted support occupy the left third, while a large layered product artifact extends across the right and can clip at the viewport edge. Dotted product stage fades under the copy; heading-to-copy gap is 8px.

**Transfer:** Demonstrate a single meaningful workflow, placing the human intent card before the product result. Keep the gradient selective, not a sitewide headline treatment.

**Text style:** `heading` — neue-haas-grotesk-display 600 · 36px/40px

### Ruled capability cells

**Observed:** Two-column media-led cells and three-column detail rows share the grey background and touch along 1px cool edges. Ruled feature cell uses 40px insets, centered media and a compact heading/support group.

**Transfer:** Use cells for comparable mechanisms, choosing artwork scale before adding copy. Preserve the continuous ruled system rather than converting every item into a floating card.

**Text style:** `card-heading` — neue-haas-grotesk-display 600 · 24px/32px

### Immersive product chapter

**Observed:** Blue capability band uses a 64px white heading, a thin inverse rule and two 32px support columns within 1200px. A wide editor artifact overlaps into the grey following field, then breaks down into smaller ruled explanations.

**Transfer:** Use a saturated chapter for the product’s deepest or most distinctive capability. Carry the actual interface across the surface transition.

**Text style:** `heading-lg` — neue-haas-grotesk-display 600 · 64px/1

### Dark landscape split

**Observed:** Dark specialist band pairs a sand 64px heading, a short white check list and Pink chapter button with a crisp landscape window. The balanced halves have a 64px gap and 160px vertical breathing room.

**Transfer:** Use for a distinct use case or secondary product, preserving the warm-on-dark contrast and restrained amount of copy.

**Text style:** `heading-lg` — neue-haas-grotesk-display 600 · 64px/1

### Access-object invitation

**Observed:** Tactile access object floats left of a large headline and support group on neutral grey. Smaller checked assurances and Outlined button sit below; the warm specialist variant places this composition inside a white 8px-radius inset panel.

**Transfer:** Explain entry or upgrade through a tangible access metaphor and two concise assurances, not a complete plan table.

### Expressive proof panel

**Observed:** Green proof panel holds a staggered Word block title in its upper middle, surrounded by short quotes with tiny pink dash marks. Five statements distribute unevenly across a four-column grid; Wide proof signup spans the middle at the base.

**Transfer:** Use real testimonials or short verified outcomes, keeping the sculptural title, open spacing and subordinate attribution.

**Text style:** `quote` — neue-haas-grotesk-display 400 · 20px/1.2 · tracking 0.02em

### Offset questions

**Observed:** White proof field carries a large two-line heading at left; FAQ rows stack in an 803px right-aligned column. The title leads the row stack slightly rather than occupying a boxed sidebar. Large sections reserve about 160px of lower breathing room.

**Transfer:** Group practical objections into brief questions and let the continuous rules do the organization.

**Text style:** `heading-lg` — neue-haas-grotesk-display 600 · 64px/1

### Company coda and utility ending

**Observed:** A black company-story band pairs 64px white heading and mission copy with Name-tile wall. Forest footer follows as a separate green layer: brand/contact row, subdued full-width utility paragraphs and a final privacy control. Pricing and specialist landings omit the company story but retain the utility ending.

**Transfer:** Use the company coda when human credibility belongs in the narrative. Always finish with a purposeful brand/contact layer rather than extending the conversion artwork indefinitely.

**Text style:** `heading-lg` — neue-haas-grotesk-display 600 · 64px/1

### Photographic plan comparison

**Only for:** pricing pages

**Observed:** A restrained title leads into a dark, cool-toned, softly focused photographic field. Three equal Plan cards occupy a 1200px grid with 16px gutters, followed by a full-width business card. A white bordered referral panel pairs a landscape image with compact copy; questions then lead directly to Forest footer.

**Transfer:** Use a dark material photograph as atmosphere behind highly legible white cards; no single tier needs a colored fill.

**Text style:** `plan-heading` — neue-haas-grotesk-display 700 · 24px/29px

### Terrain capability essay

**Only for:** AI feature landing pages

**Observed:** Slate landscape field begins with a centered regular-weight headline, then a 400px column of single-word headings, supporting lines and fine rules. A three-image benefit row and broad white action conclude the terrain chapter.

**Transfer:** Use for a conceptual feature narrative where a few human benefits need more atmosphere than UI detail.

**Text style:** `chapter-value` — neue-haas-grotesk-display 600 · 60px/1.5

### Specialist closing calls

**Only for:** specialist and audience landing pages

**Observed:** Three distinct endings share a short promise and single capsule. The warm business version is a 410px brown panel with pink type and two 200px-wide terrain/sky strips at the right. The dark specialist version is a 617px split with Pathway diagram. The feature version uses Photographic closing square, then immediately meets the forest footer.

**Transfer:** Choose the ending that matches the landing theme; keep the photo strip, routed line art or square overlay as the compositional anchor, rather than mixing all three.

**Text style:** `heading` — neue-haas-grotesk-display 600 · 36px/40px

## Page flow

**Storyline:** promise → concrete product or category proof → capability explanations → credible outcomes → entry or upgrade invitation → practical objections → themed closing or company coda → utility ending

### Broad product introduction with deep demonstrations

1. **promise** — Monumental live product name and modular color field.
2. **quantified proof** — White stat strip and publication marks.
3. **product demonstration** — Layered conversational result, followed by paired capability cells.
4. **entry and expansion** — Dark specialist use-case split and tactile access-object invitation.
5. **capability chapters** — Saturated blue chapter, large editor view and detailed ruled fragments.
6. **social proof** — Green word-block panel and wide signup.
7. **objection handling** — Offset question stack.
8. **company credibility and ending** — Black mission/name-tile coda followed by green utility footer.

**Transfer:** Use the visual range to support a broad product story; shorten or rearrange capability chapters without losing the monumental opening and graphic proof device.

### Decision-focused plan comparison

1. **orientation** — Simple regular-weight title on a dotted canvas.
2. **pricing** — Three equal white tier cards and a full-width business option over dark photographic material.
3. **incentive** — Bordered landscape-and-copy referral panel.
4. **objection handling** — Right-offset questions.
5. **utility ending** — Green footer directly after the question field; no additional conversion banner.

**Transfer:** Let structured comparison and practical questions carry the decision; do not force the broad-product hero into this page type.

### Explain a specialist account or use case with reassurance

1. **promise** — Dark split opening with sand heading, pink action and aerial terrain.
2. **explanation** — Ivory ruled sections with benefits, mechanics and transfer details.
3. **entry invitation** — White inset access-object panel.
4. **capability proof** — Centered diagram and paired benefit explanations.
5. **closing call** — Near-black promise-and-pathway split.
6. **utility ending** — Forest footer.

**Transfer:** Use the warm paper/dark chapter variant for reassurance-heavy specialist content; keep required qualifications close to the claims they qualify.

### Audience-specific product landing with a consultative conversion

1. **audience promise** — 60px multi-line text and tall terrain image in balanced halves.
2. **capability overview** — Three illustrated benefits and dark audience taxonomy panel.
3. **assisted entry** — Subtle inset support panel with consultation action.
4. **social and quantified proof** — Terrain-backed quote and compact stat panel.
5. **capability chapters** — Interactive-looking explanation list and ruled two-by-two illustrated features.
6. **practical enablement** — Reporting assurances and physical guide mockup on a green half-panel.
7. **objection handling** — Offset FAQ.
8. **closing call and utility** — Pink-on-brown call with narrow photo strips, then charcoal footer.

**Transfer:** Lead with the audience’s work and constraints; preserve the consultative action and warm material palette.

### Feature-focused landing that combines human imagination with technical execution

1. **promise** — Short medium-weight headline and luminous hand-held composite.
2. **proof** — Compact highlighted metrics and large presenter video.
3. **product demonstration** — Selectable-looking workflow descriptions beside result imagery.
4. **capability narrative** — Dark terrain essay, single-word value headings, diagrammatic benefit row and white action.
5. **objection handling** — Extended offset FAQ on cool grey.
6. **closing call** — Green message square over rock photography with orange action and hatch ornament.
7. **utility ending** — Forest footer.

**Transfer:** Balance one imaginative composite with actual product outcomes; retain the richly composed final call rather than ending on an ordinary gradient card.

## Writing

Confident and practical with flashes of creative enthusiasm. Technical capability is explained through plain verbs and concrete actions, while reassurance reduces the sense that expertise is required.

**Do not copy:** Do not reuse Composer or SoFi names, logos, proprietary marks, product names, financial claims, trading statistics, fees, referral rewards, testimonials, people, partner marks or legal language. Replace all claims and proof with material that is true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Use we for assistance and commitments; name the product when describing what it does automatically.
- **Rhythm:** Short benefit headlines mix with one- or two-sentence explanations. Verb sequences and occasional fragments add pace; longer procedural paragraphs belong in specialist explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Introduce the product directly or state the category plus the intended audience. | 2–10 words before any audience extension | “Meet [Brand]”<br>“The AI for Trading.”<br>“Automated trading for emerging funds & family offices.” |
| Supporting line | Name the workflow in a sequence of concrete verbs, then remove a barrier. | 15–30 words | “Build trading algorithms with AI, backtest them, then execute—all in one platform. No coding skills required.” |
| Capability headline | Use a short verb pair or a direct noun phrase, not an abstract manifesto. | 2–5 words | “Customize and Create”<br>“Learn and adapt”<br>“Seamless Asset Transfers” |
| Benefit explanation | Explain what the user can change and what the product handles. | 1–2 sentences | “Every strategy on [Brand] is fully editable. Swap out assets, adjust programmatic logic, and tweak parameters.” |
| Primary action | Short verb-led entry or assisted next step. | 2–5 words | “Get started”<br>“Book a free consultation”<br>“Start free trial” |
| Question | Ask the practical question a new buyer would actually voice. | 5–14 words | “Do I need coding experience?”<br>“What happens if I cancel Advanced or Pro?” |

**Words and phrasing to use:** build; create; automate; test; compare; edit; swap out; adjust; fully editable; all-in-one; end-to-end; no coding required

**Avoid:** revolutionary disruption; guaranteed outcomes; effortless riches; enterprise-grade synergy; unexplained technical acronyms

**Rules:**

- Pair each broad benefit with the concrete mechanism or workflow that makes it possible.
- Use reassuring constraints and qualifications near material claims rather than hiding them in the footer.
- Prefer direct verbs over strings of adjectives.
- Use short creative turns sparingly; most copy should explain what happens and what the reader controls.
- Distinguish product assistance from promises of user success.

## Do's and Don'ts

### Do

- Keep the primary name at monumental scale: 244px/1 at desktop, with normal tracking.
- Use 1px #bec6cc rules and contiguous cells for detailed capabilities.
- Set ordinary support at 20px/1.4 with 0.025em tracking and a visibly muted tone.
- Preserve the 16px by 36px capsule construction and a clear right-arrow tail.
- Keep wide demonstrations near 1200px and use smaller fragments to explain mechanisms.
- Concentrate bright color into modular art and chapter-scale bands, including a green graphic proof moment.
- Offset the FAQ into a roughly seven-twelfths right column instead of centering every block.
- Finish with the restrained brand/contact row and a clearly subordinate utility layer.

### Don't

- Do not tighten 64px display headings with aggressive negative tracking; their normal spacing is part of the grotesk character.
- Do not turn all feature cells into 24px-radius floating cards; their default construction is square and ruled.
- Do not use rectangular or mildly rounded primary buttons; actions are full capsules.
- Do not make the light-grey canvas pure white throughout; white has a distinct proof and utility role.
- Do not spread the blue-to-pink text gradient across every heading; it belongs to a selective demonstration lead.
- Do not give all product UI the same flat drop shadow; large artifacts need soft layered directional depth.
- Do not use generic circular stock portraits in the company tile composition; its human detail is typographic.
- Do not default to an all-dark page or fill every section with saturated color; neutral reading fields must remain dominant.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares 0.3s transitions with cubic-bezier(0.4,0,0.2,1); the wide proof signup declares a 0.2s color transition.
- Opening colored blocks declare repeating 5s movement with cubic-bezier(0,0.9,0.4,1).
- Announcement emphasis declares a 2.5s linear shimmer. Product holdings and detail sequences use 10s cycles, while concentric rings use 3s ease-in-out cycles.

**Transfer:**

- Keep motion concentrated in the modular opening and product-process diagrams, so the large live headline remains the stable anchor.
- Use declared color changes for compact navigation; reserve the more expressive cyclic motion for illustrated processes.

**Unknown:**

- Exact keyframe paths and scroll-trigger timing are not specified here.
- Focus-visible appearance is not established for the default marketing capsules.

### Responsive

**Observed:**

- Declared width breakpoints include 478px, 479px, 640px, 767px, 768px, 991px, 1023px, 1024px, 1280px, 1440px and 1536px.
- Layout classes declare single-column stacks before two- and three-column desktop grids. Several split openings reverse the stack so media can precede copy.
- Pricing title follows clamp(48px, 16vw, 60px). Compact desktop navigation links are hidden below the large-layout breakpoint.

**Transfer:**

- On narrow layouts, preserve a dominant live name but fit it deliberately; keep the modular blocks around rather than over support text.
- Stack ruled cells and move the FAQ column to full width while retaining the same line-based system.
- Reduce photographic closing compositions to one dominant image and one legible message panel; keep their attached geometric ornament.

**Unknown:**

- Exact mobile typography, navigation drawer construction and image crops are not established.
- No general fluid formula is known for the monumental name; fit it to the actual new copy rather than assuming a desktop size scales automatically.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
