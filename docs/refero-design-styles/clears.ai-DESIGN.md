# Clears — lilac control room

## Overview

A near-black technical world with fine diagonal hatching, faint grain and small lilac signals. Light geometric sans-serif headlines contrast with uppercase monospace controls, while dark interface imagery and wired diagrams make complex products feel observable and tangible. The atmosphere is spacious and restrained rather than neon-heavy, suited to infrastructure, automation and sophisticated business software.

### Essentials

- A framed black control room: 48px hatched side rails, #222222 edges and barely visible grain surround the entire page; retain these devices even when the product has no imagery.
- The promise floats above a wired system: centered 54.7px Figtree at weight 300, line height 1 and -0.03em tracking; 30px gaps lead to support and a single action, then a 120px pause before a broad technical diagram.
- Conversion looks like a machine control, not a pill: 278×48px lilac buttons, 4px corners, diagonal 1px hatching every 6px, black uppercase 18px Space Mono and a tiny square before the label.
- Color is a signal in a predominantly black field: #bf8dff appears in actions, star ratings, node sockets and sparse square particles, not broad section fills; white and gray carry nearly all text.
- Product imagery is a dark instrument under inspection: black or charcoal frames hold purple-gray interfaces, thin wires and tiny lilac nodes. When interface media is unavailable, supply a real labeled process diagram rather than decorative stock art.
- A luminous final invitation and an oversized patterned emblem anchor the ending: 64px/1 medium sans type with a 12px white glow, sparse lilac pixel clusters, then a 175px-tall low-contrast repeating geometric ribbon before the footer. Adapt the emblem to a new geometric mark; keep the device.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lilac signal | `#bf8dff` | `--color-lilac` | action, accent, text | Primary actions, stars, active links and technical nodes. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black canvas | `#000000` | `--color-canvas` | background, text | Full marketing canvas and text on lilac actions. |
| Control charcoal | `#191919` | `--color-control` | surface | Secondary navigation button. |
| Rail graphite | `#222222` | `--color-rail` | border, surface | Side-rail hatch lines, navigation separator and secondary action hover fill. |
| Card edge | `#2c2c2c` | `--color-card-edge` | border | Fine outlines around capability cards. |
| Control edge | `#424242` | `--color-strong-edge` | border | Outlined navigation action. |
| Utility gray | `#616460` | `--color-utility` | text | Low-priority footer information and certification icon. |
| Statement gray | `#7f7f7f` | `--color-muted` | text | The contextual first part of split-tone statements and secondary feature explanations. |
| Equipment gray | `#828282` | `--color-badge` | surface | Small category badge backing. |
| Light gray | `#e1e1e1` | `--color-body` | text | Support paragraphs and footer links. |
| Soft white | `#fcfcfc` | `--color-headline` | text | Headlines and footer positioning line. |
| Signal white | `#ffffff` | `--color-white` | text | Navigation, highlighted statement endings, customer names and FAQ prompts. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Violet edge | `#8b55c7` | `--color-plan-edge` | border | Outline of the emphasized plan. |
| pricing pages | Plan charcoal | `#101010` | `--color-plan` | surface | Visible backing of highlighted plan, rgba(23,23,23,0.7) over black. |
| pricing pages | Secondary plan charcoal | `#121212` | `--color-plan-secondary` | surface, border | Visible rgba(25,25,25,0.7) plan backing over black; also FAQ row separators. |

## Typography

