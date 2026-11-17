# Sanity — editorial meets machinery

## Overview

A technical platform presented with the scale and image-making of a fashion editorial. Near-black and white chapters alternate with hot orange signals, tightly set regular grotesk headlines, and small monospace labels. Layered interfaces, photographic fragments, dot fields and data diagrams make the product feel both programmable and expressive; spacious storytelling gives way to dense, orderly specification grids.

### Essentials

- Headlines feel like oversized interface labels rather than advertising lettering: regular 400 grotesk, 112px/1 with -0.04em tracking for the main promise, 72px/1 for major chapters and 48px/1.075 for section leads.
- The default opening is an immersive dark data stage: left-aligned white copy overlays a photographic-to-pixel composition, followed by three 55px pill actions and a 72px orange proof ticker visible at the foot of the first screen.
- Controls form a scale ladder of capsules: 35px uppercase mono utilities, 55px sentence-case hero actions and 140px closing pills with 60px text. Keep all three levels distinct.
- Color behaves like a signal inside a monochrome system: white and #0b0b0b carry most of the page; orange fills actions, a narrow proof ribbon and an occasional demonstration panel, not every section.
- Interfaces are editorial objects: overlap light and dark windows over soft gray, black and orange blurred forms; combine them with fine grids, dot fields and tiny technical annotations. Without finished product media, compose one credible workflow window and a simple data diagram instead.
- Technical ornament is structural: an 8px dot lattice, fine rules, numbered chapter tabs and compact monospace captions give otherwise expansive layouts their engineered character.
- End with contrasting scales: a strong conversion gesture above a deep black directory footer, then a centered white identity surrounded by generous black space and a tiny utility row.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5500` | `--color-signal` | accent, action, background | Primary actions, proof ticker and isolated interactive demonstration panels; authored as display-p3 orange. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-paper` | background, text, surface | Light editorial canvas, reversed text and foreground interface windows. |
| Soft gray | `#ededed` | `--color-soft` | surface, border | Metadata sidebars, subdued actions and light panel backing. |
| Light edge | `#d6d6d6` | `--color-edge` | border | Fine outlines around light media panels and interface windows. |
| Reversed secondary | `#b9b9b9` | `--color-dim` | text | Secondary text and social icons on dark surfaces. |
| Faint annotation | `#797979` | `--color-faint` | text | Directory headings, understated metadata and annotations. |
| Secondary ink | `#4a4a4a` | `--color-secondary` | text | Small supporting text on light surfaces. |
| Dark edge | `#353535` | `--color-dark-edge` | border | Dark panel outlines, newsletter input and theme-control edge. |
| Charcoal | `#212121` | `--color-charcoal` | surface, border, text | Inset dark controls and low-contrast internal panel edges. |
| Near black | `#0b0b0b` | `--color-ink` | text, background, action | Primary ink on white; immersive chapter and footer canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer stories | Editorial blue | `#027fff` | `--color-quote-blue` | border, link | Blue quotation rule; authored in display-p3. |

## Typography

