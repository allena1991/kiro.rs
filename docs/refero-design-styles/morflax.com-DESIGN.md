# Morflax — material playground

## Overview

A cinematic playground for creative software, mixing black exhibition stages with bright white galleries and a cool gray collage interlude. Compact grotesk headlines give way to oversized product imagery: polished 3D objects, fanned capability cards and layered interface windows. The mood is playful but technical, with color concentrated in the work rather than in the page furniture.

### Essentials

- The product opens as a deck of possibilities: a black 900px stage, centered 48px/1 semibold headline, a gray concluding line and overlapping portrait cards beneath a white pill action.
- Headlines behave like compact sculptures: Inter 600, 48px/1 with -0.01em tracking for the main promise; 60px/1 with -0.025em tracking for standalone benefit statements.
- Actions are soft capsules, not hard UI rectangles: the default is white with dark text, 12px 24px padding, 48px height and 9999px corners, with a small right arrow.
- Color lives inside the work: black and white dominate the page, while coral, violet and gold are concentrated in full-bleed media tiles. The one emphatic marketing accent is #298ef5 on a 484px × 168px exploration capsule, not an all-page blue theme.
- An airborne collage is a signature interruption: cool #eff0f2 backing, varied image postcards with 6px white rims and 24px corners, rotated around the giant 72px action. Use real output samples or carefully composed illustrative cards when there is no 3D library.
- Evidence of making is staged at exhibition scale: 1120px × 560px feature panels, 320px × 489px portrait tool tiles and 750px × 500px demonstration frames, often extending beyond the right edge.
- The ending becomes a black directory with a short two-line credo: 48px/1 medium type with -0.025em tracking above four link columns, 40px gutters and muted 18px/28px links.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Explore blue | `#298ef5` | `--color-blue` | action, accent | Oversized exploration capsule only; not the normal primary action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-white` | background, surface, text, action | White gallery bands, primary action fills, bright text on black and postcard rims. |
| Stage black | `#000000` | `--color-black` | background, surface | Default opening, cinematic chapters and footer. |
| Tile charcoal | `#171718` | `--color-tile-base` | surface, text | Backing for portrait artwork and dark headings on pale surfaces. |
| Object panel | `#1c1c1e` | `--color-dark-card` | surface | Object cards in dark catalog chapters. |
| Gallery ink | `#25282b` | `--color-ink` | text, surface | Section titles, action text and dark demonstration badges. |
| Object edge | `#2a2a2d` | `--color-dark-edge` | border | Subtle outline of dark catalog cards. |
| Feature graphite | `#767881` | `--color-feature-shade` | background | Upper end of a silver-backed feature panel. |
| Muted gray | `#7c7e83` | `--color-muted` | text, link | Support lines, secondary headline clauses and directory links. |
| Silver text | `#a3a7ad` | `--color-secondary` | text, link | Gray opening qualifier, navigation and subdued metadata. |
| Feature silver | `#c6c8d7` | `--color-feature-light` | background | Lower end of a silver-backed feature panel. |
| Pale label | `#e4e4e7` | `--color-catalog-label` | text | Names beneath objects in dark catalog cards. |
| Gallery edge | `#e5e7eb` | `--color-light-edge` | border | Fine outline of white catalog panels. |
| Collage ground | `#eff0f2` | `--color-collage` | background | Cool full-width airborne postcard stage. |
| Soft white | `#fbfbfe` | `--color-soft-white` | text, surface | Slightly cool display text and demonstration backing; active white action fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| identity-led corporate openings | Lavender shade | `#aeb1cc` | `--color-lavender-shade` | background | Outer shade of the identity-stage radial gradient. |
| identity-led corporate openings | Lavender light | `#dfe1f0` | `--color-lavender-light` | background | Light end of the identity-stage radial gradient. |
| pricing pages | Upgrade ink | `#1a1b1e` | `--color-upgrade-ink` | text | Text on silver upgrade actions. |
| pricing pages | Pricing ink | `#323238` | `--color-pricing-ink` | text, action | Pricing title, price and selected billing segment. |
| pricing pages | Pricing copy | `#4f5057` | `--color-pricing-copy` | text | Feature lists and questions. |
| pricing pages | Chrome gray | `#8d8e96` | `--color-chrome-edge` | accent, text | Metallic action gradient edges and billing support. |
| pricing pages | Pricing edge | `#ececef` | `--color-pricing-edge` | border, surface | Half-pixel plan outlines and pale saving labels. |
| pricing pages | Question rule | `#f3f3f4` | `--color-faq-edge` | border | Very faint separator beneath questions. |
| pricing pages | Pricing ground | `#f7f7f8` | `--color-pricing-ground` | background | Application-style pricing canvas. |
| pricing pages | Chrome highlight | `#f8f8f9` | `--color-chrome-light` | accent | Center of metallic actions and plan labels. |