- **Figtree** — Display, headings, paragraphs and footer links. Geometric sans with open bowls and a delicate light cut for large promises. Font stack: "Figtree", "Avenir Next", sans-serif.
- **Space Mono** — Navigation, controls, equipment labels, customer names and plan features. Wide monospaced letterforms make small controls feel like terminal commands. Font stack: "Space Mono", "JetBrains Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing | Figtree | 500 | 64px | 1 | normal, capitalize | fixed | Short glowing conversion invitation. |
| display | Figtree | 300 | 54.7px | 1 | -0.03em | size clamp(48px, 3.8vw, 88px) | Centered landing-page promise. |
| statement | Figtree | 300 | 42px | 1.2 | -0.03em, capitalize | fixed | Wide split-tone contextual statement before capability cards. |
| heading | Figtree | 400 | 32px | 1.2 | -0.035em | fixed | Capability card titles and centered FAQ section heading. |
| proof-heading | Figtree | 300 | 30px | 32px | normal | fixed | Centered introduction to customer endorsements. |
| chapter-heading | Figtree | 400 | 28px | 1.2 | -0.04em | fixed | Titles beside the large product demonstrations. |
| footer-positioning | Figtree | 300 | 22px | 1.25 | -0.01em, capitalize | fixed | One-line positioning beneath the footer logo. |
| customer-name | Space Mono | 400 | 20px | 1.5 | normal, uppercase | fixed | Customer identity below star ratings. |
| lead | Figtree | 300 | 18px | 1.5 | normal | fixed | Centered hero support, generally two lines. |
| action | Space Mono | 400 | 18px | 1.5 | -0.03em, uppercase | fixed | Lilac primary button labels. |
| body | Figtree | 300 | 16px | 1.5 | normal | fixed | Card descriptions, customer roles and detailed support. |
| navigation | Space Mono | 400 | 16px | 1.5 | normal, uppercase | fixed | Header links and footer column headings. |
| footer-link | Figtree | 400 | 16px | 1.5 | normal, capitalize | fixed | Footer destination links. |
| chapter-body | Figtree | 300 | 14px | 1.5 | normal | fixed | Narrow descriptive columns accompanying expansive demonstrations. |
| compact-action | Space Mono | 400 | 14px | 1 | -0.03em, uppercase | fixed | Outlined header conversion action. |
| login-action | Space Mono | 400 | 14px | 1.5 | -0.03em, uppercase | fixed | Filled secondary header control. |
| badge | Space Mono | 400 | 12px | 1 | normal, uppercase | fixed | Gray equipment labels above demonstration titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Figtree | 300 | 56px | 1 | -0.0536em, capitalize | fixed | Centered two-line commercial promise. |
| product detail pages | product-display | Figtree | 300 | 48px | 1 | -0.03em, capitalize | fixed | Left-aligned multiline product promise. |
| pricing pages | plan-heading | Figtree | 300 | 40px | 1.1 | -0.03em | fixed | Outcome or deployment proposition inside plans. |
| product detail pages | detail-closing | Figtree | 300 | 40px | 1.2 | -0.036em, capitalize | fixed | Centered split-tone closing statement replacing the short glowing invitation. |
| product detail pages | detail-heading | Figtree | 400 | 24px | 1.2 | -0.035em | fixed | Screenshot-card titles and icon-led benefits; gray explanations may use the same recipe. |
| pricing pages | question | Figtree | 400 | 20px | 1.2 | -0.035em | fixed | Accordion questions. |
| pricing pages | plan-feature | Space Mono | 400 | 13px | 1.9 | normal, uppercase | fixed | Compact plan inclusion lists. |
| pricing pages | plan-label | Space Mono | 400 | 12px | 1.5 | 0.2em, uppercase | fixed | Lilac plan identifier. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large promises use weight 300 and tight tracking, not bold display grotesks. Reserve weight 500 for the short conversion invitation.
- The default display scales with the viewport; commercial and detail-page openings use their own fixed desktop recipes rather than averaging the three sizes.
- Monospace uppercase marks actions and identity; paragraphs remain proportional, light and predominantly sentence case. A capability card variant uses deliberately lowercase support.
- Split-tone statements begin in gray and resolve in white without a change in family, size or weight.

## Layout

**Density:** Airy overall, with compact technical labels and cards nested within long black pauses.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Badge-to-title spacing and button marker gap. |
| 12px | Portrait-to-caption gap and vertical accordion padding. |
| 14px | Footer link stack gaps. |
| 16px | Chapter heading-to-description spacing and footer logo-to-positioning gap. |
| 21px | Footer column heading-to-links gap. |
| 30px | Opening headline-to-support and support-to-action gaps. |
| 32px | Plan padding and product-detail card grid gaps. |
| 40px | Closing text-to-action gap and FAQ heading-to-list gap. |
| 48px | Side rail width and customer grid row gap. |
| 60px | Statement-to-capability-grid gap. |
| 64px | Customer heading-to-endorsement-grid gap. |
| 96px | Product-detail opening top padding and wide decorative band side inset. |
| 120px | Hero action-to-system-diagram gap and closing section bottom padding. |
| 160px | Main desktop side inset and detail benefits bottom padding. |
| 200px | Customer-proof bottom breathing room and trust band top pause. |

