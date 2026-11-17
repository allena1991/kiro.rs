# Upstash — mint-powered infrastructure

## Overview

An optimistic developer-product style with enormous condensed grotesk promises, emerald-to-gold lettering and soft mint light on a pale gray canvas. White, deeply rounded panels make technical detail feel approachable; dark code windows and dotted globe graphics supply the engineering texture. It suits platform launches and technical services, with airy section pacing and denser, practical comparison content.

### Essentials

- Promises behave like colored architecture: centered Inter Tight at 128px/1, weight 700, -0.025em tracking, split into two emphatic lines rather than a small heading beside an illustration.
- The first screen is type-led, not image-led: a 117px announcement/navigation assembly, 64px hero padding, 24px support text and paired 44px actions lead into a broad white product panel visible before the fold.
- Emerald is light and energy rather than a full-page paint bucket: #f5f5f5 and white dominate, with blurred mint washes behind chapter headings, #00bc7d actions, and amber restricted to gradient endpoints and small numerical accents.
- Buttons are compact rounded rectangles, not pills: 12px corners, 16px medium-weight Inter, 8px vertical padding; the secondary hero action has a 2px mint-to-yellow frame around a white 10px-radius interior.
- Technical proof is staged as friendly instruments: 35.2px-radius white cards with 32px padding hold small green diagrams or black code panels, while headings and explanations remain outside the dense interface detail.
- A monumental proof scene is a signature device: 180px gradient words sit behind a pale dotted spherical object, with a floating four-stat tray using 30px semibold numerals. Recreate the dot sculpture and tray with product-relevant evidence even when there is no globe-shaped subject.
- The ending becomes smaller and more utilitarian, not louder: a centered 688px content column, small identity mark, two short link rows, paired mint operational-status pills and fine print within 96px vertical padding.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest ink | `#022c22` | `--color-ink` | text | Default headings and body text; deep green rather than black. |
| Electric emerald | `#00bc7d` | `--color-primary` | action, accent | Primary buttons, active indicators and headline gradient midpoint. |
| Deep emerald | `#007a55` | `--color-link` | link, text | Secondary actions, statistics and gradient starts. |
| Secondary forest | `#065f46` | `--color-forest` | text | Secondary hero-action label and product-panel lead text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement mint | `#ecfdf5` | `--color-announcement` | background | Thin announcement band and secondary-action hover. |
| Status emerald | `#10b981` | `--color-status` | text, accent | Status pill labels and pulsing dots. |
| Status mint wash | `#e2f2ec` | `--color-status-wash` | surface | Visible #34d399 at 0.1 over the gray canvas, behind operational links. |
| Bright mint | `#34d399` | `--color-mint` | accent, text | Gradient frame start, glow accents and terminal command text. |
| Amber endpoint | `#f59e0b` | `--color-gold` | accent | Warm endpoint of display gradients and small instrument values, not broad page fills. |
| Frame yellow | `#fcd34d` | `--color-yellow` | accent | Warm end of the outlined hero action. |
| Proof gradient yellow | `#fde047` | `--color-proof-yellow` | accent | Warm endpoint of monumental proof lettering. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-white` | surface, text | Cards, selected tabs and reversed action text. |
| Pale gray canvas | `#f5f5f5` | `--color-canvas` | background | Main page field and proof tray. |
| Mint panel wash | `#e2ebe7` | `--color-mint-wash` | surface, border | Visible 8% #047857 over the gray canvas; use rgba(4,120,87,0.08) for soft panels, table cells and edges. Over white this is lighter. |
| Muted zinc | `#71717a` | `--color-muted` | text | Body explanations and navigation; support lines may instead use forest ink at 0.6 opacity. |
| Terminal charcoal | `#09090b` | `--color-terminal` | surface | Command bars and code panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Code light text | `#e4e4e7` | `--color-code-text` | text | Default syntax text. |
| pricing pages | Upgrade lavender | `#faf5ff` | `--color-purple-wash` | surface | Upgrade panel gradient start. |
| pricing pages | Upgrade lavender edge | `#e9d5ff` | `--color-purple-rule` | border, surface | Upgrade outline and price badge. |
| pricing pages | Upgrade purple | `#6b21a8` | `--color-purple-ink` | text | Upgrade title and badge labels. |
| pricing pages | Sales cream | `#fffbeb` | `--color-amber-wash` | surface | Sales tier gradient start. |
| pricing pages | Sales yellow edge | `#fde68a` | `--color-amber-rule` | border, action | Sales tier outline and small action. |
| pricing pages | Sales brown | `#92400e` | `--color-amber-ink` | text | Sales tier title and checklist. |
| pricing pages | Selected plan mint | `#c5e2d9` | `--color-selected-plan` | surface | Visible 20% #059669 over gray for the emphasized comparison column. |

