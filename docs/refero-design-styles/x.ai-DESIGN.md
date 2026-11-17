# x.ai — laboratory meets image studio

## Overview

A light, matter-of-fact technology style with the restraint of a technical document and the visual confidence of an image studio. Black grotesk typography, warm off-white panels and cool hairlines surround large photographic outputs and compact working interfaces. It suits developer tools and ambitious product launches: sparse at the page level, specific and information-rich inside demonstrations.

### Essentials

- The opening names the tool, then gives its promise a second voice: 60px/1, weight 450, -0.01em headline followed by a gray 36px/40px, weight 500 line; a 420×525px portrait image stack balances the left-hand text.
- Actions are small solid lozenges rather than oversized conversion banners: black and warm-gray pills, 44px high with 12px 20px padding and 14px/20px medium text; paired actions sit 12px apart.
- The page is a white demonstration gallery, not a colored campaign canvas: 1280px outer container, 24px inner side padding, 96px section padding and 1px cool-gray rules. Color belongs inside media and one contained plum-pink demonstration stage, not navigation or body text.
- Capabilities unfold beside a persistent visual: a 508px text rail and approximately 660px media rail separated by 64px; each text chapter occupies at least 450px at the desktop size, while inactive chapters recede.
- Every product landing page carries a tangible output stage and a working proof object. Use 16px rounded photographic cards and a 12px rounded interface window; when photography is not relevant, stage a credible artifact or actual result with the same dominant media-to-copy balance.
- Proof feels like instrumentation rather than dashboard decoration: warm off-white tables, 28px rank squares, 6×24px tally bars, 53px rows and a small centered citation. Keep a compact quantitative proof device even when the appropriate measure is not a ranking.
- The ending returns to utility rather than spectacle: ruled white sections and a compact directory footer with 13px links, five narrow columns, 56px column gaps, a small identity block and subdued bottom controls.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orchid light | `#e0a0d8` | `--color-pink` | accent | Lower pink bloom in the proof-object backdrop. |
| Pink light | `#f0c8e8` | `--color-pink-light` | accent | Soft luminous center within the plum demonstration backing. |
| Plum foundation | `#5a4868` | `--color-plum` | background | Contained luminous backing for the working proof window. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#0a0a0a` | `--color-ink` | text, action | Primary letters, active controls and primary button fills. |
| Secondary ink | `#6c6c6c` | `--color-muted` | text | Visible near-black 60% text on white; labels, dates, attribution and supporting metadata. |
| Cool secondary gray | `#7d8187` | `--color-secondary` | text | Large secondary hero promise and inactive language choices. |
| Cool hairline | `#d5d9e2` | `--color-rule` | border | Section divisions and accordion lines; table interior rules use this color at 50% opacity. |
| Neutral edge | `#e7e7e7` | `--color-soft-edge` | border | Visible result of near black at 10% over white; install fields and chronology separators. |
| Faint edge | `#f0f0f0` | `--color-subtle-edge` | border | Visible near-black 6% edge around media cards. |
| Warm gray action | `#f2f1ef` | `--color-secondary-action` | action, surface | Secondary pill buttons and selected neutral tabs. |
| Warm porcelain | `#f9f8f6` | `--color-panel` | surface | Comparison panels, utility callouts and grouped editorial cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas and light interface windows; reversed text on black actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| developer release announcements | Release orange | `#ff6308` | `--color-orange` | text, accent | Tiny New label, never a primary action or full-width band. |
| developer release announcements | Release wash | `#ffefe6` | `--color-orange-wash` | surface | Visible orange at 10% over white, confined to the small release badge. |
| chronology and footer utilities | Receding ink | `#c2c2c2` | `--color-faint` | text | Visible near-black 25% on white for large chronology years and very low-emphasis utility marks. |
| editorial principle groups | Pale numbering | `#cecece` | `--color-number` | text | Near-black 20% over white, slightly warmer over porcelain; oversized card indices. |
| terminal product demonstrations | Terminal charcoal | `#151515` | `--color-terminal` | surface | Dark terminal demonstration window, not a dark marketing-page theme. |

## Typography

