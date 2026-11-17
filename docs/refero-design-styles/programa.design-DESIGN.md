# Programa — editorial workbench in motion

## Overview

An editorial face for practical software: fine, light serif headlines sit above compact sans-serif controls and warm, image-rich interfaces. White and ivory dominate, with charcoal text, lemon-yellow actions and small mint signals. Floating objects, tactile paper-like panels and natural workplace photography make a spacious product story feel inhabited rather than technical.

### Essentials

- Editorial promises above workmanlike controls: Rhymes Display 300 at 60px/64px with -1.5px tracking for the opening and closing, 44px/50px for chapter statements; Inter handles the functional details.
- The first screen is a warm product stage: a centered 720px headline, 450px support line, paired 31px actions and a 1008px-wide interface rising into the lower half of a 900px scene, fading into white at the bottom.
- Actions look like miniature physical keys, not pills: 6px corners, 6px 8px padding, 12px/1.4 text, fine edge shadows and a restrained inset highlight. Charcoal is the default; lemon yellow marks navigation and the final invitation.
- Color belongs to objects, not the canvas: white, #f8f6f3 and #fcfbf9 occupy nearly all large fields; #fdffa2 appears in tiny action surfaces and mint in a small announcement. Richer hues arrive through photography and product fragments.
- Interfaces are handled like studio materials: 536px square demonstrations and 368px square tiles pair white UI fragments with warm gray halftone textures, overlapping cards and softly shadowed cutout objects. Include a floating-object constellation; without product assets, make small cards from representative outputs and real user portraits.
- Proof feels editorial and human: portrait-format project photographs carry 12px uppercase mono captions, testimonial cards have a dashed inner frame, and a photographic proof panel carries a 44px light serif quotation. Retain this physical proof language with original customer work or a real process photograph.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lemon key | `#fdffa2` | `--color-lemon` | action | Small navigation and closing conversion buttons, never a full section. |
| Mint announcement | `#d1fae5` | `--color-mint` | surface | Small opening announcement fill. |
| Mint edge | `#a7f3d0` | `--color-mint-edge` | border | Fine outline around the mint announcement. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main page canvas, raised controls and reverse text. |
| Soft paper | `#fcfbf9` | `--color-card` | surface | Capability and testimonial panels. |
| Ivory stage | `#f8f6f3` | `--color-hero` | background, surface | Opening stage, small icon backings and secondary-action hover. |
| Paper edge | `#eeece6` | `--color-rule` | border, background | Hairlines, dashed frames and the lower end of the footer wash. |
| Warm gray | `#7b736c` | `--color-muted` | text | Supporting copy, metadata and footer links. |
| Charcoal key | `#2b2926` | `--color-action` | action, surface | Default primary button fill and border. |
| Control ink | `#1a1a1a` | `--color-control-ink` | text | Text on white secondary buttons. |
| Warm ink | `#1a1916` | `--color-ink` | text | Main headlines, labels and navigation. |
| Dark key edge | `#18181b` | `--color-action-edge` | border | Fine outer ring on charcoal buttons. |
| Black action text | `#000000` | `--color-black` | text | Text on lemon trial actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form capability pages | Interview charcoal | `#262222` | `--color-proof-dark` | surface | Isolated split interview panel. |
| customer-story collections | Postcard blue | `#93c5fd` | `--color-stamp-blue` | text, border, accent | Distressed episode markings over editorial imagery. |
| customer-story collections | Postcard rose | `#fda4af` | `--color-stamp-rose` | text, border, accent | Alternate episode markings. |
| customer-story collections | Postcard peach | `#fed7aa` | `--color-stamp-peach` | text, border, accent | Alternate episode markings. |

## Typography

