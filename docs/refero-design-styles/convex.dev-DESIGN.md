# Convex — retro runtime warmth

## Overview

A warm, technically literate identity with the energy of vintage computing rather than futuristic software gloss. Cream paper alternates with near-black, chocolate and olive stages; heavy grotesk headlines meet pixel labels, readable monospace and occasional lyrical italic serif. Working interface fragments, graph-paper diagrams and small pixel constructions make the pages feel useful and playful, with compact details inside spacious chapters.

### Essentials

- Headlines behave like compressed slogans: the default opening uses 60px/0.85, weight 900, -0.04em tracking and uppercase; section headings step down to 40px/1 with -0.025em tracking.
- The opening is an actual workbench, not just a promise: a roughly 509px text column faces a 747px-wide operational panel inside a 479px dark stage, with 48px outer gutters and a 48px column gap. When no software UI exists, make a useful guided-start panel instead.
- Rounded actions contrast with squared technical details: 46px-high opening pills use 10px 20px padding, while command rows and instrument labels use 4px corners. The opening conversion pill is pale, not orange.
- Color lives in bounded mechanisms: cream, charcoal, chocolate and olive occupy almost all the page; three saturated ribbon lanes animate the opening, and vermilion is reserved for small conversion actions and status marks. Keep broad bands earthy rather than brightly saturated.
- Technical proof is made tangible: thin graph-paper lines, 10px uppercase pixel labels with 0.06em tracking, compact check rows and terminal-like controls recur alongside plain-language outcomes. Include a graph-paper proof device even when it must be drawn from simple SVG lines and real product facts.
- A constructed closing stage is a signature: a 20px graph-paper grid at 0.08 opacity sits on warm charcoal over a grainy brown gradient, surrounded by small pixel-built rings and brackets. Center a 28px bold call, a 20px italic serif response and a practical start panel; simpler institutional pages use a 56px closing statement on black instead.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement yellow | `#f3b01c` | `--color-ochre` | action, accent | Small announcement pill and the yellow family of ribbon artwork. |
| Vermilion | `#de5d33` | `--color-vermilion` | action, accent | Closing conversion actions and small error tags. |
| Earth red | `#73312b` | `--color-wine` | background, accent | Compact assurance band and warm end of the closing gradient. |
| Command peach | `#ffd7bf` | `--color-peach` | text | Command arguments and technical catalog names. |
| Brown atmosphere | `#573932` | `--color-brown-glow` | background | Base beneath the closing atmosphere. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale action | `#f1f1f1` | `--color-pale-action` | action | Default opening conversion pill. |
| Cream paper | `#f6eedb` | `--color-canvas` | background, text | Default light sections and warm reversed body text. |
| Terminal well | `#1a0f0f` | `--color-terminal` | surface | Command inputs inside the workbench. |
| Near-black ink | `#141414` | `--color-ink` | text, background | Text on cream; darkest major bands and alternate footer. |
| Charcoal band | `#191919` | `--color-dark-band` | background | Capability and objection-handling sections. |
| Deep brown chapter | `#2a1b1b` | `--color-deep-brown` | background, text | Expertise chapters and deeper technical explanation. |
| Warm charcoal | `#221f1d` | `--color-footer` | background, surface | Default footer and inset closing grid panel. |
| Chocolate stage | `#281d1d` | `--color-hero` | background | Default landing-page opening. |
| Brown panel | `#281e1d` | `--color-panel` | surface | Inset setup groups. |
| Panel edge | `#272424` | `--color-panel-edge` | border | Subtle setup panel edges. |
| Charcoal card | `#292929` | `--color-card` | surface, border, text | Raised capability cards, secondary actions and dark separators. |
| Slate tile | `#38383a` | `--color-tile` | surface | Small integration tiles. |
| Warm gray brown | `#473e36` | `--color-armadillo` | text, background | Muted dark text and subdued end of closing gradient. |
| Rifle olive | `#444435` | `--color-olive` | background | Default testimonial stage and technical demonstrations. |
| Moss band | `#5b5b45` | `--color-olive-light` | background, surface | Smaller quote cards and alternate feature bands. |
| Footer label gray | `#a9a9ac` | `--color-footer-label` | text | Footer group names and understated secondary text. |
| Muted copy | `#c2c2c2` | `--color-muted` | text | Secondary copy and workbench labels on dark. |
| Cool proof edge | `#c1cdd1` | `--color-proof-edge` | border | Fine rectangular proof-row outlines. |
| Old lace | `#faf4e9` | `--color-paper` | surface, text | Proof rows, light cards and terminal foreground; also the source hue of the setup copy control at 25% opacity. |
| Soft white | `#fffff9` | `--color-soft-white` | text | Longer lead text and capability headings on dark backgrounds. |
| White lettering | `#ffffff` | `--color-white` | text, border | Headlines, controls and thin outlines on dark stages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan gold | `#bc7914` | `--color-gold-border` | border, accent | Recommended tier outline and small popularity tag. |

