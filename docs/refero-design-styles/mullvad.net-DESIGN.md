# Mullvad — civic conviction, utilitarian warmth

## Overview

A forthright, people-first style that pairs public-interest editorial writing with practical product explanation. Steel blue and deep navy alternate with pale gray chapters, while acid yellow punctuates actions and a rallying statement. Humanist sans-serif headings and readable paragraphs meet chunky monospace buttons, tilted interface imagery, small illustrated emblems and occasional cinematic footage. It suits tools that need to explain their purpose and earn trust, with spacious chapters rather than dense sales dashboards.

### Essentials

- Headlines sound like public declarations, not luxury advertising: Source Sans Pro 600 at 80px/1 for the opening and rallying statement, 56px/1 for chapter headings, with normal tracking.
- The opening is a blue editorial stage with a tangible product alongside it: a 960px text-stage container, approximately 485px copy column, 80px column gap and a 455px-wide tilted interface extending beyond the section boundary.
- Actions look like stamped commands: Martian Mono Variable 700, 18px/1.4, uppercase, 16px 32px padding, 2px matching borders and square corners; yellow is primary, white is the companion and navy serves reading actions.
- Color is organized into whole chapters, not sprinkled across cards: steel-blue opening, navy product chapters and footer, pale-gray explanatory chapters; acid yellow is concentrated in buttons and one emphatic full-width statement band rather than dominating the page.
- Product evidence has physical presence without a decorative scene: a tilted, softly shadowed interface floats on blue, and upright browser windows sit on pale gray. Include this tangible product staging; when no interface exists, use a crisp working artifact or tool specimen in the same framing.
- A humane emblem interrupts the utilitarian system: a compact circular illustrated mark repeats above offer and reading-card titles, at 60px in reading cards and 80px in the offer. Use an original emblem or simple two-color pictogram, keeping it secondary to text.
- The page has a rallying color device: a yellow statement surface with centered navy 80px/1 type, a navy action and 120px vertical breathing room. Dense four-column navy footer navigation provides the sober counterweight.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Selected navigation blue | `#325e8c` | `--color-nav-selected` | surface | Current navigation item and navigation hover fill. |
| Steel blue | `#294d73` | `--color-blue` | background, text, action | Opening stage and navigation; navy-button hover and pricing figures. |
| Deep civic navy | `#192e45` | `--color-navy` | background, text, border, action | Dark chapters, footer, outlined editorial panels, text on yellow and navy reading actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#ddca00` | `--color-yellow` | action, background, accent | Primary marketing actions, selection and the rallying statement band. |
| Golden focus | `#ffd524` | `--color-focus` | border, action | Keyboard focus outlines; the softer transactional action fill is confined to pricing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial charcoal | `#2f2f2f` | `--color-ink` | text | Default copy and headings on pale chapters and white cards. |
| Control charcoal | `#363636` | `--color-control-ink` | text | Native-looking language control text. |
| Footer silver | `#dbdbdb` | `--color-muted` | text, border | Footer links and icons; language-selector hairline. |
| Cool chapter gray | `#f3f3f4` | `--color-chapter` | background | Wide explanatory and reading-resource chapters. |
| Base gray | `#f5f5f5` | `--color-canvas` | background | Main canvas and compact transactional information chapters. |
| White | `#ffffff` | `--color-white` | text, surface, action | Text on blue, offer and reading cards, companion action and bright support chapters. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral status | `#ee6965` | `--color-status` | text, accent | Negative connection state in the utility strip; not a marketing accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and account-related content | Information blue | `#366699` | `--color-link` | link | Inline transactional links. |
| pricing and detailed product explanation | Support charcoal | `#4a4a4a` | `--color-secondary` | text | Support and transactional copy. |

## Typography