- **Rhymes Display** — Promise headlines, chapter statements, photo titles and closing invitations. High-contrast editorial serif with fine strokes, compact proportions and a light, literary presence. If unavailable, use **Bodoni Moda**. Use the lightest available cut and tune line breaks to retain the narrow two-line silhouette. Font stack: "Rhymes Display", "Bodoni Moda", Georgia, serif.
- **Inter** — Functional headings, body copy, navigation and actions. Neutral compact sans serif, primarily regular with medium headings. Font stack: "Inter", system-ui, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.
- **Roboto Mono** — Eyebrows, locations, customer captions and footer category labels. Small uppercase monospaced annotations, usually regular rather than heavy. Font stack: "Roboto Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Rhymes Display | 300 | 60px | 64px | -0.025em | fixed | Default centered opening promise and closing invitation. |
| chapter | Rhymes Display | 300 | 44px | 50px | -0.0045em | fixed | Centered chapter statements and large photographic quotations. |
| photo-title | Rhymes Display | 300 | 36px | 34px | -0.0056em | fixed | Reverse titles on stacked editorial photo cards. |
| feature-heading | Inter | 500 | 24px | 1.25 | normal | fixed | Left-aligned explanation beside a square demonstration. |
| card-heading | Inter | 500 | 20px | 1.4 | normal | fixed | Main overview tile titles and editorial section leads. |
| body | Inter | 400 | 16px | 1.5 | normal | fixed | Supporting paragraphs; muted by default. |
| small | Inter | 400 | 14px | 20px | normal | fixed | Navigation and compact testimonial copy. |
| button | Inter | 400 | 12px | 1.4 | normal | fixed | Compact primary and secondary actions. |
| annotation | Roboto Mono | 400 | 12px | 20px | normal, uppercase | fixed | Eyebrows, footer category headings and locations. |
| photo-caption | Roboto Mono | 500 | 12px | 1 | normal, uppercase | fixed | Customer name beneath portrait project photography. |
| footer-link | Inter | 400 | 12px | 16px | normal | fixed | Compact footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| audience-specific campaign landings | immersive-display | Rhymes Display | 300 | 80px | 84px | -0.0187em | fixed | Two-line white headline centered over full-screen workplace film. |
| customer-story collections | story-index | Rhymes Display | 300 | 80px | 73px | -0.02em | size clamp(40px, 5.55vw, 80px) | Oversized centered names with small peripheral metadata. |
| customer-story collections | episode-stamp | Roboto Mono | 400 | 25.2px | 1.1 | normal, uppercase | fixed | Names and locations inside distressed film-card markings. |
| long-form capability pages | detail-heading | Inter | 500 | 16px | 1.25 | normal | fixed | Compact benefit titles in square cards. |
| capability directories and help sections | utility-heading | Inter | 500 | 16px | 1.5 | normal | fixed | Icon-directory titles and help-row labels. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the serif light; visual emphasis comes from scale and line breaks, not bold weight. Sans-serif explanation headings remain medium.
- Opening promises usually balance into two lines; functional headings are smaller and left aligned. Mono annotations are untracked capitals, not widely spaced luxury labels.
- Use the default 60px display for normal landings; the 80px immersive variant belongs to photographic audience campaigns, not every section.

## Layout

**Density:** Airy at section level, compact within controls and cards; large pauses surround small functional text.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Button vertical padding and tight metadata stacks. |
| 8px | Navigation link padding and footer link-stack gaps. |
| 12px | Opening text-stack and paired-action gaps; testimonial outer inset. |
| 20px | Card text inset, testimonial inner padding and feature action separation. |
| 24px | Container side padding and capability-grid gutters. |
| 32px | Editorial section and footer vertical padding. |
| 60px | Recurring demonstration-section vertical padding. |
| 80px | Space between equal demonstration columns. |
| 96px | Room around support/help sections. |
| 160px | Default closing invitation top and bottom padding. |

### Containers and grids

- **site-container**: max width 1200px · side padding 24px. Centered desktop container; 1152px usable content width at 1440px.
- **centered-promise**: max width 720px. Centered serif promise and chapter copy; support generally narrows to 450px.
- **demonstration-pair**: 2 columns · gap 80px. Equal 536px media and text columns, with text vertically centered and paragraph width up to 440px.
- **capability-grid**: 3 columns · gap 24px. 368px square cards across the usable content width.
- **testimonial-grid**: 3 columns · gap 20px. Three approximately 371px proof cards, matched in height.
- **footer-grid**: 7 columns · gap 24px. Brand spans the first three tracks; four narrow link groups occupy the remaining tracks.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 6px |
|  | demonstration-and-capability-panels | 8px |
|  | editorial-media-and-nav | 10px |
|  | testimonial-outer-and-directory | 12px |
|  | avatars | 50% |
| customer-story collections | film-cards | 17.7px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| fine-panel-edge | `0px 0px 0px 1px rgba(0,0,0,0.08), 0px 1px 2px 0px rgba(0,0,0,0.12)` | Capability tiles and square demonstrations. |
| raised-paper | `0px 2px 8px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.08)` | Testimonial outer cards and stacked editorial media. |

