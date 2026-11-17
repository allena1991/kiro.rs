# Augen — objects emerging from darkness

## Overview

A cinematic technology style that treats a small device like a museum object, alternating deep black stages with cool porcelain interludes. Thin neo-grotesk lettering, restrained orange signals and metallic product renders make it feel experimental and scientific rather than retail-driven. Text stays sparse within expansive scenes, then becomes compact and methodical in technical chapters.

### Essentials

- The object speaks before the headline: a 900px black opening stages a centered 468×374px image, with the 43px product name low in the composition and a compact 280px support paragraph beneath it.
- Headlines become scenery: 140px weight-300 type with 1.2 line height and 0.008em tracking sits behind a floating product, with dim neutral words and one orange word. Include this layered typographic device even when the object must be replaced by a simple original silhouette.
- Controls are miniature instruments, not sales blocks: 25px category pills, an 18×40px scroll capsule, and text actions preceded by a 22×14px outlined arrow capsule.
- Color behaves like a signal light: black and off-black occupy most of the product story; #ff5102 marks names, links and small rounded-square markers, then expands into a short full-width statement band. Cool #f2f2f4 provides the contrasting technical interlude.
- Navigation floats independently of the story: a fixed 528×45px translucent bar with 10px corners and 20px backdrop blur sits beside a separate 45px circular identity button, 34px below the top.
- The ending is an asymmetric index rather than a final billboard: a 474px light two-topic callout leads into a 623px off-black footer, with 27px links on the right, small decimal section numbers, and a largely open left field. Carry the numbered-index device into every new page.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5102` | `--color-signal` | accent, link, background | Default product identity, arrow links, small square markers and the compact statement band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Off-black | `#0f1012` | `--color-ink` | background, text | Technical chapters and footer; text on light bands. |
| Stage black | `#000000` | `--color-stage` | background, surface | Primary product opening and object-reveal stages. |
| Dark navigation glass | `#121212` | `--color-nav-glass` | surface | Visible rgba(175,175,175,0.1) over black; the translucent bar adapts to light sections. |
| Dark tag glass | `#1a1a1a` | `--color-tag-glass` | surface | Visible rgba(255,255,255,0.1) over black for pills and scroll control; over off-black the same material appears lighter. |
| Ghost lettering | `#333333` | `--color-ghost` | text | Visible white at 20% opacity over black in monumental background lettering. |
| Dark-field hairline | `#3f4041` | `--color-edge` | border | Visible white at 20% opacity over off-black for technical row dividers; over pure black it appears #333333. |
| Subdued gray | `#6b6b6a` | `--color-subdued` | text | Low-emphasis development and roadmap notes. |
| Navigation gray | `#717173` | `--color-nav-text` | text | Navigation's neutral declared text color; contrast switches with the band beneath it. |
| Muted gray | `#adadad` | `--color-muted` | text | Supporting explanation below device comparison actions. |
| Base gray | `#efefef` | `--color-canvas` | background, text | Underlying canvas and secondary text base; support text uses this at 50% opacity over black, appearing near #787878. |
| Porcelain | `#f2f2f4` | `--color-porcelain` | background, text | Light technical interludes and main text on dark fields. |
| White | `#ffffff` | `--color-white` | text, border | High-emphasis dark-stage headings and larger conversion links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| system focus indicators and corporate overview pages | System blue | `#0071e3` | `--color-blue` | link, border, accent, background | Focus-visible outlines throughout; corporate-theme headlines, pills, links and proof band. |
| multi-product comparisons | Comparison amber | `#fca311` | `--color-amber` | text, accent | Second device identity within a comparison; not an additional everyday page accent. |
| corporate overview pages | Portrait white | `#fdfdfd` | `--color-hero-paper` | background | High-key portrait opening with a soft white lower fade. |

## Typography

