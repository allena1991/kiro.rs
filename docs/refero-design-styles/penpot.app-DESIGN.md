# Penpot — playful systems at scale

## Overview

A light, approachable software style with oversized humanist grotesk headlines, deep violet ink and small bursts of turquoise and pink. Airy editorial sections alternate with vivid interface collages, softly glowing cards and occasional dark violet chapters. It suits collaborative tools and complex products that want to feel capable without becoming corporate or austere.

### Essentials

- Headlines emphasize a phrase rather than shouting in bold: Work Sans 72px/1 at weight 400 with an embedded 500 phrase; section titles repeat the pairing at 54px/1.2.
- The opening is a left-aligned verbal promise, not a giant floating device: a 900px headline and support column inside a 1200px container, paired turquoise and outlined actions, with the next centered chapter and the tops of image cards entering the first 900px.
- Color behaves like light around practical content: #fafafa dominates, violet and mint radial washes use 0.13–0.14 alpha, #14ceca marks actions, and #f23ae5 marks a selected edge or small expressive detail. Full dark #151035 bands provide deliberate chapter changes and the ending.
- Buttons stay modest and tool-like: 16px/24px medium labels, 12px 20px padding, 8px corners, a 48px filled primary beside a 50px outlined secondary.
- Product proof is an edited collage rather than a generic dashboard: real interface fragments, large pointer arrows and lavender or violet backing in 10px rounded frames; use a legible reconstruction of the new product’s main task if finished product media is unavailable.
- Human warmth interrupts the system: include a flat pink-and-violet illustration with turquoise sparkles and a heartfelt proof treatment with magenta heart speech bubbles, 15px cards and a soft pink shadow. A simple original hand-and-tool drawing and a genuine attributed customer quote are sufficient equivalents.
- The closing changes scale from open editorial space to a useful directory: a pale blue illustrated signup band leads toward a full-width violet footer with 130px top padding, compact link groups and a ruled social/legal baseline.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action turquoise | `#14ceca` | `--color-turquoise` | action, accent, border | Primary buttons, diagram details and dotted problem frames. |
| Violet ink | `#151035` | `--color-ink` | text, background, border | Primary headline and body ink, outlined controls, dark chapters and footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric magenta | `#f23ae5` | `--color-magenta` | accent, border, text | Highlighted card edge, heart motifs and small badges; not a page-wide fill. |
| Soft pink | `#ff8cf4` | `--color-pink` | accent, surface | Illustration fills and the enterprise pricing identity. |
| Lavender | `#c8a2ff` | `--color-lavender` | accent, surface | Graphic backing and pricing tier identity. |
| Lavender atmosphere | `#f0e8f8` | `--color-lavender-wash` | background | Visible soft lavender light: rgba(172,115,232,0.13) over soft white. |
| Mint atmosphere | `#ddf5f4` | `--color-mint-wash` | background | Visible mint light: rgba(42,211,207,0.14) over soft white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Secondary ink | `#302c4d` | `--color-muted-ink` | text | Consent and accordion text; violet ink at 0.88 alpha over the pale canvas. |
| Black | `#000000` | `--color-black` | text | Some card and explanatory headings; violet ink remains the default. |
| Announcement edge | `#cfd2d5` | `--color-announcement-edge` | border | Fine outline around the compact announcement capsule. |
| Input edge | `#d9d9d9` | `--color-input-edge` | border | Fine neutral outline around email inputs and checkboxes. |
| Inverse edge | `#eeeeee` | `--color-inverse-edge` | text, border | Outlined actions within dark capability chapters. |
| Accordion tint | `#f5f5f6` | `--color-subtle-fill` | surface | Visible 2% violet ink over soft white for accordion rows. |
| Blue white | `#f5f8fb` | `--color-cool-canvas` | background, text | Newsletter bands and the positioning-page canvas; inverse supporting text. |
| Soft white | `#fafafa` | `--color-canvas` | background, surface, text, border | Default marketing canvas and cards; inverse text and footer rule. |
| Pure white | `#ffffff` | `--color-white` | surface, background, text | Inputs, comparison panel and plain explanatory bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Tier violet | `#2f226c` | `--color-deep-violet` | surface | Darkest tier badge and plan-header wash. |
| feature catalogues | Feature rule | `#d1d5db` | `--color-list-edge` | border | Thin horizontal rules in feature summaries. |
| pricing pages | Switch tray | `#dde3e9` | `--color-switch-fill` | surface | Hosting selector tray. |
| pricing pages | Table edge | `#e5e7eb` | `--color-table-edge` | border | Pricing comparison row separators. |

