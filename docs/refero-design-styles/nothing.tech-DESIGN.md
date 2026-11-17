# Nothing — machines meet culture

## Overview

An industrial editorial style that pairs delicate serif headlines with utilitarian monospace labels and dot-matrix lettering. Dark charcoal and black stages give reflective hardware, exploded views and closely framed fashion photography an almost exhibition-like presence. It suits design-led hardware and software launches, with spacious visual chapters and compact technical explanations; light editorial and vivid pink culture variants broaden the same mechanical vocabulary.

### Essentials

- Editorial headlines interrupt the machinery: regular-weight NType82 at 48px/1 and 40px/1, normal tracking, paired with Geist paragraphs at 16px/1.3 rather than bold startup typography.
- The opening is an object exhibition, not a headline billboard: a 900px-tall black stage, one dramatically rim-lit object, a centered 576px-wide floating navigation bar and a 56px bottom product dock with a 20px dot-lettered product name.
- Controls feel like equipment labels: uppercase 12px/1.25 mono actions in 40px-high rectangles with 4px corners; 11px/1.1 utility labels sit in 48px-high controls with 6px corners.
- The default page is overwhelmingly achromatic: #181818 chapters, #000000 immersion bands and #040404 closing ground; #ffc700 is reserved for tiny active indicators and a small closing action, not broad decoration.
- Images carry the argument: near-black technical renders and macro material details occupy square or 4:3 panels, with 8px radii and 8px gutters; full-width 16:9 photographic interludes provide human scale. Use a clean isolated photograph with a technical overlay when a 3D model is unavailable.
- Mechanical marks unify the entire page: a faint white dot field, numbered parenthetical captions and a dot-matrix destination stack in the closing section. Rebuild the field with 1px dots spaced about 115px apart and use a dotted lettering substitute for the destination names; these devices persist even without custom artwork.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#ffc700` | `--color-yellow` | action, accent, border, link | Selected states, small pin-like marks and occasional high-priority closing actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black stage | `#000000` | `--color-stage` | background, text | Immersive hardware chapters and black lettering on vivid campaign fields. |
| Near black | `#040404` | `--color-ink` | text, background, action | Light-theme text, light-button text and the closing footer ground. |
| Charcoal canvas | `#181818` | `--color-canvas` | background | Default marketing canvas. |
| Utility frost | `#242424` | `--color-utility` | surface | Visible white at 5% over charcoal; the same translucent control appears darker over the footer. |
| Smoked panel | `#2e2e2e` | `--color-panel` | surface | Visible result of #f4f4f4 at 10% or #3c3c3c at 60% over charcoal; media backing and frosted cards. |
| Frosted chrome | `#3f4040` | `--color-chrome` | surface | Visible #595a5a at 60% over charcoal in navigation and sticky product chrome; underlying imagery changes its appearance. |
| Raised media grey | `#4f4f4f` | `--color-panel-strong` | surface | Visible #f4f4f4 at 25% over charcoal for larger split-media frames. |
| Graphite rule | `#595a5a` | `--color-rule` | border, text | 0.5px specification rules and small light-theme captions. |
| Technical grey | `#9b9d9d` | `--color-muted` | text | Specification values and secondary detail. |
| Soft white | `#d1d1d1` | `--color-soft-text` | text | Visible white at 80% over charcoal for accordion labels and secondary panel copy. |
| Pale grey | `#d8d9d9` | `--color-body` | text | Main descriptive text on charcoal. |
| White | `#ffffff` | `--color-white` | text, action, accent | Headings, dot graphics and default light action fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture campaigns | Culture pink | `#ff42ad` | `--color-pink` | background | Full-bleed culture manifesto field, behind black text. |
| light editorial proof tiles | Pale stat tile | `#ededed` | `--color-stat` | surface | Visible #595a5a at 5% over editorial paper. |
| light product campaigns | Light canvas | `#f4f4f4` | `--color-paper` | background | Light product campaign canvas. |
| company and editorial stories | Editorial paper | `#f5f5f5` | `--color-editorial-paper` | background | Light editorial canvas. |

## Typography

