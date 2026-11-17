# Shader — analog dream theatre

## Overview

A cinematic, retro-futurist style that feels like a strange late-night broadcast rather than a conventional software brochure. Charcoal stages, warm ivory, dusty spectrum stripes and occasional electric blue surround tactile computer-generated objects and surreal photographic collages. A literary serif gives the supporting language a human counterpoint to the machinery; visual density comes from scenes rather than interface furniture. It suits creative technology, experimental studios and products with a compelling physical or metaphorical world.

### Essentials

- The opening behaves like a miniature film set: a full-bleed 1440px × 900px stage, a large object in the lower-right half, and atmospheric light across the floor rather than a card enclosing the media.
- Analog texture unifies unlike imagery: fine grain, soft bloom and restrained red/cyan edge separation cover 3D objects, cutout people and graphic transitions alike.
- Typography is a literary counterweight to technical imagery: STIX Two Text at 400, with a 16px/24px supporting-text default and normal tracking; keep added copy subordinate to the scene.
- Darkness is the default material, not a feature-card theme: black foundations and charcoal scenery carry most object scenes; warm ivory is a contrasting graphic chapter and saturated blue is concentrated near the lower edge.
- A muted spectrum ribbon and an undulating ivory-and-charcoal stripe field supply the signature graphic vocabulary: use full-width, gently bowed parallel lines and a curtain-like optical pattern, not scattered rainbow badges.
- Actions should remain visually lighter than the scenery: transfer them as readable serif text links rather than introducing filled pill buttons; the world, not a button cluster, is the dominant silhouette.
- The closing retains physical theatre: a group of three ivory communication devices is staged in depth on charcoal under a warm spotlight; carry this principle into a final product-relevant object ensemble. Without 3D assets, use a carefully lit photographic still life.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Broadcast blue | `#251a83` | `--color-blue` | background, accent | Low-lying glow beneath the optical curtain and dark graphic scenes. |
| Faded teal | `#7daba5` | `--color-ribbon-teal` | accent | Thin bands in the spectrum ribbon, not general action fills. |
| Faded mauve | `#b77e9b` | `--color-ribbon-mauve` | accent | Muted spectrum bands. |
| Faded rust | `#bd8063` | `--color-ribbon-rust` | accent | Warm spectrum bands. |
| Faded gold | `#c5ad71` | `--color-ribbon-gold` | accent | Warm spectrum bands and restrained golden highlights. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm text | `#fcf9f3` | `--color-text` | text, link | Default foreground on dark scenery. |
| Aged ivory | `#ece8d2` | `--color-ivory` | background, accent | Graphic chapter backing and luminous stripe artwork; also the visual family of aged plastic props. |
| Optical charcoal | `#34362f` | `--color-optical-ink` | accent, text | Dark stripes and foreground language on ivory. |
| Charcoal stage | `#202120` | `--color-stage` | background, surface | Visible dark theatrical environments; preserve tonal texture rather than making every dark area pure black. |
| Black foundation | `#000000` | `--color-foundation` | background | Underlying page canvas and deepest scene shadows. |

## Typography

- **STIX Two Text** — Supporting language and restrained text-led controls. A bookish serif with bracketed serifs, human warmth and enough detail to contrast with synthetic scenery. Font stack: "STIX Two Text", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| body | STIX Two Text | 400 | 16px | 1.5 | normal | Default supporting prose and a conservative starting point for short text actions. |
| text-action | STIX Two Text | 400 | 16px | 1.5 | normal | Use the supporting-text scale for new readable text actions; distinguish actions through placement and underlining rather than a filled button. |
| scene-caption | STIX Two Text | 400 | 16px | 1.5 | normal | Use the same restrained serif scale for brief explanations beside a scene. Isolate captions spatially instead of adding a separate miniature UI font. |

**Notes:**

- Keep the serif's natural spacing; do not impose the tightly tracked grotesk treatment associated with conventional technology landing pages.
- For added section leads, use brief serif statements and establish hierarchy through isolation and contrast. Let imagery carry the monumental scale rather than inventing a competing giant wordmark.

## Layout

**Density:** Airy in the text layer and immersive in the visual layer; objects and graphic fields occupy entire stages rather than a dense stack of cards.

### Spacing

| Value | Use |
| --- | --- |
| 0px | Side inset of full-bleed scene artwork. |
| 24px | For added text, use one body line as a local separation between a short explanation and its action; keep this subordinate to the full-stage composition. |
| 900px | Desktop visual-stage height at a 1440px-wide composition; treat this as a viewport composition, not a fixed content-section rhythm. |