## Typography

- **Work Sans** — All marketing headings, paragraphs, actions and labels. Open, friendly grotesk with a broad readable lowercase; regular headlines accented by medium-weight phrases. Font stack: "Work Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Work Sans | 400 | 72px | 1 | normal | Default hero headline; use sentence case and an inline medium phrase. |
| display-emphasis | Work Sans | 500 | 72px | 1 | normal | Key phrase embedded in the hero, allowed to cross a line break. |
| heading | Work Sans | 400 | 54px | 1.2 | normal | Major centered section titles and the FAQ heading. |
| heading-emphasis | Work Sans | 500 | 54px | 1.2 | normal | Inline emphasis within major section titles and closing proof statements. |
| compact-heading | Work Sans | 500 | 54px | 1.1 | normal | Newsletter title and compact chapter titles. |
| feature-heading | Work Sans | 500 | 32px | 1.2 | normal | Alternating capability row titles and FAQ subheadings. |
| card-heading | Work Sans | 500 | 32px | 1.1 | normal | Image-card headings. |
| lead | Work Sans | 400 | 20px | 1.5 | normal | Hero support and capability paragraphs. |
| quote | Work Sans | 400 | 18px | 1.2 | normal | Compact testimonial text. |
| body-roomy | Work Sans | 400 | 18px | 1.5 | normal | Dark-chapter prose and positioning-page detail. |
| directory-heading | Work Sans | 700 | 18px | 1.5 | normal | Footer group headings. |
| body | Work Sans | 400 | 16px | 1.5 | normal | Card descriptions, questions, forms and compact details. |
| action | Work Sans | 500 | 16px | 1.5 | normal | Buttons, navigation and footer links. |
| text-link | Work Sans | 700 | 16px | 1.5 | normal | Short exploration links below feature descriptions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature catalogues | catalogue-display | Work Sans | 400 | 72px | 1 | -2px | Broad, multiline catalogue hero with inline 500-weight emphasis at the same tracking. |
| pricing pages | price | Work Sans | 400 | 52px | 1.5 | normal | Plan price numerals; leave unit and billing period on a smaller line. |
| feature catalogues | catalogue-heading | Work Sans | 400 | 48px | 1.1 | normal | Catalogue demonstration and learning-resource section titles. |
| dark capability chapters | dark-feature-heading | Work Sans | 600 | 32px | 1.2 | normal | Text-led feature titles inside violet chapters. |

**Notes:**

- Contrast within headlines comes from 400 versus 500 weight, not color, italics or all caps. Preserve a natural continuous reading order when emphasizing words.
- Default display tracking is normal; the -2px variant belongs to the catalogue opening rather than every title.
- Keep marketing text in Work Sans. Lettering embedded in illustrations and interface panels is not an additional marketing font.

## Layout

**Density:** Airy between narrative chapters, compact within cards, forms and the closing directory.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-label gaps, small wrapper insets and problem-card heading-to-copy gaps. |
| 12px | Image-card padding and button vertical padding. |
| 16px | Card content gaps and pricing-grid gutters. |
| 20px | Hero action gap, feature heading-to-copy gap and narrow section side padding. |
| 24px | Card grid gutters and paragraph-to-link spacing. |
| 28px | Hero heading-to-support spacing and dark heading-to-copy spacing. |
| 32px | Panel insets and section-title-to-support spacing. |
| 48px | Larger subsection separation. |
| 63px | Testimonial card vertical padding. |
| 64px | Dark chapter row gaps and broad explanatory section insets. |
| 68px | Centered card and testimonial chapter vertical padding. |
| 80px | Split-feature column gap and newsletter band vertical padding. |
| 100px | Logo-proof and closing proof band vertical padding. |
| 130px | Footer top padding. |

### Containers and grids