- **Source Sans Pro** — Headlines, card titles, category tags and footer headings. Open, humanist sans with approachable forms and compact semibold headlines. Font stack: "Source Sans Pro", "Open Sans", Arial, system-ui, sans-serif.
- **Open Sans** — Paragraphs, navigation, checklist text and footer links. Sturdy humanist sans with a large readable x-height and generous counters. Font stack: "Open Sans", Arial, system-ui, sans-serif.
- **Martian Mono Variable** — Marketing action labels. Wide, emphatic monospace; heavy uppercase labels contrast with the humanist text. Font stack: "Martian Mono Variable", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Source Sans Pro | 600 | 80px | 1 | normal | size clamp(1rem, 20vw, 5rem) | Main editorial opening headline and the monumental statement band. |
| heading | Source Sans Pro | 600 | 56px | 1 | normal | size clamp(2rem, 12vw, 3.5rem) | Major chapter headings, usually one or two lines. |
| card-heading | Source Sans Pro | 600 | 36px | 1 | normal | fixed | Offer headline and resource-card titles. |
| footer-heading | Source Sans Pro | 600 | 24px | 1.125 | -0.0156em, uppercase | fixed | Footer group headings. |
| body | Open Sans | 400 | 18px | 1.5 | normal | fixed | Marketing paragraphs and descriptive card copy. |
| action | Martian Mono Variable | 700 | 18px | 1.4 | normal, uppercase | fixed | All large marketing buttons. |
| footer-link | Open Sans | 400 | 17.6px | 1.5 | normal | fixed | Footer navigation and contact links. |
| navigation | Open Sans | 700 | 16px | 1.5 | normal | fixed | Main navigation and its compact conversion action. |
| category | Source Sans Pro | 600 | 16px | 1.5 | normal, uppercase | fixed | Small boxed reading-card categories. |
| compact-body | Open Sans | 400 | 16px | 1.5 | normal | fixed | Utility strip and compact informational paragraphs; transactional pages use it as their body default. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated product landing pages | product-display | Source Sans Pro | 600 | 75.2px | 1.125 | normal | size clamp(1rem, 10vw, 4.7rem) | Multi-line product promise beside an offer card. |
| pricing pages | pricing-display | Source Sans Pro | 600 | 64px | 1.125 | normal | size clamp(2rem, 8vw, 4rem) | Centered pricing opening title. |
| pricing pages | price | Source Sans Pro | 700 | 64px | 0.75 | normal | fixed | Large amount inside equal-status rate tiles. |
| dedicated product capability chapters | feature-heading | Source Sans Pro | 600 | 34.1px | 1.125 | normal | fixed | Unboxed capability-grid titles. |
| pricing pages | period | Source Sans Pro | 700 | 32px | 1.5 | normal | fixed | Rate-tile duration labels. |
| pricing pages | compact-heading | Source Sans Pro | 600 | 32px | 1.125 | normal | fixed | Short explanatory and FAQ group headings. |
| detailed product explanation | explanation-heading | Source Sans Pro | 600 | 28.4px | 1.125 | normal | fixed | Compact explanatory cards staged beside device imagery. |
| editorial indexes and pricing questions | editorial-title | Source Sans Pro | 600 | 24px | 1.125 | normal | fixed | Outlined editorial-card titles and compact FAQ questions. |
| product FAQ chapters | faq-question | Open Sans | 600 | 24px | 1.5 | normal | fixed | Disclosure summary labels. |
| editorial indexes | editorial-label | Source Sans Pro | 600 | 20px | 1.25 | normal | fixed | Sentence-case topic label positioned above the title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use normal tracking throughout the large type; the distinctive hierarchy comes from size, compact headline leading and family contrast, not tightly squeezed grotesk lettering.
- Headlines and body remain sentence case. Capitals belong to monospace actions, boxed categories and footer headings.
- The 36px card title is deliberately substantial and can wrap across several lines; let shorter titles leave breathing space above aligned actions.

## Layout

**Density:** Airy at chapter scale, practical at reading scale: long empty approaches around substantial text blocks contrast with packed footer links.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Primary horizontal padding and gaps; smaller local exceptions remain possible.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Compact heading-to-copy gaps and footer-heading spacing. | fixed |
| 16px | Action-pair gap, card internal grid gap and FAQ row separation. | fixed |
| 24px | Editorial-panel internal gaps and FAQ horizontal padding. | fixed |
| 32px | Paragraph separation, footer columns and split FAQ columns. | fixed |
| 40px | Headline-to-body and body-to-action spacing; default card padding and resource-grid gap. | clamp(1rem, 3vw, 2.5rem) |
| 56px | Outlined editorial-grid gaps and capability-grid columns. | fixed |
| 64px | Footer vertical padding. | fixed |
| 80px | Opening-column gap and rate-tile gap. | fixed |
| 120px | Statement-band vertical space and capability-grid row gaps. | fixed |
| 144px | Product-offer column gap and editorial-index outer spacing. | fixed |
| 192px | Film-caption chapter vertical space. | fixed |
| 240px | Default major marketing chapter top and bottom space. | fixed |