- **NType82** — Headlines and light editorial prose. A slender editorial serif with compact proportions and visible stroke contrast; the visual counterpoint to engineering graphics. If unavailable, use **Libre Caslon Text**. Use 400; preserve compact line lengths and normal tracking. Font stack: "NType82", "Libre Caslon Text", Georgia, serif.
- **Geist Variable** — Default product explanation and specification text. Clean, compact contemporary grotesk, primarily regular weight. Font stack: "Geist Variable", Arial, sans-serif.
- **Geist Mono Variable** — Product actions, tabs and specification headings. Even-width technical lettering, usually uppercase for short labels. Font stack: "Geist Mono Variable", ui-monospace, monospace.
- **Ndot** — Product names, chapter numbers and closing destination links. Dot-matrix lettering with regular and bold cuts; small names can look pixel-like rather than fully circular. If unavailable, use **DotGothic16**. Use 400 and retain open spacing between dotted letterforms. Font stack: "Ndot", "DotGothic16", monospace.
- **LatteraMonoLL** — Small navigation, service and technical captions. Compact utilitarian monospaced letters with an equipment-panel feel. If unavailable, use **IBM Plex Mono**. Use 400 at the specified small sizes. Font stack: "LatteraMonoLL", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | NType82 | 400 | 48px | 1 | normal | Major section leads, centered product promise and large proof numerals. |
| heading | NType82 | 400 | 40px | 1 | normal | Alternating image-and-copy chapters. |
| destination | Ndot | 400 | 40px | 1 | normal, uppercase | Large centered closing navigation links. |
| card-heading | NType82 | 400 | 24px | 1.1 | normal | Feature captions below imagery. |
| product-name | Ndot | 700 | 20px | 1 | normal, uppercase | Product dock and related-product names. |
| body | Geist Variable | 400 | 16px | 1.3 | normal | Product support lines and explanatory paragraphs. |
| accordion-label | Geist Mono Variable | 400 | 16px | 1.25 | normal | Technical accordion headers; uppercase category names, sentence case for questions. |
| chapter-number | Ndot | 700 | 16px | 1 | normal, uppercase | Parenthetical numbers pinned immediately outside feature images. |
| detail | Geist Variable | 400 | 14px | 1.4 | normal | Specification values and expanded practical information. |
| action | Geist Mono Variable | 400 | 12px | 1.25 | normal, uppercase | Buttons, inline directional links and technical tabs; underline inline links, not filled button labels. |
| utility | LatteraMonoLL | 400 | 11px | 1.1 | normal, uppercase | Service controls and small peripheral labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and editorial stories | editorial-intro | NType82 | 400 | 43.2px | 1.074 | normal | Multi-line statement spanning roughly seven columns. |
| company and editorial stories | editorial-subhead | NType82 | 400 | 24px | 1.333 | normal | Modest section titles above longer serif prose. |
| culture campaigns | culture-body | Ndot | 700 | 24px | 1.333 | normal | Centered manifesto prose in a narrow column. |
| company and editorial stories | editorial-body | NType82 | 400 | 20px | 1.2 | normal | Narrative paragraphs in narrow editorial columns. |
| light editorial proof tiles | stat-caption | LatteraMonoLL | 400 | 12px | 1.25 | normal, uppercase | Short centered captions below oversized proof numerals. |

**Notes:**

- Keep regular serif headings distinct from the sans-serif product paragraphs: hierarchy comes from family, scale and placement, not heavy weights or compressed tracking.
- Use normal tracking throughout. The small monospace labels are compact and functional, not widely letterspaced luxury captions.
- The first-screen product name is deliberately only 20px. The 48px editorial promise belongs to the next chapter rather than competing with the opening object.

## Layout

**Density:** Airy visual chapters with compact captions and technical controls.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Most chapter gaps, padding and component dimensions follow this rhythm.
- **horizontal step** 16px, horizontal — Inner padding and editorial layout spacing; the image grid uses half-step gutters.

| Value | Use |
| --- | --- |
| 8px | Media gutters, outer product-page inset and small control gaps. |
| 10px | Feature-title to explanatory-copy gap and inline directional-link spacing. |
| 16px | Heading to support, image to caption and panel padding. |
| 24px | Tab-to-heading gap and closing destination spacing. |
| 32px | Support-to-cinematic-media gap and footer side inset. |
| 40px | Heading-to-grid or heading-to-accordion separation. |
| 80px | Closing navigation-to-service-stack separation. |
| 96px | Staggered editorial-grid row gaps and text-card internal breathing room. |
| 144px | Default desktop chapter separation and black immersion-band padding. |
| 160px | Company and editorial story section spacing. |