## Typography

- **Inter** — Headlines, support copy, actions, navigation and pricing. High-x-height contemporary grotesk; compact semibold headlines contrast with regular utility text. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **rogan** — Demonstration category badges and identity-stage description. Compact rounded sans with a slightly softer technical voice. If unavailable, use **Manrope**. Use 500; retain the measured tracking in uppercase labels. Font stack: "rogan", "Manrope", Inter, ui-sans-serif, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| explore-display | Inter | 600 | 72px | 1 | -0.01em | The oversized blue exploration action. |
| statement | Inter | 600 | 60px | 1 | -0.025em | Large isolated benefit statements on black. |
| hero | Inter | 600 | 48px | 1 | -0.01em | Centered opening promise and major editorial section headings. |
| section-heading | Inter | 600 | 48px | 1 | normal | Left-aligned carousel section names. |
| closing-credo | Inter | 500 | 48px | 1 | -0.025em | Two-line footer credo. |
| feature-heading | Inter | 600 | 36px | 1.111 | -0.01em | Short headlines inside large feature panels. |
| caption-heading | Inter | 500 | 24px | 1.333 | -0.01em | Demonstration captions and icon-led chapter labels. |
| support | Inter | 500 | 20px | 1.4 | -0.01em | Short descriptive copy accompanying a feature or collage. |
| directory-link | Inter | 400 | 18px | 1.556 | normal | Footer directory links. |
| action | Inter | 500 | 16px | 1.5 | normal | White pill actions and supporting text links. |
| body | Inter | 400 | 16px | 1.5 | normal | Navigation, concise lists and utility copy. |
| eyebrow | Inter | 500 | 16px | 1.5 | 0.05em, uppercase | Directory group labels. |
| demo-tag | rogan | 500 | 16px | 1.5 | 0.05em, uppercase | Small category badges below demonstration media. |
| catalog-name | Inter | 400 | 16px | 1.5 | 0.05em, uppercase | Names below dark object previews. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product directory pages | directory-display | Inter | 600 | 60px | 1 | -0.01em | Centered introductory promise on white. |
| pricing pages | pricing-heading | Inter | 600 | 45px | 1 | normal | Compact pricing promise. |
| pricing pages | price | Inter | 700 | 45px | 1 | -0.0033em | Large amount with smaller billing period beside its baseline. |
| pricing pages | faq-heading | Inter | 600 | 33.8px | 1.111 | -0.0044em | Centered question-section heading. |
| identity-led corporate openings | identity-description | rogan | 500 | 24px | 1.333 | normal | Short description beneath a monumental wordmark. |
| pricing pages | question | Inter | 500 | 18.8px | 1.4 | -0.008em | Question rows. |
| pricing pages | pricing-body | Inter | 400 | 15px | 1.5 | -0.01em | Plan feature lists. |
| pricing pages | upgrade-action | Inter | 600 | 13.1px | 1.43 | -0.011em | Metallic plan conversion buttons. |

**Notes:**

- Keep the main promise short enough for two bright lines plus one gray qualifier. The qualifier shares its parent's size and weight.
- The large isolated benefit statements use tighter tracking than the opening promise; do not apply -0.025em to all interface copy.
- Sentence case dominates headlines. Uppercase is reserved for small group labels, catalog names and category badges.

## Layout

**Density:** Airy at chapter scale, compact within controls: full-screen media scenes alternate with tight cards and short text blocks.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Caption spacing and footer link separation. |
| 12px | Action vertical padding and heading-to-support spacing. |
| 24px | Page side gutters, portrait rail gap and action-to-headline separation. |
| 32px | Demonstration rail gap. |
| 40px | Footer column gap and collage text/action spacing. |
| 48px | Feature-panel inner padding and editorial heading-to-media spacing. |
| 56px | Benefit statement separation and rail heading-to-image interval. |
| 80px | Standard gallery chapter vertical padding. |
| 112px | Feature chapter top padding and major interlude separation. |
| 160px | Extended exhibition chapter breathing room. |

### Containers and grids