### Containers and grids

- **Main content**: max width 1920px · side padding 160px. Centered outer container; 1120px of content is visible at a 1440px viewport. Align the header, hero illustration, capability cards, demonstrations and footer to it.
- **Decorative frame**: side padding 48px. Continuous hatched edge rails leave a 1344px central field at desktop.
- **Hero support**: max width 680px. Centered support paragraph beneath a broad single-line promise.
- **Capability grid**: 3 columns · gap 35px. Three equally sized 350px-wide cards across the main content field.
- **Endorsement grid**: 2 columns · gap 58px. Two columns of compact portrait-and-identity figures, two rows with 48px row gaps.
- **Closing stage**: max width 1524px · side padding 96px. A broad particle field with centered text constrained to 840px.
- **Detail card grid** (only for product detail pages): 3 columns · gap 32px. Three 352px-wide screenshot-led cards.
- **Plan comparison** (only for pricing pages): max width 596px · 2 columns · gap 32px. Each plan is at most 596px wide; two equal-height plans sit side by side.
- **FAQ column** (only for pricing pages): max width 856px. Centered question list, narrower than the main content field.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Controls and badges | 4px |
|  | Capability cards | 4.2px |
| product detail pages | Detail cards | 4px |
| pricing pages | Plan cards | 6px |
| pricing pages | FAQ triggers | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Action aura | `0px 0px 28px 0px rgba(191, 141, 255, 0.18)` | Subtle lilac glow behind primary actions. |
| pricing pages | Plan aura | `0px 0px 32px 0px rgba(191, 141, 255, 0.28)` | Only the emphasized plan. |

### Surfaces

#### Black grain canvas · level 0

**Use:** Continuous page backing.

**CSS:** `background-color: #000000`

**Observed:** A faint irregular noise texture spans the inner field; it is subtle enough that the page still reads as black.

**Transfer:** Overlay a low-opacity monochrome SVG turbulence texture, keeping grain nearly imperceptible and avoiding visible cloudy patches.

#### Hatched edge rails · level 1

**Use:** A continuous narrow architectural frame on both sides.

**CSS:** `background-color: #000000; background-image: repeating-linear-gradient(139deg, rgba(0, 0, 0, 0) 0px, rgba(0, 0, 0, 0) 5px, #222222 5px, #222222 6px); width: 48px; border-right: 1px solid #222222`

**Observed:** The right rail mirrors the edge border. Rails span the document rather than belonging to individual cards.

**Transfer:** Keep the hatching outside the reading column and make it noninteractive.

#### Outline capability panel · level 1

**Use:** Grouped capability artwork and explanatory text.

**CSS:** `background: transparent; border: 1px solid #2c2c2c; border-radius: 4.2px; overflow: hidden`

**Observed:** The black canvas shows through; artwork occupies the upper region and the title and support sit below.

**Transfer:** Use fine outlines rather than raised gray tiles.

#### Highlighted plan panel · level 1

**Only for:** pricing pages

**Use:** Emphasized commercial option.

**CSS:** `background-color: rgba(23, 23, 23, 0.7); background-image: repeating-linear-gradient(135deg, rgba(255, 255, 255, 0.04) 0px, rgba(255, 255, 255, 0.04) 1px, rgba(0, 0, 0, 0) 1px, rgba(0, 0, 0, 0) 8px); border: 1px solid #8b55c7; border-radius: 6px; padding: 32px; box-shadow: 0px 0px 32px 0px rgba(191, 141, 255, 0.28)`

**Observed:** The companion plan has an unhatched rgba(25,25,25,0.7) backing and no violet outline or aura.

**Transfer:** Emphasize one option with material and border, not a promotional badge explosion.

## Components

### Navigation

**Use:** Persistent orientation at the top of the page.

**CSS:** `height: 97px; position: sticky; top: 0px; padding-top: 30px; background: #000000; z-index: 40`

**Text style:** `navigation` — Space Mono 400 · 16px/1.5 · uppercase

**Observed:** A compact white logo sits left; product dropdown, destination links and two small controls align right with 20px gaps. A thin graphite separator stops at the side rails. The active destination becomes lilac.

**Transfer:** Keep navigation terse and technical; use a small downward chevron only for a real menu.

