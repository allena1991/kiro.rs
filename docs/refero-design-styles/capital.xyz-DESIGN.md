# Capital — sculptural utility on black

## Overview

An expansive, almost cinematic technology style with featherweight grotesk headlines, warm ivory surfaces and a predominantly black canvas. Product interfaces are staged as physical objects, while documentary photography adds human texture. Mint announcements and coral actions punctuate an otherwise restrained neutral palette; the overall density is low, with compact controls floating over monumental scenes.

### Essentials

- A two-line promise behaves like a luminous title card: Muoto 300 at 115.2px/1.15 with -0.02em tracking, centered within 1120px above an oversized product object.
- Navigation is a persistent bottom instrument dock rather than a conventional top menu: 1328px maximum width, 56px height, 12px corners and 25px backdrop blur; a small identity alone occupies the 108px top header.
- Color is concentrated into tiny signals and one enormous action: a mint 31px announcement, coral 40px rectangular buttons with 8px corners, and a 522px coral circular call to action. Black and ivory account for almost all other page area.
- Interfaces become exhibits: a broad dark tablet dominates the opening, and 576×720px ivory panels with 16px corners isolate individual workflows against black. Use a clean representative interface in a restrained device frame when bespoke media is unavailable.
- Warm ivory interrupts the black canvas as full-width proof and product bands: 90px light headlines at weight 300, narrow gray support copy, and oversized device art cut off by the section edges.
- A tactile circular action is a signature graphic, not merely an enlarged button: 50% radius, peach inset illumination and a 90px centered verb, isolated in black with 80px separation from the small closing information.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral action | `#ed5145` | `--color-coral` | action, surface | Small conversion buttons and the monumental circular action, never ordinary content bands. |
| Peach rim | `#ff7a70` | `--color-peach` | accent | Inset illumination around the circular action, including a 50% alpha layer. |
| Mint signal | `#a5efd9` | `--color-mint` | surface, accent | A compact announcement above the main promise; not a page background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black stage | `#000000` | `--color-canvas` | background, text | Default marketing canvas and text on mint announcements. |
| Smoked glass | `#151515` | `--color-glass` | surface | Visible dock fill over black, made with 80% charcoal; underlying light content changes its appearance. |
| Near-black badge | `#161616` | `--color-badge` | surface | Understated editorial chapter link. |
| Charcoal | `#1a1a1a` | `--color-charcoal` | surface, text, border | Text on ivory; dark controls and fields; source hue of the translucent dock. |
| Control edge | `#302f2f` | `--color-edge` | border, surface | Faint dark control borders and icon-tab hover fill. |
| Stone gray | `#8e8c87` | `--color-muted` | text | Support text on ivory and discreet closing information. |
| Warm gray | `#bfbcb7` | `--color-secondary` | text | Secondary paragraphs, role descriptions and small mono labels. |
| Warm ivory | `#efece6` | `--color-ivory` | text, background, surface | Primary text on black, full-width light bands, demonstration panels and light subscription actions. |
| Action white | `#ffffff` | `--color-white` | text | Small primary-action labels and active navigation links. |

## Typography

