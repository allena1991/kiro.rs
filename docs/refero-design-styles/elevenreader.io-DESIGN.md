# ElevenReader — paper objects in motion

## Overview

An off-white, consumer-friendly style that makes digital tools feel like tangible things to browse, hold and enjoy. Light grotesk headlines and practical sans-serif text surround floating editorial objects, warm lifestyle film and softly blurred interface stages. Most of the page is pale and spacious; coral, violet and rich artwork arrive inside carefully bounded demonstrations rather than in the navigation or typography.

### Essentials

- The product becomes a floating editorial sculpture: a compact overlapping fan of portrait objects occupies roughly 460px by 380px above the centered promise. Recreate this dimensional object arrangement even when the product has no physical packaging, using designed output cards instead.
- Headlines feel conversational rather than monumental: Waldenburg 60px/1, weight 400, -0.03em tracking for the opening, then 36px/42px, weight 375, -0.01em for section statements. Keep the opening to two lines and about 508px wide.
- Actions look like small tactile capsules: black primary and white secondary pills, 52px high in the opening and 44px in content, with 16px Inter text. The white version gets a delicate layered edge rather than a dark outline.
- Color belongs to objects, not the page: #fdfcfc canvas and #f5f3f1 panels dominate; coral #f58971 and violet #7767d8 are bounded by 32px rounded demonstration cards. Keep headlines black and use green only for savings or equivalent positive commercial annotations.
- A specimen-like heading device unifies the story: a 36px outlined icon badge, a muted 16px medium label, then a 36px light headline. Use 56px between the heading group and major media, with 176px breathing room between many chapters.
- Proof and access have their own visual choreography: an open left-hand ratings column faces a softly edge-faded review stream, while four 220px square miniature platform scenes sit above matching 44px pills. Carry both the proof composition and the miniature access gallery into new pages, using appropriate outcomes and delivery channels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Narrative coral | `#f58971` | `--color-coral` | surface | A vivid prompt-led demonstration card, never the page canvas. |
| Ambient violet | `#7767d8` | `--color-violet` | surface | Base color behind atmospheric interface demonstrations. |
| Warm ambient base | `#a0713a` | `--color-ochre` | surface | Base beneath soft brown and cream photographic interface backdrops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Headlines, primary actions and monochrome icons. |
| Paragraph gray | `#4c4c4c` | `--color-body-muted` | text | Visible result of black at 70% on the warm paper canvas; expanded explanatory text. |
| Secondary gray | `#656565` | `--color-muted` | text | Visible result of black at 60% on the warm paper canvas; supporting copy and section labels. |
| Warm caption | `#6b665f` | `--color-warm-caption` | text | File-format help text within the upload panel. |
| Directory gray | `#767676` | `--color-label-gray` | text | Small footer group headings. |
| Warm input edge | `#8e8880` | `--color-input-edge` | border | Link input outline. |
| Upload dashed edge | `#d6d3ce` | `--color-upload-edge` | border | Upload target dashed outline. |
| Navigation edge | `#e5e5e5` | `--color-nav-edge` | border | Fixed header bottom border and small outlined controls. |
| Panel hairline | `#eae9e9` | `--color-hairline` | border | Free plan outline, pricing switch and separators. |
| Warm stone | `#f5f3f1` | `--color-stone` | surface, background | Large demonstration panels, reviews, promotion strip and paid plan. |
| Pink paper | `#faf8f8` | `--color-soft-card` | surface | FAQ rows and compact explanatory cards. |
| Upload paper | `#faf9f7` | `--color-upload-paper` | surface | Inner upload target. |
| Warm paper | `#fdfcfc` | `--color-canvas` | background | Default page canvas. |
| Raised white | `#ffffff` | `--color-white` | surface, text | Secondary actions, interface cards, fixed navigation and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| commercial offers | Savings green | `#307d18` | `--color-saving-ink` | text | Text on savings badges. |
| commercial offers | Savings mint | `#e1f5e0` | `--color-saving-wash` | surface | Small savings badges. |

## Typography