### Primary button

**Use:** The main conversion action in openings and closing sections.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; width: 278px; height: 48px; padding: 0px 13px; background-color: #bf8dff; background-image: repeating-linear-gradient(135deg, rgba(0, 0, 0, 0.07) 0px, rgba(0, 0, 0, 0.07) 1px, rgba(0, 0, 0, 0) 1px, rgba(0, 0, 0, 0) 6px); color: #000000; border: 1px solid transparent; border-radius: 4px; box-shadow: 0px 0px 28px 0px rgba(191, 141, 255, 0.18)`

**Text style:** `action` — Space Mono 400 · 18px/1.5 · tracking -0.03em · uppercase

**Observed:** A 6px black square with 2px corners precedes the text. Pricing uses a full-width 55px-tall variant with 3px corners and 17.5px/26.3px mono text; both plans use the lilac action.

**States:** Declared: hover background-color #c89cff and black text; focus-visible lilac border at 0.6 alpha with the existing 28px aura; active translate 0 0.

**Transfer:** Use a single short verb-led label and preserve the square marker.

### Header outline button

**Use:** Compact conversion action within navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 37px; padding: 8px 10px; background: #000000; color: #ffffff; border: 1px solid #424242; border-radius: 4px`

**Text style:** `compact-action` — Space Mono 400 · 14px/1 · tracking -0.03em · uppercase

**Observed:** Text-only, without the primary button square; it sits after the login control.

**States:** Declared: hover border-color #bf8dff; focus-visible neutral border with no added shadow; active translate 0 0.

### Login button

**Use:** Secondary access action in navigation.

**CSS:** `height: 37px; padding: 8px 10px; background: #191919; color: #ffffff; border: 1px solid transparent; border-radius: 4px`

**Text style:** `login-action` — Space Mono 400 · 14px/1.5 · tracking -0.03em · uppercase

**Observed:** A small filled charcoal rectangle before the outlined conversion control.

**States:** Declared: hover background-color #222222; focus-visible neutral border with no added shadow; active translate 0 0.

### Equipment badge

**Use:** Compact category marker above chapter headings.

**CSS:** `display: inline-flex; padding: 4px 5px; background: #828282; color: #000000; border-radius: 4px`

**Text style:** `badge` — Space Mono 400 · 12px/1 · uppercase

**Observed:** Content-width label placed 8px above the chapter title. The product-detail opening uses the same badge with a 13px title gap.

### Capability card

**Use:** A small collection of high-level capabilities.

**CSS:** `display: flex; flex-direction: column; height: 395px; border: 1px solid #2c2c2c; border-radius: 4.2px; overflow: hidden`

**Text style:** `heading` — Figtree 400 · 32px/1.2 · tracking -0.035em

**Observed:** Upper line-art space and bottom-aligned title with a short lowercase paragraph. Titles are left-aligned and support follows after 13px. Product-detail cards instead use real dark interface images above 24px headings and 16px paragraphs inside 352×558px outlined cards.

**Transfer:** Give each card a distinct explanatory diagram or interface view, not a generic colored icon in a circle.

### Customer endorsement

**Use:** Human proof without long quote cards.

**CSS:** `display: flex; align-items: center; gap: 12px; max-width: 303px`

**Text style:** `customer-name` — Space Mono 400 · 20px/1.5 · uppercase

**Observed:** A circular headshot sits beside a stack of five lilac 24px stars, uppercase mono name and a light sans role/company line. There is no filled card backing or quotation block.

**Transfer:** Use genuine identities and available endorsements; do not invent ratings.

### Footer link column

**Use:** Compact destination groups beside the footer identity block.

**CSS:** `display: flex; flex-direction: column; gap: 14px; color: #e1e1e1`

**Text style:** `footer-link` — Figtree 400 · 16px/1.5 · capitalize

**Observed:** Uppercase mono column title is separated from the links by 21px. Three columns sit to the right of a logo and positioning line; copyright and a muted certification marker sit below the identity block.

**States:** Declared: hover color #ffffff; focus-visible rounded edge and outline-style none.

**Transfer:** Keep link groups small and preserve the distinction between mono headings and proportional destination labels.

### Plan card

**Only for:** pricing pages

**Use:** Outcome-led plan comparison rather than a numeric price table.