### Surfaces

#### White canvas · level 0

**Use:** Main reading surface.

**CSS:** `background: #ffffff`

#### Ivory stage · level 0

**Use:** Opening product scene.

**CSS:** `background: #f8f6f3`

**Observed:** A warm field behind the headline and floating objects transitions softly into the white body.

**Transfer:** Keep this warm staging separate from the white explanation sections.

#### Paper panel · level 1

**Use:** Capability tiles and framed demonstrations.

**CSS:** `background: #fcfbf9; border-radius: 8px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 1px 2px 0px rgba(0,0,0,0.12)`

#### Glass navigation · level 3

**Use:** Compact persistent navigation.

**CSS:** `background: rgba(255,255,255,0.7); border-radius: 10px; backdrop-filter: blur(20px); box-shadow: 0px 0px 0px 1px rgba(43,41,38,0.08), 0px 1px 2px -1px rgba(0,0,0,0.08), 0px 2px 8px 0px rgba(0,0,0,0.1)`

#### Footer paper wash · level 0

**Use:** Default footer backing.

**CSS:** `background: linear-gradient(#ffffff 0%, #eeece6 83.89%)`

**Observed:** Fine grain softens the low-contrast downward wash. Other page types use a plain white footer.

**Transfer:** Keep the wash nearly invisible at its top and gently warmer at the base.

#### Interview panel · level 1

**Only for:** long-form capability pages

**Use:** An occasional dense proof interruption.

**CSS:** `background: #262222; color: #ffffff; border-radius: 10px; padding: 20px`

**Observed:** Quote and identity at left, square interview still at right.

**Transfer:** Use one real story rather than making a whole page dark.

## Components

### Navigation

**Use:** Persistent orientation and compact trial action.

**CSS:** `background: rgba(255,255,255,0.7); border-radius: 10px; padding: 8px; height: 46px; width: 504px; backdrop-filter: blur(20px); box-shadow: 0px 0px 0px 1px rgba(43,41,38,0.08), 0px 1px 2px -1px rgba(0,0,0,0.08), 0px 2px 8px 0px rgba(0,0,0,0.1)`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** The initial header distributes a wordmark left, navigation center and login/trial right within a 72px header. Scrolling gathers these into a centered floating bar with a compact symbol. Trial key is lemon, 28px high; tabs have 8px horizontal padding.

**States:** Declared: hover on tabs uses #f8f6f3 with 6px corners and no underline.

### Primary button

**Use:** Default conversion action in product explanations.

**CSS:** `background: #2b2926; color: #ffffff; border: 1px solid #2b2926; border-radius: 6px; padding: 6px 8px; height: 31px; box-shadow: inset 0px 0.8px 0px 0px rgba(255,255,255,0.2), 0px 1px 2px 0px rgba(0,0,0,0.4), 0px 0px 0px 1px #18181b`

**Text style:** `button` — Inter 400 · 12px/1.4

**Observed:** Compact text-only key, often paired with a white discovery action.

**States:** Declared: hover and active use white text, rgba(26,26,26,0.6) fill and transparent border; focus-visible adds a 4px rgba(60,60,60,0.5) ring with outline 0px.

### Secondary button

**Use:** Demo or deeper feature discovery.

**CSS:** `background: #ffffff; color: #1a1a1a; border: 1px solid #ffffff; border-radius: 6px; padding: 6px 8px; height: 31px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.12), 0px 0px 0px 1px rgba(0,0,0,0.08)`

**Text style:** `button` — Inter 400 · 12px/1.4

**Observed:** Matches the primary key’s proportions; width follows the label.

**States:** Declared: hover and active use black text, #f8f6f3 fill and rgba(0,0,0,0.08) border; focus-visible adds a 4px rgba(221,221,221,0.5) ring with outline 0px.

### Trial button

