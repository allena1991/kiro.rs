# BaseHub — ember-lit product workbench

## Overview

A near-black technical marketing style with warm orange edges, tightly fitted grotesk headlines and unusually tangible product demonstrations. The mood is capable and hands-on rather than futuristic: dark interface panels, restrained diagrams, a handwritten invitation and a small luminous object soften the engineering vocabulary. Broad empty intervals surround dense, useful demonstrations, making it well suited to developer tools and collaborative software.

### Essentials

- Headlines feel fitted rather than oversized: Geist at 60px/1.2, weight 500 and -0.05em tracking for the opening; 48px/1.2 with the same tracking for capability chapters.
- The opening is a left-aligned workbench, not a centered billboard: a small announcement, headline, two-line 18px introduction and 38px orange pill sit above a 1300px-wide dark product stage that escapes the content column to the right.
- Orange behaves like an energized edge against an almost entirely black page: #040404 canvas, #0c0c0c panels, #252525 hairlines; #ff6c02 is concentrated in the hero's 20px top/left frame, tiny actions, progress details and a 34px closing ribbon.
- Actions are small and rounded, not chunky: the main pill is 38px tall with 14px horizontal padding and 96px radius; secondary actions are 32px tall with 16px padding, #1b1b1b fill and a 1px outline.
- Product proof is staged as real work: a large dark application view, smaller tightly framed workflow details and a capability index with 24px labels. If there is no usable interface, create a credible dark workflow schematic with real inputs and outputs in the same frames.
- An ember guide ties technical chapters together: a thin left-side vertical rail, rounded branches toward 34px section-label pills and a tiny glowing orange marker. Pair the opening stage with one handwritten orange invitation and curved arrow.
- The ending changes scale rather than shouting: a full-width 34px orange uppercase action ribbon precedes a black footer with a small luminous sculptural emblem, one horizontal link group and subdued legal/social details. Rebuild the emblem as an original beveled monogram or abstract outlined object.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ember orange | `#ff6c02` | `--color-orange` | accent, action, background, link | Stage frame, primary actions, closing ribbon, active marks and short feature links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lit orange | `#ff9b51` | `--color-orange-light` | accent | Warm end of active-label gradients and glowing edges. |
| Copper outline | `#9f4d11` | `--color-warm-edge-strong` | border | Warm technical-chapter label outline. |
| Warm outline | `#854416` | `--color-warm-edge` | border | Active section-label outline. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer black | `#000000` | `--color-footer` | background | Footer canvas and deep shading inside sculptural artwork. |
| Near-black canvas | `#040404` | `--color-canvas` | background | Default marketing canvas and the interior of the main product stage. |
| Base panel | `#0c0c0c` | `--color-panel` | surface, background | Navigation, cards, large bordered panels and section-label pills. |
| Toolbar charcoal | `#121212` | `--color-toolbar` | surface | Code toolbars, feature tiles and selected capability backing. |
| Control charcoal | `#1b1b1b` | `--color-control` | surface, border | Secondary action fill and the subtle outline of testimonial cards. |
| Panel hairline | `#252525` | `--color-edge` | border | One-pixel panel outlines, rows and separators. |
| Hover charcoal | `#303030` | `--color-hover` | surface, border | Declared secondary-action hover fill and border. |
| Faint text | `#646464` | `--color-faint` | text | Tertiary annotations, code line numbers and subdued hover links. |
| Muted text | `#909090` | `--color-muted` | text | Supporting prose, navigation, captions and inactive index items. |
| Soft text | `#dedede` | `--color-soft-ink` | text | Secondary action labels, plan names and compact supporting content. |
| Bright text | `#f3f3f3` | `--color-ink` | text | Headlines, main numerals and bright content. |
| Action white | `#fafafa` | `--color-action-ink` | text | Text on orange actions and the closing ribbon. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recessed edge | `#131313` | `--color-subtle-edge` | border | Barely visible outer edge of the billing selector. |
| pricing pages and social proof walls | Raised charcoal | `#161616` | `--color-shade` | surface | Higher contrast grouped content. |

## Typography