**CSS:** `display: flex; flex-direction: column; max-width: 596px; min-height: 520px; padding: 32px; border-radius: 6px; background-color: rgba(23, 23, 23, 0.7); border: 1px solid #8b55c7; box-shadow: 0px 0px 32px 0px rgba(191, 141, 255, 0.28)`

**Text style:** `plan-heading` — Figtree 300 · 40px/1.1 · tracking -0.03em

**Observed:** Plan label, two-line proposition, audience paragraph, inclusion label and uppercase mono bullet list lead to an action anchored to the bottom. Equal card heights align the two actions. Use Highlighted plan panel for the emphasized option; the companion is plain charcoal.

**Transfer:** Lead with what changes for the buyer; allow pricing to be consultative rather than forcing a price figure.

### FAQ row

**Only for:** pricing pages

**Use:** Commercial objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 12px 0px; min-height: 66px; border: 1px solid transparent; border-radius: 10px; color: #ffffff`

**Text style:** `question` — Figtree 400 · 20px/1.2 · tracking -0.035em

**Observed:** Question left, thin white chevron in a 40px icon box right. Each wrapper except the last has a 2px #121212 bottom rule. Closed rows dominate the list.

**States:** Declared: hover text-decoration-line none; focus-visible neutral border and no added shadow.

**Transfer:** Use direct buyer questions, with one answer revealed per trigger.

## Imagery and graphics

### Wired system diagram

**Use:** The primary opening object, spanning the main content width beneath the text.

**Observed:** A central tall black execution panel is wired with fine dashed curved paths to smaller dark source and context panels on either side. Lilac square sockets punctuate junctions; stacked outlines, faint edge light and tiny terminal details keep it technical. The 1120×564px object is larger than the text block and continues below the first fold.

**Transfer:** Draw a domain-specific input-to-process-to-output system with a clear central hub. The minimum version is a crisp SVG with labeled black panels, a few meaningful rows and real connections.

**Build:** Use a 1120×564 SVG viewBox. Place a roughly 315px-wide tall center panel and smaller 230px-wide side panels. Use #000000 and #191919 fills, 1px #2c2c2c outlines, subdued dashed cubic paths and 10px #bf8dff rounded-square sockets. Add a very faint lilac duplicate outline glow and a few staggered card outlines; keep labels sparse and readable.

### Dark product inspection

**Use:** Large demonstrations, detail-page opening media and screenshot-led cards.

**Observed:** Purple-gray interfaces sit inside charcoal frames against black. Broad walkthrough media is about 693×413px; it is paired with a much narrower text column. Detail openings use a 534×362px workflow graph with diagonal hatching around the frame. Smaller card images concentrate on a meaningful workflow, code session or execution view.

**Transfer:** Use your own dark interface or a carefully reconstructed representative view. Maintain legibility and surrounding black space; neutralize bright chrome rather than tinting the entire image purple.

### Pixel signal field

**Use:** Signature artwork around conversion statements.

**Observed:** Sparse one-, two- and three-square lilac clusters surround the center, brighter near some edges and almost disappearing elsewhere. The center remains clear for text and action; the headline has a soft white halo.

**Transfer:** Keep this sparse field even without product media. It is a signal motif, not a starry sky or ambient gradient.

**Build:** In a 1248×430px stage, distribute roughly eight small clusters around the outer thirds. Use 10px rounded squares, about 3.3px corners, #bf8dff at 0.3 opacity for dim cells and full opacity with 0 0 9.8px rgba(191,141,255,0.5) for lit cells. Offset neighbors by 16–20px. Apply text-shadow: 0 0 12px rgba(252,252,252,0.6) to the short closing headline only.

### Patterned emblem ribbon

**Use:** Signature full-width transition into the footer, plus a thin technical separator band.

**Observed:** An oversized repeating angular emblem runs horizontally beyond the viewport, about 175px tall, rendered in tiny low-contrast dots rather than a solid white logo. A 54px-tall striped technical band finishes the footer and also separates major chapters.

**Transfer:** Create a repeating abstract emblem derived from the new identity, or interlocking open hexagonal brackets when no suitable emblem exists. Preserve the monumental scale and low contrast.