**Use:** Final invitation and highlighted conversion.

**CSS:** `background: #fdffa2; color: #000000; border: 1px solid #fdffa2; border-radius: 6px; padding: 6px 8px; height: 31px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.2), 0px 0px 0px 1px rgba(229,225,146,0.8)`

**Text style:** `button` — Inter 400 · 12px/1.4

**Observed:** Lemon emphasis is reserved for the small key rather than the surrounding section.

**States:** Declared: hover uses #ccca88 fill and border; focus-visible uses the same fill plus a 4px rgba(215,217,138,0.5) ring; active uses #9d9c6b fill and border.

### Capability tile

**Use:** Scannable overview of a product benefit.

**CSS:** `background: #fcfbf9; border-radius: 8px; position: relative; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 1px 2px 0px rgba(0,0,0,0.12)`

**Text style:** `card-heading` — Inter 500 · 20px/1.4

**Observed:** Square tile with a title and short support at top in a 20px inset; enlarged UI fragment or object collage fills and clips at the lower edge. Detailed capability collections reduce titles to the detail-heading recipe.

**Transfer:** Illustrate one operation per tile, not an entire dashboard.

### Testimonial card

**Use:** Compact human proof in a three-column row.

**CSS:** `background: #fcfbf9; border-radius: 12px; padding: 12px; box-shadow: 0px 2px 8px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.08)`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Inner 10px-radius frame has a 1px dashed paper-edge border and 20px padding. Logo/name precedes the quote; a tiny editorial link follows; portrait and uppercase mono attribution anchor the bottom.

**Transfer:** Retain the double frame and clear attribution even when quotes vary in length.

### Project photo card

**Use:** Customer-work carousel.

**CSS:** `border: 1px solid #eeece6; border-radius: 8px; overflow: hidden; position: relative; aspect-ratio: 336 / 416`

**Text style:** `photo-caption` — Roboto Mono 500 · 12px/1 · uppercase

**Observed:** Photo runs to the inside edge. A separate metadata row sits 12px below, with a small square identity mark, two mono lines and a tiny category tag aligned opposite. Carousel shows three full portraits and part of the next; 36px square previous/next keys sit above at right.

**Transfer:** Use a real output or working environment with strong material detail; keep metadata outside the image.

### Editorial photo stack

**Use:** Press, community or external validation.

**CSS:** `border-radius: 10px; overflow: hidden; position: relative`

**Text style:** `photo-title` — Rhymes Display 300 · 36px/34px · tracking -0.0056em

**Observed:** One 802px by 495px front photo overlaps two progressively smaller landscape cards to the right. White serif title and glass action sit at top left; uppercase mono event/source and date sit at bottom left, with 16px inset.

**Transfer:** Keep the stepped depth and editorial hierarchy with original external proof.

### Glass media action

**Use:** Actions placed on editorial photography.

**CSS:** `background: rgba(255,255,255,0.2); color: #ffffff; border: 1px solid transparent; border-radius: 6px; padding: 6px 8px; backdrop-filter: blur(10px)`

**Text style:** `button` — Inter 400 · 12px/1.4

**Observed:** A small translucent key beneath the photo title; does not become a large play overlay.

**States:** Declared: hover and active use #ffffff fill and #1a1a1a text; focus-visible adds a 4px rgba(255,255,255,0.5) ring.

### Footer

**Use:** Compact site directory after the spacious close.

**CSS:** `background: linear-gradient(#ffffff 0%, #eeece6 83.89%); color: #7b736c`

**Text style:** `footer-link` — Inter 400 · 12px/16px

**Observed:** Brand mark at left, four narrow link columns to the right. Uppercase mono category labels precede 8px-gap link stacks. A 49px bottom strip has a dashed top rule, copyright at left and tiny raised social keys at right. Plain white is the secondary page-type variant.

**States:** Declared: hover on text links underlines; social keys use #f8f6f3 fill.

### Help row

**Only for:** capability and support sections

**Use:** Offer next steps without a dense accordion.

**CSS:** `border: 1px solid #eeece6; border-radius: 12px; padding: 20px 24px; display: flex; align-items: center; justify-content: space-between; gap: 16px`

**Text style:** `utility-heading` — Inter 500 · 16px/1.5