- **Geist** — All marketing headings, paragraphs, labels, actions and numerals. Compact contemporary grotesk with open counters; medium rather than bold headings and tight negative tracking. Font stack: "Geist", Inter, -apple-system, system-ui, sans-serif.
- **Geist Mono** (only for technical demonstrations) — Visible code examples. Small regular monospace, aligned in numbered lines. Font stack: "Geist Mono", monaco, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 60px | 1.2 | -0.05em | Primary landing-page promise. |
| heading | Geist | 500 | 48px | 1.2 | -0.05em | Capability chapter headings, gallery invitation and centered commercial opening. |
| offer-heading | Geist | 500 | 32px | 1.2 | -0.05em | Compact offer callout headline. |
| feature-index | Geist | 500 | 24px | 1.5 | -0.05em | Large text-only capability index. |
| lead | Geist | 400 | 18px | 1.5 | -0.03em | Opening introduction and centered explanatory copy. |
| support | Geist | 400 | 16px | 1.4 | -0.03em | Section support lines; keep narrower than the main heading. |
| body | Geist | 400 | 16px | 1.5 | -0.03em | Quotes and regular descriptive text. |
| label | Geist | 500 | 16px | 1.5 | -0.03em | Section labels, workflow titles, feature cells and questions. |
| primary-action | Geist | 500 | 16px | 1 | -0.03em | Opening action label. |
| small | Geist | 400 | 14px | 1.5 | -0.03em | Workflow descriptions, card captions and compact feature lists. |
| navigation | Geist | 400 | 14px | 1.5 | normal | Top navigation. |
| compact-action | Geist | 500 | 14px | 16px | -0.03em | Secondary buttons and standard commercial actions. |
| footer-link | Geist | 500 | 14px | 1.1 | -0.03em | Horizontal footer links. |
| micro-label | Geist | 500 | 13px | 1.5 | -0.03em | Announcement text and technical tabs. |
| ribbon | Geist | 600 | 12px | 1.5 | -0.04em, uppercase | Full-width closing conversion strip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | commercial-display | Geist | 400 | 32px | 1.5 | -0.04em | Plan prices and oversized included-feature tiles. |
| social proof walls | proof-heading | Geist | 500 | 32px | 1.2 | -0.04em | Centered testimonial-wall heading. |
| pricing pages | commercial-heading | Geist | 500 | 24px | 1.3 | -0.04em | Estimator and FAQ headings. |
| technical demonstrations | code | Geist Mono | 400 | 13px | 1.5 | -0.03em | Code and muted line numbers. |

**Notes:**

- Keep medium-weight headings at 500; their character comes from -0.05em tracking, not heavy strokes.
- Most compact marketing text uses -0.03em tracking; navigation retains normal tracking. The closing ribbon is the exception to sentence-case labels.
- Use 48px headings for long, wrapping statements and 60px for the short primary promise. Section support is 16px and opening support is 18px.
- Pricing numerals use regular weight, not the heavier weight of the offer callout. Keep these two 32px roles distinct.

## Layout

**Density:** Airy between chapters, compact within working panels; the contrast is central to the workbench feel.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Opening headline-to-introduction gap and tight icon/text spacing. |
| 12px | Section heading-to-support gap, FAQ row separation and workflow-number gap. |
| 16px | Workflow card padding and gaps; footer wrapping row gap. |
| 24px | Gallery and commercial card gutters; testimonial padding. |
| 32px | Support-to-action gap, heading-to-demonstration gap and footer top content offset. |
| 56px | Opening action-to-stage separation and capability-index-to-media gutter. |
| 70px | Opening top padding beneath the navigation. |
| 80px | Typical chapter top and bottom padding. |
| 112px | Gallery opening space and long capability-block bottom space. |
| 120px | Top breathing room around the compact offer panel. |
| 160px | Commercial objection-handling bottom space. |
| 240px | Long release of space beneath the compact offer panel. |

### Containers and grids

- **marketing container**: max width 1148px · side padding 32px. Centered outer shell; 1084px of usable content at desktop. Navigation and most chapters share its left edge.
- **support measure**: max width 800px. Section-support paragraphs stop short of the wide heading edge.
- **workflow grid**: 3 columns · gap 16px. Equal-width steps; each holds a compact numbered heading and a much larger interface detail.
- **gallery grid**: 3 columns · gap 24px. Equal-width preview cards in the marketing content shell.
- **capability split**: gap 56px. A 336px-wide text index at the left with a much wider product detail extending toward the right viewport edge.
- **commercial container** (only for pricing pages): max width 1280px · side padding 64px. Wider commercial shell with 1152px usable width.
- **commercial grid** (only for pricing pages and social proof walls): 3 columns · gap 24px. Equal-width plan cards or independently stacked quote columns.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 96px |
| labels | 9999px (pill) |
| cards | 12px |
| gallery and FAQ cards | 8px |
| offer panel | 16px |
| product stage | 21px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product inset | `2px 4px 6px rgba(0,0,0,1)` | A drop shadow beneath the inset dark application stage, not a floating card halo. |
| pricing pages | recommended plan | `0px 0px 50px 0px rgba(255,108,2,0.1)` | Soft warm halo around the recommended tier. |