**Build:** Create an SVG ribbon of broad angular open-loop shapes repeated at roughly 440px intervals, cropped by the viewport edges. Mask a 2–3px-spaced microdot pattern into the shapes using #222222 at reduced opacity. For the thin band, use 1px vertical graphite strokes with varied spacing on black, bounded by fine horizontal rules.

### Human proof portraits

**Use:** Small endorsement figures.

**Observed:** Circular headshots, a mix of color and grayscale, remain secondary to lilac star ratings and compact identity text; no large lifestyle photography.

**Transfer:** Use consistently sized genuine portraits and keep the surrounding canvas black.

### Icons

**Observed:** Tiny square nodes and markers are characteristic. Ratings use filled lilac 24px stars; navigation chevrons are about 9×6px with a 1px stroke. FAQ chevrons use a thin round-ended white stroke in a 40px box. Detail benefits use small lilac outline symbols.

**Transfer:** Choose sparse geometric line icons for benefits, simple chevrons for disclosure and rounded squares for system state; avoid multicolor illustration-style icons.

## Section recipes

How recurring sections are built.

### First screen: Wired promise opening

**Observed:** The 97px Navigation sits over Black grain canvas inside Hatched edge rails. A centered single-line promise spans roughly three quarters of the 1120px reading field, starting 66px below navigation. Lead support is constrained to 680px, separated by 30px; Primary button follows another 30px later. After a 120px pause, the Wired system diagram fills the content width. Within the first 900px the headline, two-line support, action and most of the upper diagram are visible; the bottom of the diagram and trust content continue below. Layers are grain, faint panel glows and dashed wires, black diagram panels, readable labels and lilac sockets; the hero text stays above the diagram rather than overlaying it.

**Transfer:** Translate the central system into the new product's meaningful inputs, operations and outcomes. Use the SVG fallback when no interface is ready. Product-detail openings switch to a 48% left text column with Equipment badge, product-display headline, body and action opposite a dark graph; pricing openings center a two-line pricing-display promise and lead into two Plan cards.

**Avoid:** Do not replace the diagram with a giant floating app window behind the headline, a stock robot or a full-screen violet gradient. Do not force the entire diagram above the fold.

**Text style:** `display` — Figtree 300 · 54.7px/1 · tracking -0.03em

### Compact human proof

**Observed:** A wide trust-logo region is introduced by an uppercase mono label and a generous 200px top pause. Customer endorsements follow under a centered proof-heading, with 64px to the two-column grid, 48px row gaps and 200px below the group. Figures sit directly on black.

**Transfer:** Separate institutional recognition from individual identity. Use genuine proof at its natural density rather than filling the space with fabricated quotes.

**Text style:** `proof-heading` — Figtree 300 · 30px/32px

### Split statement and capability panels

**Observed:** A left-aligned 42px statement starts in #7f7f7f and finishes white. After 60px, a three-column Capability card grid uses Outline capability panel. Technical diagrams occupy the upper card region; 32px titles and light 16px paragraphs sit below.

**Transfer:** Use the gray clause for context and the white clause for the decisive benefit. Let the card collection explain distinct facets, not repeat the same claim.

**Text style:** `statement` — Figtree 300 · 42px/1.2 · tracking -0.03em · capitalize

### Long product inspection chapter

**Observed:** A 326px descriptive column sits beside media around 693px wide. Equipment badge, chapter-heading and chapter-body are vertically centered in 900px-tall chapter stops. Large black gaps give the changing interface scene its own attention; a thin technical band introduces the sequence.

**Transfer:** Use the long scrollytelling treatment for a few genuinely different operations, with a persistent media stage and concise text. Match each chapter to a visible product change rather than padding a static screenshot.

**Text style:** `chapter-heading` — Figtree 400 · 28px/1.2 · tracking -0.04em

### Luminous conversion stage

**Observed:** A 550px closing section includes a 430px Pixel signal field and 120px bottom padding. The short closing headline is centered above Primary button with a 40px gap; white text glow is restricted to the headline. Product-detail pages use a 720px-wide, 40px split-tone statement in this same sparse field instead.

**Transfer:** Make one clear final invitation, framed by small lilac signals. Use the longer statement variant only when a specific product story needs a concluding synthesis.

**Text style:** `closing` — Figtree 500 · 64px/1 · capitalize

### Monumental ribbon and practical footer

