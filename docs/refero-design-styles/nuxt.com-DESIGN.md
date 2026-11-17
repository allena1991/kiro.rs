# Nuxt — greenlit developer confidence

## Overview

An almost-black technical marketing style with fresh emerald accents, rounded geometric headlines and highly legible sans-serif detail. It feels practical and welcoming rather than cinematic: real interfaces, monochrome customer marks and fine schematic illustrations carry the story. Spacious chapters surround compact controls and information-dense grids, making it well suited to developer tools, infrastructure and extensible software.

### Essentials

- Two-tone promises read as a category statement: Outfit 72px/1, weight 500, -0.025em tracking, with a white first line and emerald second line; ordinary chapter headings use 48px/1 with the same weight and tracking.
- The opening is a working product bench, not a poster: a 656px text column faces a roughly 688×540px dark interface stage across a 64px gap, underneath a shallow green light wash.
- Emerald is a signal on a predominantly black page: #00dc82 marks the headline conclusion, primary action and small capability icons; broad sections remain #0a0a0a with restrained neutral gradients.
- Controls are small engineered rectangles: 6px corners, 40px hero buttons and 32–36px chapter actions, with 8px 12px padding on the standard button rather than oversized pills.
- Proof is framed, not decorated: 1px #404040 edges, 8px cards, joined comparison cells and full-color application views inside dark frames; use a believable task interface when no finished product image exists.
- Fine-line infrastructure and social proof provide texture: include a low-contrast connected diagram or system drawing and a restrained mark or portrait grouping, with 128px chapter padding keeping these devices distinct from dense text.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Emerald signal | `#00dc82` | `--color-primary` | accent, action, text, link | Primary action, emphasized headline phrase, active navigation and capability icons. Keep large areas dark. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-highlight` | text, action | Headlines, strong labels, monochrome proof marks and white chapter buttons. |
| Soft white | `#e5e5e5` | `--color-text` | text | Control text and small high-legibility labels that do not need headline white. |
| Toned gray | `#d4d4d4` | `--color-toned` | text | Quotes and denser descriptions. |
| Muted gray | `#a3a3a3` | `--color-muted` | text | Support paragraphs, navigation and secondary links. |
| Control edge | `#525252` | `--color-control-edge` | border | Inset 1px rings on dark buttons, small tags and input fields. |
| Hairline gray | `#404040` | `--color-rule` | border | Chapter separators, card rings and joined-cell dividers. |
| Elevated charcoal | `#171717` | `--color-elevated` | surface, text | Secondary button fill and code backing; dark foreground on bright buttons. Its 50% alpha use produces a subtle near-black card surface. |
| Card charcoal | `#101010` | `--color-card` | surface | Visible low-contrast card field produced by a half-opacity elevated neutral over the canvas. |
| Near black | `#0a0a0a` | `--color-canvas` | background | Default canvas and recessed interface areas; also the source hue for the 75% opaque navigation layer. |

## Typography

- **Outfit** — Hero, chapter headings and small footer group headings. Rounded geometric sans with open counters and a friendly single-storey construction. Font stack: "Outfit", Inter, ui-sans-serif, system-ui, sans-serif.
- **Inter** — Support copy, navigation, actions, card labels and statistics. Neutral compact sans; regular paragraphs contrasted with medium actions and semibold labels. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **ui-monospace** (only for technical product demonstrations) — Code inside a functional demonstration. Plain system monospace, with restrained syntax coloration. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Outfit | 500 | 72px | 1 | -0.025em | Primary marketing promise, usually split into two lines. |
| heading | Outfit | 500 | 48px | 1 | -0.025em | Major chapter titles and compact directory openings. |
| lead | Inter | 400 | 20px | 1.6 | normal | Opening explanation; wide enough for two or three lines. |
| section-support | Inter | 400 | 18px | 28px | normal | One short support paragraph below a chapter heading. |
| item-title | Inter | 600 | 16px | 1.5 | normal | Feature and directory card names; small section eyebrows. |
| body | Inter | 400 | 16px | 1.5 | normal | Quote band and ordinary prose. |
| hero-action | Inter | 500 | 16px | 1.5 | normal | Hero action pair. |
| card-body | Inter | 400 | 15px | 1.5 | normal | Compact feature explanations and directory descriptions. |
| control | Inter | 500 | 14px | 20px | normal | Navigation and chapter action labels. |
| caption | Inter | 400 | 14px | 20px | normal | Footer links, metric labels and short secondary descriptions. |
| footer-heading | Outfit | 500 | 14px | 20px | normal | Small navigational group headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| proof directories | stat | Inter | 600 | 36px | 40px | normal | Large numerical proof strip. |
| directories and proof tiers | tag | Inter | 500 | 12px | 16px | normal | Location tags and category filters. |