## Typography

- **gtAmerica** — Body, navigation, section titles and buttons. Matter-of-fact grotesk with sturdy proportions and a generous x-height. If unavailable, use **Inter**. Use weights 300–900 and retain the tight headline tracking. Font stack: "gtAmerica", "Inter", Arial, sans-serif.
- **neue-haas-grotesk-display** — Default opening slogan. Dense black grotesk with tightly interlocked uppercase shapes. If unavailable, use **Archivo**. Weight 900; preserve the compact line height and broad, heavy letterforms. Font stack: "neue-haas-grotesk-display", "Archivo", Arial, sans-serif.
- **vcr** — Section instrument labels, setup labels and occasional oversized statistics. Square, retro terminal lettering distinct from ordinary coding mono. If unavailable, use **VT323**. Tune width to keep labels compact; do not turn body copy into pixel text. Font stack: "vcr", "VT323", monospace.
- **IBM Plex Mono** — Commands, role captions and technical annotations. Readable engineered monospace, normally regular weight. Font stack: "IBM Plex Mono", ui-monospace, monospace.
- **publico** — Testimonials, editorial interludes and the short response below the closing call. Expressive italic editorial serif, a deliberate contrast to the heavy sans. If unavailable, use **Libre Caslon Display**. Use an italic companion or italic styling; preserve the wide editorial silhouette. Font stack: "publico", "Libre Caslon Display", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | neue-haas-grotesk-display | 900 | 60px | 0.85 | -0.04em, uppercase | Default landing-page opening slogan, normally two tightly stacked lines. |
| quote | publico | 400 italic | 60px | 1 | -0.025em | Centered major testimonial. |
| heading | gtAmerica | 700 | 40px | 1 | -0.025em | Default section heading. |
| closing-title | gtAmerica | 700 | 28px | 1.1 | normal | Centered heading in the elaborate closing stage. |
| hero-support | gtAmerica | 300 | 20px | 1.25 | normal | Opening support paragraph. |
| hero-emphasis | gtAmerica | 500 | 20px | 1.25 | normal | First sentence within the opening support paragraph. |
| closing-response | publico | 400 italic | 20px | 1 | normal | Short lyrical line beneath the closing title. |
| body-lead | gtAmerica | 400 | 18px | 1.5 | normal | Section introductory paragraphs. |
| body | gtAmerica | 400 | 16px | 1.5 | normal | Ordinary explanatory paragraphs and supporting content. |
| ui-label | gtAmerica | 500 | 16px | 1.5 | normal | Navigation, opening buttons and capability card titles. |
| footer-link | gtAmerica | 400 | 15px | 1.25 | normal | Footer directory links. |
| small-action | gtAmerica | 500 | 14px | 1.5 | normal | Closing buttons and wide setup-copy control. |
| card-copy | gtAmerica | 300 | 14px | 1.5 | normal | Muted capability card descriptions. |
| footer-heading | gtAmerica | 400 | 14px | 1.25 | 0.025em | Muted footer group labels. |
| panel-label | vcr | 400 | 12px | 1.5 | 0.08em, uppercase | Setup group headings. |
| command | IBM Plex Mono | 400 | 12px | 1.625 | normal | Compact runnable commands. |
| eyebrow | vcr | 400 | 10px | 1.5 | 0.06em, uppercase | Small outlined section markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| long-form technical proof pages | editorial-display | publico | 400 italic | 70px | 75px | -0.02em | Single-statement chapter divider. |
| quantified feature proof | pixel-stat | vcr | 400 | 70px | 75px | -0.02em | Sparse numerical contrast with tiny mono captions. |
| focused product pages | product-display | gtAmerica | 700 | 60px | 0.9 | -0.05em | Sentence-case title alongside a code example. |
| pricing and institutional pages | utility-display | gtAmerica | 900 | 56px | 1 | -0.025em | Simple page title on cream. |
| pricing and institutional pages | simple-closing | gtAmerica | 700 | 56px | 1 | -0.025em | Two-line centered final promise. |

**Notes:**

- Negative tracking is concentrated in large type: -0.04em in the black uppercase opening, -0.025em in standard section titles and -0.05em in focused product openings. Body copy remains untracked.
- The serif is a change of voice, not a universal heading face. Use it for a human statement, an editorial pause or the closing response.
- Default opening support combines a medium first sentence with a light continuation at the same 20px/1.25 recipe.
- Keep uppercase instrument labels small and widely tracked; commands remain mixed case and untracked.

## Layout