## Typography

- **Inter** — Body, support lines, controls, navigation and quotes. Neutral high-x-height grotesk, with regular body and restrained medium actions. Font stack: "Inter", Arial, sans-serif.
- **Inter Tight** — Hero lettering, section headings, card headings and statistics. Compact grotesk with a dense silhouette and tightly packed display words. Font stack: "Inter Tight", Inter, Arial, sans-serif.
- **JetBrains Mono** (only for technical demonstrations) — Executable commands and code examples. Technical monospaced texture used in small isolated dark windows. Font stack: "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| proof-display | Inter Tight | 700 | 180px | 1.25 | normal | size min(12vw, 180px) | Oversized atmospheric words behind the proof sculpture. |
| display | Inter Tight | 700 | 128px | 1 | -0.025em | fixed | Default marketing hero; centered two-line gradient headline. |
| heading | Inter Tight | 600 | 48px | 1 | normal | fixed | Core chapter headings. |
| stat | Inter Tight | 600 | 30px | 1.2 | normal, features "tnum" | fixed | Floating proof tray numerals. |
| support | Inter | 400 | 24px | 32px | normal | fixed | One short centered sentence below the hero and core chapter titles. |
| card-heading | Inter Tight | 600 | 24px | 32px | normal | fixed | Card titles and product selectors. |
| body | Inter | 400 | 16px | 24px | normal | fixed | Explanations, navigation and footer links. |
| action | Inter | 500 | 16px | 24px | normal | fixed | Buttons and short action links. |
| caption | Inter | 400 | 14px | 20px | normal | fixed | Announcement text and small supporting labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise sales pages | sales-display | Inter Tight | 700 | 72px | 1 | normal | fixed | Longer two-line promise in a narrower hero. |
| pricing, customer and company pages | page-title | Inter Tight | 600 | 48px | 1.16 | normal | fixed | Compact purpose-led page openings. |
| supporting pages | subheading | Inter Tight | 600 | 36px | 1.16 | normal | fixed | Supporting page sections and sales closing call. |
| enterprise sales pages | sales-eyebrow | Inter Tight | 400 | 24px | 32px | 0.05em, uppercase | fixed | Category label above the sales promise. |
| supporting pages | support-compact | Inter | 400 | 20px | 28px | normal | fixed | Supporting page introductions and sales quotes. |
| customer proof galleries | quote | Inter | 600 | 20px | 28px | normal | fixed | Centered customer quotation with emerald-to-forest text gradient. |
| company pages | person-name | Inter Tight | 500 | 20px | 28px | normal | fixed | Names beneath circular portraits or partner marks. |
| pricing pages | faq-question | Inter | 500 | 18px | 1.625 | normal | fixed | Question rows in the accordion. |
| technical demonstrations | command | JetBrains Mono | 400 | 14px | 20px | normal | fixed | Single-line executable commands. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Only the largest hero uses negative tracking; most headings retain normal spacing. Keep Inter Tight for compact title silhouettes and Inter for longer reading.
- Gradient display lettering clips the color field to text; it is not translucent body text. Support lines use muted zinc or forest ink at 0.6 opacity.
- The proof-display size follows 12vw below its 180px desktop cap; the main hero switches between fixed size classes rather than following a continuous viewport formula.

## Layout

**Density:** Airy chapter spacing around compact technical panels; generous white margins prevent dense detail from taking over the page.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap, icon spacing and tight controls. |
| 12px | Card-title-to-copy gap and action-row spacing. |
| 16px | Paired hero action gap, small panel padding. |
| 24px | Main grid gaps, support-to-action gap and internal group separation. |
| 32px | Default feature-card padding and customer-gallery gap. |
| 40px | Desktop container side padding and major footer subgroup gaps. |
| 64px | Hero padding and lighter chapter padding. |
| 80px | Heading-to-feature-grid separation. |
| 96px | Major chapter and footer vertical padding. |
| 112px | Spacious capability chapter vertical padding. |
| 128px | Company chapter padding and proof-scene separation. |
| 160px | Separation before comparison and FAQ chapters. |