- **Main container**: max width 1200px · side padding 20px. Centered desktop framework for the hero, split rows, signup and footer.
- **Hero text**: max width 900px. Left-aligned hero heading and support occupy about three quarters of the main container, leaving a calm right margin.
- **Chapter heading**: max width 800px. Centered major chapter titles and supporting lines.
- **Wide card stage**: max width 1248px · 3 columns · gap 24px · side padding 24px. Three image-led capability cards beneath a centered headline.
- **Split feature**: max width 1200px · 2 columns · gap 80px · side padding 8px. Balanced text and media columns, each about 552px, reversing the media side between rows.
- **FAQ column**: max width 1000px · side padding 32px. A narrower left-aligned editorial question-and-answer area; nested rows span 920px.
- **Plan grid** (only for pricing pages): max width 1200px · 4 columns · gap 16px. Four plans aligned at the bottom, with the featured plan slightly taller.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and accordion | 8px |
|  | Image cards and media | 10px |
|  | Testimonial cards | 15px |
|  | Wide panels and resource cards | 20px |
|  | Navigation shell | 50px |
|  | Email input | 6px |
| pricing pages | Plan badges | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Image card halo | `0px 0px 10px 10px rgba(21,16,53,0.04)` | Soft edge separation for small capability cards. |
| Panel lift | `0px 4px 16px 0px rgba(21,16,53,0.06)` | Wide capability and learning-resource panels. |
| Heart glow | `0px 4px 10px 2px rgba(242,58,229,0.11)` | Testimonial cards. |
| Media violet glow | `0px 4px 16px 0px rgba(113,0,255,0.46)` | A selected vivid product image, balanced by quieter mint-glow media elsewhere. |

### Surfaces

#### Canvas · level 0

**Use:** Default light marketing background.

**CSS:** `background-color: #fafafa`

**Observed:** Broad uninterrupted fields let headings and edited product scenes carry the page.

**Transfer:** Keep most of the page light; reserve solid violet for an intentional chapter and the footer.

#### Lavender atmosphere · level 0

**Use:** Opening background extending into the first capability chapter.

**CSS:** `background-color: #fafafa; background-image: radial-gradient(40% 21% at 50% 0%, rgba(172,115,232,0.13) 0%, #fafafa 100%)`

**Observed:** A very pale central lavender light, not a sharp color block.

**Transfer:** Use a tall background layer so the light fades gradually through the opening and next chapter.

#### Mint atmosphere · level 0

**Use:** Backing for deeper product explanations.

**CSS:** `background-image: radial-gradient(49% 71% at 50% 98%, rgba(42,211,207,0.14) 0%, #fafafa 100%)`

**Observed:** Mint light gathers low in the chapter beneath near-white panels.

**Transfer:** Let the glow sit behind content rather than tinting text or every card.

#### Soft panel · level 1

**Use:** Wide capability rows and learning resources.

**CSS:** `background-color: #fafafa; border-radius: 20px; box-shadow: 0px 4px 16px 0px rgba(21,16,53,0.06)`

**Observed:** A near-white raised surface barely separates from its background.

**Transfer:** Use shallow elevation rather than a hard grey border.

#### Violet chapter · level 0

**Use:** Detailed capability chapter and directory ending.

**CSS:** `background-color: #151035; color: #fafafa`

**Observed:** Full-width, opaque, flat violet; no starfield or dramatic lighting.

**Transfer:** Use to signal a substantial narrative shift, not as the default page theme.

#### Newsletter band · level 0

**Use:** Illustrated signup near the end.

**CSS:** `background-color: #f5f8fb; padding: 80px 20px`

**Observed:** Pale blue, open two-column composition with no enclosing card border.

**Transfer:** Pair a short form with original flat illustration.

#### Accordion tint · level 1

**Use:** Compact expandable explanation rows.

**CSS:** `background-color: rgba(21,16,53,0.02); border-radius: 8px`

**Observed:** Rows form a quiet stack with very little separation.

**Transfer:** Keep the tint subordinate to the text and chevron.

#### Plan header wash · level 1

**Only for:** pricing pages

**Use:** Color-coded upper portion of a plan.

**CSS:** `background-image: radial-gradient(100% 97% at 0% 3%, rgba(20,206,202,0.41) 0%, #fafafa 100%); border-radius: 10px; padding: 8px`

**Observed:** Turquoise, violet, pink and deep-violet washes distinguish tiers; each fades to near-white before the detailed prose.

**Transfer:** Assign colors to meaningful tiers, not every sentence or feature.

## Components

### Navigation

**Use:** Persistent site orientation and conversion actions.