- **xVf** — All marketing text, headings, actions and metadata. Compact contemporary grotesk with open counters, lightly rounded geometry and restrained medium-weight headings. If unavailable, use **Inter**. Use weights 400–500, including variable 450; preserve tight heading tracking. Font stack: "xVf", "Inter", Arial, sans-serif.
- **GeistMono** (only for code and installation controls) — Command lines and technical demonstrations. Even-width technical type contrasting with the proportional marketing text. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | xVf | 450 | 60px | 1 | -0.01em | Default left-aligned product and mission headline. |
| heading | xVf | 500 | 36px | 40px | -0.01em | Section leads and capability titles; also the secondary hero promise in cool gray. |
| quotation | xVf | 400 | 20px | 1.4 | normal | Centered testimonial text, never a large display quote. |
| lead | xVf | 400 | 18px | 1.625 | normal | Opening support paragraph and centered editorial introductions. |
| body | xVf | 400 | 16px | 1.625 | normal | Explanatory copy, usually constrained to 448px. |
| item-title | xVf | 500 | 16px | 24px | normal | Accordion question labels and compact product links. |
| small | xVf | 400 | 14px | 1.625 | normal | Feature checklist and brief section support. |
| control | xVf | 500 | 14px | 20px | normal | Pill actions, eyebrows, tabs and rank numerals. Sentence case, not spaced capitals. |
| navigation | xVf | 500 | 13px | 1.5 | normal | Header links and directory group headings. |
| footer-link | xVf | 400 | 13px | 1.625 | normal | Directory links. |
| caption | xVf | 400 | 12px | 16px | normal | Specification strip, dates and compact citations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| developer openings and chronology | display-medium | xVf | 500 | 60px | 1 | -0.01em | Centered developer headline or oversized pale year. |
| editorial introductions and developer closing calls | heading-lg | xVf | 500 | 48px | 1 | -0.01em | Centered editorial headings, closing conversion line and pale numbered-card indices. |
| developer tools and editorial utility sections | heading-sm | xVf | 500 | 30px | 1.2 | -0.01em | Developer capability chapters, utility callouts and news section heads. |
| editorial principle groups | principle-title | xVf | 500 | 20px | 1.4 | -0.01em | Short titles below numbered indices. |
| chronology and update lists | timeline-title | xVf | 400 | 16px | 22px | -0.01em | Compact title opposite a date. |
| editorial principle groups | principle-body | xVf | 400 | 14px | 2 | normal | Spacious paragraph within the joined card group. |
| developer installation controls | command | GeistMono | 400 | 14px | 20px | normal | Single-line command with copy affordance. |

**Notes:**

- The headline is lighter than the section headings: 450 versus 500. Large type stays close to one line-height and uses -0.01em tracking, rather than extra-bold weights.
- Body text opens to 1.625 line-height; controls return to 20px. Keep metadata proportionally small instead of scaling every element with the headline.
- Use the 36px heading as a gray second statement beneath the product name. Keep that statement distinct from the 18px explanatory paragraph.
- No viewport-relative type formula is needed; use breakpoint steps rather than continuous enlargement.

## Layout

**Density:** Airy between chapters, compact within working objects and directory lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Checklist item separation and wrapped metadata rows. |
| 12px | Paired buttons, icon-title gaps and hero headline-to-secondary-statement gap. |
| 16px | Eyebrow-to-heading and capability-heading-to-body spacing. |
| 20px | Checklist lead-in and accordion vertical padding. |
| 24px | Container inner side padding; hero paragraph lead-in. |
| 32px | Paragraph-to-action spacing and opening specification strip lead-in. |
| 40px | Proof-table lead-in, editorial card padding and footer group separation. |
| 48px | Inner breathing room around the proof window. |
| 64px | Split-section column gap, chronology block padding and footer bottom padding. |
| 80px | Default two-column opening gap. |
| 96px | Major section top and bottom padding. |
| 112px | Testimonial section padding. |
| 192px | Default product opening top padding including the header zone. |

### Containers and grids

