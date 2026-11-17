# Central — cream type, red conviction

## Overview

A dark, grainy industrial identity with tall condensed headlines, warm cream lettering and abrupt signal-red accents. Compact grotesk paragraphs and spaced monospace labels make operational products feel tangible and human rather than abstract. Interface vignettes, documentary testimonials and faint technical line art sit inside restrained charcoal frames; the overall page is spacious while individual evidence blocks are dense.

### Essentials

- Headlines behave like tightly stacked poster lettering: American Grotesk Condensed Bold at 100px/0.97, weight 700, -0.01em tracking, uppercase; a muted #524e47 first line gives way to warm #e4dac3 promise lines.
- The default opening is a narrow typographic monument, not a dashboard splash: a centered 535px headline block beneath a 96px fixed header, three 16px support lines, then a 316px × 35px red action. Product scenes enter below the first screen.
- Actions resemble equipment keys rather than pills: 2px corners, 35px height, 10px padding and uppercase Söhne Mono at 15px/1 with 0.1em tracking; the secondary key is #302e2b.
- Nearly the entire page stays near-black and warm-neutral: #0e0e0e canvas, cream headlines and taupe body text. #e50000 is concentrated in small actions, numbered chapter markings and the monumental closing slogan, never broad colored feature bands.
- Product proof is staged as dim, tangible dioramas: 720px × 638px hairline-bordered scenes pair with a 260px text rail across a 120px gap; phones, documents and small charcoal panels overlap and clip at the stage edges. When product media is unavailable, construct a readable task vignette with layered HTML panels.
- A grainy closing band and oversized red slogan are signature punctuation: a #191918 footer, thin red top rule, compact link columns and a repeated 152px/0.95 uppercase statement clipped by the viewport. Use a new short mission phrase; preserve this device even when there is no equivalent brand illustration.
- Technical atmosphere stays almost invisible: square proof stages contain faint converging warm lines or dark interlaced strands behind small interface panels. Recreate these with low-opacity SVG geometry and fine noise, not bright neon glows.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#e50000` | `--color-red` | action, accent, text, border | Primary buttons, chapter labels and oversized closing slogan. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cream | `#efe5cd` | `--color-cream` | text, accent | Section headings, emphasized labels and monochrome marks. |
| Warm headline | `#e4dac3` | `--color-headline` | text | Hero promise and pricing headline emphasis. |
| Secondary cream | `#d9cfba` | `--color-secondary-cream` | text | Pull quotes and supporting subheads. |
| Header ivory | `#f3ead4` | `--color-header-text` | text | Compact navigation action. |
| Warm body | `#c2baa6` | `--color-body` | text | Hero support and long testimonial text. |
| Near-black canvas | `#0e0e0e` | `--color-canvas` | background | Default page ground. |
| Panel low | `#151414` | `--color-panel-low` | surface | Low end of the broad testimonial panel gradient. |
| Panel dark | `#171716` | `--color-panel-dark` | surface | Lower-right end of interface panel gradients. |
| Footer charcoal | `#191918` | `--color-footer` | background, surface | Closing band and dark gradient highlights. |
| Panel high | `#201f1d` | `--color-panel-high` | surface | Upper-left highlight of layered interface panels. |
| Announcement charcoal | `#252321` | `--color-announcement` | surface, background | Announcement strip and inset controls. |
| Fine stage edge | `#292825` | `--color-edge` | border | Hairlines around demonstration stages and broad proof panels. |
| Secondary action charcoal | `#302e2b` | `--color-secondary-action` | action, border | Secondary buttons and internal panel dividers. |
| Recessed headline | `#524e47` | `--color-recessed` | text | Opening qualifier line. |
| Inactive label | `#5d5951` | `--color-inactive` | text | Condensed capability lists under chapter headings. |
| Deep taupe | `#7f796d` | `--color-subtle` | text, link | Tertiary explanatory copy and outbound proof links. |
| Taupe | `#958f80` | `--color-muted` | text, link | Secondary paragraphs, navigation and footer links. |
| Action ivory | `#fff8e6` | `--color-action-text` | text | Primary action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer-story collections | Dark olive wash | `#26220d` | `--color-story-yellow` | surface | Visible yellow tint over near-black; built with rgba(255,213,0,0.1). |
| customer-story collections | Story edge | `#3b3934` | `--color-story-edge` | border | Stronger fine outlines around tinted story cards. |

## Typography