**Observed:** Title and one-line muted description stack at left; small right chevron at far edge. Three rows sit at 8px gaps opposite a short introductory heading.

**States:** Declared: hover uses #fcfbf9 background.

## Imagery and graphics

### Floating studio objects

**Use:** Signature animation layer around opening and chapter statements.

**Observed:** Small white rounded tiles bearing furniture, swatches, documents and tiny state labels float at differing angles; circular portrait cutouts mingle with them. Shadows make these look like loose objects above paper. Colors are localized and the central text remains unobscured.

**Transfer:** Use recognizable artifacts of the new workflow: output thumbnails, files, material samples and real participants. Minimum version is four to six cutout cards and two portraits, not unrelated stock 3D shapes.

**Build:** Create absolutely positioned 40px–88px white cards around the outside of the headline field. Use 6px–12px corners, a 1px rgba(26,25,22,0.08) edge and a soft downward rgba(0,0,0,0.12) shadow. Rotate individual cards slightly in both directions; insert cropped object images and occasional tiny status labels. Place circular portraits in thin white rims. Keep the center 720px text zone clear.

### Halftone demonstration backing

**Use:** Signature square product demonstration material.

**Observed:** Warm gray, grainy halftone photographs resemble soft folded fabric or rounded stones. Large white interface pieces overlap and crop beyond the square, leaving texture visible along the top and one side. These media blocks are visually heavier than the adjacent small text.

**Transfer:** Use the new product’s own interface fragments over an equally tactile monochrome backing. If no interface exists, use a believable output card with two or three pieces of metadata.

**Build:** Fill a 536px square with a low-contrast grayscale photograph of folded cloth or smooth forms, tint toward warm gray, then overlay an SVG dot pattern with small regularly spaced dots at low opacity. Clip to 8px corners. Add a white panel inset roughly 60px from one edge and offset downward; let it extend beyond the opposite edges. Retain the paper edge shadow.

### Warm opening atmosphere

**Use:** Unify the hero and dissolve the product stage into the body.

**Observed:** Ivory behind a centered text stack, small floating objects and a wide interface panel; the bottom of the interface disappears through a soft white veil.

**Transfer:** Keep the glow neutral rather than turning it into colored neon.

**Build:** On #f8f6f3, place a centered 1008px-wide radial ellipse using rgba(245,243,239,0.9) at 0%, rgba(245,243,239,0.6) at 40%, and transparent at 70%. Overlay a white 200px-high lower veil with 40px blur. Layer the interface behind the lower veil and text above the atmosphere.

### Natural work and output photography

**Use:** Human proof panels, customer galleries and demonstration alternatives.

**Observed:** Sunlit interiors, rich wood, stone, upholstery and lived-in workspaces; natural greens and warm browns, not high-saturation brand washes. Portrait project images are tightly framed; interview footage uses close human gestures or a seated speaker. A wide photographic quote panel combines white serif type with the real environment.

**Transfer:** Show the equivalent real work, materials and people of the new product. Preserve warm natural lighting and tangible detail; use one strong environment photograph if finished customer work is unavailable.

### Founder portraits

**Only for:** company-story pages

**Use:** Team introduction and origin story.

**Observed:** A broad group portrait and three tall individual portraits share a warm gray studio wall, black clothing and soft even light. Names and mono role captions sit below, not over faces.

**Transfer:** Photograph the actual team in a consistent neutral setting rather than assembling unrelated headshots.

### Postal film collage

**Only for:** customer-story collections

**Use:** Editorial collection opening.

**Observed:** Warm ivory canvas, an oversized typographic masthead, hand-lettered uppercase subtitle, postal seals, cancellation waves and a torn blue note. Three landscape film cards float across the width, the center enlarged; distressed pastel episode/date stamps sit over real photography. Below, large serif names form a centered index with small occupation/location annotations.

**Transfer:** Make a distinctive editorial collection for original stories, using a postal or field-notebook vocabulary rather than the normal product-stage hero.

**Build:** Use three rounded photo/video cards around 497px by 379px, enlarging the central card to roughly 643px by 491px. Overlay a thin rectangular blue, rose or peach stamp with uppercase mono name/location and handwritten date strokes. Distress the stamp using an SVG turbulence/displacement filter. Add circular double-ring seals and four wavy cancellation lines; a small torn-paper polygon can hold a simple line drawing. Keep this collage confined to the editorial collection.