**Notes:**

- Headlines stay at weight 500 even when the promise is emphatic; the geometric face, scale and -0.025em tracking supply impact.
- Body text and controls use normal tracking. Do not import the tight display spacing into descriptions.
- Use sentence case, not tracked uppercase eyebrows. Green section labels can use the semibold item-title recipe.

## Layout

**Density:** Airy chapter structure with compact internal controls and dense but orderly information grids.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Compact icon-label and navigation gaps. |
| 8px | Hero action gap and common button vertical padding. |
| 12px | Standard button horizontal padding and form separation. |
| 16px | Small panel gaps, action-to-command gap and footer link spacing. |
| 24px | Heading-to-support distance and standard card interior padding. |
| 32px | Desktop side padding, card grid gap and support-to-chapter-action distance. |
| 40px | Feature grid gaps and hero support-to-action distance. |
| 48px | Footer vertical padding and compact quote-band padding. |
| 64px | Split-column gutter and heading-group-to-main-content gap. |
| 80px | Directory opening vertical padding. |
| 128px | Default chapter vertical padding. |
| 160px | Marketing opening top padding below navigation. |

### Containers and grids

- **container**: max width 1440px · side padding 32px. Centered desktop shell shared by headers, chapter contents and footer; leaves 1376px of usable width.
- **split stage**: 2 columns · gap 64px. Equal 656px content columns; the demo can extend into the right outer gutter.
- **capability grid**: 4 columns · gap 40px. Unboxed 314px-wide feature entries, read left to right.
- **joined cards**: 3 columns · gap 0px. Connected tool or extension cards, with shared edges rather than detached floating tiles.
- **logo matrix** (only for proof directories): 5 columns · gap 0px. Equal 275px-wide cells with 172px height inside one continuous hairline grid.
- **partner directory** (only for service directories): 2 columns · gap 32px. Two card columns beside a narrow filter rail; the outer layout uses ten tracks with a two-track rail, eight-track catalog and 40px gutter.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 6px |
|  | cards | 8px |
|  | demo stage | 16px |
|  | portrait tiles | 12px |
| proof directories | filter pills | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| edge ring | `0px 0px 0px 1px #404040` | Card outline, not a floating drop shadow. |
| inset control ring | `0px 0px 0px 1px #525252 inset` | Dark controls and inputs. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #0a0a0a; color: #e5e5e5`

#### Chapter fade · level 0

**Use:** Separate capability and proof chapters without changing theme.

**CSS:** `background: linear-gradient(to bottom, rgba(23,23,23,0.4), #0a0a0a); border-top: 1px solid #404040`

**Observed:** A subtle lighter top edge fades back to the canvas; sections are broadly padded, not enclosed in rounded boxes.

**Transfer:** Use the fade as a chapter reset, keeping it much weaker than the opening green atmosphere.

#### Outlined charcoal card · level 1

**Use:** Metrics, extensions and directory results.

**CSS:** `background: rgba(23,23,23,0.5); border-radius: 8px; box-shadow: 0px 0px 0px 1px #404040`

**Observed:** Low elevation is communicated by the thin ring and slightly lighter backing, not by blur or deep shadows.

