# Dirt — chrome and creative worlds

## Overview

A white gallery shell gives exuberant moving objects and cinematic work room to perform. Compact grotesk text, tiny monospaced labels and soft rectangular controls keep the surrounding interface almost administrative, while glassy sculpture and full-bleed photography supply the personality. It suits visually ambitious products, creative tools and portfolio-led launches with sparse text and substantial visual proof.

### Essentials

- The opening sells a world before a headline: a 900px white stage carries a horizontal family of circular material studies, with just two 16px support lines near its lower-left edge.
- Text is compact even when the artwork is monumental: regular 40px/1 statement headings contrast with 12px/1 uppercase Chivo Mono section labels; the opening itself uses 16px/1.2 text rather than a giant slogan.
- Controls look like small soft keys, not pills: 27px height, 8px corners, 7px 19px padding and 13px Sequel Sans with -0.01em tracking; the primary key is black and secondary keys are warm off-white.
- The shell stays white and color lives inside the work: black and gray text, 15px outer gutters and no broad accent bands; acid yellow is confined to an active navigation key, while vivid hues occupy the circular opening artwork and media.
- Proof is staged as a gallery rather than boxed features: 700px-wide moving panels, 10–15px gaps and softly clipped corners; pair large environmental scenes with tactile close-ups, using product still-life studies when campaign media is unavailable.
- A monumental transparent word sculpture closes the experience: a 1410×594px artwork below compact footer columns, with white interiors, dark refractive edges and small spectral glints. Rebuild the new product's own short name or monogram in this material; it is a signature device, not ordinary footer text.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Primary text and the compact primary action. |
| Earth ink | `#352e22` | `--color-earth` | text | Selected capability label, an almost-black brown. |
| Muted gray | `#808080` | `--color-muted` | text | Inactive navigation and supporting copy. Black at 50% over white produces this same visible gray. |
| Hairline gray | `#e6e6e6` | `--color-rule` | border | Visible result of 10% black on white in separator lines. The same alpha black is used as a translucent media-label backing. |
| Warm key | `#f2f2ef` | `--color-key` | surface, text, action | Secondary navigation and footer keys; reversed primary-action text. |
| Form gray | `#f7f7f7` | `--color-field` | surface | Enquiry fields and the full-width submit control. |
| Gallery white | `#ffffff` | `--color-canvas` | background, text | Continuous page canvas; reversed media-label text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interior-page navigation | Acid key | `#ebff00` | `--color-active` | action, accent | Only the current navigation destination, on a single 84×27px key. |
| portfolio indexes | Switch ink | `#1c1c1e` | `--color-switch-ink` | text | Selected gallery view text. |
| portfolio indexes | Switch gray | `#b4b4b8` | `--color-switch-muted` | text | Unselected gallery view text. |
| case studies and portfolio indexes | Cool utility gray | `#f3f3f5` | `--color-utility` | surface | Service tags and the gallery view switch. |

## Typography