### Containers and grids

- **editorial column**: max width 960px · side padding 96px. Centered prose chapters; at 1440px the content begins 240px from either edge.
- **breakout**: max width 1248px · side padding 96px. Wide product splits, resource grids, capability grids and statement text at desktop.
- **navigation**: max width 1376px · side padding 16px. Centered 72px navigation band, with emblem and menu at left, horizontal links and account action at right.
- **resource grid**: 3 columns · gap 40px. Equal white resource cards; 300px minimum card width, auto-filling into available space.
- **product split**: 2 columns · gap 144px. Text beside the offer plate; columns fit a 400px minimum capped by available width.
- **footer**: max width 1384px · 4 columns · gap 32px · side padding 24px. Four equal columns; social links and language selector share the last column.
- **transactional reading** (only for pricing pages): max width 640px · side padding 48px. Narrow, centered text for pricing explanations and always-visible FAQs.
- **editorial index** (only for editorial indexes): max width 960px · 2 columns · gap 56px. Outlined cards in pairs, with a full-width featured card introducing a group.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing actions and outlined panels | 0px |
|  | white cards | 16px |
|  | language control | 4px |
|  | media control | 50% |
| pricing pages | rate tiles | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | rate-tile ledge | `0px 11.2px 0px -4.8px rgba(0, 0, 0, 0.2)` | A small hard shadow under each equal-status rate tile. |

### Surfaces

#### Base canvas · level 0

**Use:** Underlying light page surface.

**CSS:** `background-color: #f5f5f5`

#### Blue stage · level 0

**Use:** Opening and film-caption chapters, continuous with navigation.

**CSS:** `background-color: #294d73; color: #ffffff`

**Observed:** A flat colored field, with no ornamental lighting or texture.

**Transfer:** Use the uninterrupted field to hold a large product artifact and readable text.

#### Pale chapter · level 0

**Use:** Long explanatory and resource sections.

**CSS:** `background-color: #f3f3f4; color: #2f2f2f`

#### Navy chapter · level 0

**Use:** Product offer, capability chapters, utility strip and footer.

**CSS:** `background-color: #192e45; color: #ffffff`

#### White plate · level 1

**Use:** Offer and resource cards.

**CSS:** `background-color: #ffffff; color: #2f2f2f; border-radius: 16px; box-shadow: none`

**Observed:** White against blue or gray is sufficient separation; no visible outline is needed.

**Transfer:** Keep product offers rounded even though their internal actions are square.

#### Outlined reading panel · level 1

**Use:** Article previews and FAQ disclosures.

**CSS:** `background-color: transparent; border: 1px solid #192e45; border-radius: 0px`

**Observed:** Panels retain the section backing. Editorial previews use 40px padding; FAQ rows use 20px 24px.

**Transfer:** Reserve this lean, square treatment for reading and objection handling.

#### Rallying yellow · level 0

**Use:** The emphatic public-facing statement device.

**CSS:** `background-color: #ddca00; color: #192e45`

#### Bright support · level 0

**Use:** FAQ and transactional explanation chapters.

**CSS:** `background-color: #ffffff; color: #4a4a4a`

#### Media overlay · level 2

**Use:** Circular expand control over video.

**CSS:** `background-color: rgba(255, 255, 255, 0.25); border-radius: 50%`

**Observed:** A translucent disc sits directly over the footage, without a separate card backing.

**Transfer:** Let the footage supply most of the visual color; keep the overlay neutral.

#### Language field · level 1

**Use:** Footer language selector.

**CSS:** `background-color: #ffffff; color: #363636; border: 1px solid #dbdbdb; border-radius: 4px; padding: 8px 16px`

**Observed:** Globe and label on the left, small chevron at the right; maximum width 320px.

## Components

### Navigation link

**Use:** Primary navigation within the blue band.

**CSS:** `color: #ffffff; display: flex; align-items: center; padding: 0px 16px; height: 46px`

**Text style:** `navigation` — Open Sans 700 · 16px/1.5

**Observed:** A compact illustrated emblem and yellow circular menu mark lead the navigation. Search, login and a compact yellow conversion action sit at the far right. The current link has a selected-blue rectangular fill.

**States:** Declared: hover color #294d73, underline and background #325e8c; focus-visible outline #ffd524 solid 2px, offset 1.6px and radius 1.6px.

### Primary button

**Use:** Conversion and chapter-level exploration actions.