**Transfer:** Keep unrelated content out of the same card; combine a compact title, useful explanation and restrained metadata.

#### Glass navigation · level 2

**Use:** Persistent page header.

**CSS:** `background: rgba(10,10,10,0.75); border-bottom: 1px solid #404040; backdrop-filter: blur(8px)`

#### Partner corner tint · level 1

**Use:** Joined ecosystem cards with distinct supporting identities.

**CSS:** `background: linear-gradient(to bottom right, rgba(66,184,131,0.1) 5%, rgba(0,0,0,0) 50%); border: 1px solid #404040`

**Observed:** Each tool has a weak identity-colored tint in the upper-left corner; green, violet and coral remain subordinate to the dark canvas.

**Transfer:** Choose a very faint local identity tint only for a genuine partner or integration; do not recolor entire chapters.

## Components

### Sticky navigation

**Use:** Persistent orientation and utility access.

**CSS:** `height: 64px; position: sticky; top: 0px; z-index: 50; background: rgba(10,10,10,0.75); backdrop-filter: blur(8px); border-bottom: 1px solid #404040`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Brand lockup and a small version badge sit left, compact destinations occupy the middle, and assistant, search, theme and repository utilities sit right. Active destinations are emerald.

**Transfer:** Keep only the utilities the new product can actually support.

### Primary button

**Use:** Main entry action.

**CSS:** `background: #00dc82; color: #171717; border-radius: 6px; padding: 8px 12px; height: 40px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `hero-action` — Inter 500 · 16px/1.5

**Observed:** The green entry action leads a horizontally paired neutral video action. A compact chapter variant uses the control recipe and 32px height.

**States:** Declared: hover background-color color-mix(in oklab,#00dc82 75%,transparent); focus-visible solid 3px outline with 0px offset; active uses the hover background.

### Secondary button

**Use:** Video or alternate action next to the primary conversion.

**CSS:** `background: #171717; color: #e5e5e5; border-radius: 6px; padding: 8px 12px; height: 40px; box-shadow: 0px 0px 0px 1px #525252 inset; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `hero-action` — Inter 500 · 16px/1.5

**Observed:** A circular play icon follows the video label. Other dark outlined variants support contribution and secondary chapter actions.

**States:** Declared: hover background-color color-mix(in oklab,oklch(26.9% 0 none) 75%,transparent); focus-visible solid 3px outline; active uses the hover background.

### Chapter button

**Use:** Compact high-contrast link to deeper content.

**CSS:** `background: #ffffff; color: #171717; border-radius: 6px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Often ends with a right arrow. A 32px variant uses 6px 10px padding for a smaller directory or proof action.

**States:** Declared: hover background-color color-mix(in oklab,#fff 90%,transparent); focus-visible solid 3px outline with 0px offset; active uses the hover background.

### Capability entry

**Use:** Dense readable inventory without a grid of heavy cards.

**CSS:** `border-radius: 4px`

**Text style:** `item-title` — Inter 600 · 16px/1.5

**Observed:** Small emerald outline icon above a semibold title, then a muted card-body explanation with 4px separation. Entries sit directly on the chapter surface. One entry can become a lightly backed editorial action tile.

**Transfer:** Use short capability names and explanations of the task saved, not lists of jargon.

### Metric card

**Use:** Compact ecosystem or adoption proof.

**CSS:** `background: rgba(23,23,23,0.5); border-radius: 8px; box-shadow: 0px 0px 0px 1px #404040`

**Observed:** Small square service icon at left, value above a caption at right. Pairs of short cards flank one wider participation card; this creates a 1:2:1 composition rather than four equivalent numbers.

**Transfer:** Use real measurable evidence; let the central card explain the human or operational meaning.

### Newsletter input

**Use:** Low-key recurring conversion in the footer.

**CSS:** `background: #0a0a0a; border-radius: 6px 0px 0px 6px; padding: 8px 12px; height: 36px; box-shadow: 0px 0px 0px 1px #525252 inset`