- **PP Neue Montreal** — All marketing type, navigation, technical labels and actions. A light neo-grotesk with restrained proportions and compact spacing; most text uses weight 350, monumental text uses 300. If unavailable, use **Inter**. Use variable weights 300 and 350; retain the negative tracking on ordinary headings and text. Font stack: "PP Neue Montreal", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental | PP Neue Montreal | 300 | 140px | 1.2 | 0.008em | Two-line background statements behind product renders and large comparison-section heading. |
| product-title | PP Neue Montreal | 350 | 43px | 1.2 | -0.02em | Opening product name, centered technical highlight and statement-band title. |
| device-heading | PP Neue Montreal | 350 | 38px | 1.2 | -0.02em | Individual device titles in comparison blocks. |
| heading | PP Neue Montreal | 350 | 27px | 1.2 | -0.02em | Capability chapter headings, closing callout headings and footer links. |
| action-lg | PP Neue Montreal | 350 | 20px | 1.2 | -0.02em | Larger conversion text links. |
| body | PP Neue Montreal | 350 | 16px | 1.2 | -0.02em | Paragraphs, navigation, categories, standard arrow links and decimal chapter numbers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| corporate overview pages | overview-label | PP Neue Montreal | 350 | 14px | 1.2 | -0.02em | Small section labels above compact editorial statements. |
| corporate overview openings | announcement | PP Neue Montreal | 350 | 12px | 1.2 | -0.02em | Compact announcement strip beneath navigation. |

**Notes:**

- Ordinary text and headings share -0.02em tracking and 1.2 line height; hierarchy comes from scale, placement and color rather than heavier weights.
- Monumental type deliberately reverses the spacing rule to positive 0.008em tracking and weight 300.
- Use sentence or title case, not all-caps technical eyebrows. Decimal indexes use the same sans as paragraphs.
- Support copy is often visually softened to 50% opacity. Keep the sparse short-line composition without making functional actions equally faint.

## Layout

**Density:** Airy at section scale, compact within text blocks and controls; short lines occupy small islands within full-width scenes.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Gap between category pills. | fixed |
| 10px | Small label-to-heading separation and technical-row bottom padding. | fixed |
| 21px | Arrow capsule to action label. | fixed |
| 22px | Closing heading to support text. | fixed |
| 34.5px | Main grid gutter; describe as 34.5px when communicating layout. | fixed |
| 40px | Opening product-name group to supporting paragraph. | fixed |
| 45px | Technical row top padding and comparison list separation. | fixed |
| 50px | Navigation item gap and footer top padding. | fixed |
| 114px | Capability chapter top padding. | fixed |
| 130px | Dark editorial and device-chapter section padding. | fixed |
| 144px | Major light callout band padding. | 10vw |
| 110px | Light technical-highlight top padding. | 7.63889vw |
| 320px | Light technical-highlight lower breathing room. | 22.2222vw |
| 120px | Signal statement band top padding. | 8.33333vw |
| 85px | Signal statement band bottom padding. | 5.90278vw |

### Containers and grids

- **five-column frame**: 5 columns · gap 34.5px · side padding 69.1px. Desktop frame spans 1302px inside a 1440px viewport. Columns are about 233px. Align editorial content one column inward rather than centering every section.
- **technical chapters**: max width 767px · 3 columns · gap 34.5px. Right-aligned chapter field begins around the third main column; labels and narrow headings sit beside concise capability lists.
- **device comparison**: 2 columns · gap 34.5px. Two 634px device blocks span the main frame; each combines media, title, ruled capability rows and a right-inset action area.
- **copy islands**: max width 280px. Centered hero support. Elsewhere use approximately 200px for headings and 370px for explanatory paragraphs, retaining short lines.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation | 10px |
| identity control | 50% |
| category pill | 54px |
| arrow capsule | 94px |
| scroll capsule | 26px |
| device media | 4px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Product introduction and floating object scenes.

**CSS:** `background-color: #000000; color: #f2f2f4`

**Observed:** Full-bleed unboxed darkness gives the object a continuous background.

**Transfer:** Let the media backing disappear into the section instead of outlining its container.

#### Off-black chapter · level 0

**Use:** Long technical content and footer.

**CSS:** `background-color: #0f1012; color: #f2f2f4`