### Surfaces

#### Canvas · level 0

**Use:** Default continuous page backing.

**CSS:** `background: #040404; color: #f3f3f3`

**Observed:** Most of the page remains uncolored and near-black; large empty intervals separate useful material.

**Transfer:** Preserve the uninterrupted darkness instead of alternating light and dark sections.

#### Bordered work panel · level 1

**Use:** Workflow cards, quotes and technical demonstrations.

**CSS:** `background: #0c0c0c; border: 1px solid #252525; border-radius: 12px`

**Observed:** Edges are visible but understated; contrast is mostly generated by text and the working content inside.

**Transfer:** Use a single hairline and a slight lift in background rather than thick bevels.

#### Orange product stage · level 1

**Use:** The dominant opening product demonstration.

**CSS:** `background: #ff6c02; border-radius: 21px; overflow: hidden`

**Observed:** The dark interior is inset 20px from the top and left, making an asymmetric warm frame. Interior radius is 6px at top-left and 21px at bottom-right; its 1px edge is #252525.

**Transfer:** Back a real interface or carefully built workflow schematic with an orange edge, not an orange full-bleed illustration.

#### Offer panel · level 1

**Use:** A concise commercial bridge within a product narrative.

**CSS:** `background: #0c0c0c; border: 1px solid #252525; border-radius: 16px; overflow: hidden`

**Observed:** A broad low panel with a soft charcoal light patch near its lower edge and nearly disappearing cross-dividers on the right.

**Transfer:** Pair a compact promise and secondary action with a small matrix of useful inclusions.

#### Footer black · level 0

**Use:** Closing brand and utility area.

**CSS:** `background: #000000`

**Observed:** An orange ribbon is the top boundary; the rest returns to deep black rather than a large final promotional panel.

**Transfer:** Retain this low, graphic ending across page types.

#### Included feature tile · level 1

**Only for:** pricing pages

**Use:** Text-only included-capability mosaic.

**CSS:** `background: #121212; border: 1px solid #252525; border-radius: 12px; padding: 24px 36px`

**Observed:** Tiles flex to different widths, with centered 32px text; the final tile spans the row.

**Transfer:** Let short capability names determine tile widths without turning this into a uniform icon grid.

#### Raised proof card · level 2

**Only for:** social proof walls

**Use:** Dense customer comments.

**CSS:** `background: #161616; border: 1px solid #1b1b1b; border-radius: 8px; padding: 24px`

**Observed:** Slightly lighter than ordinary work panels, with content-driven heights.

**Transfer:** Keep the warmer human material visually separate from technical demonstrations.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 48px; background: #0c0c0c`

**Text style:** `navigation` — Geist 400 · 14px/1.5

**Observed:** Small brand lockup at left, centered text navigation and two small authentication pills at right. The inner shell uses a 250px / flexible / 250px composition; links have 10px horizontal padding. Authentication pills are 26px tall.

**States:** Declared: hover is not specified for the navigation text; focus-visible uses a solid outline.

**Transfer:** Keep the bar visually thinner than every content panel.

### Primary button

**Use:** Opening conversion action.

**CSS:** `background: #ff6c02; color: #fafafa; border-radius: 96px; padding: 0px 14px; height: 38px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `primary-action` — Geist 500 · 16px/1 · tracking -0.03em

**Observed:** A solitary small orange pill below the introduction. Standard commercial variants shrink to 32px with 14px text; authentication variants shrink to 26px with 13px text.

**States:** Declared: hover background-color and border-color become rgb(255 139 53/1); focus-visible uses a solid outline.

### Secondary button

**Use:** Lower-intensity conversion links and supporting actions.

**CSS:** `background: #1b1b1b; border: 1px solid #252525; color: #dedede; border-radius: 96px; padding: 0px 16px; height: 32px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `compact-action` — Geist 500 · 14px/16px · tracking -0.03em

**Observed:** Used inside the offer panel and on non-emphasized commercial cards. The compact authentication variant is 26px tall.

**States:** Declared: hover background-color and border-color become #303030; focus-visible uses a solid outline.

### Announcement chip

**Use:** A short timely message preceding the main promise.

**CSS:** `background: #0c0c0c; border: 1px solid #252525; border-radius: 8px; padding: 4px 11px; height: 32px; color: #909090; display: inline-flex; align-items: center`