### Icons

**Observed:** Compact mostly monochrome SVG marks: 16px for actions/navigation, 18px for carousel arrows and 24px for directory cards. Directory marks sit in 48px warm-neutral rounded squares. Small media and circular portraits supply the color, not the control icons.

**Transfer:** Use simple filled or restrained outline utility symbols at the same scale; preserve the warm gray/ink coloring and small backings rather than adopting a colorful illustration icon set.

## Section recipes

How recurring sections are built.

### First screen: Ivory product stage

**Observed:** A 72px distributed header sits over a 900px ivory scene. Centered below it is a small mint announcement, then a balanced two-line 60px serif promise within 720px, a 450px muted support line and paired Primary button/Secondary button at 12px gaps. The copy cluster occupies the upper middle, leaving open side fields for Floating studio objects. A 1008px-wide interface begins around the lower half of the screen and extends beneath the fold; a neutral radial atmosphere sits behind it and a blurred white veil covers its base. Within the first 900px, the entire headline, support and actions are visible along with the upper dashboard and its imagery; further interface detail falls below.

**Transfer:** Use a wide, believable working view of the new product, populated with its own output. Without a dashboard, construct a large output board from real content and a few relevant floating artifacts. Company stories open with the same centered 60px promise and a broad team photograph below; audience campaigns use the immersive photographic variant; story collections use the scoped postal collage.

**Avoid:** Do not turn this into a side-by-side hero, a giant colored gradient, or a text-only opening with a tiny decorative app window.

**Text style:** `display` — Rhymes Display 300 · 60px/64px · tracking -0.025em

### Centered chapter introduction

**Observed:** A centered 44px serif statement within 720px, often with a 12px uppercase mono eyebrow, a 16px muted support paragraph and paired compact actions. Floating studio objects orbit the side margins. Typical breathing room is 60px above and below.

**Transfer:** Introduce an outcome or capability family, not a generic feature label; adapt the number of chapter breaks to the story.

**Text style:** `chapter` — Rhymes Display 300 · 44px/50px · tracking -0.0045em

### Alternating square demonstration

**Observed:** Demonstration pair within the site container, 60px vertical padding, 536px square media opposite a vertically centered text column. Feature-heading precedes body by 4px; actions sit 20px below. Adjacent sections alternate media side. Use Halftone demonstration backing or a natural square workplace scene.

**Transfer:** Explain a single operation or outcome next to one legible demonstration.

**Text style:** `feature-heading` — Inter 500 · 24px/1.25

### Benefit tile field

**Observed:** Capability tile grid has 24px gutters, square media-led panels and short top-aligned copy. Default overview uses card-heading; a deep capability chapter uses detail-heading. A payment-focused variant combines two 564px squares with a 760px-wide tile and one small square beneath.

**Transfer:** Use a small grid for scanability; reserve asymmetric spans for a genuinely richer capability rather than varying every tile.

### Photographic proof pause

**Observed:** A wide rounded photograph interrupts the white narrative with a centered 44px white serif quotation and a small identity mark near its base. On long capability pages, an alternative Interview panel places a sans-serif quote beside a square speaker still.

**Transfer:** Give real user language room to act as the headline, with a photograph of the actual work or people rather than a decorative abstract background.

### Editorial gallery and press

**Observed:** A modest 20px sans-serif section lead and 16px support introduce either the Project photo card carousel or Editorial photo stack. Actions sit above the gallery; metadata remains small and mono. The imagery does the persuasive work.

**Transfer:** Use customer results or external validation with the same framing, not oversized marketing claims.

### Support and testimonial proof

**Observed:** A centered serif support promise with floating portraits leads into a Testimonial card row. On capability pages, Help row groups instead sit opposite a short sans-serif introduction, with 96px section padding.

**Transfer:** Use genuine service reassurance, specific quoted experience and clear next steps instead of an invented statistic strip.

### Spacious invitation and directory