- **Waldenburg-75357948a2b6a39b** — Headlines, body text and the largest conversion actions. Neutral contemporary grotesk with compact proportions and tightly joined headline word shapes; regular rather than bold. OpenType features: "cv01", "cv11", "cv12", "cv13", "ss07". If unavailable, use **Inter**. Use 400 and 425 with the same negative tracking; preserve line breaks by width rather than extra weight. Font stack: "Waldenburg-75357948a2b6a39b", "Inter", Arial, ui-sans-serif, system-ui, sans-serif.
- **IBM Plex Mono-c20ba633a65a8c57** — Navigation, labels, numbered chapters, captions, footer links and commands. Matter-of-fact technical monospace; usually regular and untracked. Font stack: "IBM Plex Mono-c20ba633a65a8c57", Courier New, ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Waldenburg-75357948a2b6a39b | 400 | 112px | 1 | -0.04em | Default immersive opening promise, balanced into two lines. |
| chapter | Waldenburg-75357948a2b6a39b | 400 | 72px | 1 | -0.04em | Major chapter statements and the centered conversion heading. |
| closing-action | Waldenburg-75357948a2b6a39b | 400 | 60px | 0.8 | normal, capitalize, features "calt" 0 | Monumental paired conversion pills. |
| heading | Waldenburg-75357948a2b6a39b | 400 | 48px | 1.075 | -0.035em | Section leads in paired heading/support arrangements. |
| subheading | Waldenburg-75357948a2b6a39b | 400 | 38px | 1.1 | -0.03em | Capability chapter titles and prominent proof numbers. |
| hero-support | Waldenburg-75357948a2b6a39b | 425 | 32px | 1.1 | -0.01em, features "calt" 0 | Large support paragraph on the immersive opening. |
| footer-invitation | Waldenburg-75357948a2b6a39b | 425 | 32px | 1.2 | -0.01em, features "calt" 0 | Community and newsletter invitations above directory content. |
| card-heading | Waldenburg-75357948a2b6a39b | 400 | 24px | 1.1 | -0.01em | Feature titles and default hero button text. |
| lead | Waldenburg-75357948a2b6a39b | 425 | 24px | 1.2 | -0.01em, features "calt" 0 | Section supporting paragraphs. |
| body | Waldenburg-75357948a2b6a39b | 400 | 18px | 1.3 | -0.01em, features "calt" 0 | Explanatory paragraphs and story prose. |
| body-small | Waldenburg-75357948a2b6a39b | 400 | 15px | 1.3 | -0.01em, features "calt" 0 | Feature descriptions, plan inclusions and compact paragraphs. |
| label | IBM Plex Mono-c20ba633a65a8c57 | 400 | 13px | 1.3 | normal, uppercase, features "calt" 0 | Eyebrows, small actions, navigation and metric captions. |
| detail | IBM Plex Mono-c20ba633a65a8c57 | 400 | 13px | 1.5 | normal, features "calt" 0 | Media captions, attribution roles, directory and resource links. |
| micro | IBM Plex Mono-c20ba633a65a8c57 | 400 | 10px | 1.3 | normal, uppercase, features "calt" 0 | Footer group labels and bottom utilities. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| image-first product pages | product-name | Waldenburg-75357948a2b6a39b | 400 | 120px | 0.9 | -0.04em | Oversized product name beneath an image-first opening. |
| pricing, enterprise and customer-story pages | light-display | Waldenburg-75357948a2b6a39b | 400 | 60px | 1 | -0.04em | Light commercial and customer-story openings and their closing statements. |
| customer stories | article-heading | Waldenburg-75357948a2b6a39b | 400 | 30px | 1.1 | -0.02em | Problem, solution and results headings within long prose. |
| developer-facing landing pages | command | IBM Plex Mono-c20ba633a65a8c57 | 400 | 24px | 1.1 | -0.01em | Copyable command beside the opening actions. |
| detailed product catalogs | catalog-heading | Waldenburg-75357948a2b6a39b | 400 | 20px | 1.4 | -0.01em | Titles aligned near the bottom of square feature tiles. |

**Notes:**

- Use regular 400 headlines across sizes; scale and negative tracking do the work of hierarchy, not bold weight.
- Tracking tightens from -0.01em in body and component text to -0.04em in the largest headings. Monospace labels remain untracked, not widely letterspaced.
- Heading features differ from body text: body, detail and utility copy disable contextual alternates with "calt" 0.
- Keep type on a firm left edge except for dedicated centered pricing or conversion compositions.

## Layout

**Density:** Airy narrative chapters around dense technical exhibits; the control rhythm is compact while major transitions have 96px–128px of breathing room.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight grid gutters and internal control gaps. |
| 8px | Action groups, catalog gutters and small vertical groups. |
| 12px | Directory link rhythm and compact grid gaps. |
| 16px | Small supporting gaps and sidebar padding. |
| 24.2px | Declared content-padding and grouping token; distinct from the 24px page gutter. |
| 24px | Outer page gutter. |
| 32px | Paragraph group separation and large button horizontal padding. |
| 48px | Heading-to-media separation and supporting block gaps. |
| 64px | Large internal heading gaps. |
| 96px | Section top padding and separation of major conversion groups. |
| 128px | Deep chapter padding and bottom breathing room. |

### Containers and grids