**CSS:** `background-color: #ddca00; color: #192e45; border: 2px solid #ddca00; border-radius: 0px; padding: 16px 32px; display: flex; align-items: center; justify-content: center; text-align: center`

**Text style:** `action` — Martian Mono Variable 700 · 18px/1.4 · uppercase

**Observed:** Typically 61px tall. Labels determine width outside cards; offer-card actions span the inner width.

**States:** Declared: hover underline, background and border #ffec0a; focus-visible outline #ffd524 solid 2px, offset 1.6px and radius 1.6px; active background and border #fff25b with scale(0.99).

### Reading button

**Use:** Article previews and actions on the yellow statement surface.

**CSS:** `background-color: #192e45; color: #ffffff; border: 2px solid #192e45; border-radius: 0px; padding: 16px 32px; display: flex; align-items: center; justify-content: center; text-align: center`

**Text style:** `action` — Martian Mono Variable 700 · 18px/1.4 · uppercase

**Observed:** Full width inside reading cards, intrinsic width inside the statement band.

**States:** Declared: hover underline with background and border #294d73; focus-visible outline #ffd524 solid 2px, offset 1.6px and radius 1.6px; active background and border #48709b with scale(0.99).

### Companion button

**Use:** Second product action beside the primary action.

**CSS:** `background-color: #ffffff; color: #192e45; border: 2px solid #ffffff; border-radius: 0px; padding: 16px 32px; display: flex; align-items: center; justify-content: center; text-align: center`

**Text style:** `action` — Martian Mono Variable 700 · 18px/1.4 · uppercase

**Observed:** A solid white companion, not a transparent ghost button; paired with the primary action using a 16px gap.

**States:** Declared: hover underline with white text, background and border #192e45; focus-visible outline #ffd524 solid 2px, offset 1.6px and radius 1.6px; active background and border #315a87 with scale(0.99).

### Offer plate

**Use:** A concentrated proposition beside product explanation.

**CSS:** `background-color: #ffffff; color: #2f2f2f; border-radius: 16px; padding: 40px`

**Text style:** `card-heading` — Source Sans Pro 600 · 36px/1

**Observed:** Original circular emblem, offer headline, four check-mark benefits and a full-width Primary button. The emblem is 80px, the heading has 40px margins, and benefit copy is Open Sans 18px/1.5 at weight 600.

**Transfer:** Replace price and benefits with the new product's most useful purchase facts; preserve the simple vertical order.

### Resource card

**Use:** A compact reading recommendation rather than a product feature.

**CSS:** `background-color: #ffffff; border-radius: 16px; padding: 40px; display: grid; row-gap: 16px; grid-template-columns: 1fr`

**Text style:** `card-heading` — Source Sans Pro 600 · 36px/1

**Observed:** A 60px circular emblem, Category tag, multi-line title and bottom-aligned Reading button. Equal-height cards form a three-column grid, approximately 389px by 495px each.

**Transfer:** Use questions or explanatory titles, not short feature names. Keep repeated actions aligned even when title lengths differ.

### Category tag

**Use:** Reading-card taxonomy.

**CSS:** `color: #192e45; border: 2px solid #192e45; padding: 4px 8px; width: fit-content`

**Text style:** `category` — Source Sans Pro 600 · 16px/1.5 · uppercase

**Observed:** The small outlined label sits below the emblem, then 16px above the title; its compact rectangle contrasts with the rounded card.

### Footer navigation

**Use:** Dense, sober closing directory on navy.

**CSS:** `background-color: #192e45; display: grid; grid-template-columns: 1fr 1fr 1fr 1fr; column-gap: 32px; row-gap: 48px; padding: 64px 24px; max-width: 1384px`

**Text style:** `footer-heading` — Source Sans Pro 600 · 24px/1.125 · tracking -0.0156em · uppercase

**Observed:** Four columns combine site links, policy links, postal/contact details, and social links with language control underneath. Headings are uppercase; silver links use Footer-link type with 3px vertical padding. All four page types end with this directory.

**Transfer:** Keep real contact information and useful navigation; do not substitute a single logo and a tiny legal row.

### Editorial preview

**Only for:** editorial indexes

**Use:** Substantial summaries organized into topical reading groups.

**CSS:** `border: 1px solid #192e45; border-radius: 0px; padding: 40px; display: grid; gap: 24px; background-color: transparent`

**Text style:** `editorial-title` — Source Sans Pro 600 · 24px/1.125