- **American Grotesk Condensed** — All poster headlines, chapter titles, small emphatic subheads and closing slogan. Very narrow bold grotesk with blunt uppercase forms and high vertical impact. If unavailable, use **Barlow Condensed**. Use weight 700; preserve narrow line lengths rather than widening the text block. Font stack: "American Grotesk Condensed", "Barlow Condensed", "Arial Narrow", sans-serif.
- **Söhne Buch** — Body copy, testimonial prose, names and story summaries. Unshowy compact grotesk; Buch supplies regular prose, Kräftig supplies medium emphasis. If unavailable, use **Inter**. Use 400 for prose and 500 for emphasized summaries. Font stack: "Söhne Buch", "Inter", Arial, sans-serif.
- **Söhne Mono Buch** — Navigation, actions, numbered labels and outbound proof links. Utilitarian monospace with conspicuous uppercase spacing; Buch, Kräftig and Halbfett cuts differentiate utility from action. If unavailable, use **IBM Plex Mono**. Use 400 for navigation, 500 for labels and 600 for actions. Font stack: "Söhne Mono Buch", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| slogan | American Grotesk Condensed | 700 | 152px | 0.95 | -0.01em, uppercase | Oversized repeating red statement along the bottom edge. |
| display | American Grotesk Condensed | 700 | 100px | 0.97 | -0.01em, uppercase | Centered opening promise, stacked into short broad lines. |
| closing-heading | American Grotesk Condensed | 700 | 56px | 1.1 | normal, uppercase | Centered final conversion invitation. |
| heading | American Grotesk Condensed | 700 | 40px | 1.1 | normal, uppercase | Primary chapter headings; also the compact numeric price treatment. |
| pull-quote | American Grotesk Condensed | 700 | 32px | 1.1 | normal, uppercase | Short editorial verdict in broad testimonial panels. |
| benefit-heading | American Grotesk Condensed | 700 | 28px | 1 | normal, uppercase | Headings above square supporting demonstrations. |
| card-heading | American Grotesk Condensed | 700 | 24px | 1.3 | normal, uppercase | Brief testimonial verdicts. |
| capability-label | American Grotesk Condensed | 700 | 24px | 1 | normal, uppercase | Muted lists anchored at the bottom of capability rails. |
| body | Söhne Buch | 400 | 16px | 1.5 | normal | Default explanatory prose and pull-quote paragraphs. |
| hero-support | Söhne Buch | 400 | 16px | 1.7 | normal | Centered promise explanation in short consecutive lines. |
| testimonial-body | Söhne Buch | 400 | 16px | 1.6 | normal | Longer proof quotes and benefit descriptions. |
| footer-link | Söhne Buch | 400 | 16px | 0.9 | normal | Footer links, separated by generous row space rather than multiline leading. |
| action | Söhne Mono Buch | 600 | 15px | 1 | 0.1em, uppercase | Primary and secondary conversion keys. |
| eyebrow | Söhne Mono Buch | 500 | 14px | 1.3 | 0.1em, uppercase | Red numbered chapter markings. |
| caption | Söhne Buch | 400 | 14px | 1.3 | 0.01em | Reassurance beneath actions. |
| proof-link | Söhne Mono Buch | 500 | 14px | 1.3 | 0.05em, uppercase | Small external review and story links. |
| navigation | Söhne Mono Buch | 400 | 13px | 1 | 0.1em, uppercase | Header utility links. |
| navigation-action | Söhne Mono Buch | 600 | 13px | 1 | 0.1em, uppercase | Compact conversion action in the header. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and FAQ sections | question-category | American Grotesk Condensed | 700 | 24px | 1.1 | normal, uppercase | Question category headings. |
| customer-story collections | story-summary | Söhne Buch | 500 | 18px | 1.4 | normal | Outcome-focused story card summaries. |
| pricing and FAQ sections | compact-body | Söhne Buch | 400 | 16px | 1.3 | normal | Dense inclusion lists and question rows. |

**Notes:**

- Condensed display type carries the hierarchy; do not replace it with a normal-width sans or a serif. The Bold cut stays visually bold even where its declared weight is regular.
- Tracking is tight only on the largest headlines: -0.01em at 100px and 152px. Ordinary condensed titles use normal tracking; uppercase mono actions use 0.1em.
- Warm text hierarchy is as important as size: a dark qualifier followed by light promise lines; regular prose below it in taupe. Avoid making every line equally bright.
- Body copy remains small relative to the poster type. Use 16px prose rather than enlarging every paragraph to fill the page.

## Layout