**Observed:** A centered 60px serif invitation stands almost alone, with 160px top/bottom space and a small Trial button plus optional Secondary button. The Footer follows immediately: broad brand space, narrow directory columns, dashed bottom rule and tiny social keys. Company and audience variants place the closing copy on a softly warm atmospheric band; story collections finish with a customer-work gallery and white footer rather than an extra trial block.

**Transfer:** Close ordinary product landings with a short invitation and a single clear action; keep the directory visually subordinate.

**Text style:** `display` — Rhymes Display 300 · 60px/64px · tracking -0.025em

## Page flow

**Storyline:** Promise → visible working product → capability outcomes → human and editorial proof → reassurance → spacious invitation and compact directory.

### General product landing

1. **Promise** — Centered serif promise on an ivory object-filled product stage.
2. **Product overview** — Small logo strip, chapter statement and six square capability tiles.
3. **Social proof** — Wide photographic quotation.
4. **Capability explanation** — Alternating square demonstrations with compact sans-serif copy.
5. **Human proof** — Portrait customer-work carousel, support promise, dashed testimonials and stepped press photographs.
6. **Closing call** — Isolated serif invitation, lemon key and warm washed directory footer.

**Transfer:** Use the stage and tactile proof language as the default; choose only the capability chapters necessary for the new product.

### Company and origin story

1. **Positioning** — Centered serif statement and narrow support on white.
2. **Origin** — Wide team portrait followed by a plain three-paragraph narrative.
3. **Credibility** — Three aligned founder portraits, partner marks and stepped editorial proof.
4. **Closing call** — Warm atmospheric invitation with support line and one lemon action, then white directory.

**Transfer:** Replace product demonstrations with the actual people and origin while retaining the typographic hierarchy and editorial proof.

### Audience-specific landing

1. **Audience promise** — Full-viewport workplace film with centered white 80px serif statement and compact actions.
2. **Outcome explanation** — Centered serif benefit then three alternating square workflow demonstrations.
3. **Social proof** — Three dashed-frame testimonial cards.
4. **Consolidation** — Centered problem statement, three visual benefit panels and a nine-item icon directory.
5. **Closing call** — Warm atmospheric serif invitation, paired actions and white directory footer.

**Transfer:** Lead with a real environment of the target audience and tailor outcomes to their constraints; do not increase text density.

### Customer-story collection

1. **Editorial identity** — Masthead, hand-lettered subtitle, postal ephemera and floating film cards on ivory.
2. **Story navigation** — Oversized serif customer names with small mono location and profession annotations.
3. **Customer proof** — Portrait project gallery with compact captions.
4. **Directory** — White footer directly after the gallery; no separate trial invitation.

**Transfer:** Use the scoped editorial collage and index for a collection of original stories, not as a default SaaS opening.

### Deep capability overview

1. **Promise and demonstration** — Ivory hero with centered serif title, floating fragments and wide dashboard.
2. **Capability chapters** — Repeated centered serif chapter introduction, square demonstration and three benefit tiles.
3. **Social proof** — Occasional charcoal interview, dashed testimonial row and wide photographic quotation break the repeated chapters.
4. **Capability expansion** — Asymmetric benefit tiles give a complex transaction workflow extra space.
5. **Objection handling** — Short help introduction opposite three bordered next-step rows.
6. **Closing call** — Centered serif trial invitation and lemon action, then white directory.

**Transfer:** Let each chapter explain one substantial system; use human proof to interrupt repetition and finish with practical help.

## Writing

Direct, informed and design-literate, with warmth rooted in everyday work rather than exuberance. Claims connect attractive software to reduced admin, fewer mistakes and more time for the reader’s real craft.