**Observed:** Sentence-case topic label appears visually above the title, followed by body copy and a full-width Reading button. Full-width featured cards precede paired equal-height cards; text-heavy cards align their buttons at the bottom.

**Transfer:** Use this for a knowledge hub or explainers, not as the ordinary rounded product-card treatment.

### FAQ disclosure

**Only for:** product FAQ chapters

**Use:** Compact objections beside a short introductory text column.

**CSS:** `border: 1px solid #192e45; border-radius: 0px; padding: 20px 24px; margin-bottom: 16px; overflow: hidden`

**Text style:** `faq-question` — Open Sans 600 · 24px/1.5

**Observed:** Native details/summary construction. A bold navy plus sits at the right; labels may wrap to two lines. Answers follow inside the same outline. A Primary button is aligned to the right below the stack.

**States:** Declared: focus-visible on the summary uses outline #ffd524 solid 2px, offset 1.6px and radius 1.6px.

### Rate tile

**Only for:** pricing pages

**Use:** Repeated, equal-status numerical comparison.

**CSS:** `background-color: #ffffff; color: #294d73; border-radius: 6px; padding: 48px 0px; box-shadow: 0px 11.2px 0px -4.8px rgba(0, 0, 0, 0.2); text-align: center`

**Text style:** `price` — Source Sans Pro 700 · 64px/0.75

**Observed:** Duration first in Period type, amount after 24px in Price type, then a small per-period qualifier. Tiles are 213px by 240px in an 800px row with 80px gaps. No highlighted recommended plan.

**Transfer:** Use a repeated number only if the offer genuinely supports that comparison; otherwise retain equal visual status with truthful figures.

## Imagery and graphics

### Tangible interface artifact

**Use:** Hero and major product demonstrations.

**Observed:** The opening uses a tall, gently clockwise-tilted desktop application window with dark blue content, crisp controls, saturated state color and soft surrounding shadow. It occupies roughly the right half of the stage and overlaps the next chapter. A later browser image is upright, about 600px wide, with visible window chrome and a soft gray shadow on pale backing.

**Transfer:** Show the new product doing real work in one carefully composed interface, not a collage of tiny screens. For a non-software product, stage a single sharply rendered tool or working document at comparable scale.

**Build:** Place a portrait artifact about 455px wide on the blue field; rotate its wrapper roughly 5deg clockwise and add a diffuse dark drop shadow. Keep the artifact crisp, with the upper edge starting above the headline and the lower edge crossing the band boundary. For the pale chapter, use an upright 600px-wide artifact with a restrained neutral shadow; do not add a pedestal or glow.

### Circular illustrated emblem

**Use:** Repeated warm punctuation in offer and resource cards.

**Observed:** Small flat-color character artwork is enclosed in a dark circular badge. Ochre and warm tan shapes are isolated against navy, without a large illustrated scene; badges remain far smaller than the headings.

**Transfer:** Use an original compact emblem tied to the new product, or a two-color tool pictogram inside a navy circle as the minimum version.

**Build:** Make a 60px SVG circle filled navy, containing two or three flat, overlapping warm-colored shapes forming a simple tool or creature silhouette. Leave a dark perimeter and use a tiny white highlight. Scale to 80px for the offer. Keep linework sparse and avoid emoji rendering.

### Cinematic campaign film

**Only for:** campaign storytelling chapters

**Use:** A full-bleed visual interlude followed by an explanatory blue chapter.

**Observed:** A 1440px by 810px live-action scene fills the width, tightly framing expressive people through a vehicle window. Daylight, patterned clothing and saturated natural colors make it far more vivid than the surrounding layout. A translucent circular expand affordance sits in the center.

**Transfer:** Use an authentic, specific situation related to the product's purpose; the minimum is a strong full-width editorial still with a real visual story, not generic office stock.

### Overlapping mobile devices

**Only for:** dedicated product explanation

**Use:** Physical product proof beside explanatory cards.

**Observed:** Two black-edged phones are shown diagonally on the right, one behind the other. The foreground device is readable; the rear device is partly obscured by white explanatory cards. The image is approximately 624px by 716px and has no colored pedestal.

**Transfer:** Use two views only when they explain distinct states. Keep one dominant and allow cards to overlap the secondary object.

### Technical film inset

**Only for:** technical feature chapters

**Use:** A compact media demonstration beside a text-and-action column.