- **site container**: max width 1280px · side padding 24px. Centered outer box; 1232px usable width at 1440px. Rules span the outer container while content sits inside its padding.
- **opening split**: 2 columns · gap 80px. Equal 576px columns; left text and right centered portrait stack.
- **capability split**: 2 columns · gap 64px. Use 1fr 1.3fr proportions, giving 508px copy and 660px media. A sticky media rail tracks successive text chapters.
- **reading column**: max width 448px. Capability paragraph width within the text rail.
- **centered copy**: max width 672px. Testimonial, editorial lead and closing call.
- **proof panel**: max width 896px. Centered comparison table under a centered heading.
- **question split**: 2 columns · gap 64px. 0.4fr introduction beside a 1fr question list; approximately 334px and 834px.
- **directory**: 5 columns · gap 56px. Five 112px link columns to the right of a wider identity column.
- **news grid** (only for editorial news endings): 4 columns · gap 20px. Equal-width thumbnail stories without a surrounding card shell.
- **feature index** (only for developer capability summaries): 3 columns · gap 48px. Compact icon, title and description entries in three columns, with 40px vertical gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | media and porcelain panels | 16px |
|  | working windows | 12px |
|  | rank chips | 6px |
| editorial principle groups | joined editorial group | 24px |
| editorial news endings | news thumbnails | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| image edge | `0px 0px 0px 1px rgba(0,0,0,0.06)` | A barely visible ring around overlapping output cards. |
| working proof window | `0px 0px 0px 1px rgba(0,0,0,0.06), 0px 18px 40px -24px rgba(15,23,42,0.18)` | The white demonstration window above its luminous backing. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #0a0a0a`

**Transfer:** Keep the page light even when the product demonstration itself is dark.

#### Ruled chapter

**Use:** Separate major narrative sections.

**CSS:** `border-top: 1px solid #d5d9e2; padding-top: 96px; padding-bottom: 96px`

**Observed:** The line spans the shared outer container, not the full browser width.

**Transfer:** Use whitespace and one line instead of alternating colored section bands.

#### Porcelain panel · level 1

**Use:** Data comparison and utility callout grouping.

**CSS:** `background: #f9f8f6; border-radius: 16px`

**Observed:** No conventional drop shadow. Utility callouts use 56px 48px padding.

**Transfer:** Use as a single calm grouping surface, not a repetitive bento system.

#### Header veil · level 2

**Use:** Fixed header backing.

**CSS:** `background: rgba(255,255,255,0.85); backdrop-filter: blur(12px); height: 64px`

**Observed:** Visually near-white at rest; underlying content softens as it scrolls past.

**Transfer:** Preserve transparency without making the header a detached floating capsule.

#### Luminous proof backing · level 1

**Use:** Contained color moment behind a working proof object.

**CSS:** `background-color: #5a4868; background-image: radial-gradient(circle at 58% 42%, #f0c8e8 0%, rgba(0,0,0,0) 36%), radial-gradient(circle at 58% 71%, #e0a0d8 0%, rgba(0,0,0,0) 34%); padding: 48px; overflow: hidden`

**Observed:** A rectangular plum, pink and violet light field with fine grain and small square-cut corner details, framing a white code window.

**Transfer:** Keep luminous color behind useful content, bounded to roughly half a content row.

#### Dark terminal · level 1

**Only for:** terminal product demonstrations

**Use:** Working terminal scene within an otherwise white page.

**CSS:** `background: #151515; border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; overflow: hidden`

**Observed:** 660×440px demonstration with subdued warm text, tiny colored prompts and window controls.

**Transfer:** Use a real compact product interaction, not decorative streams of code.

## Components

### Navigation link

**Use:** Compact horizontal header navigation.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 6px 12px; color: #0a0a0a`

**Text style:** `navigation` — xVf 500 · 13px/1.5

**Observed:** Small brand mark at left, links through the middle, sales and trial actions at right; dropdown links end in a 12px chevron. The header is fixed and 64px high.

**States:** Declared: hover color hsl(0 0% 4% / 1).

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #0a0a0a; color: #ffffff; border: 0px; border-radius: 9999px; padding: 12px 20px; height: 44px`

**Text style:** `control` — xVf 500 · 14px/20px

**Observed:** Sits beside a neutral secondary action. Interior sections use a compact 40px-high variant with 10px 18px padding.

**Transfer:** Use a direct verb and destination; retain short labels.

### Secondary button