- **Waldenburg** — Headlines, FAQ questions and plan typography. An open, lightly weighted contemporary grotesk with compact spacing and rounded conversational shapes. If unavailable, use **DM Sans**. Use variable weights 375–400 and retain tight headline tracking. Font stack: "Waldenburg", "DM Sans", sans-serif.
- **Inter** — Support copy, buttons, captions, review prose and directory links. Highly legible neutral sans-serif, usually regular with restrained medium emphasis. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Waldenburg | 400 | 60px | 1 | -0.03em | Default opening promise, centered and wrapped to two lines. |
| heading | Waldenburg | 375 | 36px | 42px | -0.01em | Main section statements and proof headings. |
| feature-heading | Waldenburg | 375 | 24px | 32px | normal | Headings beneath large paired demonstration panels. |
| question | Waldenburg | 400 | 20px | 1.35 | normal | FAQ disclosure questions. |
| hero-support | Inter | 400 | 18px | 26px | 0.009em | Centered opening support, up to two lines. |
| eyebrow | Inter | 500 | 16px | 24px | 0.01em | Sentence-case label next to the small section icon; use muted color. |
| body | Inter | 400 | 16px | 1.5 | 0.01em | General prose and FAQ answers. |
| action | Inter | 400 | 16px | 1.4 | 0.01em | Primary and secondary action text. |
| review | Inter | 400 | 15px | 22px | 0.01em | First-person customer review prose. |
| caption | Inter | 400 | 14px | 20px | normal | Small supporting labels and upload format help. |
| directory-link | Inter | 500 | 14px | 1.4 | normal | Footer directory links. |
| directory-label | Inter | 500 | 13px | 1.4 | normal | Footer category headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| focused utility and pricing pages | utility-display | Waldenburg | 375 | 60px | 1 | -0.03em | Benefit-first opening for focused utility and pricing pages. |
| pricing sections | price | Waldenburg | 375 | 36px | 1 | -0.01em | Plan price numerals; small billing suffix sits on the baseline. |
| pricing sections | plan-title | Waldenburg | 375 | 22px | 28px | normal | Plan names. |
| pricing sections | plan-feature | Waldenburg | 375 | 18px | 1.3 | normal | Plan checklist items. |
| focused utility and pricing pages | chapter-body | Waldenburg | 375 | 18px | 1.4 | normal | Longer prose alongside staged interface scenes. |
| focused utility pages | card-title | Inter | 500 | 18px | 1.6 | normal | Compact explanatory card headings. |
| focused utility pages | card-body | Inter | 400 | 16px | 1.4 | normal | Compact explanatory card descriptions. |
| commercial offers | offer-label | Inter | 500 | 14px | 20px | normal | Savings annotations. |

**Notes:**

- Headline size increases without increasing weight: the opening is 400 and most smaller display statements are 375.
- Tracking tightens from -0.01em on section statements to -0.03em on opening display. Text and action recipes retain their subtle positive tracking.
- The semantic heading level is not the visual hierarchy: small category labels can precede much larger benefit statements.
- Keep supporting prose visibly lighter than the headline, without fading the primary action.

## Layout

**Density:** Airy between chapters, compact inside cards and controls; substantial media fields alternate with narrow text groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small card title-to-description gaps, FAQ row gaps and directory link list gaps. |
| 12px | Opening action gap and small horizontal control groups. |
| 16px | Paired panel gutter, carousel gutter and label-to-headline group spacing. |
| 20px | Three-column card grid gutters and supporting text gaps. |
| 24px | Compact card padding and plan checklist row gaps. |
| 27px | Opening headline, support and action stack gaps at desktop. |
| 28px | Large demo panel to its external caption group. |
| 32px | Upload target padding and switch-to-plan separation. |
| 56px | Section heading group to major media and desktop plan padding. |
| 64px | Desktop container inner side padding and split chapter gutter. |
| 96px | Early proof-to-demonstration separation. |
| 120px | Footer top and bottom padding. |
| 176px | Common separation between full marketing chapters. |
| 200px | Pricing-to-FAQ breathing room. |

### Containers and grids