**Observed:** Patterned emblem ribbon occupies 175px before the practical footer. The footer begins with 80px top padding: logo and positioning on the left, three Footer link columns on the right with 65px column gaps. Muted copyright and certification sit lower left. A 54px technical stripe band finishes the page; Hatched edge rails continue to the bottom.

**Transfer:** Keep both the oversized graphic transition and the small useful navigation. Give the new identity its own abstract ribbon motif, and include trust or compliance marks only when valid.

**Text style:** `footer-positioning` — Figtree 300 · 22px/1.25 · tracking -0.01em · capitalize

### Screenshot-led detail grid

**Only for:** product detail pages

**Observed:** Three 352×558px outlined cards place a dark image about 302px wide above a 24px title and substantial 16px support. A separate borderless three-column benefit row uses small lilac icons, white headings and gray explanations in the same 24px recipe; 160px below gives the closing statement room.

**Transfer:** Use screenshots for concrete mechanics, then a shorter icon row for resulting assurances. Preserve the larger gray benefit text rather than shrinking every description to caption size.

**Text style:** `detail-heading` — Figtree 400 · 24px/1.2 · tracking -0.035em

### Commercial comparison and questions

**Only for:** pricing pages

**Observed:** Two equal Plan cards sit 32px apart under the centered promise; one receives Highlighted plan panel. There are no prominent numeric prices. Proof precedes a centered 32px question heading, followed after 40px by an 856px-wide FAQ column and 160px of bottom breathing room.

**Transfer:** Use outcome and fit to distinguish consultative offers. Put buyer objections into direct accordion questions rather than adding more plan rows.

**Text style:** `plan-heading` — Figtree 300 · 40px/1.1 · tracking -0.03em

## Page flow

**Storyline:** Promise → system demonstration → recognition and human proof → capability explanation → concrete product inspection or commercial detail → final invitation → graphic signature and practical footer.

### Broad product marketing landing page

1. **Promise** — Centered light headline, short support and one lilac action above a wired system diagram.
2. **Social proof** — Trust-logo region followed by a compact two-by-two customer identity group with star ratings.
3. **Capability overview** — Split-tone statement and three outlined technical illustration cards.
4. **Product demonstration** — Striped transition followed by long chapter stops pairing narrow copy with a large changing interface view.
5. **Closing call** — Short glowing invitation in a sparse pixel field.
6. **Wayfinding** — Oversized patterned ribbon, identity block, three footer columns and terminal stripe band.

**Transfer:** Use this as the default visual grammar, adapting the number and order of explanatory blocks to the product.

### Consultative commercial comparison

1. **Offer framing** — Centered two-line promise above two outcome-led plans; one outlined and glowing, the other plain charcoal.
2. **Social proof** — Trust region and the compact customer endorsement group.
3. **Objection handling** — Ten closed accordion rows beneath a centered heading.
4. **Closing call** — The same short luminous invitation and lilac action.
5. **Wayfinding** — Patterned ribbon and shared practical footer ending in the striped band.

**Transfer:** Preserve the technical material treatment while prioritizing buyer fit and questions; do not force numeric pricing where the offer is consultative.

### Specific product capability explanation

1. **Focused promise** — Left-aligned label, multiline headline, support and action opposite a dark workflow graph.
2. **Product mechanics** — Three tall outlined screenshot cards with detailed prose.
3. **Resulting assurance** — Three borderless icon-led benefits with unusually large gray support.
4. **Closing synthesis** — A centered split-tone statement and action surrounded by sparse lilac cells.
5. **Wayfinding** — Patterned emblem ribbon and the shared footer with its bottom stripe band.

**Transfer:** Use a compact, evidence-rich product story rather than reproducing the long landing-page walkthrough.

## Writing

Calm technical confidence, with a clear operational vocabulary. It promises autonomy while repeatedly explaining visibility, continuity and human control rather than relying on futuristic hype.

**Do not copy:** Do not reuse the Clears name, logo, proprietary artwork, customer identities or portraits, endorsements, star ratings, security certifications, integration claims or product performance claims. Source examples illustrate phrasing only; replace them with substantiated content for the new product.