**Text style:** `micro-label` — Geist 500 · 13px/1.5 · tracking -0.03em

**Observed:** A restrained rectangular chip, not the fully rounded section label; the text remains visually subordinate.

**Transfer:** Use one brief product update rather than a promotional badge stack.

### Section label

**Use:** Introduce capability chapters and anchor the ember guide.

**CSS:** `background: #0c0c0c; border: 1px solid #252525; border-radius: 9999px; padding: 4px 16px; color: #909090`

**Text style:** `label` — Geist 500 · 16px/1.5 · tracking -0.03em

**Observed:** Neutral labels become warmly outlined at the active chapter. The active variant uses #854416 border, a 5% orange/peach wash and orange-to-peach text; another technical label uses #9f4d11.

**Transfer:** Keep labels sentence case and short; reserve warm activation for one focused chapter.

### Workflow card

**Use:** Explain a sequence through compact product details.

**CSS:** `background: #0c0c0c; border: 1px solid #252525; border-radius: 12px; padding: 16px 16px 0px; overflow: hidden`

**Text style:** `label` — Geist 500 · 16px/1.5 · tracking -0.03em

**Observed:** A 28px by 32px outlined number with 8px radius sits beside the title and muted 14px description. A close-up interface illustration fills the lower majority. Three desktop cards are 351px wide and 372px tall.

**Transfer:** Use numbered steps only when the product genuinely has a sequence.

### Capability index row

**Use:** A browsable inventory paired with large product proof.

**CSS:** `border-bottom: 1px solid #252525; padding: 16px; color: #909090; position: relative`

**Text style:** `feature-index` — Geist 500 · 24px/1.5 · tracking -0.05em

**Observed:** Rows sit in a 336px index, about 69px tall. A selected row has a dark inset background and brighter text; the paired media is much wider than the index.

**Transfer:** Keep labels readable once, and swap the paired working example rather than duplicating the text.

### Closing ribbon

**Use:** A final conversion boundary immediately above utility content.

**CSS:** `background: #ff6c02; color: #fafafa; height: 34px; width: 100%; display: flex; align-items: center; justify-content: center`

**Text style:** `ribbon` — Geist 600 · 12px/1.5 · tracking -0.04em · uppercase

**Observed:** One centered uppercase sentence spans the full viewport as a link. There is no large heading or secondary action attached.

**States:** Declared: hover underlines the label at wide widths; focus-visible uses a solid outline.

### Footer link

**Use:** Single-line wrapping navigation in the ending.

**CSS:** `color: #909090; border-radius: 4px`

**Text style:** `footer-link` — Geist 500 · 14px/1.1 · tracking -0.03em

**Observed:** A horizontal group is aligned opposite the small sculptural emblem, with 32px column and 16px row gaps; copyright and social icons form a lower row.

**States:** Declared: hover color becomes #646464; focus-visible uses a solid outline.

### Plan card

**Only for:** pricing pages

**Use:** Compare entry, team and high-capacity offers.

**CSS:** `background: #040404; border: 1px solid #252525; border-radius: 12px; padding: 16px 24px 20px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `small` — Geist 400 · 14px/1.5 · tracking -0.03em

**Observed:** Name, regular-weight price, brief fit description, inclusion list and bottom action row. Desktop cards are 368px by 474px. A divider anchors the footer; the middle tier uses the orange action and warm halo, while the others use Secondary button.

**Transfer:** Use genuine pricing and explicit billing units. Keep feature lists compact rather than adding decorative illustrations.

### Testimonial card

**Only for:** social proof walls

**Use:** Human proof after technical and commercial detail.

**CSS:** `background: #161616; border: 1px solid #1b1b1b; border-radius: 8px; padding: 24px; position: relative`

**Text style:** `small` — Geist 400 · 14px/1.5 · tracking -0.03em

**Observed:** Circular avatar, author and muted profile link sit above several short paragraphs; a small social-network glyph occupies the upper right. Cards stack independently in three columns with 24px gutters.

**States:** Declared: hover background-color becomes #1b1b1b; focus-visible uses a solid outline.

### FAQ row

**Only for:** pricing pages and objection-handling sections

**Use:** Resolve specific commercial questions in compact disclosures.

**CSS:** `background: #040404; border: 1px solid #252525; border-radius: 8px; padding: 12px; min-height: 50px; width: 100%`

**Text style:** `label` — Geist 500 · 16px/1.5 · tracking -0.03em