**CSS:** `background-color: #fafafa; border-radius: 50px; backdrop-filter: blur(5px); max-width: 1400px; height: 80px; padding: 8px 32px; display: flex; align-items: center; gap: 24px`

**Text style:** `action` — Work Sans 500 · 16px/1.5

**Observed:** Sticky full-width light header holds a brand mark on the left, grouped dropdown labels, then login, outlined signup and turquoise sales action on the right. The rounded inner shell blends into the similarly light outer header.

### Primary button

**Use:** Main conversion and signup actions.

**CSS:** `background-color: #14ceca; color: #151035; border-radius: 8px; padding: 12px 20px; display: inline-flex; align-items: center; justify-content: center; gap: 8px; min-height: 48px`

**Text style:** `action` — Work Sans 500 · 16px/1.5

**Observed:** Text-only, content-width control; appears first in hero action pairs and beneath the newsletter consent line.

### Secondary button

**Use:** Sales contact and deeper proof beside the primary action.

**CSS:** `background: none; color: #151035; border: 1px solid #151035; border-radius: 8px; padding: 12px 20px; min-height: 50px; display: inline-flex; justify-content: center; align-items: center`

**Text style:** `action` — Work Sans 500 · 16px/1.5

**Observed:** Unfilled companion action. Within violet chapters it switches to light grey text and border; geometry remains unchanged.

### Explore link

**Use:** Compact contextual navigation under a card or explanation.

**CSS:** `color: #151035; font-weight: 700; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `text-link` — Work Sans 700 · 16px/1.5

**Observed:** Image cards use a thin right arrow after the label; deeper explanation rows use an underlined text link instead of a separate button.

### Capability card

**Use:** Small image-led summaries of major product capabilities.

**CSS:** `background-color: #fafafa; border-radius: 10px; box-shadow: 0px 0px 10px 10px rgba(21,16,53,0.04); padding: 12px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — Work Sans 500 · 32px/1.1

**Observed:** Landscape product collage above title, compact body and Explore link. Three cards sit side by side. One highlighted card has a 2px magenta outline without a dark fill.

**Transfer:** Keep one meaningful capability per card, and show the action it enables rather than a decorative abstract icon.

### Heart testimonial

**Use:** Human social proof between technical sections.

**CSS:** `background-color: #fafafa; border-radius: 15px; box-shadow: 0px 4px 10px 2px rgba(242,58,229,0.11); padding: 63px 32px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `quote` — Work Sans 400 · 18px/1.2

**Observed:** A magenta heart in a small outlined speech balloon overlaps the upper-right edge. Quote sits above a small circular portrait, name and colored handle. Cards can have unequal heights; paired cards or a staggered grid preserve the conversational feel.

### Accordion row

**Use:** Explanatory lists and frequently asked questions.

**CSS:** `background-color: rgba(21,16,53,0.02); border-radius: 8px; padding: 12px 16px; min-height: 48px; color: rgba(21,16,53,0.88)`

**Text style:** `body` — Work Sans 400 · 16px/1.5

**Observed:** Small right-pointing chevron precedes the label, not a plus icon at the far right. Long questions wrap to a taller row. Pricing questions use a plain white variant.

### Email field

**Use:** Single-field newsletter form.

**CSS:** `background-color: #ffffff; border: 1px solid #d9d9d9; border-radius: 6px; padding: 3px 11px; width: 455px; height: 40px; max-width: 100%`

**Text style:** `body` — Work Sans 400 · 16px/1.5

**Observed:** Visible Email label with required marker above; small checkbox and two-line consent below; primary action on its own next line.

### Footer directory

**Use:** Final navigation and community links.

**CSS:** `background-color: #151035; color: #fafafa; padding-top: 130px; display: flex; flex-direction: column; align-items: center`

**Text style:** `action` — Work Sans 500 · 16px/1.5

**Observed:** A brand column plus three vertical directory columns inside 1200px. Multiple named groups stack within each column. Group titles use directory-heading, links have 10px vertical gaps. A full-width thin light rule precedes small ownership text on the left and a compact social/proof strip on the right.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial tiers without making the page feel like a spreadsheet.