**Observed:** Slightly lifted from pure black; separated through spacing and fine rules rather than elevated cards.

**Transfer:** Use this for dense readable chapters between cinematic stages.

#### Porcelain band · level 0

**Use:** Technical highlight and closing callouts.

**CSS:** `background-color: #f2f2f4; color: #0f1012`

**Observed:** Flat cool light gray, no visible shadow or enclosing radius.

**Transfer:** Make the change of illumination a full-width event.

#### Signal band · level 0

**Use:** Short emphatic product statement.

**CSS:** `background-color: #ff5102; color: #f2f2f4; padding-top: 120px; padding-bottom: 85px`

**Observed:** Compact centered title and two short support lines, not a grid of orange cards.

**Transfer:** Use a single concise promise or benefit to justify the saturated interruption.

#### Navigation glass · level 1

**Use:** Floating navigation bar and separate identity disc.

**CSS:** `background-color: rgba(175, 175, 175, 0.1); backdrop-filter: blur(20px); border-radius: 10px`

**Observed:** Translucent neutral material tracks the section underneath; the disc uses circular corners.

**Transfer:** Keep translucency confined to small controls rather than large content panels.

#### Portrait fade · level 0

**Only for:** corporate overview openings

**Use:** High-key human portrait stage.

**CSS:** `background-color: #fdfdfd`

**Observed:** A bottom-up near-white transparent gradient at 0.78 opacity merges the neck and shoulders into the canvas.

**Transfer:** Use a bottom-aligned white gradient over a softly lit subject; match the soft fade rather than adding a colored glow.

## Components

### Floating navigation

**Use:** Persistent top-level navigation.

**CSS:** `display: flex; align-items: center; gap: 50px; height: 45px; padding: 0px 30px; background-color: rgba(175, 175, 175, 0.1); backdrop-filter: blur(20px); border-radius: 10px`

**Text style:** `body` — PP Neue Montreal 350 · 16px/1.2 · tracking -0.02em

**Observed:** Five text destinations share a centered bar; a separate Identity disc sits across a 5px gap. The fixed group starts 34px below the top and remains above scrolling content.

**States:** Declared: hover on the link ancestor reduces opacity to 0.3; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset. Navigation material transitions background-color and color over 0.2s; link opacity over 0.3s.

**Transfer:** Use a compact set of category destinations, not a full-width masthead.

### Identity disc

**Use:** Home destination beside the navigation.

**CSS:** `width: 45px; height: 45px; border-radius: 50%; background-color: rgba(175, 175, 175, 0.1); backdrop-filter: blur(20px)`

**Observed:** A centered 25px identity symbol is isolated from the text bar.

**States:** Declared: hover is unspecified; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset.

**Transfer:** Insert the new project's own simple mark, maintaining the isolated disc.

### Category pill

**Use:** Product classes and single-letter chapter markers.

**CSS:** `display: flex; padding: 2.1px 11px 3.6px; background-color: rgba(255, 255, 255, 0.1); border-radius: 54px`

**Text style:** `body` — PP Neue Montreal 350 · 16px/1.2 · tracking -0.02em

**Observed:** Compact text-only labels stand in small groups or above a capability title. Corporate-theme destination pills use blue outlines, with the highlighted destination filled blue.

**Transfer:** Keep labels short enough to remain miniature, not card-like.

### Arrow link

**Use:** Default exploration and contact action.

**CSS:** `display: flex; align-items: center; column-gap: 21px; color: #ff5102`

**Text style:** `body` — PP Neue Montreal 350 · 16px/1.2 · tracking -0.02em

**Observed:** An outlined 22×14px capsule containing a tiny right arrow precedes plain text. Corporate-theme actions use blue instead of orange.

**States:** Declared: hover is unspecified; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset.

**Transfer:** Carry the separate arrow capsule into each important text action instead of making a solid rectangular button.

### Scroll capsule