- **Addressing the reader:** Use 'your' to frame the promise and 'you' when describing control. Name the product directly when explaining the mechanism; avoid a chatty first-person brand persona.
- **Rhythm:** Short declarative headlines contrast with longer mechanism-rich supporting sentences. Lists of parallel operations and compact reassurance clauses give the copy its cadence. Actions are terse; exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A possessive phrase naming a substantial new operating capability. | 4–8 words | “Your Autonomous Software Factory” |
| Capability title | A compact benefit with an operational constraint or assurance. | 3–6 words | “Parallel, Always Visible”<br>“Observable, not a black box” |
| Support | Explain what happens, which operations connect, and what the user retains. | 20–50 words | “Every run streams a live event view: codebase exploration, file edits, commands, PR creation. Human checkpoints sit exactly where they belong: approve a spec, review subtasks, request a fix. You steer; the agents execute.” |
| Primary action | Direct invitation to a real next step, rendered uppercase by the control. | 2–4 words | “Book a Demo” |
| Closing invitation | Short imperative with the product name and immediate time cue. | 3–5 words | “Try [Brand] Now.” |
| Buyer question | Plain-language concern stated as an actual question. | 5–12 words | “Do I need to change my current processes?” |

**Words and phrasing to use:** in plain view; coordinate; context; reliable; observable; across; continuously; with you in control; every checkpoint

**Avoid:** magic; revolutionary; game-changing; supercharge; AI wizard; effortless everything

**Rules:**

- Pair a high-level promise with a concrete mechanism in the next paragraph.
- Use parallel verbs to explain linked operations; close with a short assurance of control.
- Keep jargon meaningful to the intended buyer and give it an observable consequence.
- Use lowercase support as a deliberate capability-card variant, not a sitewide grammar rule.

## Do's and Don'ts

### Do

- Keep the main field black and preserve the 48px hatched side rails.
- Set the default promise in weight 300 Figtree with -0.03em tracking and line height 1.
- Keep hero support within 680px and separate the major opening items by 30px.
- Use 4px control corners and a tiny black square on the lilac conversion button.
- Use #2c2c2c hairlines around capability panels rather than filled bright cards.
- Keep large interface imagery dark, legible and much wider than its companion description.
- Include the sparse lilac pixel motif and the oversized low-contrast footer ribbon.
- Use gray-to-white emphasis inside one statement without changing font weight.

### Don't

- Do not turn the palette into alternating white and purple section backgrounds.
- Do not use rounded pill buttons or inflated 20px card corners; these controls are rectilinear.
- Do not make the opening promise heavy or set all marketing headlines in monospace.
- Do not apply the closing headline's 12px white halo to body copy or every heading.
- Do not enlarge the lilac stars and nodes into broad colorful illustrations.
- Do not shrink the product-detail benefit explanations below their 24px treatment to make a conventional icon grid.
- Do not introduce floating white testimonial cards; human proof sits directly on black.
- Do not add a numeric pricing hero when the offer is expressed through fit, outcomes and consultation.

## Motion and responsive

### Motion

**Observed:**

- Controls declare 0.15s transitions using cubic-bezier(.4, 0, .2, 1), including color, border, shadow and transform properties.
- A trust-logo loop is declared at 40s linear infinite; the patterned band scroll is declared at 150s linear infinite.
- Accordion enter/exit and open/close keyframes are declared.

**Transfer:**

- Keep the patterned identity motion slow enough to remain an architectural texture.
- Use the declared short transitions for the button color and border changes, not theatrical scale jumps.

**Unknown:**

- Exact diagram animation sequencing, scroll synchronization and accordion timing are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 520px, 560px, 640px, 681px, 768px, 900px, 1024px, 1280px, 1440px, 1536px and 1920px.
- The header has an 80px small-screen height declaration and a 97px larger-screen variant; desktop navigation is hidden below its large-screen layout.
- Main containers declare 24px small-screen side padding. Side rails are hidden below the small-screen breakpoint.

**Transfer:**

- On narrow screens, stack the product-detail text above its graph and let the system diagram scale as a coherent object rather than scattering nodes.
- Stack plan and capability cards, preserve thin edges and the lilac control material, and keep the patterned ribbon clipped horizontally.
- Replace the long side-by-side walkthrough with sequential text-and-media chapters while retaining the narrow-copy-to-wide-media hierarchy.

**Unknown:**

- Mobile rendering, menu behavior and exact intermediate container insets were not visually established; stacking guidance is a transfer recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