- **main-container**: max width 1304px · side padding 64px. Centered outer container, including its side padding; at 1440px the main inner content runs approximately from 132px to 1308px.
- **paired-panels**: 2 columns · gap 16px. Two equally sized demonstration panels with captions beneath.
- **chapter-split**: max width 1180px · 2 columns · gap 64px · side padding 16px. Vertically centered explanatory text and a portrait or square interface scene.
- **faq-column**: max width 796px. Left-aligned heading and disclosure list inside a centered narrow column.
- **access-gallery**: max width 928px · 4 columns · gap 16px. Four square scenes with equal-width pill actions below.
- **footer-directory**: 12 columns · gap 20px. Logo occupies the left three-column zone; the remaining space contains three vertical stacks of link categories.
- **feature-grid** (only for focused utility pages): max width 1000px · 3 columns · gap 20px. Compact explanatory cards, usually one or two rows.
- **plan-grid** (only for pricing sections): max width 1188px · 2 columns · gap 20px. Equal-height free and paid plan cards.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| compact-cards | 20px |
| reviews-and-upload | 24px |
| portrait-scenes | 32px |
| large-panels-and-plans | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| tactile-control | `0px 0px 0px 1px rgba(0,0,0,0.06), 0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.04)` | White pill actions and small raised controls; the edge is more important than depth. |

### Surfaces

#### Paper canvas · level 0

**Use:** Entire ordinary marketing page.

**CSS:** `background: #fdfcfc; color: #000000`

#### Stone stage · level 1

**Use:** Large paired demonstrations and paid plan cards.

**CSS:** `background: #f5f3f1; border-radius: 40px; overflow: hidden`

**Observed:** Tonal separation rather than a shadow; internal content can be richly colored while the framing remains pale.

**Transfer:** Use as a large backing plane for a tangible product specimen or interactive tool.

#### Soft explanatory card · level 1

**Use:** FAQ disclosures and compact explanatory content.

**CSS:** `background: #faf8f8; border-radius: 20px`

**Observed:** Flat and borderless; text does most of the organizing.

**Transfer:** Keep these visually subordinate to large media stages.

#### Coral specimen · level 1

**Use:** Short prompt or generative demonstration within the horizontal capability gallery.

**CSS:** `background: #f58971; border-radius: 32px; overflow: hidden`

**Observed:** A single saturated panel among pale and atmospheric panels; black prompt text and a small white play control.

**Transfer:** Use a brief input or intended outcome rather than a full paragraph of marketing.

#### Atmospheric interface stage · level 1

**Use:** Backplate for portrait interface specimens.

**CSS:** `background: #7767d8; border-radius: 32px; overflow: hidden`

**Observed:** Soft mottled pale light over violet, or cream over warm brown, with sharply rendered white interface content in front.

**Transfer:** Match the diffuse light and material contrast, not an exact gradient stop pattern.

#### Outline plan · level 1

**Only for:** pricing sections

**Use:** Entry plan paired with a filled paid plan.

**CSS:** `background: #fdfcfc; border: 0.5px solid #eae9e9; border-radius: 40px; padding: 56px`

## Components

### Navigation

**Use:** Persistent access to the product and conversion actions.

**CSS:** `height: 64px; background: #ffffff; border-bottom: 1px solid #e5e5e5; display: flex; align-items: center; justify-content: space-between`

**Text style:** `caption` — Inter 400 · 14px/20px

**Observed:** Opening navigation shows logo left, compact discovery links centrally, sign-in and a black action right. The scrolled version simplifies to the logo and paired white upload and black conversion pills; these are 40px high.

**Transfer:** Keep the persistent state conversion-oriented rather than retaining every discovery link.

### Primary button

**Use:** Main opening conversion and paid-plan action.

**CSS:** `background: #000000; color: #ffffff; border-radius: 9999px; height: 52px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 400 · 16px/1.4 · tracking 0.01em

**Observed:** Placed first in a two-action group. The opening button is content-width; plan buttons span the card interior. Compact navigation variants are 36px or 40px high.

**Transfer:** Use an immediate low-friction verb and retain black as the main conversion color.

### Secondary button

**Use:** Content actions and alternate paths.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; height: 44px; padding: 0px 20px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.04); display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 400 · 16px/1.4 · tracking 0.01em

**Observed:** White elevated capsule; the opening alternate action grows to 52px with 24px horizontal padding. Platform actions can lead with a small icon.

### Upload target

**Use:** Hands-on import demonstration.

**CSS:** `background: #faf9f7; border: 1px dashed #d6d3ce; border-radius: 24px; height: 240px; padding: 32px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 20px`

**Text style:** `caption` — Inter 400 · 14px/20px