- **wide-gallery**: max width 1536px · side padding 24px. Broad horizontal sections; media rails extend to the viewport edge rather than narrowing to the text measure.
- **opening-deck**: max width 1152px. Centered fan of portrait cards below the opening copy.
- **opening-copy**: max width 768px · side padding 24px. Centered headline block; actual copy occupies roughly 600px on desktop.
- **feature-rail**: gap 24px. 1120px-wide feature panels with a following panel peeking in at the right edge.
- **portrait-rail**: gap 24px. 320px-wide portrait tiles in an overflow rail, not compressed to fit every item.
- **footer-grid**: 4 columns · gap 40px · side padding 40px. Four equal directory columns on the black ending.
- **directory-grid** (only for product directory pages): 5 columns · gap 28px · side padding 24px. Five portrait capability tiles across; larger legacy panels occupy a separate two-column row.
- **plan-grid** (only for pricing pages): max width 840px · 2 columns · gap 30px · side padding 15px. Two equally tall 375px plan cards, one white and one black.
- **questions** (only for pricing pages): max width 960px · side padding 45px. Centered wrapper around an 870px question list.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | media-and-tiles | 16px |
|  | feature-panels-and-postcards | 24px |
|  | demonstration-badges | 12px |
| pricing pages | plan-cards | 22.5px |
| pricing pages | metallic-actions | 15px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-media | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Layered interface windows, postcards and the giant exploration action. |
| opening-card | `0px 20px 40px -8px rgba(0,0,0,0.5)` | Separation between cards in the black opening fan. |
| white-action | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | Subtle lift under normal white pill actions. |

### Surfaces

#### Black stage · level 0

**Use:** Default opening, product exhibition chapters and closing directory.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Objects are revealed by highlights rather than by lighter rectangular boxes. Wide black sections alternate decisively with white.

**Transfer:** Use genuine black around the showcased object so the page reads like a gallery, not a dark dashboard.

#### White gallery · level 0

**Use:** Feature rails, demonstration chapters and directory content.

**CSS:** `background: #ffffff; color: #25282b`

**Observed:** Broad uninterrupted white canvas; headings and media align to 24px outer gutters.

**Transfer:** Let art provide color while the surrounding layout remains neutral.

#### Collage ground · level 0

**Use:** The airborne postcard interlude.

**CSS:** `background: #eff0f2; overflow: hidden`

**Observed:** Full-screen pale cool ground without a visible texture.

**Transfer:** Leave enough empty center to read the label, action and support copy.

#### Feature panel · level 1

**Use:** Wide capability panels in the feature rail.

**CSS:** `background: #ffffff; border-radius: 24px; overflow: hidden`

**Observed:** 1120px × 560px panels split short copy and an oversized editor view. One version uses a colorful meadow and sunset backdrop; another uses a silver gradient from #767881 above to #c6c8d7 below.

**Transfer:** Pair a short benefit with one legible product view; use a bottom black fade only where needed for copy contrast.

#### Demonstration backing · level 1

**Use:** Video and editor demonstrations.

**CSS:** `background: #fbfbfe; border-radius: 16px; overflow: hidden`

**Observed:** 750px × 500px panels carry dark or pale editor windows, often slightly tilted within a soft gray setting.

**Transfer:** Use complete workflows or useful outputs rather than decorative browser chrome.

#### Pricing canvas · level 0

**Only for:** pricing pages

**Use:** Denser application-style pricing presentation.

**CSS:** `background: #f7f7f8`

**Observed:** A pale application shell replaces the full-width dark marketing navigation.

**Transfer:** Keep pricing a scoped utility variant rather than extending its chrome to ordinary landing pages.

#### Identity atmosphere · level 0

**Only for:** identity-led corporate openings

**Use:** Lavender backdrop for an oversized wordmark and foreground person.

**CSS:** `background: radial-gradient(64.38% 210.53% at 35.62% 50%, #dfe1f0 0px, #aeb1cc 100%)`

**Observed:** Very low saturation; white wordmark and white actions sit behind and beside a silhouetted person holding a luminous phone.

**Transfer:** Use a cool atmospheric field and one credible human/product interaction.

## Components

### Navigation

**Use:** Persistent marketing navigation.

**CSS:** `position: fixed; top: 0px; height: 48px; width: 100%; background: rgba(0,0,0,0.8); backdrop-filter: blur(16px); z-index: 50`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Small symbol at left, compact links beside it, access and sign-in links at right and a white 36px-high launch pill. Outer gutter is 24px.

**Transfer:** Keep the navigation shallow enough that artwork remains the dominant first impression.

### Primary button

**Use:** Normal conversion and catalog actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #25282b; border-radius: 9999px; padding: 12px 24px; height: 48px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Text style:** `action` — Inter 500 · 16px/1.5