- **wide stage**: max width 1392px · 12 columns · gap 4px · side padding 24px. Primary desktop scaffold at 1440px; imagery can break full bleed while text aligns to the gutter.
- **editorial inset**: max width 1159px · side padding 24px. Centered proof, article framing and the large closing action pair.
- **reading assembly**: max width 927px · 2 columns · gap 12px. Inset feature lists and FAQ; headings may sit on a wider outer rail.
- **chapter triptych**: 12 columns · gap 4px. Numbered navigation occupies about two columns, prose four and the media stage six; navigation and media persist while prose chapters change.
- **proof row**: 3 columns · gap 48px. Equal-width numbers with short mono captions on dark.
- **catalog grid** (only for detailed product catalogs): 4 columns · gap 8px. Square technical inventory tiles with a category tile at the start.
- **story reading column** (only for customer stories): max width 621px. Readable prose beside a 299px sticky metadata sidebar within the editorial inset.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | media panels | 0px |
| product demonstrations | interface windows | 12px |
| product demonstrations | inset fields | 3px |

## Surfaces and depth

### Surfaces

#### Light canvas · level 0

**Use:** Editorial capability chapters, conversion and commercial pages.

**CSS:** `background: #ffffff; color: #0b0b0b`

**Observed:** Broad unboxed fields; separators carry structure rather than raised cards.

**Transfer:** Keep prose and most feature grids directly on this canvas.

#### Dark stage · level 0

**Use:** Default opening, technical demonstrations, proof chapters and footer.

**CSS:** `background: #0b0b0b; color: #ffffff`

**Observed:** Nearly black, not navy; image layers merge into the background.

**Transfer:** Use large contiguous dark chapters rather than alternating small dark cards.

#### Dot field · level 0

**Use:** Chapter rails, diagram backing and grid edges.

**CSS:** `background-color: #ffffff; background-image: radial-gradient(#0b0b0b 0.8px, transparent 0.8px); background-size: 8px 8px`

**Observed:** Fine regular points contrast with soft photographic fields; sometimes inverted against black.

**Transfer:** Expose the lattice at panel margins and rails; keep reading copy on solid backing.

#### Signal band · level 0

**Use:** Proof ticker and isolated demonstration focus.

**CSS:** `background: #ff5500; color: #0b0b0b`

**Observed:** Flat color without shadows, gradients or rounded band edges.

**Transfer:** Make this a deliberate interruption of the neutral page.

#### Metadata panel · level 1

**Only for:** customer stories

**Use:** Compact factual sidebar.

**CSS:** `background: #ededed; padding: 16px`

**Observed:** Square-edged gray panel with mono labels, integration icons and application links.

**Transfer:** Use for sector, use case and implementation facts.

#### Interface window · level 1

**Only for:** product demonstrations

**Use:** Foreground application or code windows inside media scenes.

**CSS:** `background: #ffffff; border: 1px solid #d6d6d6; border-radius: 12px; overflow: hidden`

**Observed:** Light editor windows contrast with near-black code windows; toolbar and content are separated by hairlines.

**Transfer:** Show only enough authentic UI to make the workflow legible.

## Components

### Hero primary button

**Use:** Main opening conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ff5500; color: #0b0b0b; border: 1px solid #ff5500; border-radius: 9999px; padding: 8px 32px; min-height: 55px`

**Text style:** `card-heading` — Waldenburg-75357948a2b6a39b 400 · 24px/1.1 · tracking -0.01em

**Observed:** Sentence case distinguishes this from compact utility controls; sits first in an 8px-spaced row.

**States:** Declared: hover background and border #0b0b0b with orange text; focus-visible 2px dotted white outline with 2px offset; active restores orange fill and black text.

### Hero secondary button

**Use:** Demonstration or second path beside the primary.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #0b0b0b; border: 1px solid #ffffff; border-radius: 9999px; padding: 8px 32px; min-height: 55px`

**Text style:** `card-heading` — Waldenburg-75357948a2b6a39b 400 · 24px/1.1 · tracking -0.01em

**Observed:** White pill gives the second path equal physical presence without orange emphasis.

**States:** Declared: hover near-black fill, white border and text; focus-visible 2px dotted white outline with 2px offset; active restores white fill and dark text.

### Compact action

**Use:** Navigation and repeated conversion links.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ff5500; color: #0b0b0b; border: 1px solid #ff5500; border-radius: 9999px; padding: 4px 12px; height: 35px`

**Text style:** `label` — IBM Plex Mono-c20ba633a65a8c57 400 · 13px/1.3 · uppercase

**Observed:** Secondary variants use black fill with white text, or transparent fill with a black or white edge. Inset feature and enterprise calls also use 45px height with 8px 32px padding.