### Containers and grids

- **Product grid**: 12 columns · gap 8px · side padding 8px. Full-width desktop grid; three features each span four columns, paired media span six, and offset five-column squares support asymmetrical storytelling.
- **Centered heading**: max width 768px · side padding 8px. Centered major headings and introductory support lines.
- **Reading column**: max width 576px · side padding 8px. Technical specs and FAQs, centered with large empty margins.
- **Split chapter**: max width 1186px · 2 columns · gap 120px. An inset square image around 589px wide paired with a roughly 469px text column; alternate sides between chapters.
- **Service stack**: max width 320px · gap 2px. Narrow centered closing service controls.
- **Editorial grid** (only for company and editorial stories): 12 columns · gap 16px · side padding 16px. Wide statement followed by narrow text columns, overlapping photography and small proof tiles.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and panels | 8px |
| Utility controls | 6px |
| Product actions | 4px |

## Surfaces and depth

### Surfaces

#### Charcoal canvas · level 0

**Use:** Default product and software marketing ground.

**CSS:** `background: #181818; color: #ffffff`

#### Black immersion band · level 0

**Use:** Large object demonstrations and material chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flush full-width ground changes rather than floating cards.

**Transfer:** Use the darker band to isolate a different mode of demonstration.

#### Media frame · level 1

**Use:** Square and 4:3 feature media.

**CSS:** `background: rgba(244, 244, 244, 0.1); border-radius: 8px; overflow: hidden`

**Observed:** Finished artwork commonly has its own black backing. Larger split media also uses a 25% version of the same pale fill.

**Transfer:** Let the artwork define the visible backing; keep the frame restrained.

#### Smoked glass panel · level 1

**Use:** Text proof cards, related products and compact mid-story calls.

**CSS:** `background: rgba(60, 60, 60, 0.6); backdrop-filter: blur(45px); border-radius: 8px`

**Observed:** Low-contrast grey glass without a drop shadow.

**Transfer:** Keep content readable through muted backing rather than a conspicuous outline.

#### Chrome glass · level 2

**Use:** Floating navigation and sticky product controls.

**CSS:** `background: rgba(89, 90, 90, 0.6); backdrop-filter: blur(45px); border-radius: 8px`

#### Closing ground · level 0

**Use:** All page endings.

**CSS:** `background: #040404; color: #ffffff`

#### Light campaign canvas · level 0

**Only for:** light product campaigns

**Use:** Bright product renders and saturated photography.

**CSS:** `background: #f4f4f4; color: #040404`

#### Editorial paper · level 0

**Only for:** company and editorial stories

**Use:** Long-form serif storytelling.

**CSS:** `background: #f5f5f5; color: #040404`

#### White frost · level 2

**Only for:** light product and culture campaigns

**Use:** Floating sign-up panels and culture-question cards.

**CSS:** `background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(45px); border-radius: 8px`

#### Culture field · level 0

**Only for:** culture campaigns

**Use:** A concentrated text-led manifesto.

**CSS:** `background: #ff42ad; color: #000000`

## Components

### Floating navigation

**Use:** Global navigation above visual storytelling.

**CSS:** `max-width: 576px; min-height: 48px; background: rgba(89, 90, 90, 0.6); backdrop-filter: blur(45px); border-radius: 8px; overflow: hidden`

**Observed:** Centered within an 80px fixed header, inset 8px from the top. A small menu mark sits left; a dotted wordmark occupies the center. Light variants use White frost.

**Transfer:** Use a compact identity mark and sparse menu control, not a full desktop link row.

### Product dock

**Use:** Persistent product identity and local navigation.

**CSS:** `background: rgba(89, 90, 90, 0.6); backdrop-filter: blur(45px); padding: 8px 8px 8px 16px; min-height: 56px; border-radius: 8px`

**Text style:** `product-name` — Ndot 700 · 20px/1 · uppercase

**Observed:** Bottom-sticky strip, 8px from the viewport edges. Name at left; underlined overview/specification links, a vertical divider and a compact variant selector at right.

**Transfer:** Keep local information distinct from the global navigation.

### Light action

**Use:** Play, watch and chapter-transition actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #ffffff; color: #040404; padding: 12px 16px; height: 40px; border-radius: 4px`

**Text style:** `action` — Geist Mono Variable 400 · 12px/1.25 · uppercase