**Observed:** Short verb phrase followed by a small right-pointing arrow. Width follows the label; the same white control appears on black and image-backed panels.

**States:** Declared: hover background-color rgba(249,250,251,1); focus-visible unknown; active background-color rgba(251,251,254,1).

### Opening card

**Use:** The overlapping capability fan in the first screen.

**CSS:** `position: relative; background: #171718; border-radius: 16px; overflow: hidden; box-shadow: 0px 20px 40px -8px rgba(0,0,0,0.5)`

**Observed:** Portrait art fills each card. The central card is largest and frontmost, approximately 258px × 410px, with smaller receding neighbors and a tiny icon/name at the top.

**Transfer:** Use distinct outputs or use cases, with the strongest image at the center. A minimum version uses three overlapping original output cards.

### Postcard

**Use:** Floating media around the exploration action.

**CSS:** `background: #ffffff; border: 6px solid #ffffff; border-radius: 24px; overflow: hidden; box-shadow: 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Observed:** Mixed portrait, landscape and square cards, slightly rotated and overlapping; white rims unify otherwise unrelated artwork.

**Transfer:** Mix actual results, UI details and product objects rather than repeating a single thumbnail.

### Explore capsule

**Use:** Signature giant action within the collage interlude.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #298ef5; color: #ffffff; padding: 48px 112px; border-radius: 9999px; box-shadow: 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Text style:** `explore-display` — Inter 600 · 72px/1 · tracking -0.01em

**Observed:** Centered above the postcards; one broad verb becomes a graphic object. An icon-led category label sits above, with a short muted paragraph below.

### Demo badge

**Use:** Category label beneath a demonstration panel.

**CSS:** `display: inline-block; background: #25282b; color: #ffffff; padding: 4px 12px; border-radius: 12px`

**Text style:** `demo-tag` — rogan 500 · 16px/1.5 · tracking 0.05em · uppercase

**Observed:** Placed above the sentence-case caption, outside the media panel; compact rather than spread across the full width.

### Object card

**Use:** Featured results in dark catalog chapters.

**CSS:** `background: #1c1c1e; border: 1px solid #2a2a2d; border-radius: 16px; padding: 8px; overflow: hidden; width: 320px`

**Text style:** `catalog-name` — Inter 400 · 16px/1.5 · tracking 0.05em · uppercase

**Observed:** Large isolated object on a matching charcoal field, then uppercase name and smaller gray category/creator metadata. Image area is 302px × 320px; card height is 414px.

**Transfer:** Keep each object surrounded by dark negative space and reserve the lower strip for metadata.

### Directory link

**Use:** Black footer navigation.

**CSS:** `display: flex; color: #7c7e83; margin-bottom: 8px`

**Text style:** `directory-link` — Inter 400 · 18px/1.556

**Observed:** Links are grouped under small uppercase labels; no card backgrounds or enclosing outlines.

**States:** Declared: hover color rgba(255,255,255,1); focus-visible unknown.

### Plan card

**Only for:** pricing pages

**Use:** Comparison of paid tiers.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 0.5px solid #ececef; border-radius: 22.5px; padding: 30px`

**Text style:** `pricing-body` — Inter 400 · 15px/1.5 · tracking -0.01em

**Observed:** Silver tier badge, price, billing explanation, savings pill, checked feature list and bottom-aligned Metallic upgrade. Premium variant is solid black with pale text; both cards are 375px × 570px.

### Metallic upgrade

**Only for:** pricing pages

**Use:** Plan conversion actions and one-time-offer action.

**CSS:** `display: block; width: 100%; background: linear-gradient(to right, #8d8e96, #f8f8f9, #8d8e96); color: #1a1b1e; border: 1px solid rgba(255,255,255,0.4); border-radius: 15px; padding: 11.3px 22.5px; box-shadow: 0px 1px 0px 0px rgba(255,255,255,0.65) inset; text-align: center`

**Text style:** `upgrade-action` — Inter 600 · 13.1px/1.43 · tracking -0.011em

**Observed:** Full-width silver action at the bottom of either light or black plans. The same metallic material appears on small tier labels.

### Question row

**Only for:** pricing pages

**Use:** Objection handling beneath pricing.

**CSS:** `position: relative; border-bottom: 1px solid #f3f3f4; overflow: hidden`

**Text style:** `question` — Inter 500 · 18.8px/1.4 · tracking -0.008em

**Observed:** A 65px row with the question on the left and a small downward chevron on the right; inner padding is 18.8px vertically and 7.5px horizontally. Eight rows form a single restrained list.

### Legacy panel

**Only for:** product directory pages

**Use:** Secondary or earlier product families.