**States:** Declared: on the dark opening, hover white fill and border with orange text; focus-visible 2px dotted dark outline with 2px offset; active restores orange fill.

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: sticky; top: 0px; z-index: 200; display: flex; align-items: center; height: 67px; padding: 0px 24px; background: transparent`

**Text style:** `label` — IBM Plex Mono-c20ba633a65a8c57 400 · 13px/1.3 · uppercase

**Observed:** Identity mark at left, compact category links beside it, account and conversion utilities at right. White links over the opening turn to black links on a white header during the light chapters; a 36px black announcement strip sits above the opening header.

**Transfer:** Preserve the compressed utility scale rather than enlarging navigation to body size.

### Numbered chapter tab

**Use:** Index for long capability narratives.

**CSS:** `display: flex; align-items: flex-start; width: fit-content; background: #ffffff; color: #0b0b0b; padding: 4px 0px`

**Text style:** `label` — IBM Plex Mono-c20ba633a65a8c57 400 · 13px/1.3 · uppercase

**Observed:** Two-digit index precedes an uppercase label. The active index reverses white on a small black rectangle; a dot field extends down the rail below the tabs.

**States:** Declared: focus-visible 2px dotted dark outline with 2px offset.

### Newsletter input

**Use:** Email entry in the footer.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid #353535; border-radius: 9999px; padding: 0px 18px; width: 240px; height: 45px`

**Observed:** Paired with an outlined white Subscribe capsule, separated by 8px; community and newsletter invitations sit above it.

### Directory link

**Use:** Footer directory and technical resource lists.

**CSS:** `display: flex; align-items: center; color: #ffffff`

**Text style:** `detail` — IBM Plex Mono-c20ba633a65a8c57 400 · 13px/1.5

**Observed:** Links form compact vertical columns beneath faint micro labels; resource-list variants use dark text and an arrow.

**States:** Declared: hover underline with 0.1em offset and 0.08em thickness; focus-visible 2px dotted white outline with 2px offset.

### Monumental action

**Use:** High-impact closing conversion pair.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ff5500; color: #0b0b0b; border-radius: 9999px; padding: 24.2px; height: 140px`

**Text style:** `closing-action` — Waldenburg-75357948a2b6a39b 400 · 60px/0.8 · capitalize

**Observed:** Two near-equal wide capsules separated by 8px within the editorial inset; second is black with white type.

**States:** Declared: hover near-black fill and white text; focus-visible 2px dotted dark outline with 2px offset; active restores orange.

### Command capsule

**Only for:** developer-facing landing pages

**Use:** A direct executable entry point beside opening actions.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #ffffff; background: transparent; border: 1px solid #ffffff; border-radius: 9999px; padding: 8px 32px; height: 55px`

**Text style:** `command` — IBM Plex Mono-c20ba633a65a8c57 400 · 24px/1.1 · tracking -0.01em

**Observed:** Single-line command with a small overlapping-squares copy icon at the end; an inset 35px version belongs in the conversion toolkit.

**States:** Declared: hover white fill and dark text; focus-visible 2px dotted white outline with 2px offset.

### Ruled feature item

**Only for:** enterprise and detailed product pages

**Use:** Technical capability lists without card chrome.

**CSS:** `display: flex; flex-direction: column; gap: 24.2px; border-top: 1px solid #0b0b0b; padding: 24.2px 48px 24.2px 0px`

**Text style:** `card-heading` — Waldenburg-75357948a2b6a39b 400 · 24px/1.1 · tracking -0.01em

**Observed:** Heading followed by body-small description; arranged two across or as a single detailed list.

**Transfer:** Use a short capability name and concrete implementation detail.

### Editorial quotation

**Only for:** customer stories

**Use:** Voice-of-customer interruptions within prose.

**CSS:** `background: #ffffff; border-left: 4px solid #027fff; padding: 48px 96px; display: grid; gap: 24.2px`

**Text style:** `body` — Waldenburg-75357948a2b6a39b 400 · 18px/1.3 · tracking -0.01em

**Observed:** Monochrome customer identity above the quote, then a small circular grayscale headshot with mono attribution; text remains normal weight rather than oversized display.

**Transfer:** Place beside implementation detail, not in an ornamental testimonial carousel.

### FAQ row

**Only for:** pricing pages

**Use:** Dense objection handling after comparison content.

**CSS:** `display: flex; background: #ffffff; color: #0b0b0b; padding: 24.2px 0px`

**Text style:** `label` — IBM Plex Mono-c20ba633a65a8c57 400 · 13px/1.3 · uppercase