**Observed:** Raised white upload icon above a stronger 18px semibold instruction and smaller format help. A thin OR divider separates the drop area from Link input; a voice selection row and play action complete the enclosing Stone stage.

**Transfer:** Replace the file operation with the simplest authentic input step for the new product.

### Link input

**Use:** Alternate input inside the hands-on demonstration.

**CSS:** `background: rgba(255,255,255,0.6); border: 1px solid #8e8880; border-radius: 24px; height: 56px; padding: 8px 24px; box-shadow: none`

**Observed:** Full-width softly translucent input under the upload target. Its outline is noticeably stronger than card hairlines.

### Review card

**Use:** Customer proof stream.

**CSS:** `background: #f5f3f1; border-radius: 24px; padding: 22px 24px 0px; overflow: hidden`

**Text style:** `review` — Inter 400 · 15px/22px · tracking 0.01em

**Observed:** A small star row leads, followed by first-person prose. A thin top rule separates the source strip at the bottom; no portrait is necessary. Cards of varied heights form a vertical stream opposite a stable proof heading.

### FAQ disclosure

**Use:** Late-page objection handling.

**CSS:** `background: #faf8f8; border-radius: 20px; margin-bottom: 8px`

**Text style:** `question` — Waldenburg 400 · 20px/1.35

**Observed:** Native disclosure construction with a 20px 24px padded question row and right-aligned plus sign. Closed rows are 67px high at desktop and 780px wide; answers use Body with 24px side padding and 20px bottom padding.

**Transfer:** Use direct customer questions; expand the answer without introducing a new surface.

### Footer link group

**Use:** Dense but low-pressure navigation at the page ending.

**CSS:** `display: flex; flex-direction: column; gap: 8px; margin-top: 12px`

**Text style:** `directory-link` — Inter 500 · 14px/1.4

**Observed:** A 13px gray category heading precedes black medium links. Category groups are separated by 36px, stacked in three directory columns to the right of the logo.

### Plan card

**Only for:** pricing sections

**Use:** Commercial plan comparison.

**CSS:** `background: #f5f3f1; border-radius: 40px; padding: 56px; display: flex; flex-direction: column`

**Text style:** `plan-feature` — Waldenburg 375 · 18px/1.3

**Observed:** Plan name and savings badge share the top row. Price, billing qualifier, a thin divider, feature checklist and bottom-aligned action follow. The paid plan uses the filled surface and black button; the free plan uses Outline plan and a white button. Desktop cards are 584px wide and 722px high.

**Transfer:** Preserve calm equality of size; emphasize the paid choice tonally rather than with a bright border.

### Savings badge

**Only for:** commercial offers

**Use:** Positive offer annotation.

**CSS:** `background: #e1f5e0; color: #307d18; border-radius: 9999px; padding: 4px 12px; height: 28px; display: inline-flex; align-items: center`

**Text style:** `offer-label` — Inter 500 · 14px/20px

**Observed:** Lives beside the annual billing option and at the upper right of the paid plan; green is confined to this small annotation.

### Explanatory card

**Only for:** focused utility pages

**Use:** Short process steps, supported inputs or capability criteria.

**CSS:** `background: #faf8f8; border-radius: 20px; padding: 24px; display: flex; flex-direction: column; align-items: flex-start; gap: 8px`

**Text style:** `card-body` — Inter 400 · 16px/1.4

**Observed:** Medium 18px title above muted body. Numbered steps add a small muted step label above the title. Repeated in equal-width three-column groups.

## Imagery and graphics

### Airborne object fan

**Use:** Signature opening object and later browse-oriented galleries.

**Observed:** Portrait cover-like objects overlap with visible thin spines, gentle perspective and a few differing yaw angles. The opening centers a compact fan above the headline, with pale chevrons well outside its edges. A later gallery spreads seven objects into a shallow arch, center highest and edges lower.

**Transfer:** Create original output covers, report cards, designs or other product artifacts. The minimum acceptable version is a set of designed portrait cards with real content, thin shaded edges and perspective, not a generic dashboard rectangle.

**Build:** Use a perspective parent around 460px wide and 380px high; layer portrait cards around 200px by 320px, preserve readable faces, and offset them laterally so only a narrow slice of rear cards remains. Apply differing rotateY transforms, narrow darker side faces and restrained contact shading. For the wide arch use 177px by 265px cards with about 26px overlap and stepped vertical offsets.