**CSS:** `display: flex; justify-content: space-between; background: #ffffff; border: 1px solid #e5e7eb; border-radius: 16px; overflow: hidden`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Wide 682px × 384px panel with icon/name at upper left, small version marker at upper right, concise description low on the left and oversized art entering from the right.

**Transfer:** Separate secondary offerings from the main portrait grid without giving them a different visual language.

## Imagery and graphics

### Material capability art

**Use:** Opening fan and repeated portrait rails.

**Observed:** Close-up 3D sculptures and mockups: ribbed coral forms, iridescent violet extrusions, warm metallic stars, pale stone busts and silver devices. Objects are dramatically enlarged and clipped by portrait frames; category labels remain small near the top.

**Transfer:** Create distinct output families with physical-looking depth and one dominant material per tile. For nonvisual software, use polished diagrams or composed output documents with similarly strong silhouettes and coherent backgrounds.

**Build:** Use portrait frames near a 2:3 ratio. Fill each with a simple SVG or rendered extruded form: repeated rounded ribs on coral, a beveled geometric silhouette on warm cream, or a violet object with narrow pink and cyan edge highlights. Put the object in the lower four fifths, leaving a label strip; use soft directional shadowing and let edges extend beyond the frame.

### Airborne postcard constellation

**Use:** The signature pale exploration interlude.

**Observed:** An asymmetrical cluster of white-rimmed cards surrounds a central blue capsule. A cup, abstract forms, phones, editor windows, landscape art and a laptop alternate in size and orientation. Shadows are broad and downward, not glows.

**Transfer:** Compose a miniature world of product outcomes around a single verb, using real examples wherever available. A minimum version needs varied output cards rather than empty decorative rectangles.

**Build:** On Collage ground, position roughly nine Postcards around the center, mixing approximately 180px–270px widths and portrait/square/landscape aspect ratios. Rotate alternately about -8deg to 8deg, overlap several cards, keep the central action on the highest layer and leave its support paragraph readable. Apply the floating-media shadow and 6px white rims.

### Layered editor windows

**Use:** Product demonstration between headline chapters.

**Observed:** Three oversized editor views overlap on black or a graphite panel. A dark rear window, translucent pale middle window and white front window create depth; the stack is much larger than the accompanying paragraph.

**Transfer:** Use genuine product screens or realistic outcome boards. Keep the frontmost view readable and let rear views communicate breadth.

**Build:** Stack three 16px-rounded image planes; offset them vertically, tilt the middle plane slightly counterclockwise and the front plane slightly clockwise. Add floating-media shadows. Keep neutral outer frames and place the most useful output in the front plane.

### Black-on-black sculpture

**Use:** Cinematic catalog and premium chapters.

**Observed:** A huge hollow rounded form emerges from black with soft silver rim light; a second scene arranges glossy black discs into a radial flower. The objects occupy roughly half the section and fade into the bottom ground.

**Transfer:** Use a single product-relevant silhouette with restrained highlights, not a multicolor illustration. A minimum equivalent is a carefully shaded SVG sculptural loop.

**Build:** For a loop, layer several thick curved SVG paths or a rendered rounded lattice over black, using near-black bodies and narrow semitransparent white edge highlights. For the radial variant, arrange elliptical discs around an empty center, varying foreshortening and highlight position; fade the lower edges using a transparent-to-black overlay.

### Identity portrait and wordmark

**Only for:** identity-led corporate openings

**Use:** Corporate-scale first impression distinct from the default product opening.

**Observed:** A giant white geometric wordmark spans nearly the whole width over lavender. A backlit person using a phone overlaps the lettering and reaches the lower edge; short left-aligned copy and two pale pills remain subordinate.

**Transfer:** Use a new brand's own lettering with a credible cutout portrait or product silhouette; the subject should overlap the type without hiding all of its recognition.

**Build:** Set a wide SVG wordmark behind the subject with approximately 24px side clearance and a 241px-high artwork area at desktop. Use Identity atmosphere behind both layers; align two 54px pill actions near the bottom left.

### Perspective floor

**Only for:** community invitation sections

**Use:** A pale closing invitation before the black directory.

**Observed:** A nearly invisible gray wireframe floor recedes into white beneath a left-aligned two-line invitation and oversized social marks at the right.

**Transfer:** Use a few relevant community destinations with generous space; keep the floor subordinate.

**Build:** Draw a thin gray SVG perspective grid across the lower part of a white band: converging rays toward a central horizon plus increasingly spaced horizontal lines. Mask the upper half toward transparency so it dissolves into white; no saturated colors or heavy horizon line.

