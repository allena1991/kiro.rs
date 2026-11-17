# Presentable — magenta after dark

## Overview

A near-black gallery with rounded geometric sans typography, vivid little windows of work, and a flamboyant serif signature. Cool white and grey carry the reading while hot pink punctuates the opening and floods the closing. The mood is cultured, personable and deliberately crafted, suited to creative products, premium services and visually rich portfolios; spacious chapters surround compact, orderly card collections.

### Essentials

- A two-part promise behaves like a changing label above a fixed conclusion: Poppins 84px, weight 500, -0.03em tracking; the pink first line uses 1.22 line height and the white conclusion uses 1.
- The opening balances a broad verbal promise with a small cabinet of colorful objects: a 764px text region beside four 180px square images, arranged in two staggered columns with 12px gaps, all within an 828px-tall stage below a 72px header.
- Actions are small, pale lozenges rather than pink slabs: the principal button is 50px tall with 26px horizontal padding and a fully rounded silhouette; its companion is a bare 17px text link with a tiny muted chevron.
- Color lives inside media and at the bookends: #06060a dominates the long body, #111116 forms cards, #ff00bf marks the changing hero word and active navigation, and a full-width #ff2ec8 closing field replaces the darkness. The closing field occupies about one eighth of the long landing page, not alternating feature bands.
- Work is presented as collectible rounded windows: 24px card corners, 12px grid gutters, 586×366px landscape media above compact captions. Include richly colored product or application scenes; if finished work is unavailable, stage original diagrams and product details on solid colored backings.
- The final brand signature is monumental and serif, not another sans headline: black word artwork spans about 1193px by 209px over the pink field, beneath a detailed contact directory. Recreate this scale with the new product's own name and an expressive serif silhouette.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pink closing field | `#ff2ec8` | `--color-closing` | background, accent | Expansive closing field, paired with night-colored text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric pink type | `#ff00bf` | `--color-accent` | text, accent, link | Changing hero noun, small serif brand signature, current navigation and link hover. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool porcelain | `#f2f2f4` | `--color-foreground` | text, action | Headings, primary labels and pale button fills. |
| Night canvas | `#06060a` | `--color-canvas` | background, text | Default canvas and reversed text on pale actions and the pink closing field. |
| Smoked navigation | `#0b0b10` | `--color-glass` | surface | Visible result of rgba(19,19,25,0.41) over the night canvas; reserved for the compact floating navigation. |
| Gallery card | `#111116` | `--color-card` | surface | Rounded cards and broad media backing. |
| Media backing | `#18181e` | `--color-media` | surface | Backing behind image and video windows; normally covered by actual artwork. |
| Dark hairline | `#1a1a1d` | `--color-rule` | border | Visible white-at-about-8%-opacity separator over the night canvas; use rgba(255,255,255,0.0784) for ruled lists. |
| Chevron grey | `#66666e` | `--color-subtle` | text, accent | Small trailing chevrons that must not compete with their labels. |
| Reading grey | `#9b9ba3` | `--color-muted` | text | Paragraphs, supporting copy, inactive navigation and captions. |

## Typography