- **font** — Main headings, body, capability labels and opening copy. Compact grotesk with assertive, closely fitted forms; the regular cut has a visually substantial presence. If unavailable, use **Inter Tight**. Use 400; preserve compact widths and short line heights rather than adding bold. Font stack: "font", "Inter Tight", Arial, sans-serif.
- **Sequel Sans** — Navigation, action keys, footer links and editorial support lines. Clean neutral sans, slightly more relaxed than the main text face. If unavailable, use **Inter**. Use 400 with -0.01em tracking on keys. Font stack: "Sequel Sans", "Inter", Arial, sans-serif.
- **Chivo Mono** — Small uppercase section identifiers and quote attributions. Plain utilitarian monospaced labeling, without exaggerated tracking. Font stack: "Chivo Mono", ui-monospace, monospace.
- **Inter Tight** — Media category labels, case-study service tags and gallery switch labels. Narrow sans for auxiliary interface text. Font stack: "Inter Tight", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | font | 400 | 40px | 1 | normal | Offset introductory statement, capability selector and centered testimonial. |
| contact-line | font | 400 | 29px | 0.95 | normal | Short location-and-reach closing statement. |
| contact-link | font | 400 | 29px | 0.9 | normal | Unboxed email link immediately above the closing statement. |
| invitation | font | 400 | 20px | 1 | normal | Compact conversion paragraph beside the enquiry form. |
| heading | font | 400 | 18px | 1.1 | normal | Editorial titles, project name and proposition, FAQ questions and short narrative subheadings. |
| opening-copy | font | 400 | 16px | 1.2 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | The two short lines at the base of the opening stage; also portrait names. |
| caption | Sequel Sans | 400 | 15px | 1.3 | normal | One-line editorial support beneath a title, rendered in muted gray. |
| action | Sequel Sans | 400 | 13px | 1 | -0.01em | All compact navigation and footer action keys. |
| category | Inter Tight | 400 | 13px | 1 | normal | Translucent media badges and view-switch labels. |
| section-label | Chivo Mono | 400 | 13px | 1 | normal, uppercase, features "blwf", "cv03", "cv04", "cv09", "cv11" | Editorial collection headings and enquiry labels. |
| eyebrow | Chivo Mono | 400 | 12px | 1 | normal, uppercase | Section labels, metadata keys, footer headings and testimonial attribution. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and culture narratives | principle | font | 400 | 32px | 1 | normal | Numbered selectable principles. |
| company narratives | company-lead | font | 400 | 22px | 1.1 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Company introduction and numbered service rows. |
| company narratives | company-body | font | 400 | 15px | 1.4 | 0.01em | Company introduction support and selected principle explanation. |
| case studies | case-body | font | 400 | 14px | 1.2 | normal | Muted case-study narrative and metadata values. |
| case studies | service-tag | Inter Tight | 400 | 11px | 1 | normal | Small service chips in the project metadata column. |

**Notes:**

- Use role and positioning more than font weight to signal hierarchy. Keep measured text weights at 400; let large artwork carry the spectacle.
- The 40px statement is tightly led but not negatively tracked. Only action text and the 22px company lead use -0.01em tracking.
- The closing word sculpture is artwork, not a text-heading recipe; ordinary text never needs to match its scale.

## Layout

**Density:** Airy at section scale and compact within controls: large white intervals separate closely fitted text and image groups.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Tight spacing between capability labels or opening support lines. |
| 10px | Default small group gap, project-grid gutters and navigation-key separation. |
| 12px | Form row gaps and case-study media seams. |
| 15px | Page side gutters, editorial column gaps and image-to-title spacing. |
| 20px | Project title-to-narrative spacing and quote attribution gap. |
| 30px | Section-label-to-content spacing and collection action separation. |
| 50px | Capability-list-to-secondary-action gap. |
| 80px | Vertical padding on case-study text interludes. |
| 100px | Default section bottom breathing room. |
| 120px | Introduction top padding and footer links-to-artwork interval. |
| 150px | Vertical padding above and below a centered testimonial. |

### Containers and grids

- **edge gallery**: side padding 15px. Fluid edge-to-edge shell; at 1440px the usable width is 1410px. Avoid a conventional centered narrow marketing container.
- **offset statement**: 2 columns · gap 10px. A label occupies roughly the left third; a 900px statement occupies the remaining width with 50px extra right breathing room.
- **proof pair**: 2 columns · gap 10px. Equal approximately 700px-wide proof panels; mix occasional narrow portrait media into the same gallery logic.
- **editorial trio**: 3 columns · gap 15px. Three 460px columns for editorial and portrait cards.
- **enquiry split**: 2 columns · gap 15px. Equal 698px columns, left invitation text constrained to 600px and right single-column form.
- **case metadata** (only for case studies): 2 columns · gap 100px. Two 655px columns: title and narrative at left, compact metadata and wrapped service tags at right.
- **quote measure** (only for case studies): max width 666px. Centered testimonial measure, independent of the otherwise edge-aligned shell.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | keys and fields | 8px |
|  | gallery media | 10px |
|  | editorial media | 8px |
| case studies | service chips | 7px |
| portfolio indexes | view switch | 34px |
| portfolio indexes | switch thumb | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| portfolio indexes | selected view | `rgba(0, 0, 0, 0.1) 0px 2px 4px 0px` | Only the white selected thumb inside the gallery view switch. |