**Density:** Airy at page level, compact within evidence blocks: very long dark pauses separate chapters while buttons, utility labels and panels are closely packed.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing in actions. |
| 10px | Repeated label gaps and action padding. |
| 14px | Benefit heading-to-description gap. |
| 16px | Internal copy and testimonial heading gaps. |
| 20px | Closing heading-to-support gap and small panel separation. |
| 28px | Footer heading-to-links spacing. |
| 36px | Outer side padding, testimonial card padding and action-group separation from copy. |
| 48px | Hero support-to-action gap and internal testimonial breathing room. |
| 56px | Broad testimonial inset and FAQ category spacing. |
| 120px | Chapter text-rail-to-scene gutter. |
| 144px | Two-column supporting proof grid gutters. |
| 264px | Long pauses between major capability chapters and around final conversion sections. |

### Containers and grids

- **main container**: max width 1100px · side padding 36px. Centered content frame for chapters, proof, navigation and footer; at 1440px the content begins 170px from the left edge.
- **opening text**: max width 535px · side padding 36px. Centered, vertically stacked hero headline. Supporting copy is narrower and the action is 316px wide.
- **capability split**: max width 1100px · 2 columns · gap 120px. A 260px left rail beside a 720px scene; rail title at top and muted capability list near bottom.
- **testimonial grid**: max width 1100px · 3 columns · gap 0px. An editorial ruled grid with 36px insets; the first broad quote spans two columns, followed by three narrow columns.
- **supporting proof grid**: max width 1100px · 2 columns · gap 144px. Two 478px columns, with descriptive text above square media stages.
- **story index** (only for customer-story collections): max width 1100px · 4 columns · gap 36px. Wrapping 235px-wide story cards, four across then a partial second row.
- **documentary wall** (only for customer-proof pages): max width 1100px · 2 columns · gap 30px. Two independent 535px-wide columns of testimonial images with natural, varying heights.
- **pricing split** (only for pricing pages): 2 columns · side padding 36px. A central hairline divides subdued right-aligned logos on the left from a left-aligned price, actions and inclusion lists on the right. The right column begins with a 56px inset.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion keys | 2px |
|  | small demonstration panels | 3px |
|  | media frames | 4px |
| customer-story collections | story cards | 10px |

## Surfaces and depth

### Surfaces

#### Grainy canvas · level 0

**Use:** Default dark ground for ordinary landing pages.

**CSS:** `background-color: #0e0e0e`

**Observed:** A fine, low-contrast grain lies across the otherwise flat dark field; it is visible around both text and media.

**Transfer:** Use the subtle grain recipe in Atmosphere, keeping text crisp above it.

#### Demonstration stage · level 1

**Use:** Large media stages and square benefit demonstrations.

**CSS:** `background: rgba(239,229,205,0.01); border: 1px solid #292825; overflow: hidden`

**Observed:** Almost indistinguishable from the canvas; a thin rectangular perimeter contains layered product objects.

**Transfer:** Keep the outer stage square-edged and use tiny radii only on the objects inside.

#### Charcoal panel · level 2

**Use:** Inset task panels within product illustrations.

**CSS:** `background: linear-gradient(130deg, #201f1d 0%, #171716 100%); border: 1px solid #302e2b; border-radius: 3px`

**Observed:** A nearly imperceptible upper-left lift, not gloss or a large drop shadow.

**Transfer:** Use for one or two legible task fragments, not a whole simulated application.

#### Editorial proof panel · level 1

**Use:** Broad portrait-and-quote proof block.

**CSS:** `background: linear-gradient(130deg, #191918 0%, #151414 100%); border: 1px solid #292825; padding: 56px`

**Observed:** A wide low rectangular band containing a portrait, short condensed verdict and prose; no inflated rounded corners.

**Transfer:** Use one meaningful testimonial or short customer narrative with an authentic portrait.

#### Closing band · level 0

**Use:** Shared footer and monumental statement stage.

**CSS:** `background-color: #191918; border-top: 1px solid #e50000; padding-top: 90px; overflow: hidden`

**Observed:** Soft irregular charcoal texture behind a brand mark and link columns; the slogan extends beyond both viewport edges.

**Transfer:** Retain the textured band, thin accent rule and giant phrase with the new brand's own mark.

#### Tinted story card · level 1

**Only for:** customer-story collections

**Use:** Outcome cards in a story directory.

**CSS:** `background-color: rgba(255,213,0,0.1); border: 1px solid #3b3934; border-radius: 10px; padding: 24px 20px`