**CSS:** `background-color: #fafafa; border-radius: 20px; box-shadow: 0px 0px 10px 2px rgba(229,231,235,0.65); padding: 16px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `price` — Work Sans 400 · 52px/1.5

**Observed:** A washed header holds a small icon and pill badge, price, billing unit and action; detailed prose and secondary contact links follow. Four plans sit in a 16px-gutter row. The featured plan is taller, outlined by pink light and uses a pink badge; turquoise and outlined actions are mixed according to tier.

### Dotted problem card

**Only for:** positioning and problem-solution pages

**Use:** Frame a reader frustration before explaining the solution.

**CSS:** `border: 5px dotted #14ceca; border-radius: 10px; padding: 16px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 8px`

**Text style:** `body-roomy` — Work Sans 400 · 18px/1.5

**Observed:** A roughly 600px text box pairs with a much smaller line illustration outside it. Heading and support are centered; boxes and illustrations alternate sides down the page.

## Imagery and graphics

### Edited product scenes

**Use:** Main proof throughout capability cards and alternating feature rows.

**Observed:** Dark editor chrome and light working canvases are combined with saturated lavender, turquoise or pink project content. Scenes are flat front-facing compositions, often with floating panels, visible selection boxes and oversized pointer arrows. Typical split-row media is 552px wide; image cards use about 362×204px scenes.

**Transfer:** Show the new product’s actual core task. Combine one primary screen with one enlarged useful detail, rather than shrinking a whole dashboard into illegibility. Minimum equivalent: a faithful static reconstruction with realistic content and two legible controls.

**Build:** Place a front-facing interface in a 10px rounded frame. Back one portion with a lavender rectangle; float a smaller dark inspector or light properties panel over an edge. Add a white triangular SVG cursor with violet or turquoise outline and a short pink selection rectangle. Use a soft mint shadow for most scenes and a violet glow for one focal scene.

### Pastel light fields

**Use:** Signature atmospheric backing for the opening and capability chapters.

**Observed:** Pale lavender radiates behind the opening text and first cards; pale mint pools below deeper panels. The light is broad and barely visible at its edge, preserving a near-white page.

**Transfer:** Include this soft-light device even when there is no finished product imagery; it supplies color without turning the page into a gradient poster.

**Build:** Use the Lavender atmosphere and Mint atmosphere surfaces as background layers spanning multiple content blocks. Keep center opacity near 0.13–0.14 and fade to soft white. Match the soft glow; exact stops are not essential.

### Flat hand-drawn helper

**Use:** Newsletter closing illustration and small human accents.

**Observed:** An irregular pink character and hand hold three violet pencils, with thin violet facial lines, turquoise nails and two turquoise four-point sparkles. It occupies roughly 409×395px opposite the form; no photo texture, dimensional shading or enclosing frame.

**Transfer:** Create an original friendly hand-and-tool metaphor related to the new product. A simpler hand, a useful tool and two sparkles are the minimum version; keep the drawing bold, flat and slightly eccentric.

**Build:** Draw an asymmetric pink SVG silhouette with curved lobes, add sparse dark-violet 2–3px strokes for expression and hand contours, and overlap three narrow violet tool shapes at a diagonal. Put one filled and one outline turquoise four-point star above-left. Leave ample transparent space.

### Heart speech marker

**Use:** Signature motif on testimonial cards.

**Observed:** Small white speech balloons with pale magenta outlines contain a solid magenta heart, overlapping the top edge near the right corner. Portrait circles repeat the magenta accent.

**Transfer:** Keep a heartfelt, handmade proof cue even when portraits are unavailable; initials in a circle can replace the portrait.

**Build:** Create an approximately 60×64px transparent SVG. Draw a rounded speech rectangle with a small lower-right tail, a fine pink outline and soft-white fill; center a magenta heart inside. Position it above the card edge, with a separate small circular portrait below the quote.

### Resource posters

**Only for:** learning and resource catalogues

**Use:** Image tiles that make help and education feel creative.

**Observed:** Violet-backed landscape posters mix interface previews with thin outlined hands, selection frames, pointer arrows, turquoise squiggles and magenta sparkles. A white caption strip sits immediately below each poster.

**Transfer:** Give each resource a distinct visual cue while retaining the shared violet stage and concise caption.

**Build:** Use a deep-violet rectangular background, one legible central preview or title, a thin turquoise looping path and a magenta selection frame with tiny square handles. Add one white pointer and sparse four-point stars. Clip to the resource card’s 20px upper corners.