### Icons

**Observed:** Marketing actions use 20px arrows with rounded 3px strokes; rail controls use 20px chevrons inside 40px pale or dark circles. General marks are 24px filled glyphs. Pricing checks are outlined circles, about 23px with 2px round strokes.

**Transfer:** Use one coherent set of compact arrows, chevrons and circled checks. Keep labels dominant and avoid large multicolor navigation icons.

## Section recipes

How recurring sections are built.

### First screen: Fanned product opening

**Observed:** Black stage fills the first 900px, with Navigation on top. Center a compact 48px semibold promise about 176px below the page top: two white lines and one gray concluding line, around 600px wide. Primary button follows after 24px. Below it, a 1152px-wide fan occupies most of the lower half: the center portrait is about 258px × 410px, frontmost and lowest; neighboring cards get smaller and recede laterally. Back-to-front layers are Black stage, faint surface texture, overlapping Opening cards, centered copy/action and fixed Navigation. The headline, gray qualifier, action and whole visual fan are visible within the first 900px; longer benefit statements and editor demonstrations begin below.

**Transfer:** Give a different product a short promise and a fan of distinct outcomes. Without 3D assets, art-direct original output boards or illustrative capability cards with varied material-like backgrounds. Product directories instead open with a centered 60px promise on white; pricing opens with a 45px title, billing switch and paired plan cards; identity-led corporate openings use the wordmark-and-person variant.

**Avoid:** Do not replace the fan with a tiny dashboard thumbnail, a conventional left-copy/right-card split or a blue-filled hero. Do not use the 72px exploration-action type for the opening headline.

**Text style:** `hero` — Inter 600 · 48px/1 · tracking -0.01em

### Benefit statements and editor proof

**Observed:** Centered 60px statements on black, each short enough for a line, separated by about 56px. A stack of Layered editor windows follows; a centered muted paragraph and Primary button complete the proof chapter.

**Transfer:** Move from outcome statements to concrete visible proof. Keep the statements separate rather than turning them into a dense paragraph.

**Text style:** `statement` — Inter 600 · 60px/1 · tracking -0.025em

### Feature rail

**Observed:** White gallery with 112px top and 80px bottom padding. A 48px section name and small circular arrow controls lead into Feature panels after about 56px. Panels keep 48px inner padding, benefit copy at upper left, action low left and a very large interface view to the right; the next panel peeks beyond the viewport.

**Transfer:** Organize distinct capabilities as broad visual chapters rather than small equal feature boxes.

**Text style:** `section-heading` — Inter 600 · 48px/1

### Portrait capability gallery

**Observed:** A left-aligned section name pairs with a small secondary link and circular arrows. Portrait media tiles follow with 24px gaps, 320px × 489px dimensions and 16px corners. The rail intentionally reveals a partial next item.

**Transfer:** Use capability or outcome families, each with a distinctive dominant color confined to its media.

### Exploration collage

**Observed:** Full-screen Collage ground supports Airborne postcard constellation. Center an icon-led 24px category label, then Explore capsule after 40px, then a muted 20px support paragraph after another 40px. The blue action overlaps the floating media and is the strongest text object.

**Transfer:** Use this signature device somewhere in a new landing page as an invitation to discover examples, templates or outputs; its position and repetition can follow the new story.

**Text style:** `explore-display` — Inter 600 · 72px/1 · tracking -0.01em

### Dark catalog chapter

**Observed:** Black stage holds a huge Black-on-black sculpture with white heading and gray concluding clause. One composition centers text above the object; another splits text left and object right. A white action leads into a rail of Object cards below.

**Transfer:** Turn a product's breadth into a sculptural exhibition scene; keep the supporting library rail visually subordinate.

**Text style:** `hero` — Inter 600 · 48px/1 · tracking -0.01em

### Demonstration journal

**Observed:** White gallery; 48px heading, a muted support line 12px below and media rail after 48px. Two 750px × 500px Demonstration backings use 32px gaps. Each carries a Demo badge and 24px caption underneath.

**Transfer:** Show a workflow, experiment or short result, with a descriptive caption rather than a long testimonial.

**Text style:** `caption-heading` — Inter 500 · 24px/1.333 · tracking -0.01em

### Premium conversion scene

**Observed:** A black 720px chapter places a two-line 48px price-led headline, seven concise circled-check benefits and a white action on the left. Glossy radial artwork occupies the larger right region and fades into black at the bottom.

**Transfer:** End a product story with the practical paid value next to a restrained black sculpture; replace all commercial details with the new offer.