### Containers and grids

- **Main container**: max width 1280px · side padding 40px. Centered outer width produces 1200px usable content; common shell for hero, cards and navigation.
- **Compact container**: max width 1024px · side padding 40px. 944px usable width for sales stories, pricing cards and company introduction.
- **Heading measure**: max width 768px. Centered chapter-heading group.
- **Reading container**: max width 768px · side padding 40px. 688px usable content for FAQ and footer.
- **Capability grid**: 6 columns · gap 24px. Two half-width cards followed by a two-thirds card beside a one-third card; use content to determine height.
- **Customer grid** (only for customer proof galleries): 2 columns · gap 32px. Equal-width quotation cards, with variable row height.
- **Plan grid** (only for pricing pages): 3 columns · gap 24px. Three equal plan cards across the compact container.
- **Company people grid** (only for company pages): 3 columns · gap 40px. Centered wrapping portrait gallery; incomplete final row stays centered.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Major panels | 35.2px |
|  | Buttons | 12px |
|  | Code windows | 16px |
|  | Status pills | 9999px (pill) |
| enterprise sales pages | Sales benefit panels | 24px |
| company pages | Circular portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Card lift | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Minimal elevation under white feature cards. |
| Proof tray | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | The floating numerical proof tray. |
| Mint halo | `0px 0px 80px 0px rgba(16,185,129,0.3)` | A pale green rim around the spherical proof object. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light page field.

**CSS:** `background: #f5f5f5; color: #022c22`

#### Mint atmosphere · level 0

**Use:** Diffuse light behind hero and chapter headings.

**CSS:** `background: radial-gradient(ellipse at center, rgba(52,211,153,0.18) 0%, rgba(52,211,153,0) 70%)`

**Observed:** Broad low-contrast mint illumination merges into gray without a hard band boundary.

**Transfer:** Place a wide, shallow light field behind the text group. Match the soft glow; exact stops are not essential.

#### White instrument card · level 1

**Use:** Capability and integration content.

**CSS:** `background: #ffffff; border-radius: 35.2px; padding: 32px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** White panels are the main material; selected technical cards add a faint 1px black-at-5% edge.

**Transfer:** Keep one compact explanatory group above a restrained demonstration.

#### Mint inset · level 1

**Use:** Nested feature panels, logo lozenges and trial callout.

**CSS:** `background: rgba(4,120,87,0.08); border-radius: 16px; padding: 32px`

**Observed:** Soft green insets distinguish content without heavy borders; logo lozenges are pill-shaped and the trial panel uses 35.2px corners.

#### Terminal window · level 2

**Use:** Code and command contrast within a white card.

**CSS:** `background: #09090b; border: 1px solid rgba(255,255,255,0.1); border-radius: 16px; color: #34d399`

#### Lavender upgrade panel · level 2

**Only for:** pricing pages

**Use:** Paid capability pack inside a white parent panel.

**CSS:** `background: linear-gradient(to right, #faf5ff, #ffffff); border: 2px solid #e9d5ff; border-radius: 24px; padding: 40px 64px`

**Observed:** Left title and price badge face a right cluster of outlined check tags.

#### Cream sales panel · level 2

**Only for:** pricing pages

**Use:** Sales-led tier inside the same white parent panel.

**CSS:** `background: linear-gradient(to right, #fffbeb, #ffffff); border: 2px solid #fde68a; border-radius: 24px; padding: 40px 64px`

**Observed:** Brown copy and amber checks preserve a warmer scoped variant.

#### Company band · level 0

**Only for:** company pages

**Use:** People and backer chapter.

**CSS:** `background: linear-gradient(rgba(0,0,0,0.03), #f5f5f5)`

**Observed:** A faint gray top fade, not a colored portrait-card grid.

## Components

### Announcement bar

**Use:** Single short product news item above navigation.

**CSS:** `background: #ecfdf5; border-bottom: 1px solid rgba(16,185,129,0.2); height: 36px; padding: 0px 16px; display: flex; justify-content: center; align-items: center; gap: 6px`

**Text style:** `caption` — Inter 400 · 14px/20px

**Observed:** A medium-weight short prefix precedes an underlined news phrase and arrow. It stays part of the fixed header.

**States:** Declared: hover background becomes #d1fae5; focus-visible unspecified.

### Navigation link

**Use:** Low-emphasis desktop navigation.