### Containers and grids

- **Immersive stage**: max width 1440px · side padding 0px. Edge-to-edge scene composition at desktop. Expand to the viewport rather than centering inside a boxed marketing container.

## Corner radius

| Element | Radius |
| --- | --- |
| Full-bleed stage | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Scene container | `none` | Keep the image plane unraised; contact shadows belong inside the object artwork, not around the rectangular container. |

### Surfaces

#### Foundation · level 0

**Use:** Underlying page plane.

**CSS:** `background: #000000; color: #fcf9f3`

#### Charcoal theatre · level 0

**Use:** Default backing for dimensional objects and cutout scenes.

**CSS:** `background: #202120`

**Observed:** A continuous dark environment with weak floor illumination, grain and soft haze; the edge between floor and void is deliberately indistinct.

**Transfer:** Light the object and its immediate ground, leaving the surrounding field dark. Keep any light spill irregular and soft.

#### Ivory graphic field · level 0

**Use:** Backing for the spectrum ribbon and optical artwork.

**CSS:** `background: #ece8d2; color: #34362f`

**Observed:** Warm, slightly mottled ivory rather than clean white; fine grain belongs to the same analog finish as the dark scenes.

**Transfer:** Use this material behind meaningful graphic or editorial content; retain texture without reducing text contrast.

#### Blue horizon · level 0

**Use:** Backing beneath high-contrast graphic scenes.

**CSS:** `background: linear-gradient(to bottom, #202120 0%, #251a83 100%)`

**Observed:** Indigo rises from the lower part of the stage while the upper field stays very dark.

**Transfer:** Match the low glow and dark upper field; exact gradient stops are not essential.

## Components

### Scene viewport

**Use:** The continuous visual container for the experience.

**CSS:** `position: fixed; inset: 0px; overflow: hidden`

**Observed:** A full-screen image plane sits behind the content layer; changes in scene create the chapters rather than boxed section backgrounds.

**Transfer:** Use a persistent visual layer or full-bleed stills with equivalent framing.

### Hero object stage

**Use:** A single memorable object introduces the product's world.

**CSS:** `position: relative; overflow: hidden; background: #202120`

**Observed:** A beige retro computer is angled in three-quarter view at lower right; the bright screen is embedded within a shaded physical casing. Haze and light spread onto the floor around it.

**Transfer:** Replace the prop with a product-relevant object or sculptural metaphor. Keep its material, illumination and grounding convincing.

### Repeated environment

**Use:** Expand a single object into a larger visual idea.

**CSS:** `overflow: hidden; background: #202120`

**Observed:** Rows of office cubicles, chairs and monitors recede diagonally into depth. An almost screen-filling rounded optical framing and chromatic edges make it feel viewed through a CRT.

**Transfer:** Repeat a relevant unit in perspective, with enough small variation and lighting to avoid a flat pattern.

### Spectrum ribbon

**Use:** A thin full-width graphic transition.

**CSS:** `display: block; width: 100%; overflow: hidden`

**Observed:** Parallel teal, mauve, rust and gold bands run horizontally across ivory. The stack bows gently and retains thin ivory separations.

**Transfer:** Keep the colors dusty and the ribbon narrow relative to the stage. Use it as connective artwork rather than a badge or button fill.

### Optical curtain

**Use:** A large-scale graphic change of atmosphere.

**CSS:** `overflow: hidden; background: #251a83`

**Observed:** Many alternating ivory and dark vertical stripes undulate into folds. The irregular lower edge hangs above a deep-blue field, evoking a luminous stage curtain.

**Transfer:** Build an original warped line field; preserve the contrast between dense stripes above and the open dark-blue area below.

### Perspective collage

**Use:** A surreal visual proof or celebration scene.

**CSS:** `position: relative; overflow: hidden; background: #202120`

**Observed:** Photographic people in muted business clothes form two receding rows around a floating reflective gold necktie. The figures read as cutouts in a synthetic space, with bloom and grain joining them.

**Transfer:** Use cleared original figures or meaningful objects around a new central symbol; make scale and depth deliberately theatrical, not a testimonial-card grid.

### Closing object ensemble

**Use:** A final tangible cue toward conversation or next steps.

**CSS:** `position: relative; overflow: hidden; background: #202120`

**Observed:** Three cream-colored telephones form a triangular depth arrangement. A low foreground handset anchors the scene while a taller rear handset provides vertical contrast; warm light and contact shadows join them to the floor.

**Transfer:** Arrange three product-relevant objects or photographic props with foreground overlap and a shared light source. Place any new closing language in the surrounding space, not on the object surfaces.