- **Muoto** — All prose, headings, names and navigation. Open, clean grotesk with circular counters and a notably light display cut. If unavailable, use **DM Sans**. Use 300 for prose and display, 400–500 for controls; retain tight display tracking. Font stack: "Muoto", "DM Sans", Arial, sans-serif.
- **GT America Mono** — Tiny announcement text, sequence tags and proof labels. Technical monospaced capitals with conspicuously open tracking. If unavailable, use **IBM Plex Mono**. Font stack: "GT America Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Muoto | 300 | 115.2px | 1.15 | -0.02em | fixed | Centered opening promise, normally in two lines. |
| heading-lg | Muoto | 300 | 90px | 1.15 | -0.01em | size clamp(48px, 7vw, 90px) | Major benefits, short feature verbs and the circular conversion action. |
| heading | Muoto | 300 | 72px | 1.15 | -0.01em | size clamp(40px, 6vw, 72px) | Human-proof section heading; also the scale of mission statements and directory headings. |
| lead | Muoto | 300 | 32px | 1.4 | -0.01em | fixed | Centered explanatory line below a light-band benefit. |
| body | Muoto | 300 | 20px | 1.4 | normal | size clamp(16px, 2vw, 20px) | Paragraphs, image captions, names and role descriptions. |
| button | Muoto | 500 | 16px | 1.5 | normal | fixed | Small coral conversion actions. |
| identity | Muoto | 500 | 16px | 1.15 | -0.02em | fixed | Compact uppercase identity beside a small emblem. |
| eyebrow | GT America Mono | 400 | 12px | 1.15 | 0.08em, uppercase | size clamp(12px, 2vw, 12px) | Proof labels and numbered editorial tags. |
| announcement | GT America Mono | 400 | 12px | 1.6 | 0.08em, uppercase | size clamp(12px, 2vw, 12px) | Compact announcement and chapter-link text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| people directories | handle | Muoto | 300 | 16px | 1.4 | normal, lowercase | fixed | Social handles under names and roles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display typography gets lighter rather than heavier as it grows. Preserve 300 throughout headlines and body copy; reserve 500 for tiny identity and actions.
- Tracking is -0.02em for the opening, -0.01em for section headings and leads, and normal for readable body copy. Mono labels reverse the pattern with 0.08em spacing.
- Sentence case carries the main narrative; uppercase belongs to the identity and small mono apparatus. Do not treat image captions as bold subheadings.

## Layout

**Density:** Airy scenes with compact controls: large objects and brief text sit in broad black or ivory fields.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Name-to-role caption gaps. |
| 8px | Dock padding and compact control spacing. |
| 16px | Heading-to-support gaps, media-to-caption separation and directory gutters. |
| 24px | Product support-line separation and editorial image-to-caption separation. |
| 32px | Proof-section heading stack. |
| 40px | Header vertical padding and opening composition gap. |
| 64px | Main section side padding, feature column gaps and directory row separation. |
| 80px | Circular action to closing-information separation. |
| 90px | Light proof-band vertical padding. |
| 96px | Feature-chapter bottom padding. |
| 112.5px | Closing bottom breathing room and sticky-scene margins. |
| 144px | Inset human-proof section side padding. |
| 164px | Human-proof vertical padding and directory ending space. |

### Containers and grids

- **wide stage**: max width 1328px · side padding 56px. Centered product imagery and fixed bottom dock at desktop.
- **opening text**: max width 1120px. Centered two-line opening promise, smaller than the main product object.
- **benefit text**: max width 800px. Centered light-band heading; support narrows further to 530px.
- **feature pair**: 2 columns · gap 64px · side padding 64px. Ivory demonstration on the left and a narrower text block on the right.
- **human proof**: 3 columns · gap 57px · side padding 144px. Three tall documentary images with direct captions; heading centered above.
- **editorial archive** (only for editorial collection pages): 2 columns · gap 66px · side padding 64px. Wide 623×432px documentary frames, two per row, with metadata below.
- **people directory** (only for people directories): max width 1200px · 4 columns · gap 16px. Centered four-column wall with 288px cards and 64px breathing room between rows.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 8px |
| dock | 12px |
| demonstration panels | 16px |
| monumental action | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| dock | `rgba(0, 0, 0, 0.08) 0px 6px 20px 0px` | Soft separation under the persistent navigation. |
| circular action rim | `rgba(0, 0, 0, 0.05) 0px 4px 4px 0px, rgba(255, 122, 112, 0.5) 0px 0px 20px -1px inset, rgb(255, 122, 112) 0px 4px 20px -1px inset` | Subtle inflated edge of the large coral disc. |

### Surfaces

#### Black stage · level 0

**Use:** Default background for opening, feature chapters, photography and conversion.

**CSS:** `background: #000000; color: #efece6`

**Observed:** An uninterrupted black field; sections are distinguished by composition rather than container outlines.

**Transfer:** Use negative space as the main separator.

#### Ivory band · level 0

**Use:** High-contrast proof and cross-device scenes.

**CSS:** `background: #efece6; color: #1a1a1a`

**Observed:** Full-bleed warm neutral, not a floating white card.

**Transfer:** Give the light field a clear narrative role and allow product art to overlap its edges.