**Text style:** `hero` — Inter 600 · 48px/1 · tracking -0.01em

### Credo directory ending

**Observed:** Black stage ends the marketing experience with a 48px two-line credo at upper left. Four columns sit below in Footer grid: uppercase labels, muted Directory links with 8px separation, then a low legal/social row. The band is 768px tall with 40px side padding. The application-style pricing ending instead uses five narrower columns with a small product description and no large credo.

**Transfer:** Use a short brand philosophy line, then useful navigation grouped by task. Keep legal and social links visually minor and near the bottom.

**Text style:** `closing-credo` — Inter 500 · 48px/1 · tracking -0.025em

### Plans and one-time offer

**Only for:** pricing pages

**Observed:** Compact 45px centered promise and billing switch above Plan cards. One white plan and one black premium plan share equal height, silver labels and Metallic upgrade actions. Payment reassurance follows. A separate 780px × 315px black rounded banner presents a one-time offer with a short white headline, supporting line, silver action and small media object.

**Transfer:** Preserve the clear light/dark tier distinction and common silver action treatment; reserve the banner for a genuinely different purchasing model.

**Text style:** `pricing-heading` — Inter 600 · 45px/1

### Question list

**Only for:** pricing pages

**Observed:** Centered FAQ heading and single support sentence precede eight Question rows. The list is 870px wide within Questions, with faint bottom rules and right-edge chevrons. Large pale margins separate it from the plans and black footer.

**Transfer:** Answer concrete buying objections in plain language; retain the open list instead of boxing every question.

**Text style:** `faq-heading` — Inter 600 · 33.8px/1.111 · tracking -0.0044em

### Community floor invitation

**Only for:** community invitation sections

**Observed:** White 512px band with a left-aligned two-line invitation and oversized black social marks on the right. Perspective floor dissolves into the white background at the bottom.

**Transfer:** Give an existing user community a spacious invitation before the directory, using destinations appropriate to the new audience.

## Page flow

**Storyline:** promise → visible product possibilities → practical capability proof → exploration interlude → deeper catalog or workflow evidence → commercial invitation → directory ending

### Product landing page with cinematic product depth

1. **Promise** — Black opening with centered benefit and fanned capability art.
2. **Product demonstration** — Large independent benefit statements and overlapping editor windows.
3. **Capability chapters** — White feature panels and portrait rails.
4. **Exploration** — Pale postcard constellation with giant blue action.
5. **Product breadth** — Black sculpture scene and dark object cards.
6. **Workflow proof** — Large captioned demonstration panels.
7. **Commercial invitation** — Black premium scene with circled-check benefits.
8. **Closing directory** — Two-line credo, four link columns and legal/social row.

**Transfer:** Use as the default narrative for a new product landing page; vary the number and order of chapters while retaining the material fan, collage device and strong ending.

### Corporate identity and ecosystem overview

1. **Identity** — Monumental white wordmark behind a human/product interaction on lavender.
2. **Promise** — An isolated centered statement on white.
3. **Capability proof** — Feature rail, portrait tools and pale collage.
4. **Exploration** — Black sculptural catalog scene and captioned experiments.
5. **Community invitation** — Large social marks above a dissolving wireframe floor.
6. **Closing directory** — Black credo directory.

**Transfer:** Use when a parent brand needs identity as well as product discovery; keep it distinct from the default product-focused opening.

### Product family directory

1. **Promise** — Centered compact three-line heading on white.
2. **Flagship proof** — A wide graphite panel with layered product windows.
3. **Capability directory** — Five-column portrait grid with a social follow tile.
4. **Secondary offerings** — A pair of white outlined legacy panels.
5. **Closing directory** — Shared black credo directory.

**Transfer:** Prioritize scanability and strong media families over a long sequence of sales arguments.

### Plan selection and purchase reassurance

1. **Commercial promise** — Pale utility opening with compact title and billing switch.
2. **Pricing comparison** — Two equal-height contrasting plans with silver actions.
3. **Alternative offer** — Payment reassurance and a black one-time-purchase banner.
4. **Objection handling** — Centered open FAQ list.
5. **Closing directory** — Five columns on black, with product identity/description replacing the large credo.

**Transfer:** Use the denser application-style variant only for buying decisions; keep media secondary to terms and price clarity.

## Writing

Direct, creative and lightly enthusiastic. The language promises useful outcomes and reduced setup rather than abstract business transformation.

**Do not copy:** Do not reuse Morflax names, logos, artwork, exact slogans, product-specific claims, prices, plan savings, counts, copyright dates or customer assertions. Source examples illustrate voice, not reusable claims.