**Density:** Airy chapters with compact, functional interiors: broad full-width bands contain tightly grouped labels, commands and proof rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Panel padding, internal gaps and compact control groups. |
| 12px | Heading-to-support spacing, card gaps and navigation padding. |
| 16px | Closing title-to-response spacing and card vertical padding. |
| 20px | Footer link rhythm and pricing card padding. |
| 32px | Opening text-to-action gap and editorial statement-to-caption spacing. |
| 48px | Desktop side gutters, main column gaps and separated content groups. |
| 60px | Standard major band vertical padding. |
| 80px | Roomier technical proof chapters. |
| 120px | Editorial divider breathing room. |

### Containers and grids

- **main-container**: max width 1536px · side padding 48px. Centered full-width desktop content; at 1440px the usable width is 1344px.
- **editorial-grid**: 7 columns · gap 48px. Asymmetric chapter grid; text occupies three columns and a larger demonstration four. Reverse the balance where proof rows need more room.
- **capability-grid**: 3 columns · gap 8px. Equal-width dark capability cards.
- **integration-row**: 5 columns · gap 12px. Compact logo-and-label tiles across the capability chapter.
- **closing-panel**: max width 720px. Centered workbench and short heading inside the broad grid-paper stage.
- **pricing-grid** (only for pricing pages): 3 columns · gap 20px · side padding 48px. Equal-height tier cards.
- **portrait-grid** (only for company and people pages): 4 columns · gap 8px · side padding 48px. Square portraits in a dense wall, with an incomplete last row left-aligned.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-pill | 9999px (pill) |
|  | instrument-label | 4px |
|  | setup-frame | 12px |
|  | capability-card | 16px |
|  | integration-tile | 8px |
| pricing pages | tier-card | 32px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | small-card | `0px 2px 11px 0px rgba(0,0,0,0.05)` | Low emphasis capability cards and tiles. |
|  | workbench | `0px 15px 22px 0px rgba(0,0,0,0.3)` | Outer setup frame, making it feel like a physical instrument. |
| pricing pages | tier | `0px 14px 15px 0px rgba(5,5,5,0.03)` | Subtle tier lift. |

### Surfaces

#### Cream canvas · level 0

**Use:** Light proof and utility chapters.

**CSS:** `background: #f6eedb; color: #141414`

**Observed:** Flat warm paper, without a decorative texture.

**Transfer:** Use as the main contrast to dark technical stages.

#### Dark stage · level 0

**Use:** Default opening.

**CSS:** `background: #281d1d; color: #ffffff`

**Observed:** Full bleed chocolate with colorful artwork behind the content.

**Transfer:** Keep the stage flat enough for white type to remain dominant.

#### Earth chapters · level 0

**Use:** Full-width changes of narrative tone.

**CSS:** `background: #191919; color: #fffff9`

**Observed:** Capability sections use charcoal; expertise uses deep brown; testimonials use rifle olive; supporting feature bands use moss.

**Transfer:** Change the entire band rather than adding random colored cards.

#### Setup group · level 2

**Use:** Inset groups within the workbench.

**CSS:** `background: #281e1d; border: 1px solid #272424; border-radius: 4px; padding: 8px`

**Observed:** Dark brown groups sit within a still darker framed shell.

**Transfer:** Use the layered brown tones to differentiate functional regions.

#### Closing atmosphere · level 0

**Use:** Elaborate conversion stage.

**CSS:** `background-color: #573932; background-image: linear-gradient(238deg, #73312b 2%, #473e36 69%); padding: 60px 48px`

**Observed:** Fine dark grain subdues the gradient; an inset charcoal graph-paper plane carries the actual content.

**Transfer:** Match the soft, grainy earth atmosphere; exact noise texture is not essential.

#### Graph-paper plane · level 1

**Use:** Closing stage and graphic proof.

**CSS:** `background-color: #221f1d; background-image: linear-gradient(to right, rgba(255,255,255,0.08) 1px, rgba(0,0,0,0) 1px), linear-gradient(rgba(255,255,255,0.08) 1px, rgba(0,0,0,0) 1px); background-size: 20px 20px`

**Observed:** Fine orthogonal lines remain subordinate to centered content; the plane has straight edges.

**Transfer:** Draw the grid with two CSS gradients, not a heavy engineering blueprint.

#### Tier paper · level 1

**Only for:** pricing pages

**Use:** Light tier cards.

**CSS:** `background: #faf4e9; border: 1px solid rgba(20,20,20,0.11); border-radius: 32px; box-shadow: 0px 14px 15px 0px rgba(5,5,5,0.03)`

**Observed:** Only the recommended tier changes its outline to gold.

**Transfer:** Keep all tiers on the same paper material.

## Components

### Navigation item

**Use:** Compact sticky-header directory.

**CSS:** `display: flex; align-items: center; gap: 2px; padding: 12px; color: #ffffff`

**Text style:** `ui-label` — gtAmerica 500 · 16px/1.5