**Observed:** A small downward chevron precedes a left-aligned question. Rows have 12px vertical gaps; the question starts immediately beside the icon.

**States:** Declared: hover on the ancestor changes border-color to #646464; focus-visible behavior is not specified.

## Imagery and graphics

### Interactive product stage

**Use:** The main visual proof in the opening.

**Observed:** A near-black application view with multiple navigation rails, a content tree and an active central working document. It sits inside Orange product stage, aligned to the content left edge but extending beyond the right edge of the viewport; only its upper portion is visible initially. An orange handwritten invitation and looping arrow sit above the frame.

**Transfer:** Show one believable task in the new product, with a clear main action and realistic data. The minimum equivalent is a carefully typeset dark workflow board, not a generic laptop mockup.

**Build:** Use a 1300px by 682px orange backing with 21px corners; inset a 1280px by 662px dark interface 20px down and right. Draw the invitation as original hand-lettered SVG paths and a loose curved arrow around 150px wide above the upper-right part of the stage. Keep orange restricted to the frame and a few working controls.

### Ember chapter guide

**Use:** Connect the opening and technical chapters as one guided product story.

**Observed:** A very thin vertical gray line lies well left of the text column. A short glowing orange block marks progress; rounded elbow branches curve right toward chapter labels. Orange highlights give it a faint instrument-panel quality.

**Transfer:** Carry the rail and at least one lit marker into a new landing page, using it to connect any meaningful capability chapters.

**Build:** Place a 1px #252525 vertical SVG line in the outer left gutter. Draw branches with a vertical segment and a roughly 50px-radius quarter-turn ending near the label; blend the stroke from #ff6c02 to transparent. Add an 8px by 10px marker with a 2px radius, orange-to-peach fill and compact orange glow. Keep the guide behind text and outside the reading column.

### Workflow detail illustrations

**Use:** Lower portions of Workflow card and paired capability media.

**Observed:** Dark interface fragments show menus, comments, branch states and automation steps at readable scale, not whole applications shrunk beyond legibility. Small avatars, colored reactions and an occasional violet success state are contained inside the product imagery. Lower edges fade into the panel.

**Transfer:** Isolate the decisive interaction in each example, with mostly grayscale UI and any status hue confined to the product itself.

**Build:** Compose nested #121212 and #161616 rectangles with fine #252525 outlines, small labels and real controls. Add a transparent-to-panel gradient across the bottom to let the example recede into its parent card.

### Offer-panel light

**Use:** A restrained material accent in Offer panel.

**Observed:** A broad faint gray illumination rises from the lower-left area of an otherwise dark panel. The right-hand two-by-two feature matrix is divided by hairlines whose ends fade away.

**Transfer:** Use neutral light to make the offer panel feel tangible without adding another orange spotlight.

**Build:** Behind the content, place a 160px circular #303030 patch at 0.3 opacity with 40px blur and a very low-opacity pale ellipse near the lower edge. Draw 1px dividers with transparent ends and a rgba(255,255,255,0.2) midpoint; keep text above these layers.

### Template previews

**Use:** A compact starter-resource gallery late in the narrative.

**Observed:** Three landscape website previews with saturated purple, coral and yellow edge treatments sit above low dark caption strips. Both light and dark sites appear, but color remains inside the preview area.

**Transfer:** Use real output examples or starter resources, retaining a landscape preview and small understated caption rather than adding large decorative headings.

### Luminous closing emblem

**Use:** A small sculptural brand moment below Closing ribbon.

**Observed:** A warm outlined rounded rectangular object tilts slightly in perspective; bright beveled edges surround a dark diagonally hatched interior. It is small relative to the wide black footer and sits opposite the utility links.

**Transfer:** Create an original monogram, token or abstract object. The minimum acceptable version is a crisp beveled outline with dark hatching and one lit edge, never a huge wordmark.

**Build:** Make an SVG rounded rectangle in a roughly 176px by 121px media slot, with the visible object occupying a small central portion. Skew the object gently in perspective, use orange and peach strokes on offset paths for bevel depth, add faint diagonal lines clipped inside, and illuminate one edge with a pale warm highlight.

### Commercial amber atmosphere

**Only for:** pricing pages

**Use:** Backing behind the plan-selection opening.

**Observed:** Broad defocused brown-orange light passes diagonally behind the centered introduction and cards. The cards stay almost black and crisp; the haze fades into the canvas at the section edges.

**Transfer:** Use this warmer centered opening for commercial comparison, not as the default product-stage opening.