**Observed:** An email field joins flush to a white Subscribe button with right-only corners. The entire control is capped at 384px, below a short label and two lines of explanation.

**Transfer:** Use a real newsletter or similarly lightweight recurring relationship; retain the joined construction.

### Footer link

**Use:** Grouped secondary navigation.

**CSS:** `color: #a3a3a3; display: flex; align-items: center; gap: 6px; border-radius: 4px`

**Text style:** `caption` — Inter 400 · 14px/20px

**Observed:** Links follow a footer-heading title after 24px; subsequent links are separated by 16px.

**States:** Declared: hover color oklch(92.2% 0 none); focus-visible solid 3px outline with 0px offset.

### Directory card

**Only for:** service directories

**Use:** Comparable partner or service results.

**CSS:** `background: rgba(23,23,23,0.5); border-radius: 8px; box-shadow: 0px 0px 0px 1px #404040`

**Text style:** `item-title` — Inter 600 · 16px/1.5

**Observed:** 24px interior padding; identity mark above a title, a short card-body description and a bottom-aligned location tag. Desktop cards are about 530px wide and vary in height with content.

**Transfer:** Use meaningful comparison metadata rather than adding a loud CTA to every card.

### Category filter

**Only for:** proof directories

**Use:** Compact catalog segmentation.

**CSS:** `background: #171717; color: #ffffff; border-radius: 9999px; padding: 6px 10px; height: 28px`

**Text style:** `tag` — Inter 500 · 12px/16px

**Observed:** Only the selected category gets a filled pill; other categories are muted text on the canvas, with a preview hint aligned at the opposite edge.

**States:** Declared: hover background-color color-mix(in oklab,oklch(26.9% 0 none) 75%,transparent); focus-visible solid 3px outline; active uses the hover background.

## Imagery and graphics

### Working interface stage

**Use:** Main marketing opening and later product proof.

**Observed:** A large dark editor with a tab row, slim file rail and code pane fills the right half of the opening and extends beyond the right gutter. Thin neutral outlines and nested corners make the product feel usable; syntax colors are local to the interface. Later proof shows real, full-color website views inside dark rectangular carousel frames, with a large center item and partial neighbors.

**Transfer:** Use the new product's core task in a credible interface. If no interface exists, construct a minimal example with a navigation rail, a content header and one meaningful output, retaining the dark shell rather than substituting a stock laptop.

### Emerald overhead light

**Use:** Signature atmosphere above opening content.

**Observed:** A wide shallow green wash sits immediately below the header, strongest at the upper edge and fading to near black before it competes with the main copy. It has no hard outline or visible texture.

**Transfer:** Retain the shallow overhead glow for new marketing openings; match the soft glow rather than making a neon spotlight.

**Build:** Place an absolute full-width layer behind the opening, anchored at its top. Use a vertical gradient from rgba(0,220,130,0.2) to rgba(0,220,130,0) over roughly 200px. Keep the headline and product stage above it; do not blur text or add particles.

### Connected wireframe illustration

**Use:** A capability chapter that needs a visual counterpart to the product stage.

**Observed:** A roughly 512×439px schematic globe is drawn in extremely fine gray meridians and latitude rings. Small endpoint circles connect through dotted angular leaders to colored square platform marks. The lower hemisphere fades into black; it sits beside, not behind, the copy.

**Transfer:** Create an equally restrained network, workflow or system diagram specific to the product. A set of connected service nodes is the minimum acceptable alternative to the globe.

**Build:** Use SVG with several overlapping elliptical paths and curved vertical meridians inside a circular outline, strokes about 1px in rgba(163,163,163,0.25), small double-ring nodes and dotted elbow connectors. Surround the upper and side edges with six small rounded endpoint tiles. Apply a vertical opacity mask to dissolve the lower third.

### People and proof marks

**Use:** Social proof and participation chapters.

**Observed:** Customer marks are neutral gray in the compact strip and white in the catalog grid. Contributor imagery uses natural-color square portraits mixed with community avatars, 72×72px with 12px corners, in a six-column wall with 32px gaps. Sponsor marks can retain their original color inside an otherwise dark ruled grid.