**Observed:** Full-width summary in a ruled details row about 66px tall; question left, bracketed plus at the far right. Expanded answer uses body-small, not uppercase mono.

**States:** Declared: focus-visible 2px dotted dark outline with 2px offset.

## Imagery and graphics

### Photograph to data stage

**Use:** Signature immersive opening and large capability art.

**Observed:** A low-lit close portrait dissolves into broad teal, gray and muted magenta square pixels. Fine numeric cells and skewed perspective outlines extend to the right against black; white copy sits in front, not inside a card.

**Transfer:** Translate a relevant product output into a photograph, a pixelated middle layer and a fine data lattice. Minimum acceptable version is a darkened product photograph with a stepped mosaic edge and one annotated grid.

**Build:** Place a darkened image across the middle of a black stage. Overlay an SVG lattice of 24px square cells with 1px rgba(255,255,255,0.18) strokes and tiny mono numerals. Along the image's right edge use irregular rectangular mosaic blocks sampled from the image, increasing from 16px to 48px; add two thin perspective quadrilaterals with small square handles. Keep the foreground text unobscured.

### Soft industrial media backing

**Use:** Signature backing for capability exhibits.

**Observed:** Gray and white curved forms with defocused black edges and intense orange-red patches support overlapping sharp white interface windows. The media occupies about half the width and nearly a viewport in tall chapters.

**Transfer:** Pair a crisp, honest workflow window with an abstract soft-focus backdrop; the abstract form supplies energy, not product meaning.

**Build:** Within a rectangular gray canvas, layer a rotated elongated black ellipse near the top and a signal-orange ellipse near the right or bottom. Blur the ellipses 40px–80px and overlay translucent white curved shapes to suggest a folded reflective sheet. Keep a sharp UI layer above them. Match the soft glow; exact stops are not essential.

### Technical diagrams

**Use:** Workflow demonstrations and numbered capability exhibits.

**Observed:** Thin white or dark node lines, tiny square endpoints, sparse mono annotations, visible code and trigger/output labels. Large empty intervals between nodes make the geometry readable.

**Transfer:** Model a real input, transformation and result; if no interface exists, this diagram becomes the main proof object.

**Build:** Use an SVG with 1px lines on black or gray, joining three principal nodes and a few secondary branches. Add 5px square endpoints, one orange output marker and 10px mono labels on solid backing; combine with an 8px dot lattice at low contrast.

### Customer photography

**Use:** Outcome proof and story openings.

**Observed:** Wide lifestyle photography or video, including equestrian scenes, jewelry close-ups and expressive portraits. Story openings often use grayscale and a dark lower fade beneath white metrics; full-bleed proof chapters use a dark overlay with white headings, quotes and logos.

**Transfer:** Show the customer's actual world, not generic office teamwork; retain subdued contrast behind type and preserve natural texture.

### Light-trail demonstration

**Only for:** image-first product pages

**Use:** Large code/editor and automation demonstration stages.

**Observed:** Near-black scenes carry curved cyan and red light streaks, or a night landscape with pale sweeping road-light trails; dark code and white editor windows overlap in front.

**Transfer:** Use one continuous light gesture to suggest flow behind a real UI; keep it within the media frame rather than washing the entire page.

**Build:** Draw two long curved SVG paths across a black backing: one cyan-tinted white and one orange-red, each with a narrow bright core and a wider blurred duplicate. Arc them diagonally behind two offset interface windows; keep the center under the UI dark.

### Technical catalog tiles

**Only for:** detailed product catalogs

**Use:** Dense feature inventory after narrative demonstrations.

**Observed:** Square white tiles in a four-column grid, technical identifier at top left and title/description near the bottom. Tiny patterned seams frame the grid; these are typographic inventory rather than decorative illustrations.

**Transfer:** Use meaningful identifiers and concise feature descriptions; preserve the top-to-bottom separation without adding arbitrary icons.

### Icons

**Observed:** Mostly compact solid SVG symbols at 21px; identity marks at 32px, copy/play controls around 25px, and occasional fine 13px diagram arrows with 1px strokes. Color follows surrounding text rather than a multicolor icon set.

**Transfer:** Use simple solid utility symbols, mono arrows and small square diagram handles; reserve colored marks for authentic product or partner identities.

## Section recipes

How recurring sections are built.

### First screen: Immersive data opening