**Use:** Documentation or lower-commitment action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f2f1ef; color: #0a0a0a; border: 0px; border-radius: 9999px; padding: 12px 20px; height: 44px`

**Text style:** `control` — xVf 500 · 14px/20px

**Observed:** May end in a small northeast arrow. Interior variants are 40px high; developer resource links use 32px height and 6px 14px padding.

**States:** Declared: hover background-color color-mix(in srgb,hsl(0 0% 4%) 7%,hsl(40 18% 97%)); focus-visible box-shadow 0 0 #0000, 0 0 #0000, 0 0 #0000.

### Output card

**Use:** Portrait artifact stack in the opening.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.06); max-width: 420px; aspect-ratio: 4 / 5`

**Observed:** One legible front image dominates; other cards peek behind it with small offsets, scale changes and gentle rotation. One backing card uses -3deg rotation.

**Transfer:** Keep the image edge-to-edge. Use an actual output or a deliberately art-directed product artifact.

### Proof window

**Use:** Working example displayed on the luminous stage.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 18px 40px -24px rgba(15,23,42,0.18)`

**Observed:** White window with a slim top bar, three small traffic-light controls at left and Copy at right. Technical content fills the body; language tabs sit outside the stage below it.

**Transfer:** Use a concise useful example or a result inspector; preserve the window hierarchy without copying code.

### Instrument table

**Use:** Compact comparative or quantified proof.

**CSS:** `background: #f9f8f6; border-radius: 16px; overflow: hidden; width: 896px; max-width: 100%; text-align: left`

**Text style:** `control` — xVf 500 · 14px/20px

**Observed:** Four equal columns, a 41px header and 53px body rows. Rank chips are 28px squares with 6px corners; the highlighted rank reverses white on black. Price and latency become short groups of 6×24px vertical tally bars; subdued rows use translucent black. A 12px citation sits below.

**Transfer:** Keep the tactile tally-bar idiom for count-like measures. Replace comparisons with honest product-specific metrics when rankings are inappropriate.

### Question row

**Use:** Objection handling and technical questions.

**CSS:** `display: flex; align-items: flex-start; justify-content: space-between; gap: 24px; padding: 20px 0px; border-bottom: 1px solid #d5d9e2; text-align: left; width: 100%`

**Text style:** `item-title` — xVf 500 · 16px/24px

**Observed:** Question at left, a restrained 20px plus icon at right. Closed rows are 64px plus their separator; there is no card fill.

**Transfer:** Group short genuine questions beside a narrower explanatory heading rail.

### Directory footer

**Use:** Shared utility ending.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); column-gap: 56px; row-gap: 40px`

**Text style:** `footer-link` — xVf 400 · 13px/1.625

**Observed:** Five link columns sit to the right of a broad identity block. Group headings use Navigation link typography without its padding. Links have 4px vertical gaps, groups 40px gaps. The containing footer has a top rule, 40px top padding and 64px bottom padding; small theme and attribution controls sit low at left.

**Transfer:** Resize the taxonomy to the new product while retaining a compact directory and low identity block.

### Numbered editorial card

**Only for:** editorial principle groups

**Use:** A few foundational ideas presented as one joined block.

**CSS:** `background: #f9f8f6; padding: 40px`

**Text style:** `principle-title` — xVf 500 · 20px/1.4 · tracking -0.01em

**Observed:** Three columns share a 24px rounded outer shell with 1px white gutters. Each begins with a pale 48px index, followed by a title after 24px and a 14px/28px paragraph after 16px.

**Transfer:** Use for three substantial principles or criteria, not a generic icon-benefit grid.

### Chronology row

**Only for:** chronology and update lists

**Use:** Dense progress or release history.

**CSS:** `display: flex; align-items: baseline; justify-content: space-between; gap: 32px; padding: 14px 0px; border-top: 1px solid rgba(10,10,10,0.1)`

**Text style:** `timeline-title` — xVf 400 · 16px/22px · tracking -0.01em

**Observed:** Title left and a 12px muted date at right. A 160px year rail sits beside the 1008px list with 64px gap. The pale 60px year sticks below the header as long lists scroll.

**Transfer:** Use large low-contrast grouping labels and thin rows when history is useful; do not turn every entry into a card.

### Install command