### Surfaces

#### Gallery canvas · level 0

**Use:** All ordinary marketing sections.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** White continues between sections without alternating colored bands or elevated containers.

**Transfer:** Let whitespace and the media itself divide narrative chapters.

#### Soft key · level 1

**Use:** Secondary controls and footer links.

**CSS:** `background: #f2f2ef; border-radius: 8px`

**Observed:** A small warm-neutral solid fill, without an outline or drop shadow.

**Transfer:** Keep this material on small functional controls rather than expanding it into giant feature panels.

#### Form wash · level 1

**Use:** Enquiry fields and submit row.

**CSS:** `background: #f7f7f7; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 1px inset`

**Observed:** The wash distinguishes the field; there is no visible inset border.

**Transfer:** Use flat pale fields in a close vertical stack.

#### Media glass label · level 2

**Use:** Category labels over photographs.

**CSS:** `background: rgba(0, 0, 0, 0.1); backdrop-filter: blur(40px); border-radius: 8px`

**Observed:** Local translucency only, never a glass panel behind body copy.

**Transfer:** Place a compact label in the upper-right corner of an image.

## Components

### Fixed navigation

**Use:** Persistent global orientation and contact access.

**CSS:** `position: fixed; height: 67px; z-index: 10; padding: 20px 15px; display: flex; justify-content: space-between; align-items: center; mix-blend-mode: difference`

**Text style:** `action` — Sequel Sans 400 · 13px/1 · tracking -0.01em

**Observed:** Three small keys align left, an independent compact black wordmark sits at the true center and a black contact key anchors the right. The current destination becomes acid yellow on interior pages.

**Transfer:** Keep the center mark independent of unequal left and right control widths.

### Primary key

**Use:** Persistent conversion action.

**CSS:** `background: #000000; color: #f2f2ef; border-radius: 8px; padding: 7px 19px; height: 27px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Sequel Sans 400 · 13px/1 · tracking -0.01em

**Observed:** Text-only compact rectangle, visually equal in scale to the navigation keys.

### Secondary key

**Use:** Collection actions, navigation and footer links.

**CSS:** `background: #f2f2ef; color: #000000; border-radius: 8px; padding: 7px 19px; height: 27px`

**Text style:** `action` — Sequel Sans 400 · 13px/1 · tracking -0.01em

**Observed:** Width follows the text; inactive navigation uses muted gray text, while footer links and collection actions use black.

### Enquiry field

**Use:** Short conversion form.

**CSS:** `background: #f7f7f7; border-radius: 8px; height: 43px; padding-top: 11px; padding-bottom: 12px; padding-left: 12px; box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 1px inset`

**Observed:** Full-name and email rows precede a 136px message area; a matching 43px full-width pale submit row follows. Fields are separated by 12px, with a muted uppercase enquiry label above.

**Transfer:** Keep the form lightweight and embedded in the white page, not inside another card.

### Editorial card

**Use:** Journal, learning or proof-story collections.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 15px`

**Text style:** `heading` — font 400 · 18px/1.1

**Observed:** A 460×405px image with 8px corners leads; a compact title and muted caption sit on white beneath it with roughly 3.5px between text lines. Images use brightness(0.9); a Media badge sits over the image.

**Transfer:** Show an actual story scene, not an icon on a colored square.

### Media badge

**Use:** Short content-type label over imagery.

**CSS:** `background: rgba(0, 0, 0, 0.1); backdrop-filter: blur(40px); color: #ffffff; border-radius: 8px; padding: 7px 19px; height: 27px; position: absolute`