**Observed:** Dark olive is one variant; adjacent cards use dark rust, blue, indigo, orange-brown and purple tints. A blurred image sits beneath the tint and fine grain.

**Transfer:** Tie each dim tint to the story identity; keep all variants dark enough for cream text.

## Components

### Fixed navigation

**Use:** Persistent orientation and compact conversion access.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 96px; z-index: 4; background-color: #0e0e0e`

**Text style:** `navigation` — Söhne Mono Buch 400 · 13px/1 · tracking 0.1em · uppercase

**Observed:** Two tiers: a 39px announcement strip above a 57px navigation row. Within the centered main container, a cream logo sits left and uppercase utility links plus one compact action sit right with 32px gaps.

**Transfer:** Keep the announcement to one timely sentence and the navigation to a few short destinations.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; justify-content: center; align-items: center; background-color: #e50000; color: #fff8e6; border-radius: 2px; padding: 10px; height: 35px; width: 316px; box-sizing: border-box`

**Text style:** `action` — Söhne Mono Buch 600 · 15px/1 · tracking 0.1em · uppercase

**Observed:** A flat red rectangle with a centered mono label, without an icon. Pricing versions narrow to 272px; the opening uses one action and closing groups can stack it above a secondary action.

### Secondary button

**Use:** Human-assisted conversion beside or beneath the primary path.

**CSS:** `display: flex; justify-content: center; align-items: center; background-color: #302e2b; color: #efe5cd; border-radius: 2px; padding: 10px; height: 35px; width: 316px; box-sizing: border-box`

**Text style:** `action` — Söhne Mono Buch 600 · 15px/1 · tracking 0.1em · uppercase

**Observed:** Same construction as the primary key but a dark charcoal fill; not an outline or text-only action. Stacked closing actions have a 12px gap.

### Header action

**Use:** Small conversion key at the right of the navigation.

**CSS:** `background-color: #e50000; color: #f3ead4; border-radius: 2px; width: 120px; height: 29px; padding: 10px; box-sizing: border-box; display: flex; align-items: center; justify-content: center`

**Text style:** `navigation-action` — Söhne Mono Buch 600 · 13px/1 · tracking 0.1em · uppercase

**Observed:** The compact key can read as muted charcoal on initial entry, then signal red further down the page; keep the body conversion key unmistakably red.

### Chapter rail

**Use:** Orient readers alongside a large product demonstration.

**CSS:** `width: 260px; height: 638px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `heading` — American Grotesk Condensed 700 · 40px/1.1 · uppercase

**Observed:** A red mono number and category precede a short cream condensed heading; the lower end holds a muted uppercase list. The scene sits to the right, separated by the capability split gutter.

**Transfer:** Use a task outcome as the title and concrete included operations in the lower list.

### Testimonial cell

**Use:** Editorial proof without a wall of raised cards.

**CSS:** `padding: 36px; display: flex; flex-direction: column; justify-content: space-between; gap: 48px; background-color: #0e0e0e`

**Text style:** `testimonial-body` — Söhne Buch 400 · 16px/1.6

**Observed:** Verdict heading, quote, outbound proof link and author block are separated vertically. Faint rules divide adjacent cells. Small desaturated portraits anchor names and roles near the bottom; the lead cell can span two columns.

### Outbound proof link

**Use:** Attribute a quote or lead to a longer customer story.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; color: #7f796d`

**Text style:** `proof-link` — Söhne Mono Buch 500 · 14px/1.3 · tracking 0.05em · uppercase

**Observed:** Unboxed uppercase mono label with a small diagonal arrow; quieter than conversion actions.

### Footer link

**Use:** Utility navigation in the closing band.

**CSS:** `color: #958f80; text-decoration: none`

**Text style:** `footer-link` — Söhne Buch 400 · 16px/0.9

**Observed:** Three concise columns for company, legal and contact; cream category labels above taupe links. Small social marks sit with contact details.

**States:** Declared: hover color #efe5cd; focus-visible unknown; active unknown.

### Story card

**Only for:** customer-story collections

**Use:** Navigate to a customer outcome.

**CSS:** `width: 235px; height: 300px; padding: 24px 20px; box-sizing: border-box; border-radius: 10px; border: 1px solid #3b3934; background-color: rgba(255,213,0,0.1); display: flex; flex-direction: column; justify-content: space-between; overflow: clip`

**Text style:** `story-summary` — Söhne Buch 500 · 18px/1.4