### Diffuse interface light

**Use:** Signature material inside capability stages.

**Observed:** White mobile interface specimens are cropped by portrait or square frames. Behind them are very soft cream-to-brown photographic blurs or pale lavender light on violet, with fine mottled texture rather than a perfectly smooth neon gradient. The device remains sharply legible.

**Transfer:** Stage one meaningful interface state in front of the light. If there is no mobile interface, use a sharply rendered output document or compact workflow card.

**Build:** Inside a 32px-rounded clipped panel, use the violet or ochre base. Add several broad white and dark translucent ellipses, each about half the panel width, blur them by roughly 60px, and overlap irregularly near the upper corners and lower edge. Overlay low-opacity monochrome SVG noise, then center the crisp white interface with a fine shadow. Keep saturation softer than the flat coral card.

### Prompt specimen

**Use:** A vivid capability moment in the horizontal gallery.

**Observed:** Black conversational prompt text sits inside a coral portrait card with ample empty space; a small glossy orb punctuates the sentence and a white circular play control anchors the lower left. A short caption lives outside the card.

**Transfer:** Use an authentic short input/output example. Retain the coral field and object-like punctuation without mimicking the original sentence.

**Build:** Use Coral specimen at 381px by 508px. Set a short black text block near the vertical center with generous side insets. Insert a small sphere made from layered radial gradients with a white highlight at upper left and a dark lower-right crescent; place a white circular play control at the lower left.

### Lifestyle film

**Use:** Human emotional proof between product demonstrations.

**Observed:** Warm, sunlit cinematic footage of a person using the product in a café, with natural skin tones, environmental depth and wide windows. The main film is 1080px by 608px; the split-chapter variant is 574px by 323px. Rounded framing, subtle translucent controls and a slim seek bar keep it integrated.

**Transfer:** Show an ordinary moment improved by the product, not a studio portrait or abstract stock illustration. A warm, carefully framed still can stand in for motion.

### Miniature access scenes

**Use:** Signature platform-access gallery near the later part of the story.

**Observed:** Four 220px square rounded stone tiles show cropped miniature interface fragments: a reading panel, floating app icons, a platform strip and browser-like search elements. Details fade toward the edges; each tile has a matching action directly beneath it.

**Transfer:** Represent four real access routes or delivery contexts with small partial interface scenes. If fewer platforms exist, use meaningful output or workflow contexts rather than empty tiles.

**Build:** Build each square with 20px corners and a pale stone backing. Compose white interface strips, a small raised app badge and light neutral circles or rounded squares; clip oversize strips at the tile edges. Use one more detailed product-content tile and keep the other scenes diagrammatic and low contrast.

### Laurel proof strip

**Use:** Compact reassurance beneath the opening or demonstration.

**Observed:** Three centered proof items pair black 20px rating or achievement text with small muted captions, flanked by pale laurel branches. The strip is visually small relative to the surrounding whitespace.

**Transfer:** Use verified ratings, a real award and a real adoption signal, with the same small ceremonial treatment.

**Build:** Draw symmetrical laurel sprigs in SVG using a thin curved stem and repeated narrow leaf ellipses. Place a pair around each short text group and use a warm light gray so the marks remain secondary.

### Icons

**Observed:** Small black outline utility icons, generally 16px to 24px, use approximately 1.5px to 1.8px round strokes. Section markers sit in 36px square badges with 10px corners and a 0.5px translucent black outline. Play controls use solid triangles inside white circles; platform symbols retain their familiar small marks.

**Transfer:** Use simple line icons for chapter labels and solid transport controls. Keep decorative icons out of body paragraphs; place them beside labels or actions.

## Section recipes

How recurring sections are built.

### First screen: Floating artifact opening

**Observed:** Paper canvas carries a 49px pale promotional strip and 64px discovery navigation. A centered Airborne object fan dominates the upper middle of the screen without a backing card. Beneath it, Display wraps into two balanced lines within about 508px; Hero-support is about 473px wide and muted. The object-to-headline separation is 36px, then 27px between headline, support and the action row. Primary button precedes the raised white alternate with 12px between them. Within the first 900px the entire object, headline, two-line support and both actions are visible; the small proof strip falls below the fold.