**Text style:** `category` — Inter Tight 400 · 13px/1

**Observed:** Upper-right label, inset about 12px from the image edges.

### Capability selector

**Use:** Compact list beside an associated proof image.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 5px`

**Text style:** `statement` — font 400 · 40px/1

**Observed:** Large one-word labels stack in a narrow central column; the selected label is earth ink and the others are pale gray. A tall 342×397px proof image occupies the right side, with a Secondary key 50px below the labels.

**Transfer:** Use a short set of product capabilities with one contextual visual; preserve the label-to-image relationship.

### Footer directory

**Use:** Contact, social and legal navigation before the final sculpture.

**CSS:** `background: #ffffff; display: flex; flex-direction: column; gap: 120px; padding: 100px 15px 15px`

**Text style:** `action` — Sequel Sans 400 · 13px/1 · tracking -0.01em

**Observed:** A fine rule precedes a sparse top row: copyright at left, then three compact labeled columns across the right half. Soft keys stack with 10px gaps. The transparent word sculpture follows beneath, ending only 15px above the page edge.

**Transfer:** Keep the links small so the final artwork remains the dominant closing gesture.

### FAQ row

**Only for:** company and explanatory pages

**Use:** Objection handling without a wall of prose.

**CSS:** `padding: 16px 0px; border-bottom: 1px solid rgba(0, 0, 0, 0.1); display: flex; align-items: center; justify-content: space-between`

**Text style:** `heading` — font 400 · 18px/1.1

**Observed:** Closed questions form approximately 52px rows in an 813px right-hand column. A plain plus sits at the far right; the section label remains in the empty left column.

### Service chip

**Only for:** case studies

**Use:** Project capability metadata.

**CSS:** `background: #f3f3f5; color: #808080; border-radius: 7px; padding: 5.7px 15.6px; display: flex; align-items: center; justify-content: center`

**Text style:** `service-tag` — Inter Tight 400 · 11px/1

**Observed:** Small wrapped chips sit under the metadata rows with 8px gaps; they are labels rather than primary actions.

### View switch

**Only for:** portfolio indexes

**Use:** Change portfolio presentation.

**CSS:** `background: #f3f3f5; border-radius: 34px; padding: 2px; width: 204px; height: 32px; display: flex; align-items: center`

**Text style:** `category` — Inter Tight 400 · 13px/1

**Observed:** A fixed bottom-centered switch floats above the gallery. A white 100×27px selected thumb has 24px corners and the selected-view shadow; selected text is switch ink, unselected text switch gray.

## Imagery and graphics

### Circular material worlds

**Use:** Signature opening artwork.

**Observed:** A horizontal row of differently sized circular windows floats across a white field, with circles clipped by both viewport edges. Visible studies include polished metallic blobs against teal-to-pink light, a distorted acid-yellow chamber, a blue-violet folded organic form on black, and a coral-pink fluid-striped orb. At desktop their visible diameters are roughly 190–300px; most of the first screen remains white.

**Transfer:** Create a family of product-related material studies rather than a literal feature carousel. Without 3D media, the minimum is several original circular SVG studies with distinct optical materials, not empty circles or stock icons.

**Build:** Use an overflow-hidden horizontal track through the middle of the stage; vary circular masks between 190px and 300px and leave about 90px between centers' outer edges. In one SVG, layer overlapping rounded blob paths with radial white-to-black shading over a teal/pink backdrop. In another, clip bent grid lines to a yellow circle. Add a black-backed folded blue ribbon made from tapered curved paths, and a warm orb built from warped coral and violet bands. Use hard glossy highlights rather than diffuse page-wide glow.

### Transparent closing word sculpture