#### Ivory exhibit · level 1

**Use:** Individual workflow media.

**CSS:** `background: #efece6; border-radius: 16px; overflow: hidden`

**Observed:** Tall 576×720px panels set against black with a small interface centered within generous unused space.

**Transfer:** Keep a single understandable interface operation inside each exhibit.

#### Smoked dock · level 2

**Use:** Persistent navigation over both dark and light scenes.

**CSS:** `background: rgba(26, 26, 26, 0.8); border-radius: 12px; backdrop-filter: blur(25px); box-shadow: rgba(0, 0, 0, 0.08) 0px 6px 20px 0px`

**Observed:** The translucent fill picks up pale or dark imagery passing behind it.

**Transfer:** Preserve translucency instead of using an opaque gray bar.

#### Dark control · level 1

**Use:** Small icon tabs, sequence tags and subscription fields.

**CSS:** `background: #1a1a1a; border: 1px solid #302f2f; border-radius: 8px`

**Observed:** Only a faint edge separates the fill from nearby black.

**Transfer:** Use this treatment for apparatus, not large marketing cards.

## Components

### Bottom navigation dock

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; bottom: 16px; height: 56px; max-width: 1328px; border-radius: 12px; background: rgba(26, 26, 26, 0.8); backdrop-filter: blur(25px); display: flex; justify-content: space-between; align-items: center; z-index: 90`

**Observed:** Identity and chapter icon tabs sit left; utility links and Primary button sit right. Editorial and people variants simplify the left to an identity. It remains visible at every page ending.

**Transfer:** Use a small set of meaningful chapter anchors for a landing page; simplify them for a directory.

### Primary button

**Use:** Compact conversion action inside the dock.

**CSS:** `background: #ed5145; color: #ffffff; border-radius: 8px; padding: 8px 24px; height: 40px`

**Text style:** `button` — Muoto 500 · 16px/1.5

**Observed:** A compact solid rectangle rather than a pill; it is the brightest small control.

### Navigation link

**Use:** Utility and secondary destination links.

**CSS:** `color: #efece6; padding: 8px 16px; display: flex`

**Observed:** Unboxed 16px Muoto 400 links with normal line height and tracking arranged horizontally; the active destination uses white.

**States:** Declared: hover color #efece6; focus-visible unknown.

### Announcement badge

**Use:** A single timely message above the opening promise.

**CSS:** `background: #a5efd9; color: #000000; border-radius: 8px; padding: 6px 16px; display: flex; align-items: center; gap: 12px`

**Text style:** `announcement` — GT America Mono 400 · 12px/1.6 · tracking 0.08em · uppercase

**Observed:** Tiny mono capitals followed by a diagonal arrow. A near-black variant identifies an editorial chapter later in the page.

**Transfer:** Keep it to one short message; use the dark variant away from the opening.

### Chapter icon tab

**Use:** Direct navigation among product chapters.

**CSS:** `width: 32px; height: 32px; border-radius: 8px; background: #1a1a1a; border: 1px solid #302f2f; display: flex; align-items: center; justify-content: center; box-shadow: rgba(26, 26, 26, 0.4) 0px 8px 24px 0px`

**Observed:** A 16px light symbol is centered in each square. The selected tab is ivory with a dark symbol and a short underline.

**States:** Declared: hover background-color #302f2f and border-color #1a1a1a; focus-visible unknown.

### Workflow exhibit

**Use:** Product capability demonstration.

**CSS:** `width: 576px; height: 720px; background: #efece6; border-radius: 16px; overflow: hidden; position: sticky`

**Observed:** A video or interface fragment is isolated inside the panel; the adjacent chapter explains the outcome, then mechanics.

**Transfer:** Show real content or a carefully drawn simplified workflow, not an empty panel.

### Circular conversion action

**Use:** Monumental conversion graphic on a marketing page.

**CSS:** `width: 522px; height: 522px; border-radius: 50%; background: #ed5145; color: #efece6; display: flex; align-items: center; justify-content: center; box-shadow: rgba(0, 0, 0, 0.05) 0px 4px 4px 0px, rgba(255, 122, 112, 0.5) 0px 0px 20px -1px inset, rgb(255, 122, 112) 0px 4px 20px -1px inset`