**Observed:** A 36px announcement bar leads into a 67px navigation row over a near-black stage. Behind the copy, a photographic fragment expands from left-center into pixel blocks and a fine numeric lattice across the right. The 112px display headline is left aligned, spans roughly two thirds of the width and wraps into two strong lines. A 32px support line follows with 64px top separation, then an 8px-spaced row of Hero primary button, Hero secondary button and Command capsule after 48px. Within the first 900px the entire promise, support, actions, main visual and 72px orange proof ticker are visible; the detailed metric row starts below it.

**Transfer:** Replace the portrait with the new product's output or a relevant photographic subject, then show its transformation into data. If no finished media exists, combine a real workflow window with the lattice and diagram treatment. Pricing pages instead open with a centered 60px headline and plans; enterprise pages use a 60px left promise and right media; image-first product pages lead with a wide scene above a 120px product name.

**Avoid:** Do not turn the opening into a centered text-only SaaS hero or place the image in a separate rounded thumbnail beneath it.

**Text style:** `display` — Waldenburg-75357948a2b6a39b 400 · 112px/1 · tracking -0.04em

### Paired section lead

**Observed:** Heading at 48px occupies approximately half an inset row, with a 24px lead paragraph alongside. A 24.2px gap separates columns and 64px separates this row from the exhibit; dark chapters use 128px vertical padding.

**Transfer:** State one user outcome on the left and explain its mechanism on the right.

**Text style:** `heading` — Waldenburg-75357948a2b6a39b 400 · 48px/1.075 · tracking -0.035em

### Indexed capability chapter

**Observed:** On Light canvas, a 72px chapter statement introduces a long sequence. Numbered chapter tab rail, 38px chapter title with 18px prose and compact action, and a tall half-width image form the chapter triptych. The Dot field extends below the rail and the media uses Soft industrial media backing.

**Transfer:** Choose a small set of distinct jobs or capabilities and let the index orient the narrative, not duplicate all page navigation.

**Text style:** `subheading` — Waldenburg-75357948a2b6a39b 400 · 38px/1.1 · tracking -0.03em

### Proof as broadcast

**Observed:** Dark stage with a large white chapter heading, numbered selectors, white 38px outcome figures and 13px uppercase captions over dot-pattern fragments. A subdued full-width photograph or video backs the scene; a quote is separated by a thin white left rule near the bottom.

**Transfer:** Use verified outcomes with a short unit label and one attributable voice. A simpler alternative is the three-column metric row with 32px values and mono captions, not enormous dashboard numbers.

### Ruled capability assembly

**Observed:** A small left eyebrow rail aligns with a 48px heading in the inset content area and a compact action at right. Below, Ruled feature items appear two across with 12px column gaps. Alternating chapters pair a small paragraph with a 461px-wide graphic and 96px top/128px bottom padding.

**Transfer:** Use this light, quieter variant for technical depth and enterprise reassurance.

**Text style:** `heading` — Waldenburg-75357948a2b6a39b 400 · 48px/1.075 · tracking -0.035em

### Plan comparison

**Observed:** Centered 60px headline, 48px gap, three square white plan columns on Dot field backing. Names are 24px, prices 48px, descriptions 18px and inclusion text 15px. Free uses a gray action, recommended tier orange, enterprise black. A four-column comparison table follows with category rules, dotted row separators, mono values and a persistent plan/action header.

**Transfer:** Use pricing hierarchy rather than a giant highlighted recommended card; retain alignment across plans.

**Text style:** `light-display` — Waldenburg-75357948a2b6a39b 400 · 60px/1 · tracking -0.04em

### Long-form customer story

**Observed:** An inset 60px headline sits over a wide monochrome image with white 38px metrics at its base. A 24px introduction and bottom rule precede the article. A gray sticky factual sidebar sits left of a 621px reading column with 30px headings, 18px prose, Editorial quotation blocks and wide captioned media.

**Transfer:** Organize around problem, implementation and results; conclude the prose with related stories and a wide two-path conversion statement.

**Text style:** `article-heading` — Waldenburg-75357948a2b6a39b 400 · 30px/1.1 · tracking -0.02em

### Product demonstration chapter

**Observed:** On white, a 13px eyebrow and 48px sentence-like headline precede a large rectangular exhibit. Carousel chapters expose clipped neighboring scenes with circular Previous/Next buttons; 13px mono captions sit beneath. Ruled feature items and resource links give supporting detail below the images.

**Transfer:** Use a real workflow per scene; keep the explanatory captions outside the scene and differentiate horizontal carousel material from the vertical page flow.