**Do not copy:** Do not reuse Programa names, logos, customer identities, source artwork, quotations, trial duration, customer counts or performance claims. Write original content and use substantiated proof for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the team when discussing help and intent. Product names appear naturally inside clear verbs and nouns.
- **Rhythm:** Short outcome-led headlines alternate with one or two plain explanatory sentences. Use compact parallel phrases and occasional conversational fragments; longer audience-specific headings may wrap into three lines.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An appealing product/category promise that names the intended audience. | 5–10 words | “Beautiful software for interior designers”<br>“Run a solo studio like a team of ten” |
| Chapter statement | A clear practical outcome, often removing work or friction. | 4–12 words | “More time to design”<br>“Every hour logged, every hour billed.” |
| Feature heading | Compact parallel noun-and-result phrasing or direct contrast with the old method. | 2–9 words | “Specification, streamlined”<br>“Spreadsheets weren’t built for interior design” |
| Supporting line | Describe a concrete task and consequence rather than an abstract promise. | 10–30 words | “One link. Your client sees everything, live.”<br>“Schedules stay live and shareable. No more “final_v7.pdf”.” |
| Action | A short verb-led next step; discovery actions name their destination. | 2–6 words | “Get started”<br>“Watch our demo”<br>“View help guides” |
| Support reassurance | State why the people helping understand the reader’s work. | 1–2 sentences | “Our team isn’t outsourced. It’s built with people who’ve worked in design studios and understand your workflow.” |

**Words and phrasing to use:** built for; your studio; one link; live; connected; in one place; less admin; more time; get started; see how

**Avoid:** revolutionary; disruptive; 10x everything; game-changing platform as narrator language; unlock limitless possibilities; enterprise jargon

**Rules:**

- Name the specific old friction before explaining the new operation.
- Use tangible nouns: files, approvals, products, time, people; adapt them to the new category.
- Let customer quotes sound spoken, but keep narrator copy composed and concise.
- Pair aesthetic benefit with operational value; neither decoration nor efficiency alone carries the whole story.

## Do's and Don'ts

### Do

- Keep opening and closing serif type at 60px/64px, weight 300, with -0.025em tracking.
- Use 24px gutters for three-column capability grids and 80px separation in demonstration pairs.
- Give square demonstrations 60px vertical breathing room and vertically center the adjacent copy.
- Keep actions compact at 31px high with 6px corners and subtle physical edge shadows.
- Retain tiny 12px uppercase mono metadata beneath image-led proof.
- Use nested 12px/10px frames and a dashed paper-edge rule for testimonials.
- Carry the floating artifact device into the opening and at least one relevant chapter break.
- Keep the footer’s brand space broader than any single 145px link column.

### Don't

- Do not replace the light serif with a bold geometric headline; it removes the editorial contrast.
- Do not inflate the default 12px button text into oversized 48px-high capsule CTAs.
- Do not spread lemon yellow across backgrounds or every card; it is a small conversion signal.
- Do not use pure cool gray for all neutrals; support copy is warm #7b736c and edges are #eeece6.
- Do not turn every explanation heading into a 44px serif: the media-pair heading is 24px Inter 500.
- Do not put project gallery captions over the photography; the mono identity row belongs below.
- Do not substitute glossy neon abstract renders for tactile halftone backings and work artifacts.
- Do not make the footer a dark, oversized brand billboard; keep it light, compact and directory-led.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares transform and opacity transitions of 0.3s; the broad header becomes a centered compact glass bar during scrolling.
- Buttons declare background-color and color transitions of 0.2s. Capability and testimonial shadows declare 0.3s cubic-bezier(.4,0,.2,1).
- Floating artifacts declare 6s ease-in-out infinite motion; opening objects also use distinct 7s, 8s and 9s ease-in-out bobbing cycles. A horizontal strip declares 20s linear infinite motion.
- The immersive audience opening holds a workplace scene during scroll before releasing into the body.

**Transfer:**

- Preserve slow independent artifact drift and the broad-to-compact header transformation; keep text and actions stable.
- Use the shadow transition to make paper panels feel lightly raised, not spring-loaded.

**Unknown:**

- Exact float trajectories, complete scroll mapping and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop uses a 1200px container, 720px centered text field and 536px paired media. Declared layout switches include 768px, 992px and 1040px.
- Capability tiles declare one column before the desktop multi-column layout; testimonial and directory grids include intermediate two-column variants. Desktop card media uses square framing while a narrower variant uses a 3:2 aspect ratio.

**Transfer:**

- On narrow layouts, stack demonstration copy and media while retaining the light serif/sans distinction; shrink or move floating artifacts to outer edges so they never cover the message.
- Carry the story-collection index’s clamp(40px, 5.55vw, 80px) rule; do not apply that collection-only size to every headline.

**Unknown:**

- Exact mobile headline sizes, menu behavior, scene composition and footer treatment are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