**Observed:** A 584px by 329px dark video inset shows a softly luminous green-blue globe against near-black space, with the same circular expand control. The inset is rectangular and unrounded on a pale chapter.

**Transfer:** Use restrained technical animation showing the mechanism, with a dark frame and a single focal object rather than spreading glow across the marketing canvas.

### Icons

**Observed:** Utility icons are mostly filled silhouettes, 10–18px, set directly before text. Social and contact icons are larger, around 28–32px, in footer silver. Checklist ticks are plain navy strokes; FAQ plus signs are bold, built with 6px bars. Illustrated badges are a separate visual language.

**Transfer:** Use filled functional icons at text scale, simple checks for offer benefits and bold plus signs for disclosure. Avoid a page-wide system of oversized colorful feature icons.

## Section recipes

How recurring sections are built.

### First screen: Editorial product opening

**Observed:** A 48px navy utility strip precedes the 72px blue navigation. The blue hero continues beneath it for 783px. A centered 960px editorial stage pairs a left headline/copy column approximately 485px wide with the Tangible interface artifact on the right, separated by 80px. The white Display headline breaks into two strong lines; beneath it are two Body paragraphs separated by 32px, then Primary button and Companion button with a 16px gap. The headline-to-copy and copy-to-actions gaps are 40px. Back to front: flat blue, soft artifact shadow, tilted interface, white text and solid actions. The main object begins above the headline and extends beyond the hero into the next media chapter. Within the first 900px, utility navigation, headline, both paragraphs, both actions and most of the interface are visible; the full-width film begins just below.

**Transfer:** Preserve the confident two-part stage: a concise human outcome and a large, tangible demonstration. Without an interface, use a working document or sharply rendered tool specimen. Dedicated product pages instead open with Product-display text beside an Offer plate inside a 1248px breakout with an 80px gap. Editorial indexes use a text-only Display opening with 240px vertical space and a modest download link. Pricing uses a compact centered Pricing-display opening and equal-status Rate tiles.

**Avoid:** Do not replace the artifact with a tiny dashboard thumbnail, center every element, or turn the opening into a giant pill-button and gradient-glow startup template.

**Text style:** `display` — Source Sans Pro 600 · 80px/1

### Editorial chapter

**Observed:** Pale chapter or Blue stage, centered 960px column, Heading followed after 40px by Body copy, optional second paragraph after 32px and a Primary button after 40px. Major pale chapters have 240px top and bottom space; the film-caption version uses 192px.

**Transfer:** Use the generous chapter to make one argument with a consequence and an explicit next step, not a collection of unrelated feature slogans.

**Text style:** `heading` — Source Sans Pro 600 · 56px/1

### Offer and explanation split

**Observed:** Navy chapter with a 1248px breakout and 240px outer vertical space. A text column sits beside an Offer plate, aligned centrally with a 144px gap. A compatibility row of small filled platform icons and text links sits below, separated from the main split by 96px.

**Transfer:** Pair explanatory prose with one concrete offer. The lower row can describe supported formats, environments or integrations instead of operating systems.

### Resource shelf

**Observed:** Pale chapter with a centered Heading and three Resource cards in a 40px-gap breakout grid. The cards contain repeated emblems and Category tags; Reading buttons align at the bottom. Large chapter margins of 240px keep the shelf apart from neighboring stories.

**Transfer:** Offer three genuinely useful paths into learning, using descriptive questions rather than generic content teasers.

### Rallying statement

**Observed:** Rallying yellow surface, approximately 501px high at desktop, with 120px top and bottom space. Centered navy Display text spans up to 1248px and is followed after 40px by one Reading button. No supporting paragraph or image dilutes the declaration.

**Transfer:** Use a short, affirmative statement about the reader's agency. Retain this high-contrast device on a new marketing page, but its location and frequency can follow the new story.

**Text style:** `display` — Source Sans Pro 600 · 80px/1

### Directory ending

**Observed:** Footer navigation follows the yellow statement on broad marketing pages, but follows the final answer or final resource group directly on pricing and editorial indexes. The navy directory is about 611px tall, with 64px vertical padding and four equal columns; language selection sits beneath social links.

**Transfer:** Adapt directory contents to the new product while retaining the substantial practical ending.

### Capability field

**Only for:** dedicated product landing pages

**Observed:** Navy chapter, centered Heading and an unboxed three-column capability grid. Columns are separated by 56px and rows by 120px. Feature-heading titles precede Body paragraphs with roughly 34.1px separation; inline reference links remain underlined.