**Text style:** `heading` — Waldenburg-75357948a2b6a39b 400 · 48px/1.075 · tracking -0.035em

### Conversion toolkit

**Observed:** Centered 72px headline over three unboxed entry paths with 24px titles, 15px descriptions and compact commands or tool icons. After 96px comes the paired Monumental action. The whole white section has 128px top and bottom padding.

**Transfer:** Offer practical ways to begin, then one unmistakable conversion gesture. Nontechnical products can replace installation methods with useful first steps; keep the large pill pair.

**Text style:** `chapter` — Waldenburg-75357948a2b6a39b 400 · 72px/1 · tracking -0.04em

### Deep directory ending

**Observed:** Dark stage begins with community and newsletter invitations at 32px on the left and four compact directory columns on the right, with 10px faint headings and 13px links. A centered white identity approximately 338px wide sits in a broad black field below. The bottom utility row contains social links, tiny location/copyright text, a green status capsule and a three-mode theme control.

**Transfer:** Use the new identity as a restrained white mark, keep the generous field around it and retain the compressed utility scale. Story and enterprise endings place a 60px conversion statement above this footer; product endings add a four-card related-capability strip. Pricing ends with FAQ assistance links before the footer.

**Text style:** `footer-invitation` — Waldenburg-75357948a2b6a39b 425 · 32px/1.2 · tracking -0.01em

## Page flow

**Storyline:** promise → visible mechanism → outcome proof → capability depth → practical entry paths or objection handling → decisive conversion → directory and identity

### Broad platform landing page

1. **promise** — Immersive data opening with three direct entry paths and orange proof ticker.
2. **quantified proof** — Compact dark three-metric row.
3. **product demonstration** — Dark chapters expose editorial tools, code and connected workflow diagrams.
4. **capability chapters** — Light indexed narrative pairs concise copy with large staged interface art.
5. **social proof** — Full-bleed photographic proof with outcomes and attribution.
6. **closing call** — Assurance band, centered toolkit, monumental action pair, then deep directory ending.

**Transfer:** Move from visual possibility to inspectable mechanisms and credible outcomes; preserve contrast changes without requiring this exact section count.

### Customer outcome story

1. **quantified promise** — Inset headline, grayscale customer image, overlaid results and introduction.
2. **context** — Sticky factual sidebar and customer-world video.
3. **implementation narrative** — Problem, solution and technical chapters interrupted by attributed quotations and captioned product media.
4. **results** — Plain-language outcomes and used capabilities.
5. **closing call** — Related stories, wide conversion statement, deep directory ending.

**Transfer:** Use the customer's operational change as the spine and alternate prose with specific proof.

### Commercial comparison

1. **pricing** — Centered promise and three equal plan columns.
2. **extension** — Compact add-on cards and monochrome customer logo grid.
3. **comparison** — Long grouped feature table with a persistent action header.
4. **social proof** — Short attributed quotation.
5. **objection handling** — Ruled FAQ list followed by community/support assistance links.
6. **ending** — Deep directory footer without another oversized sales pitch.

**Transfer:** Keep plan evaluation efficient and put the dense details below the initial decision.

### Enterprise evaluation

1. **promise** — White split opening with eyebrow, 60px promise, orange action and product-output collage.
2. **reassurance** — Monochrome logos and ruled benefits.
3. **social proof** — Full-bleed photographic customer chapter with quote and story action.
4. **capability depth** — Alternating light technical chapters and two-column ruled inventory.
5. **conversion** — Technical partnership description beside a lead form.
6. **validation** — Second story, assurance details, guide, reviews and three resource cards.
7. **closing call** — Wide 60px statement with orange/black actions, then deep directory ending.

**Transfer:** Answer risk and implementation questions through concrete engineering detail, not heavier visual ornament.

### Flagship product explanation

1. **product promise** — Image-first overlapping code/editor scene above large product-name typography.
2. **demonstration** — Large video and code-to-interface exhibit.
3. **capability chapters** — Captioned horizontal media galleries with ruled detail lists and resource links.
4. **inventory** — Grouped four-column technical catalog tiles.
5. **closing call** — 60px statement, two actions and four related capability cards before the shared footer.

**Transfer:** Make the product tangible through multiple workflows before asking readers to scan a detailed feature inventory.

## Writing

Confident, developer-literate and impatient with unnecessary work. The language is direct and occasionally dryly playful, balancing big operational promises with concrete mechanisms.