**Observed:** An 80px header holds the wordmark at left, a horizontal directory, then small repository metrics and account actions. Dropdown items end with a 20px chevron. Light chapters reverse the navigation to dark ink.

**States:** Declared: hover color #d7d7d7; focus-visible outline color #fff and outline offset -4px.

### Primary button

**Use:** Default opening conversion action.

**CSS:** `background: #f1f1f1; color: #141414; border: 1px solid rgba(0,0,0,0); border-radius: 9999px; padding: 10px 20px; height: 46px`

**Text style:** `ui-label` — gtAmerica 500 · 16px/1.5

**Observed:** The pale filled pill sits beside an outlined documentation action; the pair is separated by 12px.

**States:** Declared: hover background #e5e5e5 and text #000; focus-visible box-shadow contains only zero layers.

### Secondary button

**Use:** Default opening documentation action.

**CSS:** `background: rgba(0,0,0,0.2); color: #ffffff; border: 1px solid #ffffff; border-radius: 9999px; padding: 10px 20px; height: 46px; backdrop-filter: blur(6px)`

**Text style:** `ui-label` — gtAmerica 500 · 16px/1.5

**Observed:** Light outlined pill through which the dark stage remains visible.

**States:** Declared: hover background #000; focus-visible box-shadow contains only zero layers.

### Closing action

**Use:** Conversion after proof.

**CSS:** `background: #de5d33; color: #ffffff; border: 1px solid rgba(0,0,0,0); border-radius: 9999px; padding: 8px 24px; height: 39px`

**Text style:** `small-action` — gtAmerica 500 · 14px/1.5

**Observed:** Paired with a matching white outlined documentation pill. Institutional closing stages enlarge the action to 56px high with 12px 32px padding and 20px medium text.

**States:** Declared: hover background #d62f2a; focus-visible box-shadow contains only zero layers.

### Setup workbench

**Use:** Practical start object in the opening and elaborate closing.

**CSS:** `border: 2px solid rgba(255,255,255,0.1); border-radius: 12px; overflow: hidden; box-shadow: 0px 15px 22px 0px rgba(0,0,0,0.3)`

**Observed:** A dark shell with 8px padding contains one full-width Setup group above two equal groups with an 8px gap. Top group: Panel label, Copy prompt control, short compatibility line. Lower groups: label then Command control. The lower pair becomes a single column within a container narrower than 600px.

**Transfer:** For a different product, provide one useful starting operation and two concrete next steps. For non-code products, replace commands with compact actionable instructions.

### Copy prompt control

**Use:** Primary operation inside the workbench.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; background: rgba(250,244,233,0.25); border: 1px solid rgba(250,244,233,0.3); border-radius: 9999px; padding: 4px 12px 4px 4px; height: 42px; color: #faf4e9`

**Text style:** `small-action` — gtAmerica 500 · 14px/1.5

**Observed:** Overlapping circular tool marks lead the sentence; a two-sheet copy symbol is aligned at the far right. The translucent fill reads as warm gray over brown.

**States:** Declared: hover old-lace background at 30%, border at 35% and white text; focus-visible solid white 2px outline with 2px offset.

### Command control

**Use:** Runnable or copyable starting instruction.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; background: #1a0f0f; border: 1px solid rgba(255,255,255,0.15); border-radius: 4px; padding: 4px 8px 4px 4px; height: 30px; color: #ffd7bf`

**Text style:** `command` — IBM Plex Mono 400 · 12px/1.625

**Observed:** A terminal prompt glyph precedes the command; the copy icon remains right-aligned. Keep the command a single clipped line.

**States:** Declared: hover background rgb(33, 20, 20) and white border at 20%; focus-visible uses the same fill plus a 2px white outline offset 2px.

### Capability card

**Use:** Small practical capabilities on a dark band.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 12px; background: #292929; border-radius: 16px; padding: 16px 12px; box-shadow: 0px 2px 11px 0px rgba(0,0,0,0.05); color: #fffff9`

**Text style:** `ui-label` — gtAmerica 500 · 16px/1.5

**Observed:** A tiny outlined pixel tag precedes the title; muted Card copy explains one outcome, and a dark command strip anchors the bottom. Three cards share a row.

**Transfer:** Prefer a concrete task, a useful outcome and an operation over an abstract feature icon.

### Proof row

**Use:** A compact reason to believe.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #faf4e9; border: 1px solid #c1cdd1; padding: 8px; margin-bottom: -1px`

**Text style:** `body` — gtAmerica 400 · 16px/1.5

**Observed:** Square check mark at left, medium-weight capability name followed inline by a regular-weight consequence. Rows share their touching borders rather than becoming separate floating cards.

### Footer directory link

**Use:** Dense navigation at the end of every page.

**CSS:** `display: flex; align-items: center; color: #ffffff`

**Text style:** `footer-link` — gtAmerica 400 · 15px/1.25