- **Poppins** — All reading text, navigation, numbers and sans headings. Rounded geometric sans with single-storey forms and broad circular counters; regular body and medium headings. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Poppins", sans-serif.
- **Young Serif** — Small brand signature and the character reference for monumental closing word artwork. Heavy, flared, soft-edged serif forms with a literary, almost carved silhouette. Font stack: "Young Serif", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 500 | 84px | 1 | -0.03em | Fixed hero conclusion and short interior page titles. |
| display-accent | Poppins | 500 | 84px | 1.22 | -0.03em | Changing pink first line of the landing promise. |
| section-heading | Poppins | 500 | 56px | 1.08 | -0.028em | Major chapter labels, including proof, capabilities and work. |
| statement | Poppins | 400 | 48px | 1.18 | -0.022em | Large editorial introduction; also extended white-to-grey manifesto text on company narratives. |
| feature-heading | Poppins | 500 | 48px | 1.06 | -0.026em | Large capability row titles. |
| stat | Poppins | 500 | 44px | 1 | -0.025em | Impact numerals near the lower half of a proof card. |
| contact-display | Poppins | 500 | 32px | 1.15 | -0.02em | Prominent email link within the closing field. |
| brand-signature | Young Serif | 400 | 25px | 1 | -0.006em | Pink brand link at the left of navigation. |
| name-table | Poppins | 400 | 24px | 1.5 | -0.012em | Plain-text names in an understated four-column relationship table. |
| card-heading | Poppins | 500 | 22px | 1.3 | -0.01em | Project titles, capability card names and editorial list names. |
| lead | Poppins | 400 | 20px | 1.55 | -0.005em | Hero support and section-heading partner paragraphs. |
| body | Poppins | 400 | 17px | 1.62 | normal | Reading paragraphs in introductory cards, descriptive rows and the closing introduction. |
| text-action | Poppins | 500 | 17px | 1.5 | -0.005em | Secondary actions and read-more links. |
| compact-title | Poppins | 500 | 16px | 1.5 | normal | Press-card titles and principal button labels. |
| stat-caption | Poppins | 400 | 16px | 1.45 | normal | Grey metric explanations, with at most two lines. |
| navigation | Poppins | 400 | 15px | 1.5 | normal | Header links in grey, with pink for the current destination. |
| caption | Poppins | 400 | 14px | 1.5 | 0.005em | Project provenance eyebrows, press descriptions and capability support. |
| small-button | Poppins | 500 | 14px | 1.5 | 0.005em | Compact header contact action. |
| footer-link | Poppins | 400 | 14px | 1.4 | 0.005em | Compact directory links on the pink field. |
| footer-label | Poppins | 500 | 13px | 1.5 | 0.01em | Small directory column names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company narrative feature rows | editorial-feature-heading | Poppins | 500 | 36px | 1.16 | -0.022em | Titles beside larger landscape images and longer descriptions. |

**Notes:**

- The hierarchy comes from scale and tracking rather than bold cuts: main text is 400 and titles are 500. Tighten tracking progressively from -0.005em in support copy to -0.03em in display.
- Use sentence case and original proper-name casing, not a system of uppercase eyebrows. Captions remain small, grey and closely attached to their card titles.
- Keep the serif confined to brand signatures and word artwork; ordinary editorial headings remain geometric sans. Hero display is plain Poppins rather than an elaborate feature-setting showcase.

## Layout

**Density:** Airy chapter transitions surround closely packed cards; the large black intervals are as important as the media.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Text-action label to chevron. |
| 8px | Capability card title to its support. |
| 10px | Project eyebrow to title. |
| 12px | All principal card-grid gutters and hero image gutters. |
| 14px | Metric number to explanation. |
| 18px | Capability heading to body and footer label to links. |
| 24px | Media to caption block; capability-card padding. |
| 26px | Press-card padding and hero button horizontal padding. |
| 28px | Proof-card padding, project caption side padding and hero action gap. |
| 32px | Hero heading to support; press-card logo region to text. |
| 40px | Hero support to actions; closing introduction to email. |
| 48px | Container side padding and large horizontal composition gaps. |
| 56px | Chapter heading to card group. |
| 64px | Large image/text row gutter and editorial statement to its card shelf. |
| 120px | Interior opening title top padding below the header. |
| 168px | Major chapter top spacing and final dark section bottom breathing room. |

### Containers and grids

- **Main container**: max width 1280px · side padding 48px. Centered desktop outer container; at 1440px the useful inner width is 1184px and text aligns 128px from the window edges.
- **Four-column shelf**: 4 columns · gap 12px. 287px-wide press, metric and capability cards across the useful desktop width.
- **Three-column introduction**: 3 columns · gap 12px. 387px-wide cards with landscape art above body copy.
- **Project shelf**: 2 columns · gap 12px. 586px-wide project cards; the highlighted first card occupies only the left column, leaving intentional space to its right.
- **Heading pair**: 2 columns · gap 48px. Large title on the left, a roughly 560px grey support paragraph on the right, usually aligned toward the bottom of the heading.
- **Hero support**: max width 520px. Short two-line supporting sentence below the broad display.
- **Editorial feature row** (only for company narrative feature rows): 2 columns · gap 64px. 653px-wide landscape image beside a narrower descriptive column, unlike the smaller square images in broad capability rows.