**Transfer:** Use this for meaningful product commitments, letting the text carry the weight without enclosing every feature in a card.

**Text style:** `feature-heading` — Source Sans Pro 600 · 34.1px/1.125

### FAQ split

**Only for:** dedicated product landing pages

**Observed:** Bright support surface with 240px vertical space and two columns separated by 32px. Heading, short Body introduction and a support link occupy the left; four FAQ disclosures and a right-aligned Primary button occupy the right.

**Transfer:** Answer practical objections with short, candid answers and a reachable support path.

### Editorial index group

**Only for:** editorial indexes

**Observed:** Pale chapter with a 960px column, Heading above a featured full-width Editorial preview followed by paired previews with 56px gaps. Sentence-case topic labels appear before card titles. Groups are separated by 120px; the last paired cards lead through generous pale space directly to Footer navigation, without a yellow conversion band.

**Transfer:** Organize long-form resources by questions or consequences and give summaries enough length to be useful.

### Transactional comparison

**Only for:** pricing pages

**Observed:** Blue stage with Pricing-display centered above a short support line, three Rate tiles in an 800px row and a compact currency equivalence row with flag images. A softer golden, 4px-radius sentence-case action bridges the blue-to-white boundary. Below, a 640px text column presents three compact explanatory arguments on white, followed by always-visible questions on Base canvas with 24px titles and 16px body. The last answer leads directly to Footer navigation.

**Transfer:** Keep pricing straightforward, use equal visual status for comparable choices and make purchase terms readable. Currency flags belong only where a real conversion aid is useful.

## Page flow

**Storyline:** Human promise → tangible demonstration → explanation of stakes → practical offer and capabilities → learning or objection handling → emphatic invitation or direct directory ending.

### Broad brand and product introduction

1. **Promise** — Blue editorial product opening with two actions and a tilted interface.
2. **Emotional demonstration** — Full-width cinematic interlude and a blue explanatory caption chapter.
3. **Context** — Pale editorial argument explaining why the product category matters.
4. **Offer** — Navy explanation with a white offer plate and compatibility row.
5. **Adjacent capability** — Pale split with a second product artifact.
6. **Education** — Three-card resource shelf.
7. **Closing call** — Yellow rallying statement and navy directory.

**Transfer:** Combine the reader's stakes with a visible working product; vary chapters between prose, artifact and practical facts.

### Transparent purchase explanation

1. **Pricing** — Centered blue title, three equal-status white rate tiles and currency equivalence aid.
2. **Conversion** — Action straddles blue and white, followed by concise purchase principles.
3. **Objection handling** — Narrow always-visible question-and-answer column.
4. **Directory** — Navy footer immediately follows the final answer.

**Transfer:** Let understandable terms and candid answers replace aggressive tier upselling.

### Long-form issue and knowledge index

1. **Context** — Text-only blue opening, large headline, explanatory paragraph and document download link.
2. **Education** — Pale topical groups with full-width lead previews and paired outlined cards.
3. **Consequences** — Final reading group develops the broader implications.
4. **Directory** — Final cards lead directly to the navy footer.

**Transfer:** Use the reading system for any complex subject requiring several related arguments; do not force a purchase offer into every index.

### Dedicated product explanation and conversion

1. **Promise and offer** — Large blue product promise beside the white offer plate.
2. **Product explanation** — Four rounded cards overlap a pair of diagonal mobile devices.
3. **Capabilities** — Unboxed navy three-column text grid.
4. **Technical proof** — Pale text and dark video inset.
5. **Objection handling** — White split with FAQ disclosures.
6. **Education** — Resource shelf.
7. **Closing call** — Yellow statement and navy footer.

**Transfer:** Move from a concrete offer to how the product works, then details, concerns and deeper learning.

## Writing

Principled, candid and explanatory, with occasional dry humor. The tone treats readers as capable people who deserve to understand both a tool's usefulness and its limitations.