- **Addressing the reader:** Mostly direct verbs and concise product descriptions; occasional 'your' and 'you' address the reader. The product is named in explanatory copy, while actions remain impersonal and task-led.
- **Rhythm:** Short sentence-case headlines, frequently split into two clauses. Compact statements often use periods as beats; support is usually one sentence or two short fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Describe the product category, then add a friction-removing qualifier. | 8–16 words plus a short qualifier | “A creative suite for design and motion graphics.”<br>“All in your browser.” |
| Capability headline | Active verb plus tangible output and ease or speed. | 5–9 words | “Create visuals and motion in minutes.”<br>“Turn designs into mockups with ease.” |
| Support | Remove a practical objection using brief factual fragments. | 5–18 words | “Zero setup. Runs in your browser.” |
| Editorial chapter | Three short verbs punctuated as separate beats. | 3–6 words | “Explore. Design. Animate” |
| Primary action | Plain imperative naming the immediate next step. | 1–4 words | “Get started”<br>“Open Catalog”<br>“Explore” |
| Buying objection | Ask the exact practical question in the reader's voice. | 4–12 words | “Can I cancel anytime?” |

**Words and phrasing to use:** create; explore; remix; in minutes; in just a few clicks; all in one place; zero setup; your browser

**Avoid:** revolutionary; synergy; enterprise transformation; unparalleled; disruptive ecosystem; long strings of superlatives

**Rules:**

- Lead with a visible result, then explain the mechanism or convenience.
- Use paired clauses to separate the core promise from its accessibility qualifier.
- Name actions after their destination or task; keep extra reassurance in support text.
- In commercial copy, show billing period and cancellation terms plainly.

## Do's and Don'ts

### Do

- Use a true black stage with white and gray headline clauses, not one uniform gray text block.
- Keep default opening type at 48px/1 and isolated statements at 60px/1.
- Retain 24px side gutters for gallery rails and let a following item peek into view.
- Make normal actions 48px-high white capsules with 12px 24px padding.
- Preserve the 6px white rim and 24px corners on floating postcards.
- Keep large demonstration frames at a 3:2 proportion with captions outside the media.
- Give black object cards a #2a2a2d edge against #1c1c1e.
- Use a two-line 48px closing credo above the marketing directory.

### Don't

- Do not spread #298ef5 across ordinary buttons, headings and full-width bands; concentrate it in the giant exploration action.
- Do not reduce every image to a small icon above a paragraph; the imagery is the principal content.
- Do not compress a 320px portrait rail until all five tiles fit; keep the intentional overflow.
- Do not apply plan-card metallic gradients to general landing-page controls.
- Do not add heavy outlines to white gallery chapters; reserve 1px edges for contained directory panels.
- Do not give the gray headline qualifier a separate smaller font; preserve the main recipe.
- Do not use uppercase for the main promises; reserve it for names, category tags and directory labels.
- Do not replace the black ending with a pale newsletter box or a compact single-row footer.

## Motion and responsive

### Motion

**Observed:**

- Normal white actions declare 0.3s transitions with cubic-bezier(0.4, 0, 0.2, 1); directory links declare 0.15s using the same curve.
- Postcards declare transform 0.3s and box-shadow 0.3s transitions.
- The opening fan uses layered 3D transforms, scale and per-card brightness/saturation to produce depth.
- The fixed navigation declares a 0.5s transition; artwork rails support horizontal scrolling.

**Transfer:**

- Preserve depth through card overlap and subtle transform changes rather than making the headline the animated spectacle.
- Use the declared short color and surface transitions for actions; keep the collage composition readable at rest.

**Unknown:**

- Continuous fan interaction, scroll choreography, animation durations for sculptures and exact hover scale changes are not established.

### Responsive

**Observed:**

- Styles define breakpoints at 640px, 768px, 1024px, 1280px and 1536px, with additional page-specific thresholds.
- The opening heading uses smaller text classes below the desktop size; its gray qualifier is hidden below 768px.
- Feature panels switch from column to row at 768px. Directory grids collapse to fewer columns; navigation links are hidden below the medium breakpoint.

**Transfer:**

- On narrow screens keep the centered promise, a visible white action and a legible central capability card; reduce side-card exposure rather than shrinking every label.
- Let portrait rails remain horizontally navigable. Stack feature copy above media and retain postcard overlap with fewer items in the visible field.
- Collapse the four-column footer into readable stacked groups while preserving its black ground and credo.

**Unknown:**

- Only desktop geometry is established; exact mobile fan transforms, spacing and interaction behavior are not known.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