**Build:** Layer two broad elliptical radial gradients using rgba(255,108,2,0.12) fading to transparent over #040404; offset one toward the upper left and the other toward the lower right. Blur and clip them behind the plan area. Match the soft glow; exact stops are not essential.

### Icons

**Observed:** Small compact SVG glyphs, predominantly filled paths, generally 16px or 20px; selected actions use 18px chevrons. Gray is the default, with orange or bright white only for emphasis. Product diagrams can include more detailed outlined symbols.

**Transfer:** Choose compact, visually light glyphs and keep them adjacent to labels or inside small framed controls; do not enlarge them into colorful standalone feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Workbench opening

**Observed:** Navigation occupies a 48px strip. Inside marketing container, the opening begins with 70px top padding: Announcement chip, 16px gap to a left-aligned 60px headline, 8px gap to an 18px two-line introduction, then 32px to Primary button. The text uses roughly the left two thirds of the content area, leaving open black space at right. After 56px, Interactive product stage begins: a bright orange top/left frame around the much larger dark application, with the handwritten invitation above its right half. Canvas is behind the ember guide, then text and actions, then the dominant product view. Within the first 900px, all opening text, action, arrow and the upper application are visible; the lower interface and trust-logo row fall below the fold.

**Transfer:** Use one concise category promise and show a meaningful working state immediately below it. If the product has no interface, build an input-to-result dark workflow board at the same visual scale. Commercial comparison pages instead open with a centered 48px heading, 18px explanation, billing selector and three Plan cards over Commercial amber atmosphere.

**Avoid:** Do not center the default promise, place the demonstration beside it as a small thumbnail, or shrink the stage until it fits the text column.

**Text style:** `display` — Geist 500 · 60px/1.2 · tracking -0.05em

### Guided capability chapter

**Observed:** Use Section label attached to Ember chapter guide, followed by a broad 48px heading and 16px support measure. Heading-to-support gap is 12px; useful proof begins around 32px later. Chapters use approximately 80px top and bottom padding.

**Transfer:** Give each chapter one understandable benefit and one visible proof mechanism; let long headlines wrap naturally.

**Text style:** `heading` — Geist 500 · 48px/1.2 · tracking -0.05em

### Numbered workflow

**Observed:** Three Workflow cards occupy workflow grid beneath a guided heading. Small numbers and concise text occupy the top; the interface fragments consume most of the card height.

**Transfer:** Explain an actual sequence with three legible, causally linked working details rather than three unrelated feature icons.

### Technical working example

**Observed:** A full-width Bordered work panel contains a 37px dark toolbar with compact tabs, a tall numbered code area, and a 36px footer with documentation and guide links. The active tab has a 1px orange underline. Code uses the code recipe; ordinary marketing typography remains outside.

**Transfer:** For technical products, show a short useful integration example. For non-code tools, preserve the tabbed working-example construction with a real editable artifact rather than decorative code.

**Text style:** `code` — Geist Mono 400 · 13px/1.5 · tracking -0.03em

### Capability browser

**Observed:** A 48px heading introduces capability split. Capability index row labels form a long vertical list at left, paired with a large dark working detail on the right. The selected label is brighter and backed by an inset rectangle; media can extend beyond the nominal content width.

**Transfer:** Use this for breadth without reducing every capability to an equal card. Keep a clear selected state and connect each label to concrete working proof.

**Text style:** `feature-index` — Geist 500 · 24px/1.5 · tracking -0.05em

### Low commercial bridge

**Observed:** Offer panel is 1084px wide and 233px high. Its left portion contains a faint label, a two-line 32px promise and Secondary button. The right half is a two-by-two matrix of compact icons and 16px inclusions. Offer-panel light and fading separators add material depth; 120px above and 240px below isolate it.

**Transfer:** Bridge from capabilities to commitment with a verified offer or bundled-value summary, not a second oversized hero.

**Text style:** `offer-heading` — Geist 500 · 32px/1.2 · tracking -0.05em

### Starter gallery

**Observed:** A centered two-line 48px invitation and 16px supporting sentence precede three Template previews in gallery grid. Each preview is about 343px by 215px inside a dark 8px-radius card with compact title and caption. The gallery has 112px top and 128px bottom padding.

**Transfer:** Offer useful examples, outputs or getting-started resources; keep visual variety inside the previews.

**Text style:** `heading` — Geist 500 · 48px/1.2 · tracking -0.05em

### Ribbon and object ending