## Corner radius

| Element | Radius |
| --- | --- |
| Cards | 24px |
| Capability square media | 20px |
| Small media details | 14px |
| Buttons | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Night canvas · level 0

**Use:** Default background throughout the reading and gallery body.

**CSS:** `background: #06060a; color: #f2f2f4`

**Observed:** A flat, almost-black field with a slight cool cast; no decorative texture or ambient glow.

**Transfer:** Let space and artwork create depth rather than introducing atmosphere behind every section.

#### Gallery card · level 1

**Use:** Shared enclosure for press, capabilities, metrics and projects.

**CSS:** `background: #111116; border-radius: 24px; overflow: hidden; box-shadow: none`

**Observed:** Only a small tonal lift from the canvas; there is no routine bright outline.

**Transfer:** Keep the card visually subordinate to its contents.

#### Media backing · level 1

**Use:** Support behind images and videos.

**CSS:** `background: #18181e; overflow: hidden`

**Observed:** Media sits flush against the upper edge of gallery cards, while standalone square capability art has its own rounded corners.

**Transfer:** Always supply meaningful art over this base; the backing is not a substitute for the image.

#### Smoked navigation · level 2

**Use:** Compact floating navigation over scrolled content.

**CSS:** `background: rgba(19, 19, 25, 0.41); backdrop-filter: blur(1.9px); border-radius: 9999px`

**Observed:** The full opening navigation condenses into a centered capsule during scrolling. The surrounding header remains transparent-dark rather than a solid contrasting stripe.

**Transfer:** Use this as the sole restrained glass treatment, not as the material for the card system.

#### Pink closing field · level 0

**Use:** Shared contact and directory ending.

**CSS:** `background: #ff2ec8; color: #06060a; overflow: hidden`

**Observed:** Full-bleed flat saturation with dark text and an enormous dark serif signature; the shared desktop field is 1256px tall.

**Transfer:** Preserve the abrupt dark-to-pink change and the monumental signature while adapting the directory depth to the new content.

## Components

### Navigation

**Use:** Persistent orientation and a small contact route.

**CSS:** `position: fixed; height: 72px; z-index: 10; color: #9b9ba3`

**Text style:** `navigation` — Poppins 400 · 15px/1.5

**Observed:** A pink serif brand link sits left, four short navigation labels sit right, then a pale contact pill. The open version aligns to the main container; the scrolled version is centered inside Smoked navigation. Current destination uses pink.

**States:** Declared: hover changes navigation text to #ff00bf with no underline; focus-visible and active behavior are unknown.

**Transfer:** Keep the link count small enough for the compact capsule.

### Primary button

**Use:** Principal exploration or conversion action.

**CSS:** `background: #f2f2f4; color: #06060a; border-radius: 9999px; height: 50px; padding: 0px 26px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `compact-title` — Poppins 500 · 16px/1.5

**Observed:** Text-only pale pill; paired with an unfilled secondary action rather than a second filled button.

**Transfer:** Use a short verb-led label for the new product's most useful next step.

### Header contact pill

**Use:** Small persistent contact action.

**CSS:** `background: #f2f2f4; color: #06060a; border-radius: 9999px; height: 38px; padding: 0px 18px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `small-button` — Poppins 500 · 14px/1.5 · tracking 0.005em

**Observed:** A visibly smaller sibling of Primary button at the end of the header.

### Chevron text action

**Use:** Secondary hero action and contextual exploration links.