## Imagery and graphics

### Analog object theatre

**Use:** Opening and closing visual anchors; the core image language.

**Observed:** Low-poly or simplified vintage equipment is rendered with tactile beige plastic, dark keys, warm highlights and softly shadowed floors. The opening computer occupies roughly the right half of the screen; the closing phone group is more centered. Screen imagery is brighter and more saturated than its surroundings.

**Transfer:** Use a relevant physical prop, a simplified product model or a photographic still life. Minimum acceptable treatment is one sharply composed cutout with a soft ground shadow, warm directional light and the analog finish.

**Build:** Layer the object over charcoal, add an elliptical ground-light patch behind its base using ivory at low alpha and a broad blur, and place a tighter dark contact shadow beneath it. Overlay fine monochrome SVG turbulence at low opacity across the whole scene. Add only a slight red/cyan offset at high-contrast edges and restrained bloom around emissive parts; avoid turning all edges neon.

### Spectrum ribbon artwork

**Use:** A signature connective graphic between contrasting visual chapters.

**Observed:** A narrow stack of muted colored bands runs edge to edge on warm ivory, with gentle sag and grain rather than mathematically pristine lines.

**Transfer:** Create a fresh ribbon with the same faded spectrum and slight optical curvature.

**Build:** In a 1440px-wide SVG, draw six to eight parallel cubic paths that sag about 8px toward the center. Use 6px–9px strokes separated by 2px ivory gaps, cycling faded teal, mauve, rust and gold. Keep the total band stack around 65px high. Add a low-opacity noise overlay and minimal channel fringe.

### Warped stripe field

**Use:** The signature optical graphic at a change in narrative intensity.

**Observed:** Ivory and charcoal stripes change width as they curve laterally, forming alternating swollen and pinched folds. Artwork spans the full width and about the upper two thirds of a stage; deep blue occupies the lower part.

**Transfer:** Use a generated optical pattern rather than a generic mesh gradient. A static SVG is sufficient if animation is unavailable.

**Build:** Generate closely spaced vertical ribbons across a 1440px-wide SVG. Displace each ribbon sideways with two smooth sine waves of different periods and vary their thickness from hairline to about 15px. Fill alternate ribbons ivory and optical charcoal. Clip the bottom to a shallow irregular wave and place over Blue horizon. Apply shared grain and restrained bloom.

### Surreal depth collage

**Use:** A visual emphasis scene that replaces ordinary flat proof graphics.

**Observed:** Muted photographic figures stand apart from each other in two perspective lines flanking a reflective central form. Black surrounds the figures; golden highlights and soft edge bloom create a deliberately uncanny mixture of media.

**Transfer:** Choose a meaningful central symbol and a small cast of cleared cutouts. Preserve receding scale and an empty central aisle.

**Build:** Arrange transparent cutouts in two mirrored perspective rows, scaling each successive figure down toward the center. Place a separately rendered metallic or softly illuminated object in the aisle. Unite all layers with the same grain, warm highlights and shadowless dark distance.

## Section recipes

How recurring sections are built.

### First screen: Theatrical opening

**Observed:** The first 900px is a full-bleed charcoal environment. Back to front: dark textured void, a low fog-like pool of mauve-gray light, a floor with contact shadow, and a large beige computer in the lower-right half. Its luminous green-and-blue screen is the strongest color and light source. The object fills roughly half the width and much of the lower two thirds, leaving a dark left-side field for language. Keep any added headline, support and action visually secondary; use the body recipe for supporting copy and text links. The viewport shows the main object, not the later repeated environment or closing ensemble.

**Transfer:** Open a new landing page with a product-relevant object in the same lower-right theatrical composition. If there is no renderable product, photograph a physical metaphor under a warm spotlight and apply the shared analog finish. A text-led page can use a smaller prop while retaining the full-bleed stage and serif language.

**Avoid:** Do not replace the scene with a floating browser card, a centered SaaS headline and two bright pill buttons. Do not reproduce decorative short rules as unreadable navigation.

**Text style:** `body` — STIX Two Text 400 · 16px/1.5

### World expansion

**Observed:** Repeated environment turns the opening's intimate object scale into a dense, diagonal perspective scene. Media fills almost the whole viewport; the analog finish remains continuous.

**Transfer:** Show the reach, multiplicity or context of the new product through a repeated physical system rather than adding a conventional feature grid.

### Graphic interlude

**Observed:** Spectrum ribbon on Ivory graphic field introduces a warm material contrast; Optical curtain later supplies a denser, higher-contrast graphic moment over Blue horizon.