**Use:** Small next-section invitation at the lower left of the first screen.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 18px; height: 40px; border-radius: 26px; background-color: rgba(255, 255, 255, 0.1)`

**Observed:** Contains a 7×9px downward arrow; remains visually subordinate to the product name.

**States:** Declared: hover is unspecified; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset.

**Transfer:** Retain a small directional control rather than a large scroll instruction.

### Technical row

**Use:** Capability summary inside each device comparison block.

**CSS:** `display: flex; align-items: flex-end; column-gap: 34.5px; padding-top: 45px; padding-bottom: 10px; border-bottom: 0.5px solid rgba(255, 255, 255, 0.2)`

**Text style:** `body` — PP Neue Montreal 350 · 16px/1.2 · tracking -0.02em

**Observed:** A letter or small capability icon occupies the left portion; the feature name and explanation align in a right-inset content column. Rows are about 114px tall.

**Transfer:** Use a few meaningful capability categories and preserve the repeated ruled structure.

### Large conversion link

**Use:** Action below a detailed device summary.

**CSS:** `display: inline-flex; align-items: center; column-gap: 21px; color: #ffffff; margin-top: 51px`

**Text style:** `action-lg` — PP Neue Montreal 350 · 20px/1.2 · tracking -0.02em

**Observed:** Larger white arrow capsule measures 34×21px. The action aligns to the block's inner text column, not its media's left edge.

**States:** Declared: hover is unspecified; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset.

**Transfer:** Reserve the larger white link for a consequential commitment after detail.

### Footer destination

**Use:** Primary index links and social destinations.

**CSS:** `color: #f2f2f4; background-color: transparent`

**Text style:** `heading` — PP Neue Montreal 350 · 27px/1.2 · tracking -0.02em

**Observed:** Links stack without bullet markers in the right side of the footer. Small decimal numbers and group labels occupy a separate column to their left.

**States:** Declared: hover is unspecified; focus-visible uses outline 1px dashed #0071e3 with 3px outline-offset.

**Transfer:** Maintain a short vertical index rather than many equal-width footer columns.

### Device media panel

**Use:** Image head of a comparison block.

**CSS:** `background-color: #000000; border-radius: 4px; overflow: hidden`

**Observed:** A 634×496px media area sits above the colored device heading, tags and Technical rows; the surrounding block has no card shell.

**Transfer:** Use a tightly framed product detail with the same black backing as the panel.

## Imagery and graphics

### Rim-lit object

**Use:** The main object in the opening and the large layered reveal.

**Observed:** A small rounded dark device floats on black. The opening shows a frontal upper edge traced by soft silver light, its lower body disappearing into darkness. The larger reveal exposes two separated metallic layers at diagonal angles, with silver upper faces, near-black sides and fine mechanical detail; it overlaps the monumental lettering.

**Transfer:** Create an original object render or cutout with a neutral metallic finish and restrained edge lighting. If no physical object exists, make a clean layered geometric proxy for the product's function; a single well-lit silhouette is the minimum acceptable version.

**Build:** For a simplified proxy, stack two original rounded SVG plates around 230×180px within a 468×374px transparent stage. Rotate them in opposite diagonal directions, separate them vertically, fill with near-black to gray linear gradients, add a thin upper-edge white stroke at low opacity and a blurred white highlight masked to the top edge. Keep the background pure black and the light neutral; use actual rendered material when available.

### Edge-entering macro pair

**Use:** Light technical highlight.

**Observed:** Two silver side profiles enter from opposite page edges, cut off beyond the frame. Each image is 720×173px, surrounding a compact centered title, square signal marker, support copy and Arrow link. Brushed metal, engraved tiny markings and underside sensor details contrast with the flat porcelain backing.

**Transfer:** Use enlarged matching details of the new product, horizontally cropped to face inward. For a service, use paired original layer diagrams with the same grayscale material and edge-entry framing.

**Build:** Place matching transparent detail images in two 720×173px side stages, translating their outer portions beyond the viewport and clipping at the section edge. Leave the central text island unobstructed; do not simulate the macro texture with a colored gradient.

### High-key human profile

**Only for:** corporate overview openings

**Use:** Human-centered overview hero.