**Transfer:** Use legitimate customer, contributor or partner identities. For an early product, use a smaller truthful grouping or meaningful artifact thumbnails, maintaining the same restrained framing.

### Icons

**Observed:** Mostly thin outline utility icons at 16–24px, aligned to control text; emerald capability symbols stand alone above titles. Social and platform marks use their recognizable filled silhouettes.

**Transfer:** Choose one consistent outline set with rounded joins for actions, and keep brand marks distinct from generic utilities. Use a right arrow for onward actions and a play-circle only for actual video.

## Section recipes

How recurring sections are built.

### First screen: Working bench opening

**Observed:** Below Sticky navigation, the Canvas receives Emerald overhead light. The opening uses two equal columns across a 64px gutter with 160px top padding; the left column contains a small announcement badge, a two-line display promise, a lead paragraph 24px below it and an action pair after 40px. White becomes emerald on the second headline line. A command-copy row sits 16px below the actions. At right, Working interface stage occupies roughly 688×540px, aligned to the text group and clipped by the outer right edge. Within the first 900px the complete promise, explanation, actions and main interface are visible, and the compact customer proof strip begins near the lower edge. The first capability chapter follows below the fold.

**Transfer:** Keep the text-to-working-object balance for a new landing page; fabricate a credible task preview if final media is unavailable. Proof directories instead use a left-aligned 48px heading and a short lead, with a metrics strip below; service directories center the 48px heading, support and one white action above results.

**Avoid:** Do not center the default opening, stretch the headline across the whole width or put the interface into a giant brightly colored billboard.

**Text style:** `display` — Outfit 500 · 72px/1 · tracking -0.025em

### Chapter heading pair

**Observed:** Chapter fade uses 128px vertical padding. A heading is followed after 24px by section-support, with a 32px gap to an action when present and 64px to the main grid. Capability and illustration chapters are left aligned; broad adoption and ecosystem summaries center the heading pair.

**Transfer:** Use alignment to distinguish a working chapter from a communal proof statement, not merely to alternate decoration.

**Text style:** `heading` — Outfit 500 · 48px/1 · tracking -0.025em

### Capability inventory

**Observed:** Four columns of Capability entry share 40px gaps. Icons remain small and green, descriptions use card-body, and one softly backed entry houses a direct next step. A compact full-width quote band follows with 48px vertical padding, centered 16px text, enlarged quotation marks and an attributed author.

**Transfer:** Combine task-level benefits with one concise external endorsement; do not turn every entry into a raised card.

### Joined ecosystem strip

**Observed:** Three touching cards form one bordered strip with 8px outer corners. Each contains an identity icon, semibold short heading, muted explanation and local identity-colored link; Partner corner tint lights only the upper corner. Extension cards add subdued metrics and a dashed separator above a small install-copy control.

**Transfer:** Use for genuine integrations, compatible tools or modular capabilities; preserve shared edges and small operational metadata.

### Participation proof

**Observed:** Centered heading pair above a 1:2:1 card arrangement: two stacked Metric cards on each side and a wider explanatory participation card in the middle. A later split chapter pairs a portrait wall on the left with a 48px heading and white action on the right.

**Transfer:** Separate quantitative confidence from the invitation to participate; choose a human or operational center message that makes the numbers meaningful.

### Schematic split

**Observed:** A left-aligned heading, support and Chapter button occupy one column, while Connected wireframe illustration fills the other. The text is vertically centered in a chapter around 696px high.

**Transfer:** Explain a broad system capability with one useful schematic, maintaining its low contrast and fading lower edge.

### Proof gallery

**Observed:** A bordered full-width chapter centers a green section label, two-line heading and compact white action above a framed website carousel. Large full-color views sit on dark cards; 12px pagination dots use white for the selected item and gray for the rest.

**Transfer:** Show actual outputs or applications as visual proof, not merely another logo strip.