**CSS:** `color: #f2f2f4; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `text-action` — Poppins 500 · 17px/1.5 · tracking -0.005em

**Observed:** Bare label followed by a small grey right chevron, without a box or underline in the resting state.

**Transfer:** Reserve it for a real next step, not an ornament after every paragraph.

### Press card

**Use:** Compact third-party proof.

**CSS:** `background: #111116; border-radius: 24px; padding: 26px; display: flex; flex-direction: column; gap: 32px; overflow: hidden`

**Text style:** `compact-title` — Poppins 500 · 16px/1.5

**Observed:** A monochrome publication mark occupies the upper left, a discreet outbound arrow sits upper right, and the lower block contains a small white name plus a grey caption separated by 4px. Desktop size is 287×196px.

**Transfer:** Use authentic customer, partner or review marks with brief explanatory captions.

### Metric card

**Use:** Quantified proof in an uncluttered collection.

**CSS:** `background: #111116; border-radius: 24px; padding: 28px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `stat` — Poppins 500 · 44px/1 · tracking -0.025em

**Observed:** A small colored geometric emblem sits high at the left. A 96px internal spacer separates its region from the large number; the grey Stat-caption follows by 14px. Numbers align across 287×300px cards; currency and units can flank the number in smaller grey type.

**Transfer:** Use verified measures with short explanations and custom abstract badges.

### Project card

**Use:** Media-first proof and case-study access.

**CSS:** `background: #111116; border-radius: 24px; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `card-heading` — Poppins 500 · 22px/1.3 · tracking -0.01em

**Observed:** Landscape media fills the top. Below it come a grey provenance caption, white outcome title, then a bottom row with a small project name at left and Chevron text action at right. Captions use 28px side padding, 24px top spacing and 10px eyebrow-to-title gaps. Repeated desktop cards are 586×550px; the highlighted card is slightly shorter.

**Transfer:** Pair each real product view with an outcome, not just a project name.

### Closing directory

**Use:** Contact, useful links and final brand reinforcement.

**CSS:** `background: #ff2ec8; color: #06060a; display: flex; flex-direction: column`

**Text style:** `footer-link` — Poppins 400 · 14px/1.4 · tracking 0.005em

**Observed:** Short introduction and Contact-display email at upper left, back-to-top control at upper right; below, four unequal directory columns contain small labels and links with roughly 11px vertical gaps. The serif word artwork sits beneath the directory; a thin rule and small signoff/copyright row finish the field.

**States:** Declared: hover underlines footer links in #06060a; focus-visible and active behavior are unknown.

**Transfer:** Keep meaningful contact and navigation content above the word artwork; use product categories in place of service lists.

### Capability card

**Only for:** capability catalogues

**Use:** Explain a service or feature at two levels of detail.

**CSS:** `background: #111116; border-radius: 24px; padding: 24px; display: flex; flex-direction: column; gap: 28px; overflow: hidden`

**Text style:** `card-heading` — Poppins 500 · 22px/1.3 · tracking -0.01em

**Observed:** A 96px square thumbnail and discreet arrow lead; a white name and grey description follow; a faint divider separates the final deliverable line near the base. Four columns use 287px-wide cards around 401px tall.

**Transfer:** Use a focused feature illustration, a user-facing purpose, then concrete deliverables or supported tasks.

### Editorial proof row

**Only for:** company and recognition narratives

**Use:** Longer proof collections without repeating card boxes.

**CSS:** `display: flex; align-items: center; gap: 48px; padding: 28px 0px; border-top: 1px solid rgba(255, 255, 255, 0.0784)`

**Text style:** `card-heading` — Poppins 500 · 22px/1.3 · tracking -0.01em

**Observed:** A monochrome logo, white name, grey descriptor and small outbound arrow share one 104px-tall desktop row. Logo and name occupy the left portion, description starts in the right half.

**Transfer:** Keep the same alignment for every entry, even when marks have different proportions.

## Imagery and graphics

### Staggered object cabinet

**Use:** Signature landing hero companion.