**Use:** Signature final artwork across every page type.

**Observed:** An inflated block-letter wordmark occupies almost the entire 1410×594px stage. Its front faces are nearly white and transparent; thickness is legible in dark curved edges, narrow silver highlights and occasional pink, blue and green refractions. The white backing merges with the page rather than forming a dark rendering stage.

**Transfer:** Use a short new product name or monogram with wide, heavy geometric forms. If photorealistic glass is unavailable, preserve white faces and a layered refractive outline in SVG; a flat gray word is not an equivalent.

**Build:** Convert heavy rounded letterforms to SVG paths and fit them nearly edge-to-edge in a 1410×594 viewBox. Layer a broad dark translucent edge stroke, a thinner white highlight offset toward the upper-left, and fine cyan/magenta edge fragments offset 1–3px. Keep path interiors white, add a faint lower-right edge shadow and rounded joins. For 3D, use clear bevelled extrusion, a white environment and dark side reflectors rather than opaque chrome fill.

### Cinematic proof gallery

**Use:** Main proof panels and project stories.

**Observed:** Large rounded rectangles show real environments, bodies, objects and finished visual systems with minimal surrounding UI. Full-width 1410×822px panels alternate with 699×855px portrait pairs. Media can be dark and cinematic, or brightly saturated; the surrounding page stays white.

**Transfer:** Pair a wide context view with a tactile close-up or product-use detail. Stage interfaces inside credible device or environmental photography rather than treating every panel as a floating browser window.

### Material-specific project worlds

**Only for:** case-study galleries

**Use:** Project-level visual variety without changing the marketing shell.

**Observed:** One project combines olive and cream identity boards, weathered film, fabric patches, projected marks and dark print scenes. Another uses purple architectural lighting, cream embroidery, warm timber interiors, apparel and device presentations. Their serif and varsity typography belongs inside the project artwork, not the page's interface.

**Transfer:** Let each featured product define its media palette and material language, while keeping captions, margins and controls consistent.

### People and process

**Only for:** company narratives

**Use:** Human credibility and behind-the-scenes texture.

**Observed:** Three tall 460×629px portraits sit against soft pale studio backgrounds with names and tiny mono role lines beneath. A wide seated group portrait follows; later, an edge-clipped strip mixes candid process photos, monochrome social moments and an object still life on red tiles.

**Transfer:** Use naturally posed individual portraits plus candid working scenes. Keep the portrait grid orderly but allow the process strip to feel informal.

### Icons

**Observed:** Iconography is minimal: simple plus marks in FAQ rows and tiny black filled 12×12px glyphs inside 24px case-story controls. Actions otherwise remain text-only.

**Transfer:** Use plain plus/minus geometry for disclosures and small monochrome utility glyphs; do not introduce a colorful icon family.

## Section recipes

How recurring sections are built.

### First screen: Material-world opening

**Observed:** A white 900px stage sits behind Fixed navigation. A line of circular material worlds crosses the middle, leaving broad white space above and below; partial circles at both edges imply a larger world. The compact centered mark and small navigation keys occupy the top 67px. Near the lower-left edge, two opening-copy lines sit 5px apart, the first muted and the second black, with 48px breathing room below. Within the first 900px the entire visual statement, two support lines and top-right Primary key are visible; the 40px introductory statement begins below the fold. There is no central headline-and-button cluster.

**Transfer:** Give a different product an original family of material or product studies and a two-line proposition, not a bigger text hero. Case studies instead open with a single 1410×591px media panel below 70px top clearance, with title and metadata beginning underneath; company narratives use a taller 1410×793px human-led film. Portfolio indexes open directly on a large gallery image.

**Avoid:** Do not replace the white stage with a gradient background, a centered 80px slogan or a row of feature cards.

**Text style:** `opening-copy` — font 400 · 16px/1.2

### Offset declaration