**CSS:** `color: #71717a; border-radius: 9999px; padding: 8px 12px; display: flex; align-items: center`

**Text style:** `body` — Inter 400 · 16px/24px

**Observed:** Logo left, links centered, login right in an 81px row. Active page links gain a mint pill; the default links remain unfilled.

**States:** Declared: hover background rgba(255,255,255,0.05) and text #007a55; focus-visible unspecified.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #00bc7d; color: #ffffff; border-radius: 12px; padding: 8px 20px; height: 44px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — Inter 500 · 16px/24px

**Observed:** A short label leads a northeast arrow. Supporting-page buttons use 40px height and 16px horizontal padding.

**States:** Declared: hover background #007a55 and shadow removed; focus-visible unspecified.

### Secondary button

**Use:** Exploration and resource actions inside content cards.

**CSS:** `background: rgba(4,120,87,0.08); color: #007a55; border-radius: 12px; padding: 8px 20px; display: inline-flex; align-items: center; gap: 8px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter 500 · 16px/24px

**Observed:** Right arrow or document glyph follows the label. Resource tiles use a shorter 40px version with 16px horizontal padding.

**States:** Declared: hover background rgba(4,120,87,0.2); focus-visible unspecified.

### Gradient frame action

**Use:** Secondary setup action beside the hero conversion.

**CSS:** `background: #ffffff; color: #065f46; border-radius: 10px; height: 40px; padding: 0px 20px; display: flex; align-items: center; gap: 10px`

**Text style:** `action` — Inter 500 · 16px/24px

**Observed:** Wrap this interior in a 2px-padded, 12px-radius mint-to-yellow gradient frame. A compact cluster of overlapping circular service icons leads the label; a down chevron closes it.

**States:** Declared: hover interior #ecfdf5; focus-visible unspecified.

**Transfer:** Use a small cluster of relevant integration icons or a single tool icon instead of unrelated decorative badges.

### Feature card

**Use:** Default illustrated capability block.

**CSS:** `background: #ffffff; border-radius: 35.2px; padding: 32px; display: grid; gap: 32px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `card-heading` — Inter Tight 600 · 24px/32px

**Observed:** Left-aligned title and muted explanation sit above a compact diagram or product window. In wider integration cards, the text and command sit side by side.

**Transfer:** Use one claim, one short explanation and one inspectable piece of product evidence.

### Proof tray

**Use:** Quantified evidence over the dotted sculpture.

**CSS:** `background: #f5f5f5; border-radius: 35.2px; padding: 24px 48px; display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 48px; backdrop-filter: blur(8px); box-shadow: 0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)`

**Text style:** `stat` — Inter Tight 600 · 30px/1.2

**Observed:** Four centered green numerical values each have a body-sized descriptor. A separate italic 16px footnote qualifies the set below the tray.

**Transfer:** Use verified numbers with short units and preserve their qualification.

### Status pill

**Use:** Operational reassurance in the footer.

**CSS:** `background: rgba(52,211,153,0.1); color: #10b981; border-radius: 9999px; padding: 8px 16px; display: inline-flex; align-items: center; gap: 8px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter 500 · 16px/24px

**Observed:** A 12px current-color pulsing dot precedes the label; two pills sit together below footer links.

**States:** Declared: hover background rgba(4,120,87,0.2); focus-visible unspecified.

### Command bar

**Only for:** technical demonstrations

**Use:** Copyable setup command within a technical card.

**CSS:** `background: #09090b; color: #34d399; border: 1px solid rgba(255,255,255,0.1); border-radius: 16px; padding: 12px 16px; display: flex; align-items: center; gap: 12px`

**Text style:** `command` — JetBrains Mono 400 · 14px/20px

**Observed:** One unwrapped command, a dim prompt at the start, and copy control at the right; overflow scrolls horizontally.

### Testimonial card

**Only for:** customer proof galleries

**Use:** Customer gallery proof.

**CSS:** `border: 4px solid rgba(4,120,87,0.08); border-radius: 35.2px; padding: 64px; display: flex; flex-direction: column; align-items: center; gap: 24px; overflow: hidden`

**Text style:** `quote` — Inter 600 · 20px/28px

**Observed:** A black customer logo leads, the centered emerald-to-forest quote occupies the growing middle region, and name plus muted role anchors the bottom. A fine divider separates identity from quotation.

### Plan card

**Only for:** pricing pages

**Use:** Compact plan overview.