### Monochrome organization strip

**Only for:** organization proof sections

**Use:** A broad trust band after a centered statement.

**Observed:** Small organization marks render in violet ink across a full-width horizontal line, separated by dots, with an outlined proof action below.

**Transfer:** Use authorized partner or customer marks at comparable visual height; do not substitute meaningless dot strings for the marks.

### Icons

**Observed:** Small navigation chevrons are 16×16px violet outlines with 2px round strokes. Accordion arrows are 14px. Inline exploration arrows are thin and unobtrusive. Larger editorial illustrations use expressive line art rather than a generic filled icon set.

**Transfer:** Use simple rounded-stroke chevrons and arrows for UI; keep decorative hand-drawn symbols separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Verbal promise opening

**Observed:** The light 80px sticky Navigation sits above a centered slim announcement capsule. A broad lavender light is behind a left-aligned hero within Main container. The 72px display wraps to two lines in a 900px column with its important phrase at weight 500, not on a separate colored label. Lead copy follows about 28px below in three readable lines; Primary button and Secondary button sit together after about 30px, separated by 20px. The opening occupies about 604px of document height. Within the first 900px, the full headline, support and actions are visible, followed by a centered 54px chapter title and the top portions of three Capability cards. There is no main hero object beside the heading: the image-card row is the first object stage, with its lower text continuing below the fold.

**Transfer:** Use a crisp promise with one emphasized phrase and put original product-task scenes in the first card stage. If product media is unavailable, reconstruct three real task details rather than adding an unrelated hero image. Pricing opens with a centered 72px title, short support and hosting switch before plan cards. A feature catalogue uses a broader three-line heading, mint atmosphere, one action and category tabs. A positioning page retains the left text composition and introduces a demonstration below.

**Avoid:** Do not replace this with centered giant type over a full-bleed illustration, a right-hand 3D device, or a hero so tall that no next chapter appears within 900px.

**Text style:** `display` — Work Sans 400 · 72px/1

### Mixed-weight chapter heading

**Observed:** Centered heading at 54px/1.2, usually constrained near 800px, combines regular and medium phrases in one sentence. Optional 20px/30px support follows after 32px. No routine all-caps eyebrow or numeric chapter label.

**Transfer:** Name the next benefit or question directly, emphasizing only the decisive phrase.

**Text style:** `heading` — Work Sans 400 · 54px/1.2

### Three capability cards

**Observed:** Wide card stage holds three Capability cards with 24px gaps under a centered chapter heading. Landscape imagery comes first, followed by 32px title, 16px body and Explore link; a single card can carry the magenta outline.

**Transfer:** Compare three distinct capabilities using equivalent image scale and concise descriptions; emphasize a genuinely new or important capability.

### Alternating product explanation

**Observed:** Split feature pairs 552px media with a similarly wide text column, 80px apart. Feature-heading sits above Lead copy with 20px separation. Media changes sides between rows. A deeper variant puts cropped interface collages into Soft panels with 16px insets and an Explore link beneath the prose.

**Transfer:** Alternate outcome and concrete demonstration without forcing every row into a raised card.

### Heartfelt proof

**Observed:** A mixed-weight centered title introduces paired Heart testimonial cards. Magenta speech markers rise above the cards; portraits and handles sit below the quotes. An outlined proof action sits centered below the group.

**Transfer:** Use authentic concise quotes with attribution. Retain the heart marker and pink glow even with a single strong quote.

### Violet capability chapter

**Observed:** Violet chapter spans the viewport with about 70px top and 75px bottom padding. A centered 54px title leads to two columns of text-led capabilities separated by 80px, with 64px between rows. Titles are 32px/1.2 weight 600, prose 18px/27px and actions use the light outlined Secondary button variant.

**Transfer:** Use for a deeper explanation or operational chapter. On a positioning page, the alternative is a vertical stack of large near-white product panels glowing lightly against violet.

### Explanatory FAQ

**Observed:** FAQ column presents a 54px mixed-weight title, 32px subquestions, compact explanatory paragraphs and stacks of Accordion rows. Pricing uses categorized plain-white questions; a positioning page uses a narrower question-only stack.

**Transfer:** Treat FAQs as helpful explanation rather than a full-width wall of heavy bordered cards.

### Plan comparison