**Only for:** developer installation controls

**Use:** A single copyable install action in openings, utility bands and closing calls.

**CSS:** `display: flex; align-items: center; padding: 12px 16px; border: 1px solid rgba(10,10,10,0.1); border-radius: 12px; color: #0a0a0a; max-width: 100%`

**Text style:** `command` — GeistMono 400 · 14px/20px

**Observed:** Approximately 429×46px including border. A muted dollar prefix and single-line command lead to a copy icon at right; overflow fades beneath the icon rather than wrapping.

**Transfer:** Keep the entire operation actionable and repeat the same compact control at later conversion points.

### News thumbnail

**Only for:** editorial news endings

**Use:** Linked story artwork above metadata and headline.

**CSS:** `background: #f9f8f6; border: 1px solid rgba(10,10,10,0.06); border-radius: 8px; overflow: hidden; aspect-ratio: 291 / 153`

**Observed:** Four landscape thumbnails across the container. The artwork can be dark, neon or photographic; dates and category labels follow after 16px, then a compact headline after 8px. Text remains outside the thumbnail without a filled card shell.

**Transfer:** Create coherent editorial cover graphics with short topic text and one strong motif.

## Imagery and graphics

### Artifact stack

**Use:** Main opening visual and the page's first tangible demonstration.

**Observed:** A tall studio-lit photograph of black apparel and accessories arranged on a pale gray-green tabletop. Soft shadows and restrained saturation make the image almost monochrome. The front card occupies about a third of the usable row, with narrow skewed cards visible behind it.

**Transfer:** Photograph the new product's outputs or representative artifacts against a subdued neutral ground. For intangible products, render a credible finished document, design or result instead of generic stock people.

**Build:** Place up to four 4:5 image cards in one relative stack, max-width 420px. Make the front face upright; offset a backing face -8px horizontally and 4px vertically, scale it to 0.96 and rotate -3deg. Clip each to 16px corners with a 1px 6% black ring. Keep the front output clear.

### Capability media rail

**Use:** Wide visual explanation beside scrolling capability copy.

**Observed:** Approximately 660×371px landscape scenes: a sunlit neutral living room, a fashion portrait on saturated blue, and a monochrome architectural pencil rendering. Rounded media is edge-to-edge and unframed except for its corner treatment. A compact pill selector sits immediately below, black for the selected choice and gray text for the rest.

**Transfer:** Show distinct real outcomes from the same tool. Use rich color inside the image, not as a matching section background; retain similar framing when variants change.

### Grainy luminous stage

**Use:** A signature colored frame around the working proof object.

**Observed:** Soft plum and orchid light blooms are interrupted by white square cutouts at stepped corners. Fine grain makes the light feel printed or rasterized rather than like smooth corporate gradient wallpaper. The white interface is inset 48px and remains sharply legible.

**Transfer:** Retain a contained luminous proof stage for a different product, framing a real result or a compact interface. Match the soft glow; exact light positions are not essential.

**Build:** Use a roughly 584×417px stage. Layer two radial blooms at 58% 42% and 58% 71%, fading pink-light and orchid to transparent by 36% and 34%, on a plum base. Add a fine SVG turbulence layer at low opacity for grain. Add 14px white corner squares slightly inset from stepped outer edges. Place the white Proof window above all texture, with 48px surrounding space.

### Terminal demonstration

**Only for:** developer tools

**Use:** Persistent working media in capability chapters.

**Observed:** A dark 660×440px terminal window with tiny warm monospace text, sparse command highlights and subdued inset input bands. Small colored controls and a path line establish working software rather than a glossy device mockup.

**Transfer:** Use a plausible interaction with concise output; preserve the charcoal window as a localized contrast, not a reason to darken the entire page.

### Editorial covers

**Only for:** editorial news endings

**Use:** Thumbnail artwork for recent updates.

**Observed:** Landscape covers alternate black identity compositions, blurry violet-magenta light, a bold green split field and monochrome light beams. Strong single motifs and sparse white titles remain legible at thumbnail scale.

**Transfer:** Give each story a single graphic idea within a shared landscape frame. Keep bright cover colors out of the surrounding editorial layout.

### Icons