**CSS:** `background: #ffffff; border-radius: 35.2px; padding: 32px; display: flex; flex-direction: column; align-items: center; gap: 24px; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `body` — Inter 400 · 16px/24px

**Observed:** Plan title and price lead; a tinted use-case label, ruled specification rows and bottom action follow. The emphasized middle card adds a 2px emerald edge, not a dark fill.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling beneath comparisons.

**CSS:** `border-top: 1px solid rgba(4,120,87,0.08); text-align: left`

**Text style:** `faq-question` — Inter 500 · 18px/1.625

**Observed:** A full-width question button has 24px padding with a plus at the far right. Answers use body text and inset padding. Open rows gain a mint surface and 16px corners.

## Imagery and graphics

### Dotted proof sculpture

**Use:** Signature visual chapter paired with monumental words and quantitative proof.

**Observed:** A huge pale globe curves above the lower boundary, carrying dark gray continental dot fields. Perspective compresses dots toward the horizon; mint rim light softens the silhouette. It overlaps the lower half of oversized lettering and fades into the page behind the proof tray.

**Transfer:** Retain a dimensional dotted object and pale mint lighting. For a product without a geographic story, use a dotted sphere or curved network shell; the minimum is a convincing curved dot field rather than a flat icon.

**Build:** Create an SVG or canvas hemisphere as a pale circular disc about the page width. Project evenly spaced points on a sphere, compress their spacing toward the horizon and shade the dots gray with lower opacity toward the bottom. Add a mint outer halo with rgba(16,185,129,0.3) and an 80px blur-like spread; place a gray-to-transparent mask over its lower edge. Layer the giant gradient words behind it and the proof tray in front.

### Mint light fields

**Use:** Recurring atmospheric backdrop behind opening and chapter headers.

**Observed:** Wide, shallow, very soft green illumination with no visible texture, hard edge or neon center. Most of the page remains pale gray or white.

**Transfer:** Use the same low-intensity lighting to connect text-led sections; do not turn it into a full saturated background.

**Build:** Position a broad elliptical radial gradient behind the heading group using rgba(52,211,153,0.18) fading to zero alpha around 70%; spread it across most of the container and soften its edges.

### Product instruments

**Use:** Small technical evidence within feature panels.

**Observed:** Black code panes, mint miniature meters, numbered lists, small value tiles and sparse line diagrams provide detail. White card framing keeps these insets subordinate to the promise above.

**Transfer:** Create a working-looking excerpt of the new product: a short code sample, small measured chart or interface fragment. Keep interface colors within the product-ui palette and avoid a full dashboard covering the opening.

### Monochrome proof marks

**Use:** Customer quote headers and supporting logo wall.

**Observed:** Customer marks are predominantly black or forest green, centered in white quote panels or mint pill lozenges. A six-column wrapping wall follows a single-quote carousel.

**Transfer:** Normalize approved partner marks to one color while respecting their proportions; keep small brands and long wordmarks optically balanced.

### Green benefit illustrations

**Only for:** enterprise sales pages

**Use:** Right-hand visual anchor in wide benefit panels.

**Observed:** Simple flat vector diagrams in several greens: growing rounded bars linked by arcs, upward arrows, and clustered hexagons. Illustrations occupy roughly a quarter of the card width, with no enclosing illustration box.

**Transfer:** Use elementary vector metaphors for the new benefits, keeping the palette green and the construction sparse.

**Build:** Draw five ascending rounded bars with forest-to-mint fills, connect their tops with thin green arcs and finish with a small dot; or arrange outlined and filled hexagons in a compact honeycomb. Leave white space around the diagram.

### Circular people gallery

**Only for:** company pages

**Use:** Human credibility chapter.

**Observed:** Natural-color head-and-shoulder photographs and colored organization marks use equal circular framing, unboxed against a faint gray band. Three columns carry centered names and lighter role lines; no portrait overlays or dramatic grading.

**Transfer:** Use consistent circular crops of real collaborators or relevant partner marks with concise captions.

### Icons

**Observed:** Mostly rounded outline SVGs: 24px with 1.5px strokes inside cards; 16px with 2px strokes for small arrows; community tiles use 48px icons with 1px strokes. Colors follow forest text, emerald accents or reversed white.

**Transfer:** Choose one rounded line-icon family and preserve the thin stroke; reserve filled colored marks for genuine product or integration identities.

## Section recipes

How recurring sections are built.

### First screen: Type-led opening

**Observed:** A fixed two-tier header takes 117px, with a 36px mint announcement strip above an 81px navigation row. Beneath it, a 1280px centered container with 40px side padding holds a two-line gradient promise at 128px/1 and weight 700. It spans most of the usable width but the words themselves occupy roughly the middle two-thirds; the second line is wider. Behind the text is a diffuse mint ellipse on pale gray. The 24px muted support line follows after 8px, then primary and gradient-frame actions after 24px, separated by 16px. The hero uses 64px top and bottom padding. Within 900px the entire headline, support and actions are visible, plus the attached tab row and the beginning of a 1200px white product panel; the inset feature details and dark code example continue below.

**Transfer:** Make the new product's category promise the main visual object. Use two short lines and the same colored letter mass, with the real product panel beginning near the lower edge. No elaborate source artwork is needed for this first screen. Supporting information pages open with a compact 48px title and 20px support line; sales-led pages use a 24px uppercase category and a 72px gradient promise.

**Avoid:** Do not replace the central typography with a split-screen dashboard hero, floating mockup collage or dark full-screen opening.

**Text style:** `display` — Inter Tight 700 · 128px/1 · tracking -0.025em

### Attached product chapter

**Observed:** A row of product tabs rests directly on a White instrument card: the selected tab is white and 80px tall; inactive tabs are 64px tall with gray backing, faint green top/side borders and 16px top corners. Inside, a centered 24px lead and compact action cluster precede three mint feature insets with 32px gaps, then a wide black example window.

**Transfer:** Use attached tabs only when content genuinely has peer modules; otherwise preserve the broad white stage and nested practical demonstration.

### Monumental quantified proof

**Observed:** A 500px-tall clipped scene combines proof-display words, Dotted proof sculpture and Proof tray. The tray is 786px wide and floats over the lower portion of the sphere; a small italic qualifier sits below.

**Transfer:** Use the required sculpture-and-stat device wherever evidence belongs in the narrative; it need not occupy the same sequence position.

**Text style:** `proof-display` — Inter Tight 700 · 180px/1.25

### Heading pair and capability bento

**Observed:** Centered heading and support sit within 768px, separated by 8px. After 80px, a six-column grid with 24px gaps stages Feature cards: two equal cards above a wide code-oriented card and narrow diagram card. Chapter padding reaches 112px.

**Transfer:** Keep heading groups centered but card copy left-aligned. Let the new product's evidence determine the spans and inset type.

**Text style:** `heading` — Inter Tight 600 · 48px/1

### Integration toolkit

**Observed:** A wide first White instrument card pairs copy and link on the left with a Command bar on the right; two half-width cards below contain shorter setup descriptions. Small pill badges identify compatible tools.

**Transfer:** Use this arrangement for adoption paths, integrations or workflow aids, retaining commands only when executable.

### Customer proof and resource close

**Observed:** One centered white quote panel is followed by small carousel indicators and a six-column mint logo wall. A later resource row uses four white tiles separated by 8px: only the outer edges have 35.2px corners, while inner corners are 8px. Each tile centers a 48px line icon, title, short description and Secondary button.

**Transfer:** Pair human proof with a practical next step or support destination. The resource row can be adapted to guides, help channels or learning routes rather than a generic conversion banner.

### Compact operational footer

**Observed:** The ending is identical in structure across page types: 96px vertical padding, centered small identity mark, copyright/location line after 40px, two short link rows with 16px separation, two Status pills after 40px and a small muted legal/technical note group after another 40px. The reading width is 688px. There is no dark footer band or multi-column sitemap.

**Transfer:** End with utility, identity and operational trust. Include only relevant legal notes and a concise technical access note when the product needs one.

### Pricing decision system

**Only for:** pricing pages

**Observed:** A compact title/support opening leads to a bordered segmented product selector and three Plan cards. Lavender upgrade and cream sales panels share one rounded white wrapper. A full-width five-column comparison follows, with the first column for criteria, 4px column gutters, 65px typical data rows, pale mint plan columns and a stronger green recommended column. Category bars fade from mint toward gray, and plan labels remain available while scrolling. A 688px FAQ column follows after 160px.

**Transfer:** Separate fast plan selection from detailed evaluation. Keep lavender and cream as scoped offer distinctions, not general brand section colors.

**Text style:** `page-title` — Inter Tight 600 · 48px/1.16

### Sales reassurance and trial close

**Only for:** enterprise sales pages

**Observed:** An uppercase category introduces a 72px two-line gradient promise and one action. A pale sphere bridges into centered wrapping benefit chips with green icon discs. Wide 944px white panels use 24px corners and 48px 64px padding, placing explanation left and simple green vector art right. A two-column testimonial group leads into a 944px mint trial panel with 80px 48px padding, 36px title, 20px support and one action.

**Transfer:** Use this variant for consultative buying: address constraints, substantiate benefits, then offer a low-friction conversation rather than repeating a self-service hero.

### Customer quotation gallery

**Only for:** customer proof galleries

**Observed:** A 48px compact title and 20px introduction precede a two-column grid of Testimonial cards, 584px wide with 32px gaps. Variable quote lengths change row height while names remain anchored toward the bottom. The gallery ends directly in the shared footer.

**Transfer:** Let authentic quotes carry the page; vary length naturally but keep the identity, quote and attribution hierarchy stable.

**Text style:** `page-title` — Inter Tight 600 · 48px/1.16

### Company credibility chapter

**Only for:** company pages

**Observed:** A centered 48px promise, three short 20px introductory lines and a three-column values strip open the page. Thin mint illustrations precede short value names and body copy. A faint gray Company band then holds a 36px title and introduction, followed by a centered three-column Circular people gallery, 96px below the intro. The final incomplete row stays centered, then the shared footer ends the page.

**Transfer:** Use a small number of concrete principles and real people or institutions. Do not turn every person into a raised card.

## Page flow

**Storyline:** Category promise → practical product evidence → quantified or human proof → capability and adoption chapters → purpose-specific decision support → compact operational ending.

### Broad product-platform landing

1. **Promise** — Giant two-line gradient claim and paired actions over mint light.
2. **Product demonstration** — Attached tabs, nested benefit insets and dark code example inside one white stage.
3. **Quantified proof** — Monumental wording behind a dotted sphere and floating stat tray.
4. **Capability chapters** — Centered heading pairs introduce white bento cards and technical adoption tools.
5. **Social proof** — Quote carousel and muted logo wall.
6. **Support routes** — Four attached resource tiles.
7. **Ending** — Shared centered operational footer.

**Transfer:** Keep the type-led promise and signature proof scene; choose capabilities, adoption tools and support routes appropriate to the new product.

### Pricing and plan evaluation

1. **Orient** — Compact title, explanatory line and product selector.
2. **Choose** — Three rounded plan cards followed by two tinted offer panels.
3. **Compare** — Wide categorized matrix with a stronger mint recommended column.
4. **Resolve objections** — Narrow ruled FAQ accordion.
5. **Ending** — Shared centered operational footer.

**Transfer:** Separate fast choice from exhaustive specifications, then answer concrete billing and usage questions.

### Consultative enterprise conversion

1. **Promise** — Category eyebrow, gradient sales promise and simple action.
2. **Qualify** — Wrapping benefit chips below the pale spherical art.
3. **Reassure** — Stacked white benefit panels with green vector diagrams.
4. **Social proof** — Customer quotations in white cards.
5. **Closing call** — Mint trial panel with one meeting action.
6. **Ending** — Shared operational footer.

**Transfer:** Make the benefits address buyer constraints before asking for a conversation.

### Customer credibility library

1. **Orient** — Compact centered title and single explanatory sentence.
2. **Social proof** — Long two-column gallery of outlined quote cards with monochrome marks.
3. **Ending** — Direct transition from the final quote row to the shared operational footer.

**Transfer:** Build trust through a varied set of authentic experiences, without an unrelated sales CTA appended.

### Company and human credibility

1. **Purpose** — Compact category promise and short reader-benefit statements.
2. **Principles** — Three thin green illustrations with concise value descriptions.
3. **Credibility** — Circular institution marks and natural-color portraits on a faint gray band.
4. **Ending** — Shared operational footer after the centered incomplete gallery row.

**Transfer:** Use real principles and people to make the product promise credible; retain a light, unboxed presentation.

## Writing

Direct, technically literate and reassuring. Confidence comes from practical capabilities, short benefits and specific operational detail rather than theatrical language.

**Do not copy:** Do not reuse the Upstash identity, product names, customer or investor marks, quotations, addresses, URLs, performance numbers, pricing or unsupported claims. Examples illustrate structure and tone only.

- **Addressing the reader:** Address the developer as you or your; use we for the team and the product name for factual capability statements.
- **Rhythm:** Short category headlines and benefit labels, one-sentence support lines, then compact explanatory paragraphs. Lists and numerical qualifiers make technical detail easy to scan.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category without a slogan preamble. | 3–6 words | “Serverless Data Platform” |
| Support line | One plain sentence explaining breadth or reader value. | 7–18 words | “One platform for all your data needs”<br>“You focus on more important things.” |
| Capability heading | A concise benefit or familiar technical term. | 2–6 words | “Price scales to zero”<br>“Scalability Without Limits” |
| Body explanation | Explain what happens and why it helps, using concrete operational language. | 1–3 short sentences | “Automatic scaling to meet your demands”<br>“Keep the things as simple as possible but not simpler.” |
| Primary action | Direct verb plus an immediate step; avoid a vague aspirational label. | 1–4 words | “Start for Free”<br>“Book a Meeting” |
| FAQ question | Phrase the uncertainty as the buyer would ask it. | 7–15 words | “What happens when I hit limits on Fixed plans?” |

**Words and phrasing to use:** build; manage; debug; simple; fast; global; pay only for what you use; your resources; start free

**Avoid:** revolutionary magic; unleash limitless possibilities; supercharge everything; vague transformation claims; enterprise jargon without a concrete benefit

**Rules:**

- Lead with what the product does before describing how exceptional it is.
- Pair performance claims with units, limits or qualification.
- Use familiar technical nouns when they reduce explanation; explain the benefit in ordinary language.
- Give each card one benefit rather than an inventory of unrelated promises.
- Keep resource actions literal: Read, Join, Follow, View or an equally direct verb.

## Do's and Don'ts

### Do

- Keep the hero at 128px/1 with -0.025em tracking on desktop; make the letter mass the dominant opening object.
- Use 35.2px panel corners and 32px padding for default feature cards.
- Give main grids 24px gaps and gallery proof 32px gaps.
- Use the 12px-radius emerald action as the default; preserve the gradient-framed secondary hero action.
- Keep mint light low-contrast and behind text, allowing gray and white to dominate.
- Use the dotted dimensional proof object with the floating four-stat tray and a qualifier.
- Center chapter titles while aligning feature explanations left.
- End in the narrow 688px utility column with paired operational pills.

### Don't

- Do not turn the emerald accent into a full dark-green page theme.
- Do not give every button a pill silhouette; reserve 9999px rounding for badges, status and logo lozenges.
- Do not use monospaced type for normal body paragraphs or the giant hero.
- Do not flatten the white bento into a uniform wall of bordered small tiles.
- Do not apply lavender and cream offer colors to ordinary capability chapters.
- Do not enlarge code detail until it competes with the 48px chapter heading.
- Do not place portraits in black-and-white editorial rectangles; the human gallery uses circular natural-color images.
- Do not replace the compact footer with a dark multi-column sitemap or oversized closing slogan.

## Motion and responsive

### Motion

**Observed:**

- Declared common transitions use 0.15s cubic-bezier(0.4,0,0.2,1) for color, background, borders, opacity, shadow and transform; some surfaces declare 0.3s or 0.5s variants.
- Declared pulse uses 2s cubic-bezier(0.4,0,0.6,1), infinite, on status dots and monumental proof text.
- A quote carousel uses small circular indicators and an elongated emerald active indicator.

**Transfer:**

- Keep interaction emphasis on soft color and shadow changes rather than large movement.
- Retain the gentle operational-dot pulse and muted proof-word breathing without compromising legibility.

**Unknown:**

- Exact globe animation, carousel interval and animated gradient timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints: 420px, 520px, 640px, 768px, 1024px, 1280px and 1536px.
- Main container classes switch from 24px side padding to 40px; hero type switches from 48px to 128px at the medium layout.
- The proof tray declares two columns at narrow widths and four at medium widths; gallery cards declare one column before the two-column layout.
- Company gallery declares two items per row before three at medium widths.

**Transfer:**

- Keep the same centered type-led opening at narrow widths, using the 48px title class and wrapping the paired actions.
- Reduce card padding to 24px and stack asymmetric capability cards; preserve the dotted proof scene as a clipped curved field with a two-column tray.
- Keep long commands horizontally scrollable rather than shrinking monospace text into illegibility.

**Unknown:**

- Mobile navigation appearance and exact responsive table behavior are not visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