**Observed:** Footer heading labels are muted gray. Links form four directory groups beside a wordmark; social links and a compact trust block share the right side. External links carry a small gray northeast arrow; copyright sits alone below. Default footer is warm charcoal, with near-black on focused product and utility variants.

**States:** Declared: hover color #d7d7d7; focus-visible outline color #fff.

### Tier card

**Only for:** pricing pages

**Use:** Parallel plan selection.

**CSS:** `display: flex; flex-direction: column; gap: 32px; background: #faf4e9; border: 1px solid rgba(20,20,20,0.11); border-radius: 32px; padding: 20px; box-shadow: 0px 14px 15px 0px rgba(5,5,5,0.03)`

**Observed:** Centered plan name and audience line lead to a left-aligned price, check list and full-width pill pinned to the bottom. The recommended card has a gold outline, a tiny Popular tab above its edge and a dark button; other plan buttons are white.

**Transfer:** Distinguish recommendation through outline and button contrast, not a saturated card fill.

### FAQ row

**Only for:** objection-handling sections

**Use:** Expandable questions on charcoal.

**CSS:** `border-bottom: 1px solid #292929; padding: 32px 0px; color: #ffffff`

**Observed:** A medium 18px question aligns left and a plus aligns right; the expanded item changes the plus to a small warm-colored cross and reveals a 16px answer in cream. A section heading occupies the narrow left column while the list occupies the wider right column.

**Transfer:** Use actual buying objections, not generic marketing questions.

## Imagery and graphics

### Three-lane ribbon

**Use:** Required graphic energy in the default landing opening.

**Observed:** Flat yellow, red and purple lanes enter from the lower left, run horizontally across the bottom of the chocolate stage, then sweep upward behind the right-hand workbench and exit at the far right. Thick clean bands, rounded bends and no glow; the typography and panel remain in front.

**Transfer:** Draw an original three-lane path around the new starting object. Maintain the physical routing feeling rather than substituting an arbitrary gradient blob.

**Build:** Use three parallel SVG paths with approximately 24px strokes in golden yellow, vivid red and plum. Run the path along the bottom edge, curve upward near two thirds of the stage width, then turn right behind the panel. Use rounded joins, no shadow, and clip the artwork to the stage.

### Graph-paper proof

**Use:** Required visual mechanism supporting a concrete product benefit.

**Observed:** A large cream grid with muted blue-gray and tan blocks sits next to the proof-row list. It is a diagram-like illustration, not a polished application dashboard; its restrained palette lets the text carry the claim.

**Transfer:** Render a simple schematic of a real process or improvement. A few labeled bars, states or paths are sufficient when no product image exists.

**Build:** Draw an SVG rectangle with thin neutral grid lines at roughly 45px horizontal and 14px vertical intervals; add a handful of one- or two-cell rectangles in subdued cool gray and tan. Keep the marks sparse and align them precisely to the grid.

### Pixel constructions

**Use:** Required perimeter artwork around graph-paper calls and selected technical dividers.

**Observed:** Small open rings, brackets and stepped forms are assembled from rectangular pixels. Blue, salmon and pale yellow tiles have subtle shaded variation; the forms float partly outside the grid boundary and remain much smaller than the call.

**Transfer:** Create a set of original pixel punctuation forms rather than enlarged brand symbols. A minimum version is four five-to-eight-cell rings or brackets.

**Build:** Use SVG rectangles on a 12px modular grid to build 48–72px open rings, paired brackets and stepped arrows. Alternate pale blue and rust tiles, with a separate muted yellow family; add slight within-tile linear shading. Place forms near opposing corners and above or below the panel edges.

### Framed functional scenes

**Use:** Feature chapters on focused product and technical proof pages.

**Observed:** Readable code wells and light comparative interfaces are framed in rounded dark or cream panels. One feature scene places a compact dark activity panel over large softly lit red, gray and olive geometric forms; the image fills the wider column while prose remains narrow.

**Transfer:** Use a short, legible task state rather than a full dashboard at unreadable scale. Back it with a restrained geometric still life or a plain cream comparative panel.

**Build:** For the atmospheric variant, place a dark rounded mini-interface over two oversized cropped circles and a rectangular light field; blur the colored forms softly, add fine grain, and keep the interface crisp.

### Editorial statement stage

**Only for:** long-form technical proof pages

**Use:** A breathing pause between dense demonstrations.

**Observed:** A centered italic serif assertion spans much of the width on charcoal, moss or cream; a tiny uppercase monospace claim sits below it. Fine grid lines or a small pixel punctuation mark provide just enough ornament.

**Transfer:** Turn a supported product principle into a single lyrical sentence, then explain its practical meaning in the caption.

### Company sculpture

**Only for:** company and culture pages

**Use:** Wide image following a mission statement.