**Observed:** Centered promise and hosting switch lead into the Plan grid. Color-coded Plan cards precede a three-benefit reassurance row and a white 20px-radius comparison panel. Table rows use thin neutral rules, bold left labels and turquoise check or magenta cross marks; plan names sit in colored pills.

**Transfer:** Separate purchase decisions, shared value and detailed differences. Keep units and billing qualifiers explicit; let the number remain the dominant type.

### Learning resources

**Observed:** Catalogue-heading and centered Lead introduce Resource posters in a three-card first row with a centered two-card second row. Cards use Soft panel treatment and short caption strips; a quieter row of text resources follows.

**Transfer:** Use an inviting collection of practical next steps rather than another sales grid.

### Illustrated signup and directory ending

**Observed:** Newsletter band is roughly 625px tall: a compact-heading and Lead line above the Email field on the left, Flat hand-drawn helper on the right. Consent and Primary button stay beneath the field. The default ending moves directly into Footer directory. Catalogue and positioning variants insert a 500px pale pink proof band between signup and footer, pairing a large statement and outlined action with a compact graphic. Pricing includes an organization-proof strip before signup. All endings finish with the same violet directory, thin baseline rule, legal line and social marks.

**Transfer:** Preserve the personable illustration and useful dark ending. Adapt the signup purpose and directory depth to the new product rather than appending an unrelated giant sales slogan.

## Page flow

**Storyline:** Promise → compact capability map → concrete demonstrations → human proof → deeper operational detail → objection handling → illustrated relationship action → useful directory.

### Explain a flagship product capability in depth

1. **Promise** — Left-aligned mixed-weight hero with two actions and lavender light.
2. **Capability map** — Centered statement and three image-first cards.
3. **Product demonstration** — Alternating media and text rows.
4. **Social proof** — Paired heart-marked testimonials.
5. **Capability chapters** — Wide soft panels, followed by a text-led violet chapter.
6. **Objection handling** — Explanatory questions and compact expandable lists.
7. **Closing action** — Illustrated newsletter band, then violet directory.

**Transfer:** Make this the default landing-page language; adjust the number and order of explanations to the product’s complexity.

### Help readers choose an appropriate commercial plan

1. **Promise** — Centered headline and support above a hosting switch.
2. **Pricing** — Four washed plan cards with a slightly taller highlighted tier.
3. **Value reassurance** — Three shared-benefit illustrations and a detailed comparison matrix.
4. **Objection handling** — Categorized FAQ rows on white.
5. **Social proof** — Centered statement and monochrome organization strip.
6. **Closing action** — Illustrated signup followed directly by the shared footer.

**Transfer:** Emphasize transparent units and shared value before long detail; keep the same friendly light palette.

### Make a broad feature set discoverable

1. **Promise** — Mint-backed multiline hero, small announcement and one action.
2. **Orientation** — Six horizontal category tabs with a thin active underline.
3. **Product demonstration** — Large front-facing interface collage.
4. **Capability detail** — Two-column summaries, then a compact three-column text-link index.
5. **Onboarding** — Violet resource posters and quieter supporting links.
6. **Closing action** — Illustrated signup, pale pink proof band and violet footer.

**Transfer:** Use tabs and a link index when readers need breadth rather than a single narrative argument.

### Explain product differentiation and reduce organizational concerns

1. **Promise** — Left-aligned hero with plan and sales actions, then a demonstration.
2. **Problem framing** — Alternating dotted turquoise boxes and line illustrations.
3. **Benefit explanation** — Pale-blue alternating rows with product and conceptual scenes.
4. **Social proof** — Organization strip.
5. **Capability chapters** — Large near-white product panels inside a violet chapter, followed by a plain control-and-deployment explanation.
6. **Human proof** — A staggered grid of heart testimonials.
7. **Objection handling** — Compact FAQ stack.
8. **Closing action** — Illustrated signup, pale pink proof band and shared footer.

**Transfer:** Use the dotted problem device and organizational explanation only when the new offer warrants a longer positioning story.

## Writing

Friendly, confident and practically enthusiastic. Technical detail is translated into benefits for people working together, with occasional conversational warmth rather than formal enterprise language.