**Observed:** Four 180px square windows occupy roughly the right third of the opening. Two columns are staggered vertically by about 40px, with 12px gutters and rounded corners. The subjects mix a miniature interface, front-facing physical object, construction diagram and printed packaging; cyan, green, blue and warm grey backings provide concentrated color.

**Transfer:** Create four original facets of the new product: interface, tangible application, geometric system and close detail. If there is no photography, use crisp vector diagrams and carefully framed UI rather than generic stock images.

**Build:** Use a two-column CSS grid with 180px tracks and 12px gaps. Translate the second column down 40px. Clip each square with 20px corners. Center a different product asset in each window; use flat local art colors, generous breathing room and no shared drop shadow.

### Abstract editorial art

**Use:** Signature visual language for conceptual explanations and proof badges.

**Observed:** Large introductory cards place simple graphic forms on saturated flat fields: an offset stack of horizontal bars, a centered square with a colored side strip, and translucent petal-like forms around a white square. Small metric emblems compress geometric symbols into colored rounded badges.

**Transfer:** Include original geometric art that expresses the new product's operations. The minimum is clean SVG primitives with purposeful repetition, not emoji or an unrelated illustration library.

**Build:** For a 387×290px panel, center a 90px square or a stack of five 90×16px rectangles shifted diagonally in 14px steps. Alternatively arrange four quarter-circle petals around a central square using translucent fills. Keep edges sharp within the rounded outer card, use one flat art color plus tonal variants, and scale the same geometry into compact badges for proof.

### Application films and stills

**Use:** Project shelves, standalone demonstrations and feature rows.

**Observed:** The gallery combines white-backed identity studies, near-black logo animation, vivid blue brand fields, physical packaging, screens and full-color people or spatial photography. Media remains rectangular and self-contained: 586×366px in project cards, 380px square in capability rows, and a broad 1184×666px film panel. Photographs retain rich reds, greens and warm interior light rather than receiving a uniform monochrome filter.

**Transfer:** Show the product in convincing use and its design details at multiple scales. Use a composed still when animation is unavailable; retain its clean backing, color concentration and edge-to-edge framing.

### Monumental serif word artwork

**Use:** Signature brand-scale artwork in the pink ending.

**Observed:** Dark, tightly fitted serif lettering spans nearly the complete inner container, about 1193×209px. It sits below a small brand-related sentence and above the fine closing rule; its scale contrasts dramatically with the small directory.

**Transfer:** Fit the new product name or a short ownable word into the same wide silhouette, preserving expressive serif curves and optical spacing.

**Build:** Typeset the new name in Young Serif inside an SVG viewBox approximately 1193 by 209. Fit the glyph outlines to the available width with optical kerning, use #06060a fill, and scale the SVG proportionally to the container. Prefer a single word; use a short product nickname if the full name would become too small.

### Postage portrait

**Only for:** company belief narratives

**Use:** Personal counterpoint beside a large statement.

**Observed:** A vertical 252×315px film-like portrait is framed as a cream perforated postage stamp with a vivid pink inner field. It appears to the left of the large belief paragraph.

**Transfer:** Use a real founder or maker portrait treated as a printed artifact, only where the personal story warrants it.

**Build:** Frame a vertical portrait with a cream inset border and hot-pink backing. Form repeated circular edge cutouts with an SVG mask on all four sides; retain the rectangular stamp silhouette and small print-like inner margin.

### Icons

**Observed:** Navigation and reading actions use tiny grey chevrons; card corners carry discreet outbound or right arrows around 16–18px, and the back-to-top control uses a 14px arrow. Colored geometric proof emblems are miniature artwork, not the same family as functional icons.

**Transfer:** Use simple thin directional glyphs with low contrast and consistent placement. Avoid a large colorful icon before every ordinary text label.

## Section recipes

How recurring sections are built.

### First screen: Promise and object cabinet