**Text style:** `heading-lg` — Muoto 300 · 90px/1.15 · tracking -0.01em

**Observed:** A single verb sits in the middle of a tactile disc, with no adjacent sales paragraph.

**Transfer:** Use an equally short conversion verb and preserve the disc as a recognizable visual device.

### Documentary portrait card

**Use:** Human proof on the main marketing narrative.

**CSS:** `display: flex; flex-direction: column; gap: 4px; color: #efece6`

**Text style:** `body` — Muoto 300 · 20px/1.4

**Observed:** An unrounded 346×500px photograph sits above a name and muted role. Media-to-text separation is 16px. No enclosing card surface.

### Sequence tag

**Only for:** editorial collections

**Use:** Numbered metadata alongside documentary captions.

**CSS:** `background: #1a1a1a; border: 1px solid #302f2f; border-radius: 8px; padding: 6px 12px; color: #bfbcb7; display: flex; align-items: center`

**Text style:** `eyebrow` — GT America Mono 400 · 12px/1.15 · tracking 0.08em · uppercase

**Observed:** A small right-aligned tag balances a two-line role-and-name caption beneath each wide image.

### Subscription form

**Only for:** editorial collection endings

**Use:** A restrained follow-up action after the final media row.

**CSS:** `display: flex; align-items: center; height: 40px; overflow: hidden`

**Observed:** A charcoal 262px input with a faint border and 16px side padding meets an ivory 110px button. Both use 8px outer corners. The button uses Muoto 400 at 16px with normal line height and tracking. A brief centered invitation sits 24px above.

**Transfer:** Ask for one field, not a large lead-generation form.

### Sculpture profile card

**Only for:** people directories

**Use:** Introduce individual people without conventional headshot treatment.

**CSS:** `display: flex; flex-direction: column; gap: 16px; margin-bottom: 64px; color: #efece6`

**Text style:** `body` — Muoto 300 · 20px/1.4

**Observed:** A stone-bust portrait appears above name, muted role and smaller lowercase social handle. Caption lines use 4px gaps. Cards have no border or enclosing background.

**Transfer:** Commission a consistent sculptural portrait treatment, with the same camera and lighting across people.

## Imagery and graphics

### Physical product stage

**Use:** Opening product object and large cross-device scene.

**Observed:** A front-facing black tablet with a thin metallic edge and rounded hardware corners encloses a warm ivory-and-charcoal interface. It dominates the lower opening and continues beneath the fold. Later, a phone rises at lower left while a much larger tablet extends beyond the right and bottom edges of an ivory band. Shadows remain soft and neutral.

**Transfer:** Use the new product's real interface inside a restrained dark device frame. Minimum version: a crisp interface panel with a fine metallic outline, rounded hardware silhouette and subtle shadow; retain the dramatic scale and partial framing.

### Workflow miniatures

**Use:** Inside Workflow exhibit panels.

**Observed:** Small, low-contrast interface fragments float centrally in a very large ivory field: a total-value tile or a compact amount form with a circular arrow. Thin neutral edges and soft contact shadows make the fragment feel physical without colorful chrome.

**Transfer:** Draw one meaningful transaction or operation with readable hierarchy and ample surrounding space. Keep internal product colors subordinate to the marketing palette.

### Documentary people

**Use:** Human-proof portraits and editorial collection media.

**Observed:** Candid activity, close faces, workspaces, sport, a handheld camera and city environments. Images have deep shadows, subdued greens and warm practical light rather than bright corporate lighting. Tall portraits support the marketing section; editorial collections use wide frames at 70% opacity over black with square corners.

**Transfer:** Photograph real users in their own settings with directional natural or practical light. Select frames that communicate concentration or movement; preserve dark tonal depth instead of adding colorful graphic backings.

### Coral disc light

**Use:** The signature Circular conversion action.

**Observed:** A nearly flat coral face becomes gently inflated at the rim through peach inset light. It is the only large saturated object against black.

**Transfer:** Recreate the material in CSS rather than adding an unrelated illustration.