**Do not copy:** Do not reuse Penpot names, logos, proprietary illustrations, customer identities, quotations, prices, adoption numbers, competitor comparisons or exclusivity claims. Create original assets and use only claims and proof true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your team; use we sparingly for the maker. Name the product in explanatory prose, but keep action labels direct.
- **Rhythm:** Headlines are short sentence fragments with an emphasized noun phrase. Support paragraphs usually contain one or two direct sentences; longer explanations name concrete mechanisms. Actions are short verbs, and occasional exclamation marks belong to community invitations rather than every claim.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An outcome-led phrase that embeds the capability name within the promise. | 5–12 words | “Seamless Design Systems for scaling UI”<br>“Transparent pricing” |
| Section headline | A simple assertion with a strong central phrase emphasized typographically. | 5–11 words | “A single source of truth for Product teams” |
| Feature title | Name a capability, then state the practical improvement. | 2–10 words | “Variants: smarter, cleaner and closer to code”<br>“Devs feel at home” |
| Supporting copy | Begin with the reader’s task, then explain how the feature helps. | 20–45 words | “Keep your designs consistent while scaling them across your organization. [Brand] helps designers, developers, and other stakeholders collaborate seamlessly, even on the most complex projects.” |
| Primary action | Plain verb and low-friction next step. | 2–5 words | “Try [Brand] for free”<br>“Talk to us”<br>“Find your plan” |
| Relationship action | Warm familiar invitation followed by a useful description. | 3–7 words | “Stay in the loop”<br>“Receive product and Community updates!” |

**Words and phrasing to use:** together; your team; build; reuse; scale; flexibility; control; consistent; get started; talk to us

**Avoid:** synergy; disruptive ecosystem; unlock unparalleled potential; military-grade; frictionless everything; vague superlatives without a mechanism

**Rules:**

- Tie each benefit to a concrete product mechanism or task.
- Use questions to acknowledge practical concerns, not to manufacture fear.
- Prefer a useful short title and one paragraph over stacked slogans.
- Keep technical nouns when they help informed buyers understand the product; explain what they change for the reader.

## Do's and Don'ts

### Do

- Set hero text in Work Sans 72px/1 and emphasize only selected words at 500.
- Keep ordinary section titles at 54px/1.2 with normal tracking.
- Leave a visible next-chapter teaser within the first 900px.
- Use 8px button corners and 12px 20px padding for both filled and outlined actions.
- Keep the 80px split-row gap and balanced text/media proportions on desktop.
- Use near-white cards with shallow violet or pink shadows rather than strong grey outlines.
- Give product images enough scale for the main task and one key panel to remain readable.
- Finish with the pale illustrated relationship band and the solid violet directory.

### Don't

- Do not make all headings weight 700; reserve that weight for compact links and directory labels.
- Do not apply the catalogue’s -2px headline tracking to the default landing-page titles.
- Do not turn turquoise into the site-wide background; it is primarily an action and detail color.
- Do not make every content block a magenta-outlined card; a single emphasized edge is more characteristic.
- Do not round action buttons into capsules; pills belong to announcements and small tier badges.
- Do not style the footer as a short black copyright bar; it is a substantial violet navigation area.
- Do not add glossy bevels or photorealistic 3D to the flat helper illustration.
- Do not use large drop shadows on every card; the panel lift is only 4px with 0.06-alpha violet.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary buttons declare background transitions of 0.1s; input transitions declare 0.2s.
- Organization-proof sections have left/right marquee animation declarations; a settled frame does not establish speed.
- Some other links and surfaces declare all 1s ease and all 0.2s ease transitions.

**Transfer:**

- Keep conversion-control feedback quick and subtle; reserve continuous horizontal movement for an organization-proof strip.

**Unknown:**

- Resolved hover color tokens and focus-visible appearance were not established.
- Entrance choreography and marquee speed are unknown.

### Responsive

**Observed:**

- Styles declare width boundaries including 500px, 575px, 576px, 767px, 768px, 991px, 992px, 1024px, 1199px, 1200px, 1600px and 1920px.

**Transfer:**

- On narrow screens, preserve the mixed-weight headline, then support and actions before the product proof; reduce type until the promise wraps naturally.
- Stack alternating media/text rows and the illustrated signup; preserve media legibility rather than shrinking full interfaces.
- Allow comparison data and category navigation to retain their reading order when adapted to narrow layouts.

**Unknown:**

- Only the desktop arrangement is established; mobile typography sizes, menu behavior and exact stacking breakpoints are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