**Observed:** A 72px navigation strip sits above an 828px dark stage, filling the first 900px. Back to front: Night canvas, left-aligned two-line display, a right-side Staggered object cabinet, then the action row. The verbal block spans about two thirds of the useful width; the pink changing noun sits over a fixed white conclusion with tight tracking. The four small colorful windows form a taller, staggered cluster rather than one giant hero image. The main content sits around the middle of the stage with broad empty space above and below. A 520px-wide grey support sentence follows the headline by 32px, then Primary button and Chevron text action appear 40px below the support. Headline, support, both actions and all four objects are visible inside the first screen; the explanatory chapter begins below it.

**Transfer:** Default new landing pages use this split promise-and-cabinet composition with original product artifacts or purposeful vector constructions. Interior catalogue and work pages instead open with a plain 84px title 120px below the header; a work index adds a 20px support line after 28px, while a company narrative adds a 48px editorial statement after 48px.

**Avoid:** Do not center the promise above a huge dashboard, turn the four windows into a full-width tile grid, or fill the hero background with pink.

**Text style:** `display` — Poppins 500 · 84px/1 · tracking -0.03em

### Editorial introduction shelf

**Observed:** A Statement heading up to 1000px wide introduces the chapter after 168px top spacing. Three Gallery cards follow 64px later, each with 387×290px Abstract editorial art above a grey Body paragraph; content padding is 24px top, 26px sides and 28px bottom.

**Transfer:** Explain three complementary aspects of a different product using original geometry and concise paragraphs.

**Text style:** `statement` — Poppins 400 · 48px/1.18 · tracking -0.022em

### Heading pair

**Observed:** A Section-heading at left and Lead paragraph at right share the main width with a 48px gutter. Cards or rows begin after 56px; new chapters usually begin after 168px.

**Transfer:** Use the left side to name the chapter and the right to explain why it matters, rather than restating the heading.

**Text style:** `section-heading` — Poppins 500 · 56px/1.08 · tracking -0.028em

### Proof shelf

**Observed:** Press cards form a compact four-column shelf with 12px gutters. Metric cards use the same column width but are taller, with small colored art above lower-aligned numbers.

**Transfer:** Use the proof form appropriate to the claim: third-party references or verified metrics. Preserve visual emblem space and numerical alignment.

### Capability feature row

**Observed:** Thin rules separate broad rows with 48px top and about 49px bottom padding. A Feature-heading, Body support and Chevron text action occupy the left; 380px square application media sits at right across a 64px gutter.

**Transfer:** Highlight a few key product uses without turning every chapter into a card grid.

**Text style:** `feature-heading` — Poppins 500 · 48px/1.06 · tracking -0.026em

### Catalogue chapter

**Observed:** A Heading pair introduces a capability family with Lead and Body descriptions at right. Capability cards follow in four columns with 12px gutters; longer sets continue onto a second row without changing the card grammar.

**Transfer:** Group related features into meaningful chapters instead of reproducing the original service categories.

**Text style:** `section-heading` — Poppins 500 · 56px/1.08 · tracking -0.028em

### Gallery chapter

**Observed:** A Heading pair leads into Project cards. The initial highlighted card occupies the left half alone, then a faint horizontal break and 56px spacing introduce the two-column collection. Uneven last rows stay left-aligned rather than stretching a lone card across the width.

**Transfer:** Lead with the clearest proof, then offer breadth. Keep media, outcome and attribution visibly distinct.

**Text style:** `card-heading` — Poppins 500 · 22px/1.3 · tracking -0.01em

### Plain-name relationship table

**Observed:** A Heading pair sits above a four-column table of names set in Name-table. Cells are 296px wide and about 93px tall, with 28px top spacing and faint row rules; names stay grey rather than becoming a wall of loud logos.

**Transfer:** Use when breadth of adoption matters more than one featured testimonial.

**Text style:** `name-table` — Poppins 400 · 24px/1.5 · tracking -0.012em

### Pink signature ending

**Observed:** Pink closing field takes over the full window width. Its introduction begins about 121px down, followed by a prominent email and smaller phone link. Closing directory spreads across the useful width below; generous space precedes Monumental serif word artwork. A thin closing rule, small human signoff at left and copyright at right complete the section. The fixed dark navigation does not remain visually over the final signature.