**Observed:** Small functional symbols, mostly 12–20px with 1.5–2px round-capped strokes. Capability headings pair a black 28px mark with text; checklists use subdued 14px checks; questions end with a muted 20px plus. Arrows are tiny and adjacent to labels.

**Transfer:** Choose simple outline icons with consistent stroke and minimal detail. Use a monochrome functional symbol, not colorful filled feature badges.

## Section recipes

How recurring sections are built.

### First screen: Artifact-led opening

**Observed:** White canvas under the 64px Header veil. The opening has 192px top and 96px bottom padding, ending near 813px. Equal-width text and visual columns sit 80px apart in the site container. Copy is vertically centered against the 420×525px Artifact stack: a small Control eyebrow, a 60px weight-450 product name, a cool-gray 36px promise on one or two lines, an 18px support paragraph, then Primary button and Secondary button 32px below. A wrapping 12px specification strip sits another 32px below the actions. The visual layers are pale studio ground, offset rounded output cards, then one upright dominant image. Within the first 900px, the header, all hero text, both actions, metadata and whole main object are visible; the next section's rule is visible but its substantive copy remains below the fold.

**Transfer:** Use a concise new product name and a separate outcome promise. If there is no native image output, make a finished artifact or a restrained product result portrait at the same scale. Developer tools can instead open centered within 768px, with a small release pill above a 60px medium headline and an Install command below; editorial pages retain the left-aligned opening but substitute a compact linked proof list for the photo.

**Avoid:** Do not replace the split composition with a full-bleed image, enormous centered slogan, floating bento grid or a hero packed with equal-sized thumbnails.

**Text style:** `display` — xVf 450 · 60px/1 · tracking -0.01em

### Persistent capability chapters

**Observed:** Ruled chapter with the Capability split. Text chapters occupy at least half the desktop viewport, each with a small heading icon, Heading title, body after 16px and a short checklist after 20px. The media rail stays in view while active copy turns black and adjacent chapters recede. The product-oriented version uses 36px titles; the developer variant uses 30px titles and a Dark terminal.

**Transfer:** Divide functionality into a few meaningful jobs, pairing each with an actual changing output rather than repeating decorative cards.

**Text style:** `heading` — xVf 500 · 36px/40px · tracking -0.01em

### Buildable proof split

**Observed:** Ruled chapter with a 36px heading, one 16px paragraph and paired compact 40px actions on the left. Luminous proof backing and Proof window occupy the right. Language controls sit 20px below the scene, not inside the code window.

**Transfer:** Turn the promise into one concrete action or implementation example. Keep the framed working object as the isolated chromatic payoff.

**Text style:** `heading` — xVf 500 · 36px/40px · tracking -0.01em

### Instrumented proof and quotation

**Observed:** Centered 36px heading followed after 40px by Instrument table inside an 896px column. A small citation follows the table. A separately ruled testimonial block uses a 672px centered column, 112px vertical padding, 20px/28px quotation, small attribution and tiny pagination dots.

**Transfer:** Use product-specific measurements and a concise independent endorsement. Keep proof typography smaller than marketing headings and let the table carry detail.

**Text style:** `quotation` — xVf 400 · 20px/1.4

### Question rail

**Observed:** Ruled chapter with Question split: heading and short 14px support on the narrow left rail, Question rows on the wide right rail. The introduction stays aligned near the top as the list extends. The section leads directly into the shared footer without a decorative closing billboard.

**Transfer:** Answer adoption and operational questions in short plain language. Let the question list close a technical product page.

**Text style:** `heading` — xVf 500 · 36px/40px · tracking -0.01em

### Directory ending

**Observed:** All page types finish on white with the same top rule and Directory footer. A small identity and copyright sit at left; grouped resource links form five slim columns on the right. Theme and attribution controls are low emphasis at bottom left. The whole footer occupies about 490px.

**Transfer:** Use an appropriately sized resource taxonomy while retaining the wide identity-to-directory contrast.

**Text style:** `footer-link` — xVf 400 · 13px/1.625

### Editorial grouped principles

**Only for:** editorial and organization pages

**Observed:** Centered 48px heading and 18px support within 672px introduce a joined row of Numbered editorial cards. Below it, a left-aligned 30px utility heading can pair with actions and a four-column row of simple porcelain location or category tiles.