**Observed:** A dark sculptural emblem floats beside a faceted geometric plinth in a wide, sharply rectangular frame. Strong magenta and amber backlight, deep black negative space and visible film grain create an analog poster feeling.

**Transfer:** Use an original abstract form connected to the new organization, not an interface illustration.

**Build:** Minimum version: layer a dark SVG ring or folded shape above a diagonal polygonal plinth; put blurred magenta and amber radial lights behind them on black and overlay fine monochrome noise.

### Portrait wall

**Only for:** company and people pages

**Use:** Human proof after a concise company introduction.

**Observed:** Natural full-color square portraits form four tightly spaced columns. Names, pronouns and roles sit in a translucent dark bottom strip with 8px backdrop blur; a small upward arrow at the right invites more detail. Different environments and informal expressions remain visible.

**Transfer:** Use genuine portraits with varied contexts, consistent square framing and no decorative image filters.

### Icons

**Observed:** Most functional symbols are compact 16–24px SVGs, primarily filled chevrons, arrows, copy symbols and checks. The workbench uses 32px overlapping circular tool marks; catalog logos stay small and recognizable. Section icons do not dominate the typography.

**Transfer:** Use simple monochrome icons matched to the text color. Reserve multicolor marks for actual integrations and keep technical labels as text, not icon substitutes.

## Section recipes

How recurring sections are built.

### First screen: Workbench opening

**Observed:** A 44px announcement strip and 80px navigation precede a 479px chocolate stage. Within a 48px-gutter, seven-column composition, the left text block is about 509px wide and the right workbench about 747px wide. The 60px uppercase Display headline takes two tight lines, followed 8px later by a 20px support paragraph with a medium opening sentence and light continuation. Secondary button and Primary button sit below with a 12px gap. Back-to-front layers are chocolate, Three-lane ribbon, white headline and actions, then the raised Setup workbench on the right. The ribbon routes underneath the panel and along the lower edge. Within the first 900px, the complete hero, both actions, the workbench and a cream logo-proof strip are visible; the next major chapter only begins near the fold, and capability cards come later.

**Transfer:** Keep the two-part promise-plus-useful-object composition for new landing pages. Without software media, construct an equivalent guided-start object with real operations. Focused product pages instead open on cream with a sentence-case Product display and code panel; pricing opens with a centered Utility display and small grid ornaments; company pages open left-aligned with a mission paragraph and wide sculpture.

**Avoid:** Do not replace the functional object with a huge abstract orb, center everything into a generic stacked hero, or inflate the opening until all proof disappears below the first screen.

**Text style:** `display` — neue-haas-grotesk-display 900 · 60px/0.85 · tracking -0.04em · uppercase

### Cream proof chapter

**Observed:** A compact outlined Eyebrow and monochrome customer marks establish trust. The following section pairs a Heading and Body lead with Proof rows and a dark arrow-ended action; Graph-paper proof occupies the opposite side of the seven-column grid. Standard section top padding is 60px.

**Transfer:** Pair a plain-language assertion with consequences the reader can check; use a schematic when photography would explain less.

**Text style:** `heading` — gtAmerica 700 · 40px/1 · tracking -0.025em

### Dark capability shelf

**Observed:** Earth chapters holds a narrow left-aligned introduction with 12px gaps, then a three-column Capability card shelf. Small integration tiles form a second, five-column row below, with 12px gaps and a centered browse action.

**Transfer:** Choose capabilities that stand on their own; let the operational strips make them feel available now.

### Human authority pause

**Observed:** A rifle-olive band centers the 60px italic Quote with small author attribution, followed by two smaller moss quote cards. A deep-brown chapter then uses a centered 40px statement above two portrait-and-biography columns. Tiny mono roles sit directly below the names.

**Transfer:** Use the serif for a person's experience, then support authority with concise relevant credentials rather than a wall of logos.

**Text style:** `quote` — publico 400 italic · 60px/1 · tracking -0.025em

### Compact assurance strip

**Observed:** A 187px earth-red band centers a tiny outlined assurance label above a joined horizontal object: cream compliance markings on the left and a dark italic enterprise action on the right. It is markedly more compact than the neighboring chapters.

**Transfer:** Adapt as a concise assurance or compatibility strip using only relevant verified facts; retain the joined light/dark construction.

### Elaborate closing call

**Observed:** Closing atmosphere surrounds a straight-edged Graph-paper plane. Pixel constructions cross its edges. Closing title and Closing response are centered above a 720px Setup workbench, followed by an outlined action and Closing action. The whole band is about 598px high and transitions directly into the footer directory.

**Transfer:** Resolve the story with a usable first step, not merely another slogan. Keep the graph, pixels and warm grain even when the starting operation is nontechnical.

**Text style:** `closing-title` — gtAmerica 700 · 28px/1.1

### Simple closing call

**Only for:** pricing and institutional pages