**Observed:** A small eyebrow occupies the left third while a 900px statement wraps tightly across the remaining area. Top padding is 120px and bottom padding 100px; the shell remains Gallery canvas.

**Transfer:** State the product's ambition or audience in one substantial sentence; retain the asymmetric label-to-statement relationship.

**Text style:** `statement` — font 400 · 40px/1

### Selected visual proof

**Observed:** Softly clipped landscape panels form a two-column gallery with approximately 700×452px primary media, 10px seams and occasional narrow portrait inserts. A Secondary key is right-aligned 30px after the gallery; the section has 100px bottom breathing room.

**Transfer:** Use a varied but aligned gallery of real applications or product scenes, with limited captions instead of text-heavy cards.

### Capability and specimen

**Observed:** A left eyebrow identifies the section; Capability selector sits centrally and a tall proof specimen occupies the right quarter. The whole composition is ruled lightly above and below and finishes with 100px lower breathing room.

**Transfer:** Map one short selected capability to one strong product or outcome image; move emphasis between labels without changing the shell.

**Text style:** `statement` — font 400 · 40px/1

### Editorial proof trio

**Observed:** A section-label heading introduces three Editorial cards separated by 15px. Images dominate, titles stay at 18px and support stays at 15px. Category information is carried by Media badges rather than extra text above the cards.

**Transfer:** Use this for helpful content, customer stories or product thinking; keep each card's text to a title and one short line.

### Enquiry and direct contact

**Observed:** A 600px invitation paragraph sits in the left half under an eyebrow; Enquiry fields fill the right half in a 12px vertical stack. After 100px lower breathing room, a separate contact section uses a 29px email link and a closely led location statement with 9px separation.

**Transfer:** Replace the invitation with a short statement of shared ambition and use the minimum fields needed for a conversation. Keep direct contact visible rather than making the form the only route.

**Text style:** `invitation` — font 400 · 20px/1

### Monumental closing signature

**Observed:** Footer directory supplies small functional links above the Transparent closing word sculpture. The artwork spans the usable page width, is 594px tall at desktop and finishes with a 15px lower margin. All page types share this ending.

**Transfer:** End with the new product's own materially expressive name or symbol; keep the directory and sculpture distinct so utility does not compete with spectacle.

### Case-study chapters

**Only for:** case studies

**Observed:** Opening media leads to a split project brief and metadata, followed by alternating immersive media and 80px-padded narrative interludes. A brief can pair left narrative with three right-hand challenge/strategy/solution disclosures. Results remain in 14px muted paragraphs, even when percentages and timeframes are included; they are not giant stat cards.

**Transfer:** Explain what changed, why it changed and what followed, using original proof and factual outcomes. Separate narrative from long uninterrupted visual chapters.

**Text style:** `case-body` — font 400 · 14px/1.2

### Quote and continuation

**Only for:** case studies

**Observed:** A centered 666px-wide quote uses statement type with 150px vertical padding, followed 20px later by an uppercase mono attribution. A three-column related-work gallery uses approximately 463×500px media and 10px seams. One variation places another full-width media scene after the quote and before related work.

**Transfer:** Use an attributable customer statement, then offer visually strong adjacent stories rather than another sales pitch.

**Text style:** `statement` — font 400 · 40px/1

### Numbered principles and objections

**Only for:** company narratives

**Observed:** Numbered 32px principle labels stack at 10px intervals in the left third; one dark selected label is slightly indented and its explanation appears beside it. Portraits and a wide group image provide human punctuation. Later, FAQ rows occupy the right-hand portion of the page, with the eyebrow held at left.

**Transfer:** Use a short set of decision principles or product beliefs, not a generic value-card grid. Keep objections factual and compact.

**Text style:** `principle` — font 400 · 32px/1

## Page flow

**Storyline:** World-building impression → concise positioning → visual proof → selective explanation → invitation or continuation → functional directory and monumental signature.

### Introduce a visually ambitious product or practice