**Observed:** Short label followed by a small play triangle or directional chevron; film actions are centered directly on the image. Related-product actions use a smaller 32px-high variant with 8px 12px padding and 11px mono labels.

### Signal action

**Use:** A high-priority late-story action or download.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #ffc700; color: #040404; padding: 12px 16px; height: 40px; border-radius: 4px`

**Text style:** `action` — Geist Mono Variable 400 · 12px/1.25 · uppercase

**Observed:** A small bright rectangle against the dark page, with a directional icon. A compact download variant is 32px high with 8px 12px padding.

**Transfer:** Concentrate the yellow emphasis on the action that resolves the story.

### Directional text link

**Use:** Jump from an overview to a capability chapter.

**CSS:** `display: flex; align-items: center; gap: 10px; color: #d8d9d9; text-decoration: underline`

**Text style:** `action` — Geist Mono Variable 400 · 12px/1.25 · uppercase

**Observed:** Text and a separate tiny right chevron, without a background.

### Technical accordion

**Use:** Specifications, practical information and FAQs.

**CSS:** `width: 100%; max-width: 576px; border-top: 0.5px solid #595a5a`

**Text style:** `accordion-label` — Geist Mono Variable 400 · 16px/1.25

**Observed:** The first row has no top rule. Each trigger is 52px high with 16px vertical padding, label left and chevron right. Open content uses detail text with 16px paragraph spacing and 32px bottom padding; an image can lead the content.

**Transfer:** Group information by decision or question instead of displaying a dense uninterrupted table.

### Related product card

**Use:** A small family of next destinations near the ending.

**CSS:** `display: flex; flex-direction: column; gap: 16px; background: rgba(60, 60, 60, 0.6); backdrop-filter: blur(45px); border-radius: 8px; padding: 16px; overflow: hidden`

**Text style:** `product-name` — Ndot 700 · 20px/1 · uppercase

**Observed:** Large square isolated object above a bottom row that places a dotted name left and compact white action right. Two cards occupy two thirds of the available row, leaving an intentional empty third.

**Transfer:** Keep the image dominant and the metadata to a single bottom row.

### Closing destination link

**Use:** The monumental but compact navigation stack at every page ending.

**CSS:** `display: block; color: #ffffff; text-align: center`

**Text style:** `destination` — Ndot 400 · 40px/1 · uppercase

**Observed:** Five centered dot-matrix destinations separated by 24px, not a conventional multicolumn sitemap.

### Service control

**Use:** Support, newsletter and locale/preferences actions in the closing section.

**CSS:** `display: flex; align-items: center; justify-content: space-between; width: 320px; height: 48px; padding: 16px; background: rgba(255, 255, 255, 0.05); backdrop-filter: blur(45px); border-radius: 6px; color: #ffffff`

**Text style:** `utility` — LatteraMonoLL 400 · 11px/1.1 · uppercase

**Observed:** Left-aligned label with a small right-aligned symbol. Controls are stacked with only 2px between them.

### Proof tile

**Only for:** light editorial proof tiles

**Use:** A small pair of quantified proof points beside narrative text.

**CSS:** `display: grid; justify-content: center; max-width: 200px; aspect-ratio: 1; padding: 32px; background: rgba(89, 90, 90, 0.05); backdrop-filter: blur(45px); border-radius: 6px; text-align: center`

**Text style:** `display` — NType82 400 · 48px/1

**Observed:** A centered serif number with a stat-caption beneath it, separated by 6px; paired tiles have a 16px gap. Fine registration crosses mark opposite outside corners.

**Transfer:** Use two truthful, concise metrics; retain the restrained tile scale rather than turning them into giant KPI banners.

### Campaign sign-up

**Only for:** light product campaigns

**Use:** Persistent conversion within a photo-led campaign.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 16px; background: #040404; color: #ffffff; border-radius: 6px`

**Text style:** `utility` — LatteraMonoLL 400 · 11px/1.1 · uppercase

**Observed:** A full-width dark action inside a bottom-centered White frost panel capped at 576px. The expanded panel includes product name, three tiny feature lines, a thumbnail and a variant selector; the compact version retains selector and action.

**Transfer:** Use this rather than the wide Product dock for a lightweight registration-focused campaign.

## Imagery and graphics

### Rim-lit object stage