**Transfer:** Use this calmer text-led treatment for principles, operating criteria or organizational information rather than forcing product imagery.

**Text style:** `heading-lg` — xVf 500 · 48px/1 · tracking -0.01em

### Progress ledger and recent stories

**Only for:** editorial and organization pages

**Observed:** Centered 48px chapter introduction leads to long Chronology row groups. Years sit on a pale sticky rail. Each year group has 64px vertical padding and thin neutral rules. A final four-column News thumbnail grid, introduced by a left-aligned 30px heading and All posts link, precedes the Directory footer.

**Transfer:** Organize progress by a meaningful time or release group. End editorial history with a handful of current stories rather than a conversion banner.

**Text style:** `timeline-title` — xVf 400 · 16px/22px · tracking -0.01em

### Developer utility and closing call

**Only for:** developer tools

**Observed:** A Porcelain panel utility band uses 56px 48px padding, a 30px heading and 14px support at left, Install command at right. A later three-column feature index provides compact icon-title-description entries without cards. The closing call is centered in 672px with a 48px heading, 16px support, Install command after 32px, and paired 40px secondary and primary actions beneath.

**Transfer:** Repeat the same low-friction operation at useful conversion points. Close on the action itself rather than inventing a different grand visual.

**Text style:** `heading-lg` — xVf 500 · 48px/1 · tracking -0.01em

## Page flow

**Storyline:** Clear promise → tangible capability demonstration → practical route to use → compact proof or breadth → adoption support → utility directory; editorial pages trade conversion proof for a progress ledger.

### A visual or API product landing page

1. **Promise** — Split opening with a product name, gray outcome statement, action pair, compact specifications and portrait output stack.
2. **Capability demonstration** — Long copy chapters beside persistent changing landscape media.
3. **Practical activation** — Action pair beside a working example on a luminous backing.
4. **Quantified and social proof** — Instrument-style comparison followed by a small centered quotation.
5. **Objection handling** — Narrow introduction rail beside a long plain question list.
6. **Utility ending** — Ruled directory footer.

**Transfer:** Use outcomes, implementation and adoption details appropriate to the new product; preserve the demonstration-led pacing without requiring the same chapter count.

### An organization, mission or editorial overview

1. **Purpose** — Left-aligned mission statement opposite a concise linked capability list.
2. **Operating principles** — Centered heading and joined numbered porcelain cards.
3. **Practical participation** — Utility heading, recruitment actions and small location tiles.
4. **Progress proof** — Long chronology with pale sticky years and dense dated rows.
5. **Current activity** — Four recent-story thumbnails and an index link.
6. **Utility ending** — Shared directory footer, with no additional closing conversion scene.

**Transfer:** Substitute the organization's own principles and progress; keep the ledger and numbered grouping scoped to editorial storytelling.

### A developer-tool acquisition page

1. **Immediate activation** — Centered promise, small release announcement and copyable install command.
2. **Workflow demonstration** — Capability chapters track a dark persistent terminal.
3. **Low-friction reminder** — Porcelain utility band repeats the install command.
4. **Breadth** — Three-column unboxed feature index.
5. **Closing call** — Centered restatement, install command and short action pair.
6. **Utility ending** — Shared directory footer.

**Transfer:** Place the quickest credible adoption operation where this page uses a command; retain a compact functional ending.

## Writing

Direct technical confidence with occasional ambitious purpose statements. Benefits are made concrete through operations, supported formats, implementation details and bounded claims rather than emotional sales language.

**Do not copy:** Do not reuse brand marks, product names, proprietary artwork, code endpoints, model names, quotations, pricing, rankings, company history or performance claims. Source examples illustrate voice only; replace every factual claim with substantiated information for the new product.