**Observed:** Closing ribbon spans the viewport above Footer black. After 32px, a small Luminous closing emblem sits at left in a 176px by 121px media slot; Footer link items align at right in one wrapping group. Copyright sits beneath at left, tiny social marks at right, with 106px bottom padding. The total footer is 353px tall on desktop.

**Transfer:** Keep this graphic closing device on both narrative and commercial pages: a short invitation, a small original sculptural mark and restrained utility links, not another huge claim.

### Commercial comparison and estimator

**Only for:** pricing pages

**Observed:** Three Plan cards lead into a broad ruled comparison table: feature labels at left, centered values in three plan columns, orange inclusion marks and compact repeated actions above. Below, a 1152px by 400px 16px-radius panel has a full-width heading row, three sliders at left and a 300px summary column at right. Tracks are 3px high with white active segments; handles are 30px white circles outlined by 5px of the panel color.

**Transfer:** Separate quick plan choice from detailed comparison and a working estimate. Use actual pricing logic rather than a decorative nonfunctional calculator.

**Text style:** `commercial-heading` — Geist 500 · 24px/1.3 · tracking -0.04em

### Included capability mosaic

**Only for:** pricing pages

**Observed:** A centered 24px lead introduces Included feature tile in a wrapping mosaic with 16px gaps. Different text lengths create varied tile widths, while one final tile spans the available width. A small orange feature link follows.

**Transfer:** Use this as reassurance that essential functionality is shared across tiers, not as the default capability chapter.

**Text style:** `commercial-display` — Geist 400 · 32px/1.5 · tracking -0.04em

### Proof wall and objections

**Only for:** social proof walls and commercial pages

**Observed:** A centered 32px proof heading and underlined social link lead to three stacks of Testimonial card with 24px gutters. The next compact chapter uses a left-aligned 24px heading and FAQ row items separated by 12px; 160px of lower space precedes the closing.

**Transfer:** Follow detailed buying information with human experience and specific answers. Let quote heights follow content instead of forcing uniform cards.

**Text style:** `proof-heading` — Geist 500 · 32px/1.2 · tracking -0.04em

## Page flow

**Storyline:** promise → tangible product proof → capability depth → confidence and practical commitment → useful resources or objections → narrow conversion ribbon and brand object

### Introduce a product through working proof and explain its breadth without losing a hands-on feel

1. **Promise** — A short left-aligned category statement, announcement and single orange action.
2. **Product demonstration** — An oversized orange-framed dark application with an informal invitation to try it, followed by subdued trust logos.
3. **Capability chapters** — Guided headings alternate with an inline quote, a three-step workflow and a tabbed technical example.
4. **Capability breadth** — A long text index drives larger paired working details.
5. **Commercial bridge** — A low offer panel combines a price-led promise and a four-cell inclusion matrix.
6. **Practical starting point** — A centered resource invitation with three colorful output previews.
7. **Closing call** — A narrow orange ribbon above a sparse black footer and small luminous object.

**Transfer:** Use as an adaptable product narrative. Maintain real working proof, the ember guide and the distinctive ending; choose chapter count and order to fit the new product.

### Help visitors compare plans, understand usage costs and resolve purchase uncertainty

1. **Plan selection** — A centered promise, billing toggle and three tier cards backed by amber haze.
2. **Social proof** — A low row of subdued customer marks.
3. **Detailed comparison** — A ruled feature table with repeated plan actions and compact limits.
4. **Cost clarity** — A dark working estimator with sliders and a recommendation summary.
5. **Shared value** — A varied-width mosaic of included capabilities.
6. **Human proof** — A centered introduction followed by independently stacked quote cards.
7. **Objection handling** — A short list of compact outlined disclosures.
8. **Closing call** — The same ribbon, small sculptural object and sparse utility footer.

**Transfer:** Keep commercial density inside panels and tables. Make billing units and limits explicit, then use proof and answers to ease the final decision.

## Writing

Direct, technically literate and lightly conversational. Confident claims are grounded in familiar workflows and concrete actions, with a small amount of playful invitation around the product demonstration.