**Use:** Opening and immersive demonstration scenes.

**Observed:** A single dark object floats without a plinth against black. Cool silver edge light reveals curves, glass and machined metal while most surfaces remain dark; the object occupies roughly the middle third of the width and much of the lower two thirds of the first screen.

**Transfer:** Use a high-quality isolated product photo with a darkened body and carefully masked highlights. For nonphysical products, stage one composed interface artifact rather than a collage of dashboard cards.

### Engineering point graphics

**Use:** Technical proof and explanatory media; a signature complement to the object photography.

**Observed:** White dotted waves, orbit-like contours and dotted leader lines wrap around the product. Tiny bracketed monospace callouts identify material or performance details. Graphics remain monochrome except for small selected labels.

**Transfer:** Illustrate one real mechanism or measurable benefit with a restrained point diagram. A flat vector silhouette with two annotated details is the minimum viable alternative to a complex render.

**Build:** Use SVG circles of 1px–2px radius sampled along two or three open elliptical or waveform paths around a central cutout. Vary point spacing to create broken contours, mask paths behind the object, and add 1px dashed right-angle leader lines ending in small outlined squares. Set short bracketed labels in 12px mono white at reduced opacity.

### Ambient dot field

**Use:** Persistent mechanical texture across dark and light page grounds, including the ending.

**Observed:** Very faint isolated white pinpoints lie on a broad regular lattice. The pattern is far less dense than the technical diagrams.

**Transfer:** Carry this texture across section transitions without letting it compete with text or product edges.

**Build:** Place a pointer-events:none overlay inset 32px. Use radial-gradient(circle, rgb(255,255,255) 1px, rgba(0,0,0,0) 1.5px), background-size 114.7px 114.7px, background-position -56.3px -56.3px, opacity 0.3 and mix-blend-mode:difference. Keep typography and actions above it.

### Material macros

**Use:** Feature grids and split editorial panels.

**Observed:** Extreme close-ups crop beyond the object boundary: brushed metal arms, glass rims, soft cushions and tactile switches. Dark grey gradients reveal the finish without decorative color. Square and 4:3 compositions dominate.

**Transfer:** Photograph the seam, control or material that proves the claim, rather than reusing the same complete product view in every panel.

### Human cinematic interludes

**Use:** Full-width relief between technical chapters.

**Observed:** Fashion-like studio portraits use sculptural poses, close head-and-shoulder framing, dark clothes and cool grey backgrounds. Documentary studio footage introduces warm pin lights and real equipment without changing the overall low-key tone.

**Transfer:** Choose people actively using the product in a visually controlled environment; use one wide 16:9 frame rather than a tiled stock-photo mosaic.

### Bright campaign montage

**Only for:** light product campaigns

**Use:** Image-led product launches with a persistent registration panel.

**Observed:** Small floating square editorial thumbnails surround an isolated product on a pale cool ground. Later full-screen portraits and three-up motion portraits use saturated yellow, blue and pink photographic backdrops. Small serif captions and uppercase mono category labels sit beneath thumbnails.

**Transfer:** Art-direct a limited set of vivid photo backdrops and use product cutouts to connect them; keep the surrounding interface neutral.

### Pinned editorial collage

**Only for:** company and editorial stories

**Use:** Image-and-prose narratives.

**Observed:** Portraits, documentary event photography and videos overlap at slight rotations. Yellow pin-like dots, fine registration crosses, parenthetical chapter numbers and occasional barcode marks give a printed contact-sheet quality.

**Transfer:** Combine original documentary images with the same careful imbalance. Use two overlapping frames rather than a decorative collage of unrelated assets.

**Build:** Arrange two rectangular images with about a 32px overlap; rotate the upper frame by a few degrees. Add a 12px yellow circle near one corner and 1px horizontal/vertical 14px registration strokes outside opposing corners. Keep effects flat, without drop shadows.

### Icons

**Observed:** Predominantly tiny solid SVG symbols at 16px or 20px: chevrons, arrows, play and service marks. Larger 24px symbols are rare. Color follows nearby white or near-black text; fine 1px outline symbols occur in the light editorial interface.

**Transfer:** Use compact geometric symbols with no colored icon containers. Preserve generous image space by keeping navigation and service icons subordinate.

## Section recipes

How recurring sections are built.

### First screen: Object exhibition opening