### Tiered closing proof

**Observed:** The final marketing chapter centers a heading, support paragraph and paired white/dark actions above a large 8px outlined sponsor matrix. Wide featured rows precede smaller three-column and two-column rows; tiny tier badges sit at row corners. A small centered brand glyph interrupts the horizontal separator before the footer.

**Transfer:** Adapt the tiered matrix to credible partners, endorsements or supporting organizations when such a hierarchy exists; retain the ruled, low-key closing register instead of escalating into a loud banner.

### Utility footer ending

**Observed:** A centered small glyph divides two horizontal rules. Three link groups sit left and a newsletter form sits right in a 1440px shell with 32px side padding and 48px vertical padding. Footer-heading labels precede muted links. A separate bottom rule introduces copyright and license information on the left and small social icons on the right. The complete footer occupies about 297px.

**Transfer:** Keep the ending practical and compact on all page types; use the joined Newsletter input and a restrained social row rather than another display headline.

### Directory variants

**Only for:** proof and service directories

**Observed:** Proof catalogs follow a compact opening with a four-column numerical strip, category chips and a five-column joined white-logo matrix. Service catalogs follow a centered opening with a narrow filter rail and two columns of Directory card. Both finish after the last real result and transition directly to the shared footer.

**Transfer:** Choose mark-led browsing for recognition or descriptive cards for comparison; use real category and location distinctions.

## Page flow

**Storyline:** Promise with a working artifact → concise capability explanation → ecosystem and adoption proof → visual outcomes → supporting relationships → practical navigation and subscription.

### Flagship product landing

1. **Promise** — Split two-tone headline, task interface, action pair and small activation command.
2. **Recognition** — Compact grayscale customer mark strip.
3. **Capability chapters** — Unboxed feature inventory and short attributed quote.
4. **Ecosystem proof** — Joined tool cards, adoption metrics and participation center card.
5. **Extensibility** — Module cards with operational metadata and copy controls.
6. **System capability** — Schematic illustration beside a concise benefit statement.
7. **Human proof** — Portrait wall beside a participation invitation.
8. **Outcome proof** — Full-color application carousel.
9. **Closing relationships** — Sponsor heading, actions and tiered ruled matrix.
10. **Utility ending** — Shared link groups, newsletter, legal row and socials.

**Transfer:** Use the split artifact-led opening as the default and select chapters according to the product's real proof, rather than treating every topic as required.

### Recognition and proof directory

1. **Promise** — Compact left-aligned two-tone heading and explanatory lead.
2. **Quantified proof** — Four-column ruled statistic strip, one value emphasized in green.
3. **Browse proof** — Category filters and large five-column monochrome mark grid.
4. **Utility ending** — Shared footer immediately after the final partial grid row and generous clearance.

**Transfer:** Make recognition easy to scan; keep individual marks calm and use categories when they materially help discovery.

### Service partner directory

1. **Orientation** — Centered compact heading, multi-line lead and white participation action.
2. **Comparison** — Filter rail beside two-column cards with identities, descriptions and location tags.
3. **Utility ending** — Final card pair, clear space, divided shared footer.

**Transfer:** Let descriptions and comparable metadata do the selling; reserve the header action for the directory's overarching relationship.

## Writing

Confident, useful and developer-literate, with a friendly open-community undertone. Benefits are stated plainly and then backed by mechanisms, compatibility or credible proof.