**Observed:** A small logo is pinned high; the multi-line outcome summary sits low over blurred image color, leaving substantial visual space between. The whole card is linked.

### FAQ row

**Only for:** pricing and FAQ sections

**Use:** Offer categorized objection handling.

**CSS:** `display: flex; align-items: flex-start; gap: 10px; color: #7f796d`

**Text style:** `compact-body` — Söhne Buch 400 · 16px/1.3

**Observed:** A tiny right-pointing triangle precedes each question. Rows sit below condensed cream category titles; groups are 56px apart. The left half carries the section title rather than more cards.

## Imagery and graphics

### Tangible workflow dioramas

**Use:** Main capability chapters and smaller benefit proofs.

**Observed:** A dark phone with recognizably rendered messaging screens overlaps stacks of payroll or provider tiles; other scenes show a state map with task notifications and a folded-corner document with signature and option panels. Warm desaturated objects occupy most of a 720px-wide stage while the chapter copy remains in a narrow rail. Objects are cropped at the stage bottom, not shown as a complete flat dashboard.

**Transfer:** Choose one observable task and show a before-to-done fragment. Use the real interface when available; otherwise construct a simple document, a few status rows and one confirmation panel, keeping the lighting and framing subdued.

**Build:** Place a relative 720px × 638px stage with overflow hidden. Layer a tall device or document on one side and a 238px-wide stack of Charcoal panels on the other. Use 1px warm-gray edges, 3px inner corners and cream text; fade the lowest objects into the canvas with an rgba(14,14,14,0) to rgba(14,14,14,1) overlay. Keep any functional colors inside the actual interface.

### Atmosphere

**Use:** Fine grain on dark fields and low-contrast technical geometry behind square proof demonstrations.

**Observed:** The integration scene contains many fine warm lines converging into a faint bright point at the bottom center; the security scene has dark interwoven strands behind a small verification panel. The footer carries a soft mottled, almost fabric-like charcoal field. None of these effects become a dominant colored light source.

**Transfer:** Keep the geometry secondary to the task panel. A minimal acceptable version is a faint fan of lines plus a fine monochrome grain overlay; preserve at least one technical atmosphere treatment on a new landing page.

**Build:** Generate a repeating SVG feTurbulence noise tile, desaturate it, and blend at low opacity above the #0e0e0e or #191918 ground but below text. In a 478px square SVG, draw 40–60 hairlines from a bottom-center point to spaced points across the upper edge; use rgba(239,229,205,0.04) strokes and a tiny rgba(239,229,205,0.3) convergence point. For the strand variant, interlace broad dark curved ribbons behind the panel with only faint warm edges. Match the subdued contrast; exact noise and geometry are not essential.

### Monumental red word strip

**Use:** Shared closing punctuation on all page types.

**Observed:** The repeated uppercase phrase is 152px with very tight leading, running off both edges of a textured footer. A thin red rule introduces the band; the red brand symbol and compact utility columns sit far above the strip.

**Transfer:** Repeat an original two- or three-word mission phrase with similar condensed width. This is typographic artwork, not a huge clickable button.

**Build:** Use an overflow-hidden full-width strip about 130px tall at the bottom of Closing band. Place multiple unwrapped slogan spans in a horizontal flex row with a 64px gap, color #e50000, and shift the row so letters are cut at both viewport edges. Keep the surrounding footer links on the centered main container.

### Documentary human proof

**Use:** Small author portraits and the lead editorial testimonial.

**Observed:** Tiny mostly desaturated square headshots accompany quote attributions. A broad lead panel pairs a taller portrait with a condensed verdict and longer prose. Photography is evidence, not a bright lifestyle backdrop.

**Transfer:** Use real customers or domain experts, restrained color and direct framing; retain identity and quote context.

### Blurred story backings

**Only for:** customer-story collections

**Use:** Soft imagery underneath directory-card logos and summaries.

**Observed:** Defocused photographic color patches in olive, rust, charcoal blue and purple fill each portrait-format card. Grain and dark tint unify them; the logo and cream outcome text remain sharply legible.

**Transfer:** Use customer-specific environment imagery blurred into almost abstract tonal fields, never a vivid stock-photo collage.

**Build:** Cover the card with a defocused photo layer using blur(18px) and a slight scale-up to conceal blur edges. Overlay a 10% dark warm or cool tint, or a 20% purple tint, then fine noise. Keep crisp foreground logo and text above the layers.

### Native review wall

**Only for:** customer-proof pages

**Use:** Long-form accumulation of social proof after the story directory.