**Observed:** The first 900px is an almost-black product gallery. From back to front: Black immersion band, Ambient dot field, one rim-lit front-facing object, a left vertical thumbnail rail, Floating navigation and Product dock. The object is centered and roughly a third of the page width, descending through the lower two thirds of the view. The top navigation is 576px wide and 48px tall, within an 80px header. The rail uses 64px square thumbnails with 8px gaps and a thin yellow selected edge; only a short scrollable subset is visible. The bottom 56px dock spans the width with 8px insets and carries the 20px dotted product name, overview/specification links and variant control. No oversized editorial headline or support paragraph overlays this first stage. The 48px serif promise and directional action begin below the fold, after 144px of separation.

**Transfer:** For another product, give its silhouette the same solitary stage and use a darkened isolated photograph if a 3D object is unavailable. Keep identity in the dock and move the full promise into the next chapter. Software launches instead open with a centered 48px serif name, one 16px support line and a full-width film frame with a Light action. Light campaigns use floating thumbnail navigation around the product and Campaign sign-up; editorial stories use a seven-column serif statement; culture campaigns use centered dotted title art and narrow prose.

**Avoid:** Do not replace the opening with a conventional two-column hero, a giant sales headline, a row of colorful feature badges or a stack of competing conversion buttons.

**Text style:** `product-name` — Ndot 700 · 20px/1 · uppercase

### Centered promise and cinema

**Observed:** A centered display heading within 768px, body support 16px below, then a full-width 1440px by 810px photograph or film frame after 32px. A Light action is centered over playable imagery. Standalone object demonstrations can replace the film while keeping the centered heading pair.

**Transfer:** State one benefit and show it at cinematic scale; use a single purposeful scene rather than a multi-image gallery.

**Text style:** `display` — NType82 400 · 48px/1

### Staggered numbered overview

**Observed:** A display heading occupies the upper left of a 12-column Product grid. A large square feature starts higher at right; another sits lower at left; a further feature settles nearer the middle below. Media frames are around 589px wide, with chapter-number labels pinned just outside their top-left edge, 16px image-to-title separation and 10px title-to-link separation. Row gaps expand to 96px.

**Transfer:** Use staggered scale and parenthetical numbering for a small set of distinct capabilities. Reorder the placements to suit the new story without making every chapter a uniform grid.

**Text style:** `display` — NType82 400 · 48px/1

### Alternating inset chapter

**Observed:** An inset square Media frame and a vertically centered text column share a roughly 1186px composition. Heading uses heading, support is 16px below, and optional technical tabs sit 24px above. Reverse image and text in the next chapter.

**Transfer:** Pair a mechanism image with a tightly edited explanation; vary sides to create editorial movement.

**Text style:** `heading` — NType82 400 · 40px/1

### Feature proof grid

**Observed:** A display heading and 16px support line precede two or three Media frames by 40px. Three columns are about 469px wide with 8px gutters; two columns use 708px-wide 4:3 images. Feature titles follow after 16px and body copy after 10px. Text stays outside the painted image frame.

**Transfer:** Use one consistent aspect ratio within each row, and make every image prove a different point.

**Text style:** `card-heading` — NType82 400 · 24px/1.1

### Edge-to-edge split proof

**Observed:** A near-black rounded panel spans 1424px, divided into two 712px halves. A display headline anchors the upper left, a short paragraph anchors the lower left, and an enormous cropped material or interface image fills the right half. A compact Signal action can sit below the left copy.

**Transfer:** Use the vertical separation between headline and support as part of the composition; select one close-up whose scale justifies half the page.

**Text style:** `display` — NType82 400 · 48px/1

### Practical reading column

**Observed:** A display heading leads a centered 576px Reading column; Technical accordion begins 40px below. One expanded item can contain a photograph or a compact table, with remaining rows collapsed. This format serves specifications, release guidance and questions.

**Transfer:** Let the visual story resolve into organized practical information without switching to a busy white comparison table.

**Text style:** `display` — NType82 400 · 48px/1

### Product-family closing call

**Observed:** A display title leads Related product cards; two cards align left in a three-column area. A centered Signal action follows with generous separation. This precedes the darker closing ground.

**Transfer:** Offer a small number of relevant alternatives or next steps; preserve the empty space beside them.

**Text style:** `display` — NType82 400 · 48px/1

### Instrument-panel ending