- **Addressing the reader:** Use you and your for the reader's work, we for organizational purpose, and the product name as the subject when explaining behavior.
- **Rhythm:** Short sentence-case headlines, usually two to seven words. One or two direct support sentences, then concise parallel checklist fragments. Em dashes connect a benefit to a useful qualification; exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product plainly or state the immediate job it enables. | 3–7 words | “Grok Imagine API”<br>“Bring Grok to your computer.” |
| Secondary promise | A short outcome sentence that moves from input to result. | 5–9 words | “From prompt to pixel-perfect reality.” |
| Support | Name capabilities, then explain the unifying practical benefit. | 15–28 words | “State-of-the-art image and video generation, editing, and restyling — one API for every visual modality.” |
| Capability heading | Use a literal task or familiar technical noun. | 1–5 words | “Precision edits”<br>“Plan” |
| Checklist | Lead with a supported operation or a concrete limit. | 6–14 words | “Up to 15-second clips with motion control”<br>“Every approved change shows up as a clean diff” |
| Action | Verb plus a clear destination or immediate operation. | 1–4 words | “Create API Key”<br>“Read docs” |
| Objection handling | Ask the user's exact operational question. | 6–12 words | “Can I edit existing images and videos with text prompts?” |

**Words and phrasing to use:** build; generate; edit; control; start; works with; one command; from … to …; up to; right now

**Avoid:** magical; game-changing; supercharge; revolutionize your journey; unlimited possibilities; effortless excellence

**Rules:**

- Let a plain task noun carry a capability heading; do not prepend a slogan to every section.
- Distinguish what the product does from how the reader uses it.
- Put specifications and constraints in compact metadata or checklist lines, not in the headline.
- Use exact supported facts for claims of speed, cost, compatibility or quality.
- Keep technical names and syntax intact where needed, but keep surrounding explanations conversational.

## Do's and Don'ts

### Do

- Set the default product headline to 60px, weight 450 and -0.01em tracking.
- Keep the gray 36px promise separate from the 18px support paragraph.
- Use 44px action pills in the opening and 40px compact actions inside sections.
- Keep section divisions at 1px and normal chapter padding at 96px.
- Let capability media be wider than the copy rail: 1.3fr to 1fr with a 64px gap.
- Concentrate pink-plum light inside the proof-object frame, leaving the surrounding page white.
- Retain 12px metadata and 13px directory links rather than inflating every text role.
- Use a tangible output and instrument-like proof device even for products without native photography.

### Don't

- Do not turn the warm-gray secondary pill into a black-outlined button; its hierarchy comes from a filled neutral surface.
- Do not use 700-weight grotesk headings or widely tracked all-capital eyebrows.
- Do not spread the orange release accent across primary actions, headings or section backgrounds.
- Do not apply a dark terminal theme to the marketing canvas.
- Do not add thick borders or elevated shadows to porcelain utility panels.
- Do not turn the comparison tallies into colorful progress bars or a dashboard chart.
- Do not enclose every feature-index entry or footer group in rounded cards.
- Do not enlarge the quotation to compete with the 60px opening headline.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use color, background-color, border-color and filter over 0.15s with cubic-bezier(0.4, 0, 0.2, 1).
- Capability copy declares opacity transitions over 0.5s using cubic-bezier(0.4, 0, 0.2, 1); the active chapter is dark while adjacent chapters recede.
- The chronology year and developer demonstration rail use sticky positioning.

**Transfer:**

- Keep media persistent while a single capability chapter becomes prominent. Use the declared opacity transition rather than sliding each text block through the scene.
- Restrict interaction motion to compact controls and the changing demonstration; keep ruled page geometry stable.

**Unknown:**

- Exact playback, automatic media-change timing and image-stack animation choreography are not established.

### Responsive

**Observed:**

- The product hero declares a single-column grid before its large-screen two-column layout; the portrait stack is hidden below the large-screen layout.
- Container classes specify 16px side padding before 24px at the large-screen layout.
- Footer grid classes specify two, then three, then five columns. Chronology rows stack before becoming horizontal with baseline alignment.
- Headline classes step through smaller display sizes before reaching the 60px desktop role; no fluid formula is supplied.

**Transfer:**

- At narrow widths, preserve the product-name / gray-promise / support / action hierarchy even when the hero image stack is hidden.
- Stack capability copy and media when the persistent rail no longer fits; keep each demonstration immediately associated with its chapter.
- Allow the install command to scroll horizontally beneath its copy affordance rather than wrap syntax.

**Unknown:**

- Exact mobile compositions, live breakpoint behavior and sticky-media fallbacks remain unverified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