**Do not copy:** Do not reuse BaseHub or customer names, its logo or emblem artwork, acquisition announcement, proprietary product terminology, prices, limits, performance claims or testimonial quotations as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. Use we sparingly to explain a design decision, and name the product when introducing a concrete capability.
- **Rhythm:** A compact opening promise gives way to longer sentence-like capability headings. Support is usually one or two short sentences; actions remain two to five words. Informal remarks belong around demonstrations, not in every heading.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | State the product category with one differentiating modifier. | 4–8 words | “The AI-Native Headless CMS” |
| Capability heading | Link a familiar experience to a practical benefit; a complete sentence can span two lines. | 10–20 words | “Feels like a Notion document. Packed with everything you’d expect from a robust CMS.” |
| Supporting instruction | Use concrete verbs describing actions the reader can perform. | 1–2 short sentences | “Integrate in minutes so you can start working on your content as fast as possible.” |
| Primary action | Simple verb phrase without sales embellishment. | 2–5 words | “Get Started”<br>“See pricing” |
| Commercial reassurance | Explain fit and remove uncertainty in plain terms. | One sentence | “Find the perfect plan for you and your team” |
| Resource invitation | Ask a practical question, then give a brief action-oriented answer. | Two short clauses | “Looking for a starting point?”<br>“Grab a template” |
| Closing ribbon | Pair an accessible first step with room to grow. | 7–10 words | “START FOR FREE, THEN GROW WITH YOUR TEAM” |

**Words and phrasing to use:** your team; start; integrate; review; preview; in minutes; packed with; starting point; grow

**Avoid:** revolutionary; unleash limitless potential; 10x everything; enterprise-grade magic; excessive exclamation marks

**Rules:**

- Name the actual workflow before describing its benefit.
- Use technical vocabulary only when the corresponding demonstration makes it concrete.
- Keep a playful aside short and visually local to a demonstration.
- Write plan descriptions around who the offer fits; put measurable limits in lists or tables.
- Use real customer language for proof, with attribution and a useful link.

## Do's and Don'ts

### Do

- Keep the ordinary canvas at #040404 and panels at #0c0c0c, separated by 1px #252525 edges.
- Use 60px/1.2 and 48px/1.2 Geist headings at weight 500 with -0.05em tracking.
- Keep the orange action compact: 38px in the opening and 32px in regular commercial contexts.
- Let the 1300px product stage escape the 1084px reading width toward the right.
- Combine 80px chapter padding with 12px heading-support gaps and 32px proof gaps.
- Keep workflow detail cards at 12px radius and resource preview cards at 8px radius.
- Use the ember guide and a handwritten orange invitation to make technical proof feel approachable.
- Finish with the 34px conversion ribbon and a small luminous object on black, not a giant final headline.

### Don't

- Do not replace medium-weight tight headings with 700-weight display type.
- Do not turn the default near-black canvas into a page-wide amber gradient; the amber atmosphere belongs to commercial selection.
- Do not use white cards or pale gray section bands to separate the main narrative.
- Do not make every orange action 48px or 56px tall; the small pill scale is characteristic.
- Do not apply 21px stage corners to every small card; keep the 8px, 12px and 16px hierarchy.
- Do not give workflow cards broad orange glows; the warm 50px halo is reserved for a recommended plan.
- Do not promote code syntax or product-status colors into the marketing accent palette.
- Do not turn the footer's horizontal 14px links into a dense multi-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares color-family transitions of 0.3s cubic-bezier(0.4,0,0.2,1); footer links declare 0.15s with the same curve.
- Section-label color changes declare 0.3s cubic-bezier(0,0,0.2,1). FAQ borders use 0.15s cubic-bezier(0.4,0,0.2,1).
- Primary and secondary buttons declare warmer-orange and lighter-charcoal hover states respectively; active technical tabs have an orange underline.
- The capability browser presents brighter selected text and inset backing alongside changing working examples.

**Transfer:**

- Keep interaction emphasis in small color, border and selection changes; the guide marker and paired product detail should communicate chapter focus.
- Preserve a readable static state for the sculptural object and capability media.

**Unknown:**

- Timing and triggers for chapter activation, product demonstrations and emblem animation are unspecified.

### Responsive

**Observed:**

- CSS declares width breakpoints at 375px, 576px, 600px, 640px, 768px, 1024px, 1280px, 1536px and 1920px.
- The marketing shell uses 24px side padding before its 32px desktop padding. Workflow grids declare one column, then two, then three.
- The capability split declares stacked layout before the wide-screen horizontal arrangement; the offer panel similarly changes from column to row.
- The large interactive stage is declared for extra-wide screens; a smaller-screen alternative is not specified here.

**Transfer:**

- On narrow screens, stack the workflow cards and paired capability examples while keeping labels adjacent to their proof.
- Retain the orange frame as a smaller readable working detail rather than shrinking a full desktop interface into illegible text.
- Wrap footer links with their 16px row gap and keep the closing ribbon visually distinct.

**Unknown:**

- Exact mobile headline sizes, replacement product media, navigation behavior and final narrow-screen compositions are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