**Observed:** Two masonry-like columns of native review, chat and social-post images, mostly white with black text, interspersed with dark messaging fragments. Images retain their own avatars, ratings, platform furniture and unequal heights; the marketing canvas remains dark. The columns taper independently into the common footer without a separate closing action.

**Transfer:** Use genuine permitted review or message images with private data removed, preserve their natural aspect ratios and provenance context, and keep this bright documentary density confined to a proof-focused page.

### Icons

**Observed:** Small arrows punctuate links, right-pointing triangles introduce questions, and tiny monochrome social icons sit in the footer. Typical marketing icon sizes are 12px–20px; most standalone color belongs inside product illustrations rather than feature badges.

**Transfer:** Favor plain geometric arrows and recognizable monochrome destination marks. Do not add a colorful icon to every chapter heading.

## Section recipes

How recurring sections are built.

### First screen: Poster promise opening

**Observed:** Back to front: Grainy canvas, fixed two-tier navigation, then a centered four-line poster headline in a 535px-wide block. The first qualifier line is recessed taupe; the remaining promise is warm cream. The 100px display occupies roughly the central third of the page width and almost half the first screen's height. Three centered 16px support lines follow, then Primary button after a 48px gap and a small reassurance caption. Within 900px, the complete headline, explanation and single action are visible with generous dark space around them. No product object appears above the fold; the broad proof panel and capability scenes follow below.

**Transfer:** Compose a short qualifier plus a compact product-category or outcome promise into equally emphatic narrow lines. The headline itself is the hero artwork, so no substitute stock image is needed. Pricing pages instead open with a split logo-and-price composition; customer-proof pages open with a full-container red word sculpture and a story directory.

**Avoid:** Do not turn this into a conventional left-copy/right-dashboard hero, or put a large decorative image behind the promise.

**Text style:** `display` — American Grotesk Condensed 700 · 100px/0.97 · tracking -0.01em · uppercase

### Editorial lead proof

**Observed:** Editorial proof panel spans the 1100px main container. A narrow portrait anchors the left, a 32px condensed verdict occupies the middle, and 16px prose with an outbound source link sits right. A 56px inset and subtle edge keep it cohesive without raised-card styling.

**Transfer:** Use one direct human result to bridge the promise and deeper product explanation.

**Text style:** `pull-quote` — American Grotesk Condensed 700 · 32px/1.1 · uppercase

### Numbered capability chapter

**Observed:** Chapter rail and Demonstration stage share a 638px height within the capability split. A red mono category and number sit above the 40px heading; muted condensed lists anchor the bottom left. The larger scene overlaps tangible UI objects and clips their lower edges. Major chapters are separated by 264px dark pauses.

**Transfer:** Pair each outcome with a specific task demonstration rather than repeating generic benefit copy.

**Text style:** `heading` — American Grotesk Condensed 700 · 40px/1.1 · uppercase

### Editorial review grid

**Observed:** A centered uppercase 40px section heading introduces Testimonial cells. The first row has a double-width quote and one narrow quote; below it, three columns hold varied-length verdicts, quotes, external links and small author portraits. Hairlines, not floating fills, organize the grid.

**Transfer:** Vary quote lengths and keep attribution visible. Let an unusually strong quote occupy a wider cell.

**Text style:** `card-heading` — American Grotesk Condensed 700 · 24px/1.3 · uppercase

### Guided process split

**Observed:** A two-tone condensed title heads a narrow left process column. Red mono step numbers introduce short cream action labels and taupe 16px explanations. A tall, low-contrast form illustration sits on the right; the spacing remains airy even though each step is brief.

**Transfer:** Explain adoption or a core workflow in a few meaningful steps, with one tangible visual that demonstrates ease rather than a row of generic icons.

**Text style:** `heading` — American Grotesk Condensed 700 · 40px/1.1 · uppercase

### Square supporting proof

**Observed:** The supporting proof grid uses two 478px-wide columns with 144px gutters. Each item places a 28px condensed heading above a short 16px paragraph, then a square Demonstration stage after 40px. Native communication snippets and low-contrast technical geometry distinguish the proofs.

**Transfer:** Choose supporting reasons to trust the product and give each a different tangible visual, keeping the shared framing.

**Text style:** `benefit-heading` — American Grotesk Condensed 700 · 28px/1 · uppercase

### Compact conversion pause

**Observed:** A centered 56px closing invitation, 14px reassurance line after 20px, then Primary button and Secondary button stacked with 12px separation. Dark pauses of 264px isolate the invitation from adjacent content. The pricing variant uses a smaller 40px heading within its split layout.