**Observed:** A large photorealistic bald head in left-facing profile occupies the center-right of a white field. Warm brown skin and soft rim lighting are the only natural color; neck and shoulders dissolve into a near-white lower veil. Small black copy sits at lower left rather than over the face.

**Transfer:** Use a contemplative profile or an equivalent human-scale subject, isolated against near-white with a soft lower mask; preserve the contrast between a monumental subject and restrained text.

### Icons

**Observed:** Small filled SVG arrows sit within thin capsule outlines, usually 8×6px for right arrows. The scroll arrow is 7×9px. Capability symbols are compact and single-color; identity marks are approximately 25px in the navigation and larger but muted in the footer.

**Transfer:** Use spare monochrome directional and capability glyphs. Match arrow color to the link and keep the surrounding outline at 1px rather than using heavy icon buttons.

## Section recipes

How recurring sections are built.

### First screen: Object stage opening

**Observed:** The first 900px are a full black stage. Floating navigation sits high and centered; a subdued introduction line sits below it. A centered 468×374px rim-lit object image occupies the middle third, leaving extensive darkness around it. The product name appears near the lower fifth in the product-title recipe, orange and preceded by a small rounded-square marker. A centered 280px support paragraph sits about 40px below the name. A tiny development-status note aligns at lower right and the Scroll capsule at lower left. All of these fit above the fold; the giant layered-object statement begins below the opening. Back-to-front layers are black canvas, object, title/support, then fixed navigation.

**Transfer:** Stage the new product alone with a distinct neutral rim light, short name and concise promise. Without elaborate media, use the original geometric proxy described in Rim-lit object, not an empty stage. A corporate overview instead opens on Portrait fade, with a large human profile and a 27px lower-left statement, small outlined destination pills and an announcement strip below the navigation.

**Avoid:** Do not replace the small low-positioned name with an enormous centered sales headline, or squeeze a feature grid into the opening.

**Text style:** `product-title` — PP Neue Montreal 350 · 43px/1.2 · tracking -0.02em

### Layered monumental reveal

**Observed:** A Black stage carries a centered small introduction and a two-line monumental statement about 900px wide. Dim background words surround one orange word while the exploded metallic object sits in front. A short explanatory paragraph and category pills continue beneath the visual.

**Transfer:** Require a layered word-and-object moment in the page's story, using a fresh two- or three-word concept and a relevant object or abstract proxy. Keep the emphasized word legible beside the object.

**Text style:** `monumental` — PP Neue Montreal 300 · 140px/1.2 · tracking 0.008em

### Capability chapters

**Observed:** On Off-black chapter, the content field is right-inset. Each chapter has a Category pill marker, a 27px title and compact 16px capability lines. Chapters start with 114px top padding and use fine horizontal separators rather than individual feature cards.

**Transfer:** Group real capabilities into a few named chapters. Preserve the asymmetry and compact lists while allowing the number of chapters to follow the product.

**Text style:** `heading` — PP Neue Montreal 350 · 27px/1.2 · tracking -0.02em

### Macro technical interlude

**Observed:** Porcelain band places Edge-entering macro pair around a centered 43px title with one orange term, a tiny orange square marker, two support lines and an Arrow link. The section has 110px top padding and 320px lower breathing room.

**Transfer:** Make one technical advantage tangible through a magnified product detail and a short plain-language explanation.

**Text style:** `product-title` — PP Neue Montreal 350 · 43px/1.2 · tracking -0.02em

### Signal statement

**Observed:** Signal band uses a centered 43px white heading and a compact two-line supporting statement at 16px; the full-width orange surface is about 407px tall.

**Transfer:** Use the brightest page region for one strategic benefit rather than packing it with conversion UI.

**Text style:** `product-title` — PP Neue Montreal 350 · 43px/1.2 · tracking -0.02em

### Device comparison chapter

**Observed:** An Off-black chapter begins with a centered monumental heading. Two unboxed device columns follow after 140px separation: Device media panel, colored 38px device title, Category pill, repeated Technical rows, then Large conversion link and narrow explanatory notes. The second device uses amber as a local identity.