**Transfer:** Use designed artifacts from the new product as the fan, maintaining a stronger object silhouette than text area. Focused utility pages invert the emphasis: a 60px weight-375 benefit headline with a small icon label and support appears first, followed by an edge-faded document fan centered on a working upload panel. Pricing pages open with a benefit promise, billing switch and the top of two plan cards.

**Avoid:** Do not turn this into a split hero, put a dashboard behind the headline, stretch the heading across the full container or add a colored hero band.

**Text style:** `display` — Waldenburg 400 · 60px/1 · tracking -0.03em

### Specimen heading pair

**Observed:** A small muted Eyebrow sits beside an outlined icon badge. The group leads a 36px Heading after 16px of group spacing; centered versions constrain the statement to about 362px while left-aligned versions anchor browse chapters. Major media begins 56px below the group.

**Transfer:** Name the category briefly, then state its human benefit in the larger line.

**Text style:** `heading` — Waldenburg 375 · 36px/42px · tracking -0.01em

### Paired hands-on panels

**Observed:** Two 580px square Stone stages share a 16px gutter. One contains Upload target, Link input and a selection/play row; the other displays a layered object carousel. Captions sit outside the panels after 28px, using Feature-heading and Body; secondary actions can follow the copy.

**Transfer:** Pair the product's simple input with its tangible output; keep explanation outside the visual frame.

**Text style:** `feature-heading` — Waldenburg 375 · 24px/32px

### Cinematic pause

**Observed:** A centered Specimen heading pair leads the wide Lifestyle film with 56px separation. The film occupies most of the inner container and retains rounded corners.

**Transfer:** Use this as an emotional pause after a hands-on explanation rather than another feature list.

### Browsable object gallery

**Observed:** A left-aligned heading group introduces a horizontal series of portrait objects about 223px by 335px with 32px spacing. Short title and creator captions sit beneath each. Another variant centers an overlapping arched object fan above rows of pill filters.

**Transfer:** Present real outputs, templates or examples as collectible objects; let the next object peek beyond the visible edge.

### Capability specimen rail

**Observed:** A left-aligned Heading introduces a horizontal rail of 381px by 508px portrait scenes with 16px gutters and short captions outside. Diffuse interface light, a pale selector and Prompt specimen deliberately vary the material across cards.

**Transfer:** Show distinct interactions, not repeated generic feature icons. Carry the atmospheric stage and one vivid specimen into the new page.

### Alternating utility chapter

**Observed:** A 1180px split layout with 64px gutter vertically centers a text chapter against a 360px by 480px, 420px by 560px or 480px square staged interface. Eyebrow, Heading, Chapter-body and a white action form the text stack; consecutive chapters can swap sides.

**Transfer:** Give each chapter one task and one demonstrable state. Let portrait scenes remain narrower than their half of the grid.

**Text style:** `heading` — Waldenburg 375 · 36px/42px · tracking -0.01em

### Compact explanation grid

**Observed:** Centered heading pair above three columns in a 1000px grid with 20px gaps. Explanatory cards hold either numbered steps or a title and brief description; six capabilities form two rows.

**Transfer:** Use this denser pattern for practical evaluation information rather than the emotional opening.

### Proof stream

**Observed:** A stable left column holds the heading and three compact rating/adoption lines. The right column is a 588px review stream within a 900px-tall area, with 96px canvas-colored fades at top and bottom. Review cards vary in height and keep their source strips.

**Transfer:** Use true customer language and real proof signals. Preserve the contrast between a still summary and a continuous-looking wall of experiences.

### Plan comparison

**Observed:** Centered heading and billing switch precede two equal-height Plan cards in a 1188px grid. The switch is a 292px by 50px outlined capsule with a raised white active option and Savings badge. Both plans keep actions at the bottom despite different feature lengths.

**Transfer:** Use equal geometry and tonal emphasis to make the decision readable.

**Text style:** `price` — Waldenburg 375 · 36px/1 · tracking -0.01em

### Pricing evaluation variants

**Observed:** Four compact press cards use 24px corners and fine borders. A testimonial carousel places a white central card between faded neighbors. The detailed comparison has five columns, a softly raised stone product column with white header, 128px feature rows and thin horizontal rules.

**Transfer:** Reserve these information-dense variants for evaluation-heavy commercial pages. Highlight one choice with a pale column rather than a saturated table.