**Observed:** A 556px near-black stage centers a two-line Simple closing statement within about 598px width. A single vermilion pill sits 36px below. A faint grid and small pixel constructions fill the background; the directory footer follows on the same near-black canvas.

**Transfer:** Use this stripped-back close when the preceding content is already dense or administrative.

**Text style:** `simple-closing` — gtAmerica 700 · 56px/1 · tracking -0.025em

### Pricing comparison

**Only for:** pricing pages

**Observed:** Centered Utility display sits between small grid-based decorative forms. Three Tier cards introduce the choices before broad comparison tables. Tables use low-contrast cream category bars, compact 34–36px rows, tiny uppercase categories, left-aligned feature names and centered values. Resource pricing adds smaller unit-cost lines and a region selector. A compact dark Questions panel precedes the Simple closing call.

**Transfer:** Expose differences and billing units clearly; keep the spacious card introduction separate from dense comparison detail.

**Text style:** `utility-display` — gtAmerica 900 · 56px/1 · tracking -0.025em

### Proof essay

**Only for:** long-form technical proof pages

**Observed:** A cream opening pairs a compact claim and explanatory prose with a large light chart card; a zero-result badge makes the key result immediate. Italic Editorial statement stages separate comparison tables, paired live-interface demonstrations and code examples. Moss, cream and deep brown distinguish chapters. A methodology strip and a separate related-resource banner precede the elaborate close.

**Transfer:** Structure a technical argument around reproducible comparisons and stated methodology. Preserve the typographic pauses so detailed proof does not become continuous documentation.

**Text style:** `editorial-display` — publico 400 italic · 70px/75px · tracking -0.02em

### Sparse numerical contrast

**Only for:** quantified feature proof

**Observed:** A centered heading and short support line sit above two widely separated Pixel stat numerals. Each numeral has an 11px uppercase mono caption. There is no enclosing stat card or ornamental chart.

**Transfer:** Choose two meaningful, verifiable quantities; explain the unit or outcome in the caption.

**Text style:** `pixel-stat` — vcr 400 · 70px/75px · tracking -0.02em

## Page flow

**Storyline:** Bold promise → useful first step → tangible proof → capability chapters → human or technical authority → friction removal → constructed closing call → directory.

### Broad platform or product introduction

1. **Promise and activation** — Dark slogan opening with a working start panel and ribbon.
2. **Social and functional proof** — Cream logo strip, consequence-led check rows and graph-paper diagram.
3. **Capability chapters** — Dark card shelf plus small integration tiles.
4. **Authority** — Olive testimonial, expert biographies and compact assurance strip.
5. **Closing call** — Grainy grid-paper activation stage followed by a warm-charcoal directory.

**Transfer:** Use the broadest promise first, then alternate concrete utility with human credibility.

### Plan selection and billing clarity

1. **Choice framing** — Centered cream title with small pixel-grid ornaments.
2. **Pricing** — Three equal-height plan cards with one gold-outlined recommendation.
3. **Detailed comparison** — Category-banded feature tables, resource rates and region control.
4. **Objection handling** — Compact dark support panel.
5. **Closing call** — Large black-grid promise, single orange action and full directory.

**Transfer:** Keep selection simple above detailed commercial information.

### Substantiated technical argument

1. **Thesis and quantified proof** — Cream text-and-chart opening with an immediately readable result badge.
2. **Capability proof** — Comparison table and paired live-interface examples separated by italic statement bands.
3. **Mechanism** — Dark code comparisons explaining why outcomes differ.
4. **Methodology** — Light methods strip and related-resource banner.
5. **Closing call** — Elaborate workbench close followed by black directory.

**Transfer:** Alternate proof, interpretation and mechanism; link to reproducible detail.

### Focused feature launch

1. **Product promise** — Cream split opening with sentence-case headline and code well.
2. **Benefit demonstration** — Physical key-tag still life, routing schematic and staged activity panel.
3. **Social proof** — Centered italic customer quotation on brown.
4. **Practical value** — Three small benefits and sparse two-number contrast.
5. **Breadth and currency** — Dark resource cards and two-column dated catalog rows.
6. **Objection handling** — Two-column charcoal FAQ.
7. **Closing call** — Grainy workbench activation stage and black directory.

**Transfer:** Start with a minimal integration example and expand toward operational confidence.

### Organization and people

1. **Purpose** — Left-aligned cream title and mission paragraph above wide grainy sculpture.
2. **Credibility** — Brief experience-led prose.
3. **Human proof** — Four-column natural portrait wall with translucent caption strips.
4. **Closing call** — Simple black-grid conversion promise and full directory.

**Transfer:** Let real people provide most of the page's visual density.

## Writing

Confident, direct and developer-literate, with a little mechanical swagger. Short claims are followed by concrete operations, consequences or proof rather than abstract inspiration.