**Transfer:** Use this deep-detail treatment when the visitor needs to distinguish configurations or offerings, retaining the image-to-technical-row hierarchy.

**Text style:** `device-heading` — PP Neue Montreal 350 · 38px/1.2 · tracking -0.02em

### Numbered closing pair

**Observed:** A 474px Porcelain band uses 144px vertical padding. Two small content islands start one main column inward. Each has an accent-colored decimal index separated from a 27px heading by roughly 38px, 16px support text with a 22px gap, then an Arrow link. It is conversational and small-scale rather than a giant final slogan.

**Transfer:** Close with two relevant next steps, such as learning more and contacting the team, without forcing the original topics.

**Text style:** `heading` — PP Neue Montreal 350 · 27px/1.2 · tracking -0.02em

### Asymmetric footer index

**Observed:** Off-black chapter is 623px tall with 50px top and 40px bottom padding. A small wordmark sits at upper left and a muted larger emblem at lower left. The right side holds stacked Footer destinations in numbered groups: primary pages above, social links lower down. Small legal links run along the bottom of this right-hand field, with a location at the far right. Most of the left half remains open.

**Transfer:** Use the new identity, a concise destination index and a restrained legal baseline. Preserve the strong left/right imbalance.

**Text style:** `heading` — PP Neue Montreal 350 · 27px/1.2 · tracking -0.02em

### Editorial overview and proof

**Only for:** corporate overview pages

**Observed:** Narrow, offset editorial copy uses 27px statements with blue emphasis. Dark chapters introduce short 14px section labels, decimal indexes and repeated mission-like rows. A compact full-blue proof band uses a 38px white heading, small index and larger white action before the light closing pair.

**Transfer:** Use this more editorial mode for an organization-level story, grounding aspirational text in a real proof destination rather than repeating product specifications.

**Text style:** `heading` — PP Neue Montreal 350 · 27px/1.2 · tracking -0.02em

## Page flow

**Storyline:** isolated promise → layered demonstration → capability chapters → technical contrast → focused benefit → detailed choice → human next steps → indexed ending

### Flagship product landing story

1. **Promise** — Small product name and support beneath a floating rim-lit object on black.
2. **Product demonstration** — Exploded object crosses giant dim type with a single orange term.
3. **Capability chapters** — Right-inset lists divide functions using letter pills and ruled chapters.
4. **Technical distinction** — Light macro interlude uses inward-facing product details and a comparison action.
5. **Focused benefit** — Dark object scene gives way to a compact full-orange statement.
6. **Detailed choice** — Giant heading introduces two device summaries with media, specification rows and commitment links.
7. **Closing call** — Small numbered light callouts invite further exploration or contact.
8. **Navigation ending** — Deep off-black asymmetric destination and social index with a low legal baseline.

**Transfer:** Borrow the alternation of atmospheric demonstration and compact technical explanation; adapt chapter depth and choice blocks to the decision the new product requires.

### Organization-level overview and exploratory gateway

1. **Promise** — High-key human profile with restrained lower-left statement and blue product destination pills.
2. **Positioning** — Narrow offset introduction with the final idea emphasized in blue.
3. **Principles** — Off-black numbered statements and small grouped editorial copy.
4. **Product introduction** — Monumental blue two-line heading, small product visual and concise development text.
5. **Progress and ambition** — Two offset dark editorial chapters with short section labels and blue links.
6. **Proof** — Full-blue band presents a compact white evidence-oriented title and action.
7. **Closing call** — Light numbered pair followed by the shared off-black index footer.

**Transfer:** Use this variant for a broad overview where a human-scale image and an editorial argument matter more than detailed configuration selection.

## Writing

Aspirational and research-led, with the confidence of a technical program rather than the urgency of a shop. Short conceptual headings are balanced by specific functional explanations and candid development qualifications.

**Do not copy:** Do not reuse the Augen name, identity artwork, device names, proprietary technology labels, medical claims, investment amounts, launch dates or source slogans as claims for a new product. Examples below illustrate voice only.