**Transfer:** Make a brief commitment invitation and one credible reassurance, followed by a direct and a human-assisted path.

**Text style:** `closing-heading` — American Grotesk Condensed 700 · 56px/1.1 · uppercase

### Textured slogan ending

**Observed:** Closing band is 561px tall with 90px top inset. A red brand symbol occupies the left of the centered main container; three compact utility columns occupy the right. The bottom is dominated by Monumental red word strip with 152px letters, clipped horizontally and at the lower edge. This ending is shared across landing, pricing and proof pages.

**Transfer:** Retain the texture, accent rule, asymmetric utility layout and giant repeated mission phrase, independently of how the rest of the page is sequenced.

**Text style:** `slogan` — American Grotesk Condensed 700 · 152px/0.95 · tracking -0.01em · uppercase

### Single-offer pricing and questions

**Only for:** pricing pages

**Observed:** A page-center hairline splits dim customer logos from a single 40px condensed price stack with the numeric price in cream and its explanation darker. Paired conversion keys precede grouped inclusion lists. The question section repeats the split: a right-aligned 40px title left, category headings and FAQ rows right, with 56px between categories. A compact trial invitation precedes the shared slogan ending.

**Transfer:** Use the split to contrast trust with a clear offer; do not invent multiple plan cards when the product has a simple single offer.

**Text style:** `heading` — American Grotesk Condensed 700 · 40px/1.1 · uppercase

### Proof directory and documentary accumulation

**Only for:** customer-proof pages

**Observed:** A red condensed word sculpture fills a 1100px × 174px title area. A 72px pause separates it from four-across Story cards with 36px gutters; the next row is partial. Below, Native review wall becomes an extended two-column proof field. Its final irregular-length column flows directly into Textured slogan ending.

**Transfer:** Use a concise proof-themed title, editorial outcome cards, then real documentary material. Let the volume reflect actual available proof rather than manufacturing a page length.

**Text style:** `story-summary` — Söhne Buch 500 · 18px/1.4

## Page flow

**Storyline:** Promise → human proof → task demonstrations → accumulated trust → adoption reassurance → conversion invitation → monumental brand punctuation; emphasis changes with the page's purpose.

### Default product or service landing page

1. **Promise** — Narrow centered poster headline, explanation and a single red key.
2. **Human proof** — Broad portrait-and-verdict editorial panel.
3. **Capability chapters** — Numbered task rails next to dim tangible workflow scenes.
4. **Social proof** — Ruled editorial testimonial grid.
5. **Adoption reassurance** — Short numbered process paired with a form illustration.
6. **Supporting trust** — Two-column square demonstrations of service and reliability.
7. **Closing call** — Centered invitation with stacked direct and assisted actions.
8. **Brand punctuation** — Textured utility footer and clipped red repeated statement.

**Transfer:** Use the opening as the default and redistribute proof and capability chapters around the new product's strongest story, retaining tangible demonstrations and the emphatic ending.

### Explain one straightforward offer and remove purchasing objections

1. **Pricing** — Split trust-logo rail and single price with paired actions and inclusion lists.
2. **Objection handling** — Categorized question rows across a central vertical rule.
3. **Closing call** — Small trial invitation with direct and assisted conversion paths.
4. **Brand punctuation** — The same textured utility footer and oversized red slogan.

**Transfer:** Keep the information architecture simple and editorial; let details extend vertically rather than making a dense comparison dashboard.

### Make customer outcomes and independent praise the primary argument

1. **Proof promise** — Large red word sculpture above a wrapping directory of tinted story cards.
2. **Outcome previews** — Logo-led cards with concrete multi-line result summaries.
3. **Social proof** — Long unequal-height columns of native reviews, posts and messages.
4. **Brand punctuation** — Proof tapers directly into the shared footer, without a separate conversion section.

**Transfer:** Preserve the distinct brighter documentary wall only for proof-heavy pages and use actual available material rather than requiring a fixed number of cards.

## Writing

Direct, founder-friendly and impatient with administrative friction. Confidence comes through concrete tasks, saved effort and human responsiveness rather than lofty enterprise language.

**Do not copy:** Do not reuse the Central or Mercury names, dragon mark, customer logos, competitor comparisons, proprietary interface artwork, testimonial quotations, prices, trial terms, customer counts or time-saving claims as facts for a different product. Source examples illustrate structure only; replace every claim with substantiated product-specific content.