**Build:** Create a 522px circular anchor with a coral fill. Layer a 4px downward soft black shadow at 5% alpha, an inset peach glow of 20px at 50% alpha and a second peach inset shadow offset 4px downward with 20px blur and -1px spread. Center the light 90px verb. Keep the black surroundings unlit.

### Stone portrait sculpture

**Only for:** people directories

**Use:** Consistent portrait wall.

**Observed:** Off-white sculpted busts on small plinths against almost-black studio grounds. Three-quarter faces, draped shoulders and visible modeled stone facets are lit softly from above and left; each image is close to square and unrounded.

**Transfer:** Use original likenesses rendered in the same monochrome stone material. A minimum version is a deliberately simplified faceted bust with convincing directional light and a grounded pedestal.

**Build:** Use a low-poly head-and-shoulders mesh, warm ivory rough stone material, a short round plinth and a black seamless floor. Place a broad soft light above-left with minimal fill; render the bust at three-quarter angle with consistent camera distance and a subtle contact shadow. Do not tint each person differently.

### Icons

**Observed:** Small monochrome utility symbols: 16px light chapter icons in dark 32px squares, thin diagonal arrows in badges, and 12px social marks beside handles. Selected chapter icons invert to dark on ivory.

**Transfer:** Choose a consistent compact line-symbol set; keep brand identity separate from utility symbols and preserve selected inversion rather than adding colored icons.

## Section recipes

How recurring sections are built.

### First screen: Title and tablet opening

**Observed:** Back to front: Black stage, a tiny centered identity in a 108px header, mint Announcement badge, a two-line ivory promise in the display recipe within 1120px, a large front-facing tablet below, and Bottom navigation dock floating across the lower viewport. The headline spans roughly two thirds of the screen and occupies about 265px vertically. Within the first 900px, the identity, announcement, complete headline and upper portion of the product interface are visible; the tablet continues below the fold. The visible hardware is narrower than the full 1328px image bounds. No support paragraph or paired hero buttons interrupt the title; the compact conversion remains in the dock.

**Transfer:** Write a short two-line promise and stage a representative interface or product object beneath it, using the Physical product stage fallback if needed. Editorial pages can replace the object with the start of a two-column documentary collection; people pages use a left-aligned 72px mission statement and a narrow offset supporting column instead.

**Avoid:** Do not shrink the product into a small side illustration, add a conventional top link menu, or insert a busy hero paragraph and competing buttons.

**Text style:** `display` — Muoto 300 · 115.2px/1.15 · tracking -0.02em

### Ivory proof pause

**Observed:** Ivory band with 90px vertical padding. A centered heading-lg stays within 800px, followed after 16px by a 32px lead within 530px. A low-contrast logo row and small mono label complete the proof.

**Transfer:** Give one verifiable outcome a full visual pause. Use supporting partner marks or other concise proof beneath it rather than a dense statistical dashboard.

**Text style:** `heading-lg` — Muoto 300 · 90px/1.15 · tracking -0.01em

### Workflow chapter

**Observed:** Black stage with 64px side padding and a 64px column gap. Workflow exhibit fills the left; a short heading-lg verb and two 20px text levels sit to the right, with bright outcome text before muted implementation detail. Chapters share one visual stage and chapter tabs identify the active capability.

**Transfer:** Pair one operation with one outcome per chapter. Use a sequence that suits the new product without multiplying boxed feature cards.

**Text style:** `heading-lg` — Muoto 300 · 90px/1.15 · tracking -0.01em

### Overscale device band

**Observed:** Ivory band with 64px top and side padding. Left-aligned heading-lg wraps into a narrow stack; a muted support line follows after 24px, then a compact platform badge. Physical product stage media overlaps the remaining width and is clipped at the right and bottom.

**Transfer:** Use this composition for availability, portability or a second context of use. Let scale and overlap make the scene rather than adding decorative shapes.

**Text style:** `heading-lg` — Muoto 300 · 90px/1.15 · tracking -0.01em

### Human proof triptych

**Observed:** Black stage with 164px vertical and 144px horizontal padding. A dark chapter badge precedes a centered 72px heading; three Documentary portrait cards sit beneath in a loose triptych with about 57px gutters.