**Text style:** `plan-feature` — Waldenburg 375 · 18px/1.3

### Access and ending

**Observed:** A centered heading pair leads the four Miniature access scenes with 16px gaps; each square sits over a 44px action, with the browser route black and other routes white. FAQ disclosure rows occupy a separate narrow column. The final Footer link groups remain on Paper canvas, with 120px vertical padding, a small logo on the left and three directory stacks on the right; there is no dark footer band or giant final slogan.

**Transfer:** Give the access gallery a prominent late-story position, not necessarily the last section. Finish with a practical directory and quiet breathing room; the FAQ and access gallery can exchange order according to the page's decision path.

## Page flow

**Storyline:** Tangible promise → hands-on demonstration → emotional and practical capability proof → customer reassurance → commercial choice → objections and access → useful directory.

### Broad product introduction and discovery

1. **promise** — Floating artifacts above a two-line benefit and paired actions.
2. **product demonstration** — Proof strip followed by paired input and output panels.
3. **emotional proof** — Wide lifestyle film.
4. **capability chapters** — Object browsing, arched category fan and mixed-material specimen rail.
5. **social proof** — Static ratings summary facing the review stream.
6. **access** — Four miniature platform scenes and matched actions.
7. **pricing** — Two calm plan cards and billing switch.
8. **objection handling** — Narrow FAQ column.
9. **ending** — Pale directory footer.

**Transfer:** Let a broad landing page move between useful demonstrations and pleasurable object browsing rather than repeating identical feature rows.

### Audience-specific utility landing page

1. **promise** — Small use-case label, large benefit and practical support.
2. **product demonstration** — Working upload panel surrounded by receding document artifacts.
3. **capability chapters** — Alternating sound, mobile and document-reading scenes.
4. **credible support** — Paired personal testimony and research card with a strong source link.
5. **evaluation** — Six compact criteria cards.
6. **social proof** — Ratings and review stream.
7. **pricing** — Shared plan pair.
8. **objection handling** — Audience-specific FAQ and two related-use-case cards.
9. **closing access** — Miniature platform gallery followed by the directory.

**Transfer:** Center an audience's practical friction and use restrained, sourced reassurance. Retain the shared materials and closing devices.

### Commercial evaluation and plan selection

1. **pricing promise** — Benefit headline and support directly above billing controls and plans.
2. **external proof** — Four short press quotation cards.
3. **product demonstration** — Split text and lifestyle film.
4. **social proof** — Centered testimonial carousel.
5. **comparison** — Long neutral table with one raised highlighted product column.
6. **value recap** — Three short benefit cards.
7. **access** — Shared miniature platform gallery.
8. **objection handling** — Billing-focused FAQ.
9. **ending** — Shared pale directory.

**Transfer:** Lead with the decision rather than decorative artifacts, then supply evidence and comparison before resolving billing questions.

### General utility education and conversion

1. **promise** — Task label, benefit headline and practical support.
2. **product demonstration** — Centered upload experience among document artifacts.
3. **reassurance** — Compact laurel proof strip.
4. **process** — Three numbered explanatory cards.
5. **capability chapters** — Alternating interface scene, supported-format grid, arched artifact fan and mobile chapter.
6. **evaluation** — Six capability criteria cards.
7. **social proof** — Shared review stream.
8. **pricing** — Shared plan pair.
9. **objection handling** — Task-specific FAQ.
10. **closing access** — Miniature access scenes and directory footer.

**Transfer:** Explain the task concretely, then alternate concise grids with richer staged demonstrations so a long educational page does not feel dense.

## Writing

Warm, clear and utility-led, with emotional benefits expressed in everyday language. Confidence comes from specific actions and concrete proof, not technological grandstanding.

**Do not copy:** Do not reuse the brand name, logos, book artwork, celebrity identities, proprietary product claims, ratings, install totals, prices, research findings or customer quotations as claims for another product. Source examples illustrate language structure only.