- **Addressing the reader:** Mostly 'we' for intention and belief, and impersonal product descriptions for capabilities. Direct reader address is rare; actions use short verbs.
- **Rhythm:** Headings are commonly one to four words; support is one compact sentence split into short visual lines. Technical lists favor concise noun phrases. No exclamation-driven selling.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening name | A concise product designation rather than a benefit paragraph disguised as a headline. | 1–3 words | “A¹ Sense” |
| Conceptual heading | Two or three declarative concept words, with one term available for accent color. | 2–4 words | “Invisible Sense Computing”<br>“Beyond Humanware.” |
| Supporting promise | An intention connected to a human outcome, without an urgent sales pitch. | One sentence | “We aim to seamlessly integrate our devices with human physiology to amplify the quality of daily experiences.” |
| Capability label | Specific functional noun phrase, sometimes followed by a parenthetical method. | 3–9 words | “Gesture Recognition (AI-based)” |
| Action | Short verb-led invitation to inspect or start a conversation. | 2–3 words | “Compare Devices”<br>“Learn How”<br>“Say Hello” |

**Words and phrasing to use:** engineered; integrate; capabilities; research and development; designed; interaction; everyday life

**Avoid:** buy now; hurry; game-changing!; unlimited magic; disrupt everything

**Rules:**

- Keep conceptual language in headings and put actual functions in the supporting text.
- Qualify future products explicitly with their real development status.
- Use ordinary title case selectively for named capabilities; do not turn every label into capitals.
- Let a short action describe its destination instead of promising an unspecified transformation.

## Do's and Don'ts

### Do

- Keep ordinary marketing type at weight 350, 1.2 line height and -0.02em tracking.
- Use the 140px light display recipe for a word-and-object scene rather than for every heading.
- Preserve the 34.5px desktop gutters and approximately 69px side margins.
- Pair a 22×14px outlined arrow capsule with 16px action text across a 21px gap.
- Keep large scene backgrounds flat black, off-black or porcelain.
- Use 0.5px translucent white rules to organize technical detail.
- Give the light closing callouts 144px vertical padding and small numbered labels.
- Keep comparison media only subtly rounded at 4px.

### Don't

- Do not make the main product name bold; its 43px weight-350 treatment depends on restraint.
- Do not add drop shadows to chapter panels; hierarchy comes from full-width color fields.
- Do not spread orange across every section: its large fill is a concentrated statement, not the canvas.
- Do not apply the comparison amber to routine navigation or unrelated headings.
- Do not replace the 45px glass navigation with a full-width opaque banner.
- Do not enclose every capability in a rounded tile; use compact chapters and fine rules.
- Do not distribute footer links evenly across the whole width; keep the right-heavy index.
- Do not use monospace for technical labels or decimal indexes; the same grotesk serves both.

## Motion and responsive

### Motion

**Observed:**

- Declared link opacity transitions use 0.3s; navigation background-color and color transitions use 0.2s.
- Pill background-color and color transitions use 0.3s.
- Focus-visible actions use a 1px dashed blue outline offset by 3px.
- No CSS keyframe animations are declared; fixed navigation persists over sections.

**Transfer:**

- Keep theme changes in the small floating navigation tied to the underlying light or dark band.
- Preserve the layered object-and-type scene as a complete static composition as well as any animated version.

**Unknown:**

- Exact scroll-driven object movement, reveal timing and playback behavior are not established.
- No specific easing is assigned here because rule-level associations are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 833px, 834px, 1024px and 1440px.
- Several section paddings use viewport-relative formulas, including 10vw for the closing light band.

**Transfer:**

- On narrow screens, keep the object and small product name as a single centered hierarchy; move the status note into normal reading flow.
- Stack the comparison columns and closing pair while retaining the decimal-index relationship.
- Scale the monumental word-and-object scene to remain layered; clip peripheral macro images rather than allowing horizontal page overflow.

**Unknown:**

- Mobile navigation structure and exact type scaling are not established.
- Narrow-screen stacking and scene simplification above are transfer guidance, not prescribed measured layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