1. **World-building promise** — An almost text-free white stage of circular material studies with a small two-line proposition.
2. **Positioning** — An offset statement identifies audience and ambition.
3. **Visual proof** — A varied project gallery establishes range before the capability selector explains it.
4. **Depth** — Three editorial cards make the thinking tangible.
5. **Invitation** — A compact enquiry split and direct contact line open a conversation.
6. **Closing signature** — Small footer columns precede a giant transparent word sculpture.

**Transfer:** Default landing-page pattern: lead with a memorable visual world, then make the offer legible through concise text and proof.

### Explain a cinematic, media-first product transformation

1. **Product impression** — One wide opening media panel establishes the project's world.
2. **Context** — Small title, proposition, narrative and metadata establish the brief.
3. **Reasoning** — Challenge, strategy and solution rows punctuate immersive media.
4. **Execution and outcome** — Identity, digital experience and results appear as short muted text between long visual chapters.
5. **Social proof** — A centered 40px testimonial names the collaborator below.
6. **Continuation and signature** — Related projects lead to the shared directory and transparent sculpture.

**Transfer:** Use for a transformation whose quality is best demonstrated through motion, environments and artifacts.

### Explain a physical and digital product ecosystem

1. **Product impression** — An atmospheric environmental image opens the story.
2. **Context** — A compact brief and project metadata establish the scope.
3. **System demonstration** — Pairs of material details, people, apparel and interfaces alternate with broad spatial scenes.
4. **Quantified proof** — Outcome percentages, timeframes and rollout facts remain within ordinary muted paragraphs.
5. **Social proof and demonstration** — A large centered quote is followed by one last device presentation.
6. **Continuation and signature** — Three related media tiles precede the shared sculptural ending.

**Transfer:** Use when a product needs to feel coherent across physical, digital and human touchpoints, without inventing a separate stat-card aesthetic.

### Let a collection of projects speak with minimal explanation

1. **Immediate proof** — A wide cinematic project image begins directly beneath the compact navigation.
2. **Breadth** — A sequence of 1410×711px media panels, separated by 20px, shows distinct worlds.
3. **Browsing control** — A bottom-centered Grid/List switch stays small over the media.
4. **Closing signature** — The final project gives way to the same footer directory and transparent word sculpture.

**Transfer:** Use for a visual product catalog or curated portfolio; let each media panel be the chapter rather than adding introductory cards.

### Build trust through people, principles and practical answers

1. **Human impression** — A wide, theatrical team film opens below navigation.
2. **Position and capabilities** — A split introduction leads into numbered service rows.
3. **Human proof** — A three-person portrait grid, selectable principles and a wide group image establish character.
4. **Objection handling** — A right-weighted FAQ list answers practical questions.
5. **Culture texture** — A horizontal candid-image strip adds informal context.
6. **Invitation and signature** — An enquiry split leads to the shared directory and giant glass-like word sculpture.

**Transfer:** Use original people and operating principles to make a company tangible; retain the same white gallery interface.

## Writing

Confident, culturally fluent and conversational, with tactile world-building language rather than technical bravado. Short propositions are direct; longer case narratives explain the relationship between a feeling, a system and a concrete outcome.