**Transfer:** Use three concise human stories with full-height photographs, not testimonial quote boxes. The headline explains the audience benefit rather than naming the collection.

**Text style:** `heading` — Muoto 300 · 72px/1.15 · tracking -0.01em

### Disc and discreet close

**Observed:** Circular conversion action centered on Black stage. Closing information follows 80px below, with a tiny legal-link row and a short muted disclaimer. Bottom navigation dock remains present. The section reserves 112.5px at its base.

**Transfer:** Give the primary action the scale of an object, with factual closing information subordinate beneath. Place the disc where it best resolves the marketing narrative rather than treating it as a reusable button size everywhere.

**Text style:** `heading-lg` — Muoto 300 · 90px/1.15 · tracking -0.01em

### Documentary archive and signup

**Only for:** editorial collections

**Observed:** A centered display promise opens over black. Two columns of 623×432px dark documentary images use about 66px gutters and 64px outer margins. Two-line captions sit below with a Sequence tag aligned right. After the last row, a small centered invitation and Subscription form end the page, with the dock still visible.

**Transfer:** Build a browsable collection with calm consistent metadata. Keep the final action smaller and more editorial than a landing-page disc.

**Text style:** `display` — Muoto 300 · 115.2px/1.15 · tracking -0.02em

### Mission and sculpture wall

**Only for:** people directories

**Observed:** A left-aligned 72px statement starts well below the small identity, with 180px vertical section padding. Supporting 20px prose is narrower and offset right below the statement; investor links are underlined. A 72px directory heading leads to the four-column Sculpture profile card wall. The final row is incomplete and left aligned; black breathing room and the persistent dock end the page, with no additional signup or disc.

**Transfer:** Use a specific shared purpose, then a consistent visual system for individual people. Let the directory finish naturally rather than forcing a marketing conversion section.

**Text style:** `heading` — Muoto 300 · 72px/1.15 · tracking -0.01em

## Page flow

**Storyline:** Promise → tangible product or human demonstration → focused benefits and proof → a page-appropriate next step.

### Product marketing landing page

1. **Promise** — Centered title, small announcement and dominant tablet scene.
2. **Quantified proof** — Full-width ivory benefit statement with quiet supporting marks.
3. **Capability chapters** — Shared dark stage with tall workflow exhibits and short verb headings.
4. **Context expansion** — Oversized devices against an ivory band.
5. **Human proof** — Documentary triptych beneath a broad audience-benefit heading.
6. **Closing call** — Monumental coral disc followed by discreet closing information; persistent dock remains.

**Transfer:** Alternate immersive demonstrations with brief light proof pauses, and resolve the narrative with a tactile action. Adapt block count and sequence to the new offering.

### Editorial story collection

1. **Promise** — Two-line centered display statement over black.
2. **Human demonstration** — Two-column documentary archive with role, person and numbered tag.
3. **Continuation** — Small centered subscription invitation after the last pair of stories.

**Transfer:** Let documentary imagery carry variety while metadata stays uniform. End with a compact follow action rather than the landing-page conversion scene.

### Organization and people introduction

1. **Shared purpose** — Left-aligned large mission statement and offset supporting prose.
2. **Credibility** — Short background paragraph and underlined institutional links.
3. **People proof** — Directory heading and consistent four-column stone portrait wall.
4. **Natural ending** — Final partial row, black space and the persistent navigation dock.

**Transfer:** Keep purpose expansive and biographies compact. Use the sculpture treatment only within a people-focused context.

## Writing

Confident and direct, but more inviting than institutional. Claims are plain and concrete; the emotional warmth comes from people and useful outcomes rather than exuberant sales language.

**Do not copy:** Do not reuse Capital's identity, logos, people, customer names, institutional affiliations, artwork, product screens, financial promises, percentages, claims or source quotations as claims for a new product. Examples illustrate syntax only.