**Transfer:** Preserve contact, utility and brand-scale expression in one closing field; adapt link groups and wording to the new product rather than adding an unrelated final CTA banner.

**Text style:** `contact-display` — Poppins 500 · 32px/1.15 · tracking -0.02em

### Company narrative rows

**Only for:** company narratives

**Observed:** A large Statement introduction changes from white into grey within one continuous paragraph. Later, landscape images sit left of longer descriptive columns with Editorial-feature-heading titles. Recognition is expressed both through compact Press cards and a long sequence of Editorial proof rows.

**Transfer:** Use the two-tone introduction for a clear premise followed by elaboration; use long ruled lists only when the supporting material earns that depth.

**Text style:** `editorial-feature-heading` — Poppins 500 · 36px/1.16 · tracking -0.022em

## Page flow

**Storyline:** Promise → explanation through artifacts → capability and credibility chapters → concrete applications → relationship proof → contact and monumental signature.

### A broad marketing landing page that establishes character and breadth

1. **Promise** — Split two-line promise, small object cabinet and paired actions.
2. **Explanation** — Large editorial sentence followed by three illustrated paragraph cards.
3. **Social proof** — Dense four-column publication-card shelf.
4. **Capability chapters** — Broad ruled image/text feature rows and a landscape film.
5. **Quantified proof** — Contextual heading pair and four emblem-topped metric cards.
6. **Application proof** — Highlighted project followed by a two-column gallery.
7. **Relationship proof** — Plain grey names in a ruled table.
8. **Closing call** — Pink contact directory and monumental serif artwork.

**Transfer:** Borrow the contrast between broad narrative intervals and compact proof collections; choose the chapters that serve the new product, retaining the signature hero, original art and pink signature ending.

### A capability catalogue that makes a broad offering understandable

1. **Orientation** — Short plain display title with substantial space below the header.
2. **Capability chapters** — Heading pairs introduce related groups; tall thumbnail cards separate purpose from concrete deliverables.
3. **Closing call** — Shared pink contact field, directory and oversized serif signature.

**Transfer:** Replace service families with product capabilities and use cases; retain the two-level card explanation.

### A company narrative that turns an approach into trust

1. **Identity** — Plain title and large white-to-grey descriptive statement.
2. **Belief** — Postage-style portrait beside a large editorial paragraph.
3. **Capability chapters** — Landscape-media rows with detailed text and contextual links.
4. **Social proof** — A compact recognition shelf followed by a long ruled publication list.
5. **Closing call** — Shared pink contact field and serif signature.

**Transfer:** Use the larger prose and personal artifact only for a genuine company story; keep ordinary landing pages on the shorter default opening.

### A focused work index that puts artifacts before explanation

1. **Orientation** — Short display title and one grey support sentence.
2. **Featured proof** — A single left-column highlight with open space beside it.
3. **Application gallery** — Two columns of landscape project cards with outcome titles and attribution.
4. **Closing call** — Shared pink contact directory and monumental signature.

**Transfer:** Use for customer outcomes, templates or product applications; preserve the media-first hierarchy and honest attribution.

## Writing

Considered, cultured and warm without theatrical sales pressure. Confidence comes from concrete disciplines, careful distinctions and visible work rather than superlatives.

**Do not copy:** Do not reuse Presentable's name, wordmark, contact details, client names, project artwork, founding date, publication relationships, impact numbers or claims of recognition. Replace them with authorized assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The company speaks as we, or describes itself plainly by name. Reader address is light; actions invite exploration or conversation rather than issuing demands.
- **Rhythm:** Short declarative chapter names alternate with flowing, carefully qualified paragraphs. Lists use commas and em dashes to connect related ideas; actions are usually two to four words. Exclamation marks and urgent countdown language are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A changeable category word followed by a short fixed outcome phrase. | Three to five words across two lines | “Celebrations made presentable.” |
| Supporting line | Name the work, then describe its felt qualities with a controlled three-part rhythm. | One sentence, around 10–16 words | “Design and Communication that feels personal, sensorial, and unmistakably crafted.” |
| Section heading | Plain conversational naming, sometimes first-person plural. | One to five words | “We do two things”<br>“Featured in” |
| Project title | Active gerund plus a concrete change or intended outcome. | Six to fourteen words | “Bringing modernist order to everyday wellness” |
| Proof qualification | Clearly attribute prior work and distinguish the present company from earlier contributions. | One concise sentence | “Recognition earned through the founder’s previous practice and individual professional achievements.” |
| Action | Low-pressure verb-led invitation with a clear destination. | Two to four words | “See the work”<br>“Start a conversation”<br>“View all features” |