**Do not copy:** Do not reuse Dirt's name, wordmarks, artwork, customer identities, project names, quotes, locations or performance claims. Replace all numerical outcomes and experience claims with verified facts belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader, we and our for the makers. Speak to someone already invested in what they are building, not a passive lead.
- **Rhythm:** Pair short, grounded propositions with occasional longer editorial sentences. Labels are one to three words; actions are plain verbs or destinations. Full stops give short lines weight; enthusiasm does not need exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening proposition | A brief welcome followed by a concrete description of the world or offer. | 4–10 words per line | “Welcome to the dirtverse.”<br>“A creative ecosystem for real world brands.” |
| Positioning | Say who the work is for with specific, slightly irreverent audience language. | One substantial sentence | “[Brand] is a global creative studio building for the deeply invested, the sick start-ups and the cool giants.” |
| Product proposition | Name the emotional benefit without listing features. | 4–10 words | “Real stories, masterfully told”<br>“A second home for the sporting spirit” |
| Invitation | Treat the reader's ambition as shared work, then offer a conversation. | One short line or compact paragraph | “Tell us what world you're building.”<br>“If you're all in on what you're building, we are too.” |
| Action | Use recognizable functional language rather than promotional urgency. | 1–3 words | “Contact”<br>“See All Work”<br>“Make an enquiry” |
| Editorial title | Frame a practical insight with an opinionated contrast or outcome. | 4–10 words | “A Brand Universe vs. a Brand Guide”<br>“Making fitness feel human again.” |

**Words and phrasing to use:** building; world; real; connected; felt; all in; cohesive; grounded

**Avoid:** revolutionary solution; unlock limitless potential; seamless synergy; best-in-class; act now; disrupt everything

**Rules:**

- Use one strong metaphor at a time and anchor it in an actual product benefit.
- Write case narratives as problem, decision, application and result; keep metrics inside prose when they belong to that story.
- Keep utility labels literal even when the surrounding editorial voice is expressive.
- Avoid replacing evidence of quality with repeated superlatives.

## Do's and Don'ts

### Do

- Keep the landing opening at 900px desktop height with small 16px copy and a dominant material-world composition.
- Use 15px outside gutters and 10–15px visual seams rather than an oversized centered container.
- Hold the main statement at 40px/1 and use a 12px uppercase mono label beside it.
- Use 8px rounded rectangles and 27px height for compact action keys.
- Let full-width media and tactile portrait pairs carry the color and atmosphere.
- Preserve the 120px pause between footer utility and the monumental transparent signature.
- Keep case-study results in 14px/1.2 prose instead of introducing an unrelated dashboard.
- Use 43px pale fields and 12px form gaps for a low-friction enquiry block.

### Don't

- Do not turn all secondary keys into 9999px pills; their 8px corners are part of the interface character.
- Do not spread acid yellow across section backgrounds; it belongs to one small active navigation key.
- Do not apply the selected-view shadow to editorial cards or gallery panels.
- Do not set all section headings to bold display type; labels and 18px headings deliberately stay compact.
- Do not use serif or varsity lettering from project artwork as the site's navigation font.
- Do not make the transparent closing artwork an opaque metallic slab; its white faces must merge with the page.
- Do not add decorative arrows and icons to every text-only action.
- Do not normalize all proof imagery to the same neutral product mockup; preserve contrasting scenes and materials.

## Motion and responsive

### Motion

**Observed:**

- Video is used throughout the circular opening studies and large proof panels.
- A 2.8s ease-in-out infinite animation is declared on several opening-page elements; the affected visual behavior is not established.
- No matched transition declarations establish button hover or focus animation. A case-study inline-link hover retains 50% black and no underline.

**Transfer:**

- Use moving media to animate the world inside a stable white gallery shell; avoid making the surrounding utility UI compete with it.
- Keep capability selection tied to its specimen image and use a still material study when motion is unavailable.

**Unknown:**

- Precise carousel behavior, scroll choreography, interaction timing and focus-visible treatment are not established.

### Responsive

**Observed:**

- Declared width breakpoints cluster around 810px and 1200px; only the 1440px desktop composition is established.

**Transfer:**

- For narrow layouts, retain edge clipping and varying sizes in the circular world strip rather than squeezing every circle into one screen.
- Stack the offset declaration, enquiry split and portrait pairs when their text measures fail, while preserving small labels and image-first hierarchy.
- Scale the closing sculpture as one coherent artwork rather than wrapping its letters into text lines.

**Unknown:**

- Exact mobile navigation, breakpoint-specific type sizes, mobile media ratios and stacking order are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