- **Addressing the reader:** Use you and your for outcomes; use we for organizational purpose. Refer to the product by name when describing access or an operation.
- **Rhythm:** A broad two-line promise gives way to one-word capability headings, one-sentence outcome lines and brief explanatory paragraphs. Actions are often one verb. No exclamation-driven enthusiasm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A simple declarative sentence linking an audience to the product. | 7–10 words | “Modern companies are built on [Brand]” |
| Benefit headline | Lead with the tangible result, using a number only when defensible. | 6–10 words | “Earn 4% APY on all of your money” |
| Capability heading | A single active verb names the operation. | 1 word | “Send” |
| Support | State the practical outcome first, then explain the mechanism separately. | 10–25 words per sentence | “Build trust with your partners by easily paying them from your [Brand] account”<br>“Access your [Brand] account on iOS and web.” |
| Action | Use a direct verb without sales qualifiers. | 1–2 words | “Start”<br>“Subscribe” |
| Purpose | An earnest first-person mission with a concrete beneficiary and activity. | 15–25 words | “Our mission is to inspire generations of founders by building the best products to run modern companies.” |

**Words and phrasing to use:** built on; your; access; send; run; modern; with ease; start

**Avoid:** revolutionary ecosystem; unlock limitless potential; disrupt everything; hurry; !!!

**Rules:**

- Prefer a recognizable operation to an abstract feature category.
- Separate the immediate benefit from the explanation of how it works.
- Use captions for identities and roles; keep documentary images free of overlaid slogans.
- Keep subscription invitations conversational and short.
- Place caveats in discreet closing information without obscuring material conditions of a claim.

## Do's and Don'ts

### Do

- Keep the opening at weight 300 with -0.02em tracking and a two-line, 1120px text measure.
- Use black as the default scene and warm ivory for purposeful full-width pauses.
- Keep the bottom dock 56px tall with 12px corners and 25px blur.
- Make small conversion buttons 40px tall with 8px corners and a coral fill.
- Pair 90px capability verbs with 20px/1.4 explanatory copy.
- Retain a 522px tactile circular action as a signature marketing graphic.
- Keep documentary captions outside images and use 4px gaps between identity lines.
- Use 16px corners for ivory workflow exhibits, not for documentary photos.

### Don't

- Do not replace the light grotesk hierarchy with bold 700 headlines.
- Do not turn mint into a broad page wash; its default role is a tiny announcement.
- Do not use coral as the fill of ordinary benefit cards or section backgrounds.
- Do not round the compact actions into full pills; retain their 8px corners.
- Do not put documentary photography into generic bordered testimonial cards.
- Do not spread the stone-bust treatment into ordinary product illustrations; it belongs to people directories.
- Do not replace the smoked dock with an opaque full-width bottom toolbar.
- Do not make supporting prose as bright or as wide as the main promise; preserve the warm-gray secondary tier.

## Motion and responsive

### Motion

**Observed:**

- Navigation links declare color 0.6s cubic-bezier(0.33, 1, 0.68, 1).
- Chapter tabs declare background-color and border-color transitions of 0.2s cubic-bezier(0.33, 1, 0.68, 1).
- Workflow panels declare transform 0.8s and opacity 0.4s cubic-bezier(0.33,1,0.68,1). Small and circular conversion actions declare transform 0.2s.
- Workflow exhibits use sticky positioning and chapters share an overlapping stage.

**Transfer:**

- Keep chapter changes attached to the shared product exhibit and its selected dock tab rather than introducing unrelated animated ornaments.
- Use the declared color and panel transitions for their matching components.

**Unknown:**

- Scroll choreography, trigger thresholds and conversion-button transform endpoints are not specified.
- A glow rotation keyframe is declared, but its visible playback and timing are not established.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 600px and 768px.
- Major section headings use clamp(48px, 7vw, 90px); human-proof headings use clamp(40px, 6vw, 72px); body copy uses clamp(16px, 2vw, 20px).

**Transfer:**

- On narrow layouts, preserve the title-before-object hierarchy and the oversized product feeling; simplify dock chapter controls before sacrificing the primary action.
- Stack workflow text and exhibits and reduce directory columns while preserving the sculpture camera consistency. These are adaptation rules, not alternate measured layouts.
- Scale the circular action to fit the available width while maintaining a perfect circle and its inset rim.

**Unknown:**

- Exact mobile grid counts, dock collapse behavior, hero size rule and mobile image clipping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