- **Addressing the reader:** Address the reader as you and your; use direct imperatives for actions. Product descriptions explain what happens in ordinary verbs rather than speaking as an abstract company.
- **Rhythm:** Short benefit headlines, often four to nine words, followed by one or two clarifying sentences. Longer utility chapters use familiar situations and a sequence of concrete actions; pricing uses exceptionally short paired sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad action plus an emotional or quality payoff. | 7–10 words | “Listen to anything in voices you’ll love” |
| Section statement | Human experience rather than a technical feature name. | 5–8 words | “This is how listening should feel”<br>“Designed for how you listen” |
| Utility promise | Turn an input into a desirable simple outcome. | 5–8 words | “Turn anything into natural audio” |
| Action | Verb plus immediate outcome; lower friction with free when accurate. | 2–4 words | “Start listening free”<br>“Upload & listen” |
| Commercial reassurance | Two crisp sentences remove commitment anxiety. | 4–6 words | “Start free. Upgrade anytime.” |
| Question | Plain-language practical concern in the customer's words. | 6–10 words | “What content can I import into the app?” |

**Words and phrasing to use:** anything; your way; natural; start free; anytime; pick; press play; take it with you; everywhere

**Avoid:** revolutionary ecosystem; unparalleled synergy; next-generation disruption; unlock your full potential; technical jargon without a concrete task

**Rules:**

- Pair an emotional headline with practical support that names inputs, outputs or contexts.
- Keep actions in sentence case and make them describe the next step.
- Translate quantities into a familiar unit of value when the comparison is accurate.
- Use real situations such as daily routines to explain convenience rather than abstract productivity language.
- For sensitive use cases, distinguish support and convenience from treatment or guaranteed outcomes.

## Do's and Don'ts

### Do

- Keep the main canvas #fdfcfc and most structural panels #f5f3f1.
- Use 60px weight-400 display for the default opening and 36px weight-375 section statements.
- Give major content chapters around 176px separation while keeping card interiors compact.
- Stage sharp interface specimens over diffuse light within 32px rounded frames.
- Place captions outside large demonstration panels, generally 28px below the visual.
- Keep opening actions 52px high and ordinary white content actions 44px high.
- Use the four 220px miniature access scenes as a genuine visual conversion device.
- Preserve the left-summary/right-review-stream proof composition and the pale directory ending.

### Don't

- Do not use violet or coral as the navigation color or default CTA fill; conversion stays black and white.
- Do not make section headings bold or all caps; the 375-weight grotesk is essential.
- Do not give every card the same corner size: distinguish 20px compact content, 24px reviews, 32px scenes and 40px large panels.
- Do not apply deep drop shadows to flat stone panels; reserve fine layered elevation for white controls.
- Do not replace the tactile access gallery with an unillustrated row of store badges.
- Do not make the footer a dark marketing banner; keep it a pale link directory.
- Do not inflate ordinary proof numerals into giant display typography; ratings remain compact beside icons and captions.
- Do not flatten all demonstrations into identical bordered dashboard cards; vary crisp artifacts, atmospheric stages and the coral specimen.

## Motion and responsive

### Motion

**Observed:**

- Horizontal object and capability galleries have previous/next controls; media panels expose playback and seek controls.
- The navigation disclosure icon declares a 300ms transform transition; the review layer declares a 200ms opacity transition.
- The persistent header has a transformed hidden state and a simplified visible scrolled state.

**Transfer:**

- Use gallery movement to reveal additional specimens without changing the section's framing.
- Keep the ratings summary visually stable while the review stream supplies continuity.
- Treat playback controls as small parts of the specimen, not separate oversized calls to action.

**Unknown:**

- Gallery timing, autoplay behavior, easing of major scenes and exact scroll triggers are unspecified.

### Responsive

**Observed:**

- The default opening headline has a 40px/40px smaller-size declaration and a 60px/60px desktop declaration.
- Focused utility opening headings declare 40px/42px at smaller sizes; section statements declare 30px at smaller sizes.
- Plan cards declare 32px padding before the 56px desktop treatment. Grids declare single-column bases with larger-screen multi-column variants; a 600px width breakpoint is present.

**Transfer:**

- On narrow layouts, keep the artifact fan centered and scale its framing before sacrificing the two-line promise.
- Stack paired demonstrations and split chapters; retain captions outside the panels and preserve the 20px or 32px material distinction.
- Let specimen galleries remain horizontally browsable rather than shrinking every artifact into a tiny grid.

**Unknown:**

- Exact breakpoint widths for the utility grid changes and complete mobile navigation behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