**Do not copy:** Do not reuse the brand name, logo, ribbon artwork, customer marks, customer quotations, named people, proprietary product names, benchmark outcomes, adoption counts or compliance claims. Write original promises and use only claims and proof that the new product can substantiate. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you; use we for what the team has solved. Refer to the product by name when explaining a mechanism, not in every headline.
- **Rhythm:** Punchy one-to-seven-word chapter headings contrast with explanatory paragraphs. Benefit copy often moves from one short sentence to a clipped list, then a terse payoff. Contractions and sentence fragments are welcome; hype punctuation is rare.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening slogan | A physical metaphor states speed without sacrificing reliability. | 4–7 words | “All gas no breakages” |
| Product headline | Promise the desired work and remove an unwanted chore. | 6–10 words | “Ship AI features, not model integrations” |
| Supporting line | Name concrete capabilities, then compress the integration benefit into a short payoff. | 15–30 words | “Database, functions, workflow, sync, search, file storage, and more. All TypeScript, zero glue.” |
| Section heading | Use a blunt resolution or an outcome contrast. | 1–6 words | “Solved.”<br>“More features, fewer tokens” |
| Proof consequence | Capability followed by so and the failure it prevents. | 8–14 words | “ACID transactions so concurrent writes never corrupt your data” |
| Primary action | A plain verb initiates real work. | 2–4 words | “Start building”<br>“Read the docs” |
| Closing response | Balance immediate utility with a longer horizon. | 3–5 words | “Scale it for decades.” |

**Words and phrasing to use:** built-in; out of the box; no glue; correct by default; ready; ship; build; under load; the same code; so you don’t have to

**Avoid:** revolutionary ecosystem; seamless digital transformation; unlock limitless potential; magical AI; synergize; world-class solutions

**Rules:**

- State the reader's task before describing infrastructure.
- Pair a bold assertion with a mechanism, demonstration or verifiable result.
- Use technical specificity where it helps a decision; do not fill small cards with architecture jargon.
- Give compatibility notes and commands a practical, reassuring voice.
- Let humor come from concise metaphors and contrasts, not jokes in every card.

## Do's and Don'ts

### Do

- Keep the default headline at 60px/0.85, weight 900 and -0.04em tracking.
- Use 48px desktop gutters and the seven-column, 48px-gap grid for large split chapters.
- Place the useful start object alongside the promise, not hidden behind a call to action.
- Use 4px instrument corners inside the 12px framed workbench.
- Keep section introductions to 12px heading-to-support gaps and mostly 60px vertical band padding.
- Preserve the faint 20px graph-paper plane and small pixel constructions in closing stages.
- Keep practical card interiors compact: 12px gaps and 16px 12px padding.
- Use real color photography only for people and deliberately scoped physical still lifes.

### Don't

- Do not turn every section into a separate floating rounded card; major backgrounds are full-width flat bands.
- Do not make opening conversion buttons orange by default; the opening pill is #f1f1f1 and orange arrives at the close.
- Do not substitute a generic code font for both vcr labels and IBM Plex Mono commands; their jobs differ.
- Do not apply the 32px pricing radius to technical controls or capability cards.
- Do not turn subtle 0.08-opacity grid lines into a high-contrast decorative mesh.
- Do not fill broad page areas with vermilion, bright blue or purple; saturation belongs in bounded artwork and small controls.
- Do not use italic serif for body paragraphs or every feature title.
- Do not add glossy glass panels throughout the page; translucency is concentrated in copy controls, documentation pills and portrait captions.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions are declared at 0.15s cubic-bezier(.4, 0, .2, 1). The setup copy control declares all-property transition at the same timing.
- Some surface and transform transitions are declared at 0.3s; pulse is declared at 2s cubic-bezier(.4, 0, .6, 1) infinite.
- A cursor-like typed example is visible within the starting workbench; exact typing cadence is unspecified.

**Transfer:**

- Use the measured short color transitions for pills and command wells.
- Keep typing effects confined to example instructions so the main promise and fixed starting action remain readable.

**Unknown:**

- Scroll entrance timing, ribbon animation behavior, complete looping sequences and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 640px, 768px, 1024px, 1280px and 1536px.
- Main container classes specify side padding of 12px initially, 20px at the first breakpoint, 32px at the next and 48px at desktop.
- The starting workbench lower groups declare one column, changing to two columns when their own container reaches 600px.

**Transfer:**

- On narrow screens, preserve promise, actions and practical object as a readable stack; route the ribbon around the object without covering text.
- Reflow the seven-column story into single-column chapters and keep grid-paper and pixel details attached to their stage boundaries.
- Allow pricing comparisons to remain horizontally readable rather than shrinking their text into illegibility.

**Unknown:**

- Exact mobile navigation, typography at every breakpoint and narrow-screen table interactions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