**Do not copy:** Do not reuse Mullvad names, mascot artwork, logos, campaign titles, political quotations, prices, product claims, audit claims, technical promises or company facts as claims for another product. Examples demonstrate voice and structure only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you'; use 'we' when accepting responsibility or explaining a deliberate product decision. Favor people and practical actions over abstract customer segments.
- **Rhythm:** Headlines are plain spoken declarations or questions, often 4–10 words. Body paragraphs are substantive, frequently two or three sentences, with short emphatic sentences breaking longer explanations. Actions are terse; a longer action is allowed when it names a specific destination.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State a human conviction or an outcome in ordinary words. | 4–9 words | “Privacy is for the people”<br>“A fair pricing model” |
| Explanatory heading | Ask the reader's question, then qualify the level of detail. | 6–12 words | “What is a VPN? The short version.” |
| Support paragraph | Explain what the tool does in concrete language before introducing terminology. | 2–3 sentences | “A VPN (Virtual Private Network) is a service that creates a private connection to the internet by encrypting your traffic. The outcome: your ISP (internet service provider) can’t see your activity and nobody else can use your IP address to track you.” |
| Action | Verb plus a clear next step, or the exact destination product. | 2–5 words | “Get started”<br>“Read the longer version”<br>“Read article” |
| Reassurance | Explain a choice frankly, with a conversational aside rather than a superlative. | 2–4 sentences | “Our price hasn't changed since, well, ever! We’re still offering privacy at the same rate as when we launched in 2009. Call us unconventional. Call us blind to inflation. We call it a pretty good deal.” |

**Words and phrasing to use:** you; we; people; learn more; the short version; how it works; that's why; the outcome; questions

**Avoid:** unlock your potential; revolutionary; seamless ecosystem; next-generation excellence; exclusive limited-time deal; unparalleled

**Rules:**

- Define specialist terms at first use, and connect the definition to a visible consequence.
- Name what the product cannot do as clearly as what it can.
- Use questions for learning paths and objections, not as a substitute for every assertion.
- Allow dry asides and contractions, but keep the factual argument understandable.
- Make the final declaration about the reader's agency rather than company greatness.

## Do's and Don'ts

### Do

- Keep the 80px/1 display and 56px/1 chapter scale semibold and openly spaced.
- Use flat blue and navy fields to frame white text instead of ornamental gradients.
- Let a tangible product artifact occupy roughly half the opening and cross a section boundary.
- Give ordinary major marketing chapters 240px of top and bottom space.
- Contrast 16px-radius white cards with square 2px-border action blocks.
- Use the 18px/1.4 uppercase mono action recipe consistently across marketing buttons.
- Keep practical terms readable in a 640px transactional column with 16px/1.5 body text.
- Include both a strong yellow statement device and a substantial navy directory on a broad marketing page.

### Don't

- Do not tighten the headline tracking into a compressed grotesk treatment; normal tracking is central to the humanist voice.
- Do not apply the 6px pricing-tile radius to ordinary offer cards; their default is 16px.
- Do not turn the 61px marketing action into a pill or add a glossy drop shadow.
- Do not give every capability its own colored icon tile; the navy capability chapter is unboxed text.
- Do not use acid yellow as the body-copy color on pale gray; it is a fill and action accent.
- Do not add a recommended-tier badge or unequal emphasis to the equal-status rate comparison.
- Do not turn editorial previews into image-first blog thumbnails; they are substantial outlined reading panels.
- Do not shrink the ending to a tiny legal bar; four practical columns and the language control give it weight.

## Motion and responsive

### Motion

**Observed:**

- Actions declare hover, active and focus-visible styles; large marketing actions declare active scale(0.99).
- Opacity transitions of 0.3s cubic-bezier(.25,0,.3,1) recur on actions and surfaces. Other isolated transitions are 0.15s and 0.1s.
- No matched element animations establish a general scroll-reveal system.

**Transfer:**

- Preserve the immediate color and underline feedback, slight active compression and conspicuous yellow keyboard outline on the square actions.
- Keep product artifacts legible at rest; the visual identity does not require elaborate entrance choreography.

**Unknown:**

- The timing of cinematic footage and the actual execution of declared keyframes are not established.

### Responsive

**Observed:**

- Display, chapter and pricing titles use clamp-based font sizing.
- Resource cards auto-fill with a minimum of min(300px, 100%); product splits auto-fit with a minimum of min(400px, 100%).
- Card padding uses clamp(1rem, 3vw, 2.5rem).

**Transfer:**

- Use those intrinsic grids to stack the product demonstration after its explanation when two columns no longer fit.
- Keep the tangible artifact large enough to read after stacking, and limit overlap so it cannot obscure the following heading.
- Let paired actions wrap with their 16px gap and preserve square corners.

**Unknown:**

- Narrow-screen navigation, footer stacking and exact breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