**Do not copy:** Do not reuse Sanity names, logos, artwork, commands, customer identities, quotations, performance figures, certifications or claims as facts about another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your team. Describe the product through what it lets people do; use we sparingly and let customers speak in first person.
- **Rhythm:** Short declarative headlines alternate with explanatory one- or two-sentence support. Fragments and three-part beats are common; technical paragraphs name actual operations rather than stacking adjectives.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name a category or frame a practical outcome. | 4–12 words | “The Content Operations Platform”<br>“Built to scale, not maintain” |
| Capability heading | Contrast the desired workflow with the frustrating alternative. | 4–10 words | “Custom workflows, not workarounds”<br>“Content Operations without the busywork” |
| Supporting line | Describe the mechanism and its practical consequence. | 15–35 words | “Your content model is TypeScript. Your workspace is React. Change either, see the result instantly.” |
| Action | Verb plus immediate next step. | 2–5 words | “Start building”<br>“Talk to an expert” |
| Closing statement | A terse, conversational nudge rather than a summary. | 4–9 words | “Less talk, more code”<br>“Ready to build? Let's make it real.” |
| Technical caption | Name the capability, then explain precisely what the scene demonstrates. | 12–25 words | “App SDK: embed any React application inside Studio. Here, a trail mapping tool with live data.” |

**Words and phrasing to use:** build; model; ship; configure; your team; workflows; real-time; not workarounds; one system; no waiting

**Avoid:** revolutionary magic; unlock limitless potential; seamlessly empower everything; delightful journey; excessive exclamation marks

**Rules:**

- Lead with an outcome, then explain the technical mechanism.
- Use concrete verbs and named operations in feature descriptions.
- Keep mono labels brief enough to behave as technical markings.
- Quantify proof only when it can be verified; otherwise describe the actual change.
- Use contrast and repetition for emphasis instead of inflated adjectives.

## Do's and Don'ts

### Do

- Keep the principal display at 400 weight with -0.04em tracking.
- Use the 24px outer gutter separately from 24.2px internal spacing.
- Give major chapters 96px–128px vertical breathing room.
- Retain 8px gaps between grouped pill actions.
- Use 13px mono for utility actions and captions, not the main hero action.
- Make the 8px dot lattice and fine rule system visible in at least one substantial exhibit.
- Stage sharp interface windows against soft abstract or photographic material.
- Carry the strong closing gesture into a black footer with a centered identity and tiny utilities.

### Don't

- Do not replace near-black with a blue-tinted dark theme.
- Do not turn every feature into a rounded, shadowed card; ruled lists and square media dominate.
- Do not use bold 700 display headings to manufacture hierarchy.
- Do not apply the 12px demonstration-window radius to page bands or photo frames.
- Do not enlarge 13px utility labels into a second body-text navigation system.
- Do not scatter orange, blue and green evenly through all marketing text; keep signal color concentrated.
- Do not use 38px proof values as justification for giant 120px dashboard numerals.
- Do not shrink the 140px conversion pills into ordinary compact controls when using the toolkit closing.

## Motion and responsive

### Motion

**Observed:**

- The proof ticker declares marquee-scroll 20s linear.
- Navigation declares color, background-color and box-shadow transitions over 0.2s with cubic-bezier(.4, 0, .2, 1).
- The newsletter action declares all 0.3s cubic-bezier(.4, 0, .2, 1); many controls declare 0.15s color and edge transitions.

**Transfer:**

- Keep motion tied to the broadcast ticker, chapter selection and product demonstrations; retain clear stable reading layers over animated media.

**Unknown:**

- Precise hero-video choreography and scroll-linked scene timings are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 376px, 768px and 1200px.
- Opening heading classes declare 60px at the narrow base, 72px above 400px, 96px at the medium breakpoint and 112px at the large breakpoint.
- Opening action row becomes a vertical full-width stack below the medium breakpoint; hero action text becomes 20px.
- The footer directory declares two columns before switching to four; chapter rails become horizontal rather than a tall desktop sidebar.

**Transfer:**

- Preserve the image-to-data motif on narrow screens by simplifying the lattice, not by reducing the entire desktop scene to an unreadable thumbnail.
- Stack paired section leads and keep captions adjacent to their exhibit; keep horizontally scrollable product galleries distinct from ordinary page overflow.

**Unknown:**

- Exact narrow-screen media positioning and all breakpoint-specific dimensions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