**Observed:** Closing ground fills at least 900px at desktop. The center stack starts with Closing destination links, 24px apart, followed after 80px by the 320px Service stack. Footer padding is 112px 32px 32px. Tiny utility/legal links sit along the bottom left and social links along the bottom right. Ambient dot field continues across the ground. The light product variant adds a compact disclaimer control above the destination stack.

**Transfer:** Finish any page type with this distinctive centered destination-and-service composition, adapting the number and names of destinations to the project.

**Text style:** `destination` — Ndot 400 · 40px/1 · uppercase

### Light editorial narrative

**Only for:** company and editorial stories

**Observed:** A 43.2px serif statement occupies seven columns near the top. Subsequent numbered sections pair a narrow 24px title and 20px prose column with offset Pinned editorial collage imagery. Proof tiles sit beneath prose; later media can become a three-up gallery or paired location images with underlined text links.

**Transfer:** Tell the organization's own beliefs through tangible scenes, measured proof and editorial pacing rather than generic value cards.

**Text style:** `editorial-intro` — NType82 400 · 43.2px/1.074

### Culture manifesto

**Only for:** culture campaigns

**Observed:** A full Culture field carries centered black dotted title artwork, then 24px/32px dot-lettered prose in a 544px column. Paragraph groups have 44px breathing room. White frost question cards below are about 54px high with 16px padding and 8px gaps, followed by a plain underlined terms link and the shared dark ending.

**Transfer:** Use this concentrated typographic variant for a genuinely expressive campaign; replace the subject with its own provocative invitation rather than importing product-page technical grids.

**Text style:** `culture-body` — Ndot 700 · 24px/1.333

## Page flow

**Storyline:** Object or idea → clear promise → visual capability proof → material or human credibility → practical detail → focused next step → centered destination ending.

### Flagship product landing page

1. **Product demonstration** — A solitary object gallery with persistent local controls.
2. **Promise** — A centered serif benefit above an exploded or isolated object view.
3. **Capability chapters** — Staggered numbered overview, alternating square chapters and compact image grids.
4. **Credibility** — Cinematic human scenes, material close-ups and quantified durability proof.
5. **Objection handling** — Narrow technical accordion after performance summaries.
6. **Next step** — Related-product cards and a small yellow action, then the shared centered ending.

**Transfer:** Choose the chapters that prove the new product's value; preserve changes in visual scale rather than the original section count.

### Photo-led product campaign

1. **Discovery** — Pale product stage surrounded by small captioned visual entry points.
2. **Promise** — Short product story over a dramatic full-screen portrait.
3. **Demonstration** — Alternating clean product stills and vivid full-screen human imagery.
4. **Conversion** — A persistent compact registration panel expands to show product details near the end.
5. **Closing navigation** — Disclaimer control followed by the shared dark destination and service composition.

**Transfer:** Use a smaller textual footprint when photography is the campaign's main argument.

### Culture invitation

1. **Invitation** — Dotted headline artwork on a saturated field.
2. **Motivation** — Centered manifesto paragraphs with deliberate gaps.
3. **Participation detail** — Practical conditions in frosted question cards, followed by a terms link.
4. **Closing navigation** — The shared dark destination and service composition.

**Transfer:** Center the new campaign's voice and participation mechanism rather than requiring any particular cultural subject.

### Company editorial story

1. **Positioning** — A broad serif statement on light paper.
2. **Belief** — Numbered prose paired with a portrait.
3. **Proof** — Small paired numerical tiles beside documentary imagery.
4. **Design credibility** — Narrative text gives way to a visual gallery.
5. **Human connection** — Paired real-world destination images and practical links.
6. **Closing navigation** — The shared dark destination and service composition.

**Transfer:** Use original organizational evidence and settings, retaining narrow prose and uneven image placement.

### Software release landing page

1. **Promise** — Centered serif title and support above a full-width film.
2. **Capability chapters** — Three-up interface illustrations alternate with a staggered numbered feature chapter.
3. **Practical detail** — Release and installation information in a centered accordion.
4. **Conversion** — Large split panel with a cropped device and small yellow download action.
5. **Objection handling** — Narrow FAQ before the shared dark ending.

**Transfer:** Show the software as legible visual artifacts, while keeping the page-level type and controls independent of the demonstrated UI.

## Writing

Confident, tactile and culturally alert. The language shifts between terse benefit statements, concrete engineering explanations and occasional mischievous exaggeration, without becoming a generic innovation manifesto.