**Transfer:** Use these devices around meaningful content or between substantial visual chapters. Change the artwork's arrangement to suit the story without making empty screens a design feature.

### Surreal emphasis

**Observed:** Perspective collage centers a reflective gold object between rows of receding cutout figures on Charcoal theatre. The visual hierarchy is spatial rather than typographic.

**Transfer:** Translate an important benefit or proof point into an original central symbol and supporting visual cast. Keep added explanations short.

### Tangible closing

**Observed:** Closing object ensemble returns to aged ivory hardware under warm light on charcoal. The objects shift scale and viewing angle while retaining a triangular grouping.

**Transfer:** Close with a physical metaphor for connection or a concrete next step and a readable text action in the surrounding negative space. Retain the theatrical finish rather than switching to a bright subscription panel.

## Page flow

**Storyline:** tangible hook → expanded world → graphic contrast → surreal emphasis → tangible invitation

### An immersive creative-product or studio introduction driven by spatial imagery

1. **Promise** — A single illuminated object establishes a tactile, retro-futurist world.
2. **Context** — A repeated environment expands the object into a larger system.
3. **Narrative contrast** — Warm ivory, muted spectrum bands and an optical curtain interrupt the darker imagery.
4. **Visual emphasis** — A central metallic symbol and receding photographic cutouts supply a surreal focal scene.
5. **Closing invitation** — An ensemble of ivory communication objects returns the story to tangible human connection.

**Transfer:** Borrow the changes in scale, material and visual density, not a fixed number or order of chapters. Use real product language and proof to connect the visual metaphors.

## Writing

Pair the visual eccentricity with restrained, human language. Favor concrete descriptions over technological grandstanding.

**Do not copy:** Do not reuse the Shader name, equipment labels, branded screen content, specific artwork, figures, implied awards or any unverified business claim. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** For new copy, use direct, conversational address and ordinary product nouns; keep self-description brief.
- **Rhythm:** Use short section leads, a single supporting thought and concise action labels so the imagery retains its pacing.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Object inscription | Brief naming built into the physical world rather than a paragraph laid over it. | 1–4 words | “WELCOME TO” |
| Product naming | Use a compact product name as a physical inscription; keep explanatory language separate. | 1 word | “SHADER” |
| Equipment label | A short model-like label adds a believable manufactured detail to a prop. | 1–2 words | “SuperPET” |

**Words and phrasing to use:** concrete object names; plain action verbs; human-scale explanations

**Avoid:** revolutionary; next-generation; industry-leading; unsupported superlatives

**Rules:**

- Treat added writing as a calm explanation of the visual world, not a second spectacle.
- Give text actions readable labels and sufficient contrast even when their visual treatment is minimal.
- Use only substantiated proof; the surreal imagery should not imply a real endorsement or award.

## Do's and Don'ts

### Do

- Keep supporting serif text at 16px/24px, weight 400 and normal tracking.
- Use a full-width stage with 0px side padding for major imagery.
- Make the opening object occupy roughly half of a 1440px-wide composition.
- Carry fine grain and soft highlight bloom across every image medium.
- Keep the spectrum artwork narrow: about 65px of stacked bands within a 900px stage.
- Anchor closing props with a shared light pool and real contact shadows.

### Don't

- Do not use pure white as the warm graphic chapter's default backing; use aged ivory.
- Do not spread saturated blue across every component; keep it concentrated in atmospheric lower fields.
- Do not turn muted spectrum colors into a set of bright action-button fills.
- Do not introduce a system of elevated rounded feature cards into the continuous scenery.
- Do not sharpen and denoise the artwork until the analog material disappears.
- Do not use broad neon outlines where the visual language calls for subtle edge fringing.

## Motion and responsive

### Motion

**Observed:**

- The visual journey changes camera scale, perspective and scene as the reader advances; objects remain staged within a full-screen image plane.

**Transfer:**

- Tie scene changes to meaningful narrative progress rather than independent card entrance animations.
- Provide a static composition preserving each important object and graphic device when real-time rendering is unavailable.

**Unknown:**

- Exact animation timing, easing, interaction targets and scene interpolation are unspecified.

### Responsive

**Observed:**

- The visual composition uses a full-viewport stage.

**Transfer:**

- On narrow screens, preserve the object silhouette and its grounding before preserving desktop camera framing. Move necessary text into a readable independent layer rather than shrinking it with the artwork.
- Use a static alternate framing when a wide perspective collage would make its subjects illegible.

**Unknown:**

- Mobile typography, camera positions and navigation behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