**Words and phrasing to use:** considered; crafted; coherent; clarity; meaning; intention; everyday experience; systems; personal; sensorial

**Avoid:** game-changing; unlock limitless potential; crush it; hurry; revolutionary; best-in-class; !!!

**Rules:**

- Describe the tangible work before abstract values.
- Use sensory language sparingly and attach it to materials, interactions or outcomes.
- Qualify ownership and attribution of proof precisely.
- Use short human action labels; do not make every action a sales pitch.
- Let longer catalogue copy distinguish purpose, audience and deliverables.

## Do's and Don'ts

### Do

- Use 84px medium display type with -0.03em tracking for the opening promise.
- Keep the primary hero pill 50px tall and the header pill 38px tall.
- Hold card corners at 24px and the principal grid gutter at 12px.
- Separate major chapters with 168px of top space rather than adding another background color.
- Use 56px chapter headings beside 20px grey lead paragraphs.
- Keep proof numbers at 44px and place their explanation 14px below.
- Frame vivid product art inside bounded windows while the surrounding canvas stays near black.
- Finish with a full-width pink field and a container-wide serif signature.

### Don't

- Do not turn all text white; #9b9ba3 is the sustained reading color for paragraphs and explanations.
- Do not introduce heavy 700-weight headlines; the medium 500 cut supplies the display voice.
- Do not add raised shadows to the flat #111116 gallery cards.
- Do not make active navigation a filled pink tab; it is pink text.
- Do not spread serif type into body copy or ordinary chapter titles.
- Do not stretch an incomplete project row into oversized cards; preserve the 586px desktop column width.
- Do not apply a universal desaturation filter to the art; the varied internal palettes are the main body color.
- Do not convert every caption into tracked uppercase; the measured 14px caption uses sentence case and only 0.005em tracking.

## Motion and responsive

### Motion

**Observed:**

- Navigation and many links declare color 0.2s cubic-bezier(0.2, 0.7, 0.1, 1).
- The changing hero word declares a 0.7s cubic-bezier(0.2, 0.7, 0.1, 1) entrance animation.
- Some elements declare opacity .8s and transform 1.2s with cubic-bezier(.16,1,.3,1), and some transform 1.6s with the same curve.
- The full opening navigation becomes a compact floating capsule during scroll; image and film content can change within stable rounded frames.

**Transfer:**

- Keep the hero's fixed conclusion stable while category words change above it.
- Keep film animation inside bounded media windows; preserve a composed poster and readable text while media moves.
- Use the declared color transition for grey-to-pink navigation feedback.

**Unknown:**

- Exact rotating-word sequence, interval, exit choreography and scroll thresholds.
- Focus-visible treatment and most button hover/active appearances.

### Responsive

**Observed:**

- CSS width breakpoints cluster around 360px, 810px and 1200px; only the desktop composition is established here.

**Transfer:**

- On narrow screens, place the object cabinet after the promise and actions, preserving its paired staggered arrangement rather than shrinking four windows to illegibility.
- Reduce four-column shelves to fewer columns while keeping the 12px gutter and shared 24px card silhouette.
- Stack heading pairs and image/text rows in reading order; fit the closing word artwork to the available width without clipping its defining serif forms.

**Unknown:**

- Exact mobile type sizes, page padding, header menu behavior and breakpoint-specific layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