- **Addressing the reader:** Speak directly to you in supporting copy; use we for the service team. The product can be named in explanations while customer voices stay first-person and conversational.
- **Rhythm:** Short uppercase outcome headings contrast with sentence-case prose. Support usually takes one to three short sentences; compact actions are two to four words. Testimonials retain a more spontaneous conversational rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A technical qualifier followed by a concrete list of the work covered. | A short qualifier plus three compact lines | “AI-NATIVE Payroll, HR, BENEFITS and compliance” |
| Chapter heading | A blunt verb phrase that names an outcome or removes a fear. | 3–6 words | “run payroll on autopilot”<br>“STOP FINES & PENALTIES” |
| Supporting line | Contrast do-it-yourself friction with work done for the reader. | 1–3 short sentences | “While others leave you with a dashboard to figure out,”<br>“Reach our expert team directly. No transfers, no offshoring, no nonsense.” |
| Primary action | Simple low-friction imperative, without decorative persuasion. | 2–4 words | “Get started”<br>“Talk to an expert” |
| Proof verdict | A short human benefit, stated in everyday language. | 2–6 words | “MORE THAN SOFTWARE”<br>“10 HOURS BACK EVERY MONTH” |
| Question | Voice a practical switching or purchase concern in the reader's words. | One plain question, occasionally a paired follow-up | “Is switching to [Brand] painful? Will it disrupt our payroll & benefits?” |

**Words and phrasing to use:** autopilot; we handle; expert; directly; get time back; no nonsense; white-glove; setup; switching

**Avoid:** revolutionary ecosystem; synergize; unparalleled innovation; enterprise-grade transformation; unlock limitless potential

**Rules:**

- Name the work being removed before explaining the mechanism.
- Pair a broad promise with concrete included tasks or a verifiable customer result.
- Use terse headings and conversational explanatory prose; typography supplies the drama.
- Reassurance belongs close to the action, in one compact sentence.
- Keep technical vocabulary specific to the actual product rather than decorating copy with AI terminology.

## Do's and Don'ts

### Do

- Preserve 100px condensed poster type and a much smaller 16px explanatory voice on desktop.
- Keep the ordinary opening centered and narrow, with a single 316px-wide conversion key.
- Use 2px button corners and 3px–4px inner media corners to maintain the tool-like character.
- Let #e50000 punctuate chapter numbers, actions and the giant closing phrase against near-black.
- Keep 1px warm-gray outlines around dark product stages rather than separating everything with shadows.
- Alternate major 264px pauses with tightly composed task panels and 10px utility gaps.
- Use 36px insets and hairline divisions for editorial testimonial cells.
- Include the grainy footer and repeating 152px red mission statement on every page type.

### Don't

- Do not use white as the ordinary page canvas; bright native review images belong to the scoped proof wall.
- Do not turn every section into a different saturated color band; the ordinary canvas remains #0e0e0e.
- Do not round conversion actions into pills or use 12px card corners as the default.
- Do not add luminous purple or cyan gradients to the workflow scenes; the light is dim and warm-neutral.
- Do not substitute a broad geometric display sans for the condensed headline face; it destroys the compact poster silhouette.
- Do not add floating-card drop shadows where a 1px edge already separates the layers.
- Do not enlarge paragraphs to compete with the headings; maintain the 16px prose scale.
- Do not apply the 10px tinted directory-card shape to ordinary capability chapters.
- Do not reduce the footer to a small copyright row; its oversized red typography is a major identity device.

## Motion and responsive

### Motion

**Observed:**

- Footer phrases occupy a translated repeating horizontal strip.
- The compact header action appears muted at entry and signal red in later scroll views.
- Footer links declare a hover color change from taupe to cream.

**Transfer:**

- Keep the repeating word strip visually continuous if animated, while preserving the clipped composition when static.
- Preserve the strong primary-action hierarchy independently of any scroll-linked change.

**Unknown:**

- Ticker timing and easing, scroll-trigger implementations and focus-visible treatments are not established.

### Responsive

**Observed:**

- Width breakpoints are declared near 800px, 810px, 1024px and 1200px.

**Transfer:**

- On narrower screens, retain the narrow stacked poster silhouette and scale its line lengths to the available width.
- Stack the chapter rail above its stage, keeping number, title and supporting task list together instead of squeezing two columns.
- Reduce proof-grid columns while preserving native review image aspect ratios and the clipped giant footer strip.

**Unknown:**

- Exact mobile typography, navigation collapse behavior and breakpoint-specific gutters are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