**Do not copy:** Do not reuse Nuxt names, logos, mascot, source code, customer or partner identities, quotes, adoption numbers, anniversary badge, licensing promises or product claims. Source examples demonstrate phrasing only; replace them with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Refer to the product by name when explaining what it handles; use community language only when there is a genuine participation story.
- **Rhythm:** Headlines are short declarative phrases, often four to eight words. Support copy uses one or two concrete sentences, with occasional brisk fragments and paired alternatives. Actions are brief verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category directly; put the decisive category phrase on the emphasized line. | 4–8 words | “The Full-Stack Vue Framework” |
| Chapter heading | State a practical benefit or confidence signal without a slogan. | 2–8 words | “Everything you need, nothing you don't”<br>“Deploy anywhere” |
| Supporting line | Start with the benefit, then explain the specific mechanism or scope. | 10–30 words | “[Brand] handles the architecture so you can focus on building.”<br>“Deploy with one command. SSR, static, or edge — [Brand] adapts to your platform.” |
| Primary action | Verb plus clear destination or task; no abstract encouragement. | 2–5 words | “Get started”<br>“Explore all modules”<br>“Become a partner” |
| Directory introduction | State who belongs here and what the reader can discover. | 1–2 sentences | “Explore inspiring websites, apps, and digital experiences made by developers and companies around the world.” |

**Words and phrasing to use:** build; ship; production-ready; out of the box; your choice; trusted; plug & play; one command

**Avoid:** revolutionary; unparalleled; magical transformation; disrupt everything; enterprise synergy

**Rules:**

- Follow broad claims with the concrete capability that makes them true.
- Use technical vocabulary only when it names an actual feature or choice.
- Keep metric labels literal and short; explain the unit rather than praising the number.
- Use exclamation marks for a genuine small announcement, not as the default marketing voice.

## Do's and Don'ts

### Do

- Keep the default hero at Outfit 72px/1 with -0.025em tracking and weight 500.
- Use a 1440px shell with 32px desktop side padding.
- Separate broad chapters with 128px vertical padding and fine neutral top rules.
- Use 24px between a heading and its muted explanation.
- Keep main buttons at 6px radius and 40px height; use smaller 32–36px chapter variants.
- Include a credible interface stage, shallow emerald glow and fine-line system visual in the landing-page vocabulary.
- Keep partner or output imagery inside dark, outlined framing rather than on decorative pedestals.
- Finish with a small divided footer, joined 36px email form and restrained social row.

### Don't

- Do not replace Outfit with a heavy condensed or square techno display face.
- Do not turn the near-black palette into broad emerald section fills.
- Do not apply 9999px pill corners to ordinary conversion buttons.
- Do not use pure white for every paragraph; reserve it for strong hierarchy above muted #a3a3a3 copy.
- Do not add deep drop shadows to cards whose separation is a 1px neutral ring.
- Do not make every feature a padded raised card; the inventory is primarily unboxed.
- Do not recolor customer marks into a multicolor wall when recognition is served by a white or gray treatment.
- Do not introduce giant numerical counters into ordinary chapters; the 36px statistic strip belongs to proof-directory pages.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.15s color and background transitions with cubic-bezier(.4,0,.2,1).
- Eight entrance elements declare 0.9s animations with cubic-bezier(.25,1,.5,1) and staggered delay variables.
- Logo cells declare color and scale transitions over 0.5s with cubic-bezier(0,0,.2,1).
- Carousels use small selectable pagination dots, white for active and gray for inactive.

**Transfer:**

- Keep interaction feedback in the restrained control palette; avoid making the whole page pulse green.
- Use the small pagination treatment for visual proof groups when multiple items are available.

**Unknown:**

- Exact entrance transforms, delay values and autoplay behavior are not specified.
- The resulting hover-preview content and its full animation sequence are not established.

### Responsive

**Observed:**

- The layout vocabulary includes stacked-to-two-column hero classes, one-to-three-column joined strips and a feature inventory that progresses through two, three and four columns.
- Side padding progresses through 16px, 24px and 32px classes. The opening headline has a 48px base and 72px larger-screen variant.
- The directory category rail supports horizontal overflow; exact breakpoint widths are not specified.

**Transfer:**

- On narrow layouts, place the interface below the promise and preserve its readable task content rather than shrinking the whole desktop scene.
- Stack joined strips with shared horizontal dividers and move filter controls ahead of results; preserve the compact control sizes.
- Reduce the portrait wall's column count while retaining square tiles and regular gaps.

**Unknown:**

- Exact mobile renderings, navigation collapse behavior and numerical breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