**Do not copy:** Do not reuse the brand's names, logos, proprietary product naming, collaborator names, quotations, campaign copy or unsupported performance claims and numbers. Substitute the new project's own identity and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for experience and controls, we for design decisions, and direct product naming for factual specifications.
- **Rhythm:** Headlines are usually short sentence-case fragments. Support lines are often one sentence; technical paragraphs use two or three compact sentences. Action labels are brief verbs or directional phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Benefit headline | A direct sensory or functional promise rather than an abstract category claim. | 3–8 words | “Hear more details with three drivers”<br>“More control, more intention” |
| Character headline | A brief, slightly audacious statement followed by specific support. | 2–5 words | “Ludicrously over-engineered” |
| Support line | Translate the headline into a concrete mechanism or use benefit. | 8–24 words | “Full immersion with Dynamic Spatial Audio and upgraded head tracking.” |
| Technical explanation | Material or mechanism first, then its useful consequence; include a qualified number only when warranted. | 1–3 short sentences | “Aluminium carved from a single block. And new titanium alloy arms are 45% lighter than Headphone (1).” |
| Action | A plain verb or explicit destination, visually uppercase. | 1–4 words | “Go to design”<br>“Download” |
| Culture invitation | Conversational, provocative and concrete, with an occasional abrupt sentence. | Short paragraphs with isolated punch lines | “Want to throw your own party?” |

**Words and phrasing to use:** machined; tactile; engineered; shape; control; details; designed for; up to; clearer; more personal

**Avoid:** revolutionary ecosystem; seamless solutions; unlock limitless possibilities; game-changing; enterprise-grade synergy

**Rules:**

- Lead with an experience, then explain the physical or software mechanism that makes it possible.
- Keep technical qualifications close to the claim; superscript notes can support specific performance statements.
- Write labels as actual destinations or actions, not persuasion slogans.
- Allow one playful headline to interrupt factual chapters; do not make every paragraph theatrical.

## Do's and Don'ts

### Do

- Keep the serif display at 48px/1, weight 400, with normal tracking.
- Use 8px product-grid gutters even when images become very large.
- Maintain the contrast between 144px chapter breathing room and compact 10px caption gaps.
- Keep image and panel corners at 8px, action corners at 4px and service corners at 6px.
- Give mechanical diagrams white point contours and small monospace annotations.
- Carry the faint dot field through the dark closing composition.
- Use 16px Geist prose for product explanations and reserve longer serif prose for the light editorial variant.
- Retain a focused yellow action or active mark instead of spreading emphasis evenly.

### Don't

- Do not turn compact 40px actions into pill-shaped 56px buttons.
- Do not apply the culture campaign's pink ground to ordinary technical chapters.
- Do not use white cards with deep shadows as the default on the charcoal canvas.
- Do not set the whole site in a geometric sans; the serif-versus-mono tension is central.
- Do not enlarge technical labels into oversized decorative captions; utility text is 11px and directional text is 12px.
- Do not put each feature's text inside a rounded box when the image-and-caption construction uses text on the page ground.
- Do not replace sparse dotted technical contours with colorful blob gradients.
- Do not turn the closing destination stack into a conventional four-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- The visual experience includes staged object views, media playback controls, carousels and accordion disclosures; the product dock persists while scrolling.
- No action transition or animation timing was resolved as a matched declaration.

**Transfer:**

- Let changes in object viewpoint or technical annotation carry the motion language rather than animating every text block.
- Keep a strong still composition for each scene so the dark object and its labels remain intelligible when motion is stopped.

**Unknown:**

- Exact scroll choreography, durations, easing and reduced-motion behavior.

### Responsive

**Observed:**

- The desktop composition uses a 12-column grid, 576px floating navigation and full-width local product dock.
- Class structures distinguish smaller layouts, but numeric breakpoint rules are not available.

**Transfer:**

- On narrow screens, keep the product stage dominant and reduce the dock to a compact bottom-centered panel rather than squeezing every desktop control into one line.
- Turn three-up feature media into a horizontal snap sequence or a single column; keep 8px gutters and external captions.
- Stack split editorial chapters without losing the distinction between large visual and narrow explanation.

**Unknown:**

- Exact mobile type sizes, breakpoint widths and mobile stage dimensions.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
