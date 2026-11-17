# Magnetism — attraction in oversized type

## Overview

An art-directed, light-grey editorial style where an enormous grotesk identity meets almost miniature, widely spaced labels. The monochrome framework leaves the emotional work to cinematic portraits, tactile product renders and saturated campaign worlds. It suits image-led products and cultural or premium services, with dense visual proof balanced by exceptionally sparse text and a spacious graphic sign-off.

### Essentials

- Identity behaves like architecture: a single-line vector word sculpture spans 1312px within 64px side margins, with a 130px visible cap height at a 1440px viewport.
- The opening is an editorial threshold rather than a sales panel: a 429px-wide uppercase introduction at 8px/1.5 with 0.22em tracking, right-weighted navigation, faint sweeping contours and the first full-bleed image beginning at 650px.
- Actions are tiny typographic brackets, not filled buttons: 10px capitals, 0.22em tracking, inward-facing triangles and 14px left/11.8px right padding; the contact action uses weight 500.
- Color belongs to the work: the canvas stays #ececec with #222222 rules and text, while 650px-high photographic fields occupy nearly all of each showcase row. Keep the interface monochrome except for a pinprick red point in the closing emblem.
- Proof is catalogued under the image: 43px caption rails with 1px dark rules, 16px vertical and 32px horizontal padding, category left and identity right; alternate full-width media with edge-to-edge pairs.
- A graphic magnetic field and a letter-and-arrow emblem carry the personality: hairline elliptical contours spread behind the opening, and a 183px by 175px glyph matrix anchors the spacious closing scene. Rebuild both with original letters and geometry; use an art-directed product still if no campaign imagery exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Emblem point | `#ce0037` | `--color-signal` | accent | A single tiny red point within the letter-and-arrow closing emblem, never a button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#222222` | `--color-ink` | text, border, accent, link | Primary typography and strong 1px editorial rules. |
| Charcoal identity | `#343434` | `--color-identity` | text | Oversized identity and static navigation; secondary prose uses this hue at 0.5 opacity over the canvas, visibly about #909090. |
| Secondary navigation | `#aaaaaa` | `--color-muted` | text, link | Secondary navigation ink before difference blending against imagery. |
| Soft rule | `#cccccc` | `--color-rule` | border, accent | Archive separators, heading underlines, footer baseline and progress tracks. |
| Gallery grey | `#ececec` | `--color-canvas` | background, surface | Continuous light-grey page, caption rails and footer. |

## Typography

- **TT Hoves Pro Trial** — Section titles, interface labels, actions and metadata. Unadorned geometric grotesk with open, extensively tracked capitals; regular and medium cuts rather than heavy display text. If unavailable, use **Manrope**. Use 300–500 for text; fit oversized identity lettering separately as artwork. Font stack: "TT Hoves Pro Trial", "Manrope", Arial, sans-serif.
- **NeueMontreal** — Sentence-case editorial statements, descriptive paragraphs and case-study reading text. Neutral neo-grotesk with compact, smooth lowercase and regular weight. If unavailable, use **Inter**. Use 400 with normal tracking. Font stack: "NeueMontreal", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial-statement | NeueMontreal | 400 | 24px | 1.5 | normal | fixed | A short sentence-case statement between media and catalogue; keep its width to 460px. |
| section-heading | TT Hoves Pro Trial | 400 | 20px | 1.5 | 0.1em, uppercase | size calc(1vw*1.38889) | Default ruled section heading introducing a secondary catalogue. |
| support | TT Hoves Pro Trial | 300 | 14px | 1.5 | normal | fixed | Quiet supporting paragraph beside the catalogue. |
| navigation | TT Hoves Pro Trial | 400 | 10px | 1 | 0.22em, uppercase | fixed | Navigation, image identity captions and social links. |
| action-label | TT Hoves Pro Trial | 500 | 10px | 1 | 0.22em, uppercase | fixed | Contact action and image category captions. |
| footer-address | TT Hoves Pro Trial | 500 | 10px | 2.5 | 0.22em, uppercase | fixed | Centered short lines of identity and contact context. |
| intro-marking | TT Hoves Pro Trial | 400 | 8px | 1.5 | 0.22em, uppercase | fixed | Compact opening positioning statement; the giant identity above it is vector lettering, not this text recipe. |
| collection-marker | TT Hoves Pro Trial | 500 | 8px | 2 | 0.22em | size calc(1vw*.55556) | Collection label and year range above the first media field. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company and capabilities pages | chapter-heading | TT Hoves Pro Trial | 400 | 24px | 32px | 0.22em, uppercase | fixed | Widely tracked chapter titles, sometimes broken into two lines. |
| case-study pages | case-title | TT Hoves Pro Trial | 500 | 20px | 1 | 0.22em, uppercase | size calc(1vw*1.38889) | Compact project-type title beneath the client label. |
| company and capabilities pages | body | NeueMontreal | 400 | 16px | 1.5 | normal | fixed | Company introduction and capability lists. |
| company and capabilities pages | proof-value | NeueMontreal | 400 | 14px | 1 | normal | fixed | Small right-aligned relationship duration, rather than an oversized statistic. |
| case-study pages | case-body | NeueMontreal | 400 | 11px | 1.5 | normal | fixed | Right-aligned description in the sticky project dossier. |
| case-study pages | case-subheading | TT Hoves Pro Trial | 500 | 10px | 1.5 | 0.22em, uppercase | fixed | Short concept heading above the descriptive paragraph. |
| case-study pages | case-link | NeueMontreal | 400 | 10px | 1.5 | 0.22em, uppercase | fixed | Underlined external experience link. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The dramatic size contrast comes from vector identity lettering against small text, not from a conventional ladder of enormous text headings.
- Maintain 0.22em tracking across small uppercase labels and the company-page headings; default catalogue headings use the narrower 0.1em.
- Normal-tracked prose provides relief from the uppercase markings. Keep regular weights dominant; medium is reserved for category and action emphasis.

## Layout

**Density:** Airy text chapters and closing scenes alternate with tightly abutting image fields; small captions remain compact.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Media mosaic gutters and tight repeated groups. | fixed |
| 12px | Editorial grid gutters. | fixed |
| 16px | Caption vertical padding, paragraph separation and contact-link offset. | fixed |
| 24px | Header and footer edge padding; company title underline clearance. | fixed |
| 32px | Caption side padding and catalogue heading clearance. | calc(1vw*2.22222) |
| 40px | Catalogue introduction to list and company heading-to-body separation. | fixed |
| 64px | Main desktop side inset. | fixed |
| 180px | Vertical padding around the standalone editorial statement. | fixed |
| 192px | Separation between company-page chapters. | fixed |
| 240px | Case-study gallery to next-project closing stage. | calc(1vw*16.66667) |

### Containers and grids

- **editorial-container**: max width 1312px · side padding 64px. Centered textual content, opening identity and footer at a 1440px viewport; overall layout is capped at 2400px.
- **showcase-grid**: 2 columns · gap 0px · side padding 0px. Full-bleed two-column media system with 720px halves and occasional full-span work; 1px rules replace gutters.
- **editorial-grid**: max width 1312px · 12 columns · gap 12px · side padding 64px. Company chapters and case studies share an asymmetric editorial scaffold.
- **statement-column**: max width 460px. Short prose statement inset a further 64px inside the main container.
- **case-dossier** (only for case-study pages): max width 319px. Sticky left information rail; leave a full editorial column of air before the 871px-wide right gallery.

## Corner radius

| Element | Radius |
| --- | --- |
| editorial-media-and-actions | 0px |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Default page and footer surface.

**CSS:** `background: #ececec; color: #222222`

**Observed:** A continuous neutral ground rather than alternating colored UI bands.

**Transfer:** Keep the structural canvas constant while imagery changes tone.

#### Ruled media rail · level 1

**Use:** Caption strips beneath showcase images.

**CSS:** `background: #ececec; border-top: 1px solid #222222; border-bottom: 1px solid #222222; border-radius: 0px; box-shadow: none`

**Observed:** The rail is part of the grid, not a floating card.

**Transfer:** Use the dark edge to bind captions to the media.

#### Soft editorial divider · level 0

**Use:** Chapter headings, archive rows and footer baseline.

**CSS:** `border-bottom: 1px solid #cccccc; box-shadow: none`

**Observed:** Fine grey rules organize white space without boxing content.

**Transfer:** Separate information horizontally; do not enclose every module.

#### Defocused image stage · level 0

**Only for:** case-study endings

**Use:** Atmospheric next-project backdrop.

**CSS:** `overflow: hidden; position: relative`

**Observed:** The same image appears sharply on the right and enlarged into a blurred, darkened full-width background behind pale left-hand labels.

**Transfer:** Duplicate the destination artwork, use cover sizing on the rear copy and soften it until details dissolve; retain the sharp foreground image.

## Components

### Bracket link

**Use:** Default conversion and contact action.

**CSS:** `position: relative; color: #222222; padding: 0px 11.8px 0px 14px; border-radius: 0px; background: transparent; transition: opacity 0.2s cubic-bezier(0.4, 0, 0.2, 1)`

**Text style:** `action-label` — TT Hoves Pro Trial 500 · 10px/1 · tracking 0.22em · uppercase

**Observed:** Two tiny triangles face inward toward the text. The label itself is the entire action, without a surrounding button outline.

**States:** Declared: hover opacity 0.6.

**Transfer:** Use an equally brief verb phrase and keep the brackets close to it.

### Editorial navigation

**Use:** Static opening navigation and compact sticky navigation farther down.

**CSS:** `position: relative; color: #343434; padding: 0px 11.8px 0px 14px`

**Text style:** `navigation` — TT Hoves Pro Trial 400 · 10px/1 · tracking 0.22em · uppercase

**Observed:** Opening links sit in a row beneath the giant identity, aligned toward the right. Compact navigation replaces the identity with a small wordmark, adds a top rule and uses difference blending over media; inactive ink is #aaaaaa. Navigation items are separated by 128px at desktop.

**Transfer:** Keep a small set of terse destinations; retain the same triangle-bracket language.

### Showcase tile

**Use:** Large visual proof or product story.

**CSS:** `position: relative; border-bottom: 1px solid #222222; border-radius: 0px`

**Observed:** A 650px-high image or video sits directly above the caption rail. Half-width tiles fill one side of the two-column grid; full-width tiles span it. A central 1px rule separates paired tiles.

**Transfer:** Use one strong composition per tile, alternating human context with product detail.

### Caption rail

**Use:** Index each showcase tile.

**CSS:** `display: flex; padding: 16px 32px; border-top: 1px solid #222222; background: #ececec`

**Text style:** `action-label` — TT Hoves Pro Trial 500 · 10px/1 · tracking 0.22em · uppercase

**Observed:** The left category is medium-weight, the right identity is regular navigation type and right-aligned. Both take equal space; the strip is 43px high.

**Transfer:** Pair content type with product or collection name, not a paragraph of explanation.

### Archive row

**Use:** Secondary catalogue without repeating large tiles.

**CSS:** `display: flex; position: relative; padding-bottom: 24px`

**Text style:** `navigation` — TT Hoves Pro Trial 400 · 10px/1 · tracking 0.22em · uppercase

**Observed:** Three aligned fields identify subject, format and year. A 1px grey rule sits below each row; the rows occupy the right 883px while one portrait-oriented preview occupies the left. Active selection has a darker divider.

**Transfer:** Use this as an index for editions, applications or customer stories; update the single preview to reflect selection.

### Footer baseline

**Use:** Small utility links beneath the closing composition.

**CSS:** `display: flex; align-items: center; padding: 24px 0px; border-top: 1px solid #cccccc; background: #ececec`

**Text style:** `navigation` — TT Hoves Pro Trial 400 · 10px/1 · tracking 0.22em · uppercase

**Observed:** Copyright left, bracketed social links centered, legal link and a small accreditation badge right; the band is 89px high.

**States:** Declared: hover opacity 0.6 on text links; focus-visible outline currentcolor solid 1px with outline-offset 2px on the accreditation link.

**Transfer:** Keep utilities subordinate and align them to the thirds used above.

### Experience link

**Only for:** case-study pages

**Use:** Open a project's external experience.

**CSS:** `display: inline-block; border-bottom: 1px solid #222222; color: #222222; transition: opacity 0.2s cubic-bezier(0.4, 0, 0.2, 1)`

**Text style:** `case-link` — NeueMontreal 400 · 10px/1.5 · tracking 0.22em · uppercase

**Observed:** A plain underlined line sits apart from the right-aligned description, without triangles or a box.

**States:** Declared: hover opacity 0.6.

### Project dossier

**Only for:** case-study pages

**Use:** Persistent narrative companion to a scrolling gallery.

**CSS:** `position: sticky; padding-bottom: 24px; text-align: right`

**Text style:** `case-body` — NeueMontreal 400 · 11px/1.5

**Observed:** Client label, project-type title and date/category form the upper cluster; a concept heading and prose occupy the middle; the external link, occasional awards and a small count/down-arrow/progress line finish the rail.

**Transfer:** Replace with product edition, concise purpose, role and a real destination; keep the gallery visually dominant.

### Relationship row

**Only for:** company and capabilities pages

**Use:** Understated quantified proof.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding-bottom: 16px; border-bottom: 1px solid #cccccc`

**Text style:** `proof-value` — NeueMontreal 400 · 14px/1

**Observed:** A medium 14px uppercase name sits left, a regular 14px duration sits right, and inward-facing 6px triangles mark the row ends. Rows are separated by 48px.

**Transfer:** Present a real duration or compact outcome beside its subject rather than inflating the number into a dashboard statistic.

## Imagery and graphics

### Monumental identity

**Use:** The defining opening headline artwork.

**Observed:** A dark, wide grotesk wordmark stretches almost the entire content width in one line, 1312px by 130px, with a small vertical trademark at the far right. It is the visual headline, not an ordinary prose heading.

**Transfer:** Create a single-line sculpture of the new identity or a very short product phrase. With no custom artwork, typeset a plain grotesk word in SVG and adjust its width to the container while preserving letter proportions.

**Build:** Use an SVG viewBox with a 1312:130 artwork ratio. Fit original uppercase letter paths across the width in charcoal; use even, normal letter spacing rather than the micro-label tracking. Leave 64px outer margins at desktop. Keep an accessible text equivalent.

### Magnetic contour field

**Use:** Required graphic atmosphere around the oversized opening identity; repeated in the expanded company closing.

**Observed:** Very faint elliptical curves run behind the typography and across a broad empty field. They emerge from off-center origins and are clipped by the viewport, reading as a magnetic diagram rather than a gradient or texture.

**Transfer:** Recreate the line field independently of product media; the atmosphere works even with only typography.

**Build:** Place an absolute SVG behind content with six to eight unfilled elliptical paths. Set each stroke to rgba(34,34,34,0.05), width 1px. Nest ellipses around an origin near the left quarter, stretch the larger arcs across and beyond the viewport, and clip within the opening. Use the 1527px by 1013px field as a desktop proportion, without blurring.

### Cinematic proof fields

**Use:** Main gallery and product storytelling.

**Observed:** Close, editorial portraits alternate with watch mechanisms, reflective objects and sculptural still lifes. Human images have soft studio or sunset light and decisive body crops; product renders reveal metal, glass, grain and polished reflections. Rich blue, warm amber, pink skies and monochrome frames occur inside the media, not as interface themes. Images fill their rectangular fields without mats.

**Transfer:** Use tightly cropped product photography, tactile 3D or a person in relation to the product. The minimum is one excellent still with deliberate light and material detail, reused through a wide context crop and a close detail crop.

### Closing glyph matrix

**Use:** Required graphic signature within the contact closing.

**Observed:** A 183px by 175px four-by-four arrangement of thin letters, numerals and directional arrows surrounds a tiny red point. It is centered between small identity and contact blocks, with no enclosing box.

**Transfer:** Compose an original typographic emblem from the new identity, a meaningful location or product shorthand; preserve the sparse arrow-and-letter matrix rather than using a decorative logo cloud.

**Build:** Create a transparent SVG with four evenly spaced rows and columns. Mix thin grotesk letter outlines, numerals and single-line arrows about 32px to 38px tall; center each cell. Place one red circle about 6px across in an interior cell. Use primary ink for every other glyph and no grid lines.

### Sharp image over blurred duplicate

**Only for:** case-study endings

**Use:** Next-project handoff.

**Observed:** A 640px-high full-bleed stage shows a heavily defocused enlargement of the next work behind a sharp roughly 429px by 460px image on the right. Small pale metadata is centered in the left half. One example uses a portrait in pale blue fabric; another shows amber glass framed by carved wood.

**Transfer:** Preview the next story using its own key artwork and palette, not a generic colored background.

**Build:** Duplicate the same artwork. Make the rear layer absolute with cover sizing, scale 1.1 and a starting blur of 30px; darken it with a translucent black overlay until pale labels are legible. Center a sharp image in the right half, approximately 30% of page width. Treat these effect settings as tuning guidance.

### Company image interludes

**Only for:** company and capabilities pages

**Use:** Break up institutional copy and link back to visual work.

**Observed:** A wide black-and-white sports photograph pairs with a narrower motion-exposure fashion image across an 871px/429px split. Other interludes use horizontal image strips and a centered 1091px-wide film still. The final return-to-work banner is a full-width, saturated illustration of walkers, palms and the sea with small pale text at bottom left.

**Transfer:** Pair differently framed photographs with a consistent light treatment. For the final banner use one richly colored, original campaign illustration or image; keep the navigation label small.

### Icons

**Observed:** Solid miniature directional triangles accompany links and proof rows; link brackets are approximately 4px by 4px, proof triangles 6px by 6px. Down arrows act as sparse reading cues. Large thin arrows belong to the closing glyph artwork, not an interface icon set.

**Transfer:** Use CSS border triangles and plain line arrows. Keep the rest of the interface free of feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Oversized identity threshold

**Observed:** The Gallery canvas carries the Magnetic contour field behind all content. The Monumental identity spans the main container at the top with 24px top clearance and a 130px cap height. Editorial navigation runs below the word on the right; a tiny four-line introduction occupies only the left third beneath it. A Collection marker sits lower in the open field, balanced by two down arrows toward the right. There is no central product render or conventional CTA stack: the first cinematic image begins at 650px and fills the bottom 250px of the first 900px viewport. Its caption and further proof fall below the fold.

**Transfer:** Use the new identity as the large word sculpture, a compact product-positioning statement beneath it and a strong product still starting near the lower third of the screen. The action is navigation into the work, not a filled sales button. Case-study pages instead open with Project dossier beside a gallery; company pages can open with a sparse graphic field before their first ruled chapter.

**Avoid:** Do not replace the opening with a centered two-line sales headline, two pill buttons and a floating dashboard mockup.

**Text style:** `intro-marking` — TT Hoves Pro Trial 400 · 8px/1.5 · tracking 0.22em · uppercase

### Edge-to-edge visual proof

**Observed:** Showcase tiles form a no-gutter two-column grid, alternating 1440px-wide stages and paired 720px fields. Every media field is 650px high with a Caption rail underneath. Ruled media rails form continuous horizontal bands.

**Transfer:** Sequence wide context views against tighter paired details according to the new narrative; keep the caption grammar consistent.

### Statement and catalogue

**Observed:** A 460px-wide Editorial statement receives 180px top and bottom air. The next section uses a ruled Section heading, a 319px-wide support paragraph and Archive rows occupying the right two-thirds, balanced by a single portrait preview on the left.

**Transfer:** Use the statement as an emotional pause, then let the index hold secondary proof that does not need another oversized image.

**Text style:** `editorial-statement` — NeueMontreal 400 · 24px/1.5

### Emblem contact closing

**Observed:** A 900px-high Gallery canvas holds three equal horizontal zones: small identity left, Closing glyph matrix center and Footer address plus Bracket link right. The composition sits near the vertical center with extensive air above and below; Footer baseline is pinned to the bottom.

**Transfer:** End a marketing page with a memorable graphic object and one compact conversion route. The emblem remains essential even when the contact details or conversion goal change.

**Text style:** `footer-address` — TT Hoves Pro Trial 500 · 10px/2.5 · tracking 0.22em · uppercase

### Asymmetric company chapter

**Only for:** company and capabilities pages

**Observed:** Chapter heading spans the 1312px container, with 24px clearance above a soft rule. Body copy starts on the right five columns of the 12-column grid, leaving a wide empty left region. Chapters separate by 192px. The capability chapter replaces paragraphs with three slim lists, a 1px progress rule and a dark active segment; nonactive lists are visually subdued.

**Transfer:** Use for principles, capabilities or process. Preserve the asymmetry and short lists without requiring the same subjects.

**Text style:** `chapter-heading` — TT Hoves Pro Trial 400 · 24px/32px · tracking 0.22em · uppercase

### Dossier and media mosaic

**Only for:** case-study pages

**Observed:** Below the compact 112px header, Project dossier stays in the 319px left rail. An 871px-wide gallery occupies the right, mixing wide 491px-high frames and paired 431px images with 8px gutters. Text is right-aligned toward the gallery. A 240px pause separates the final media from the next-project stage.

**Transfer:** Explain a single product story in the stationary rail while its context, details and outcomes unfold through the mosaic.

**Text style:** `case-title` — TT Hoves Pro Trial 500 · 20px/1 · tracking 0.22em · uppercase

### Expanded company closing

**Only for:** company and capabilities pages

**Observed:** Contact context sits left, the glyph matrix center and three contact categories right. A further 580px contour-field region contains a small spaced closing phrase before Footer baseline. Below that is a separate 540px-high illustrated return-to-work banner.

**Transfer:** Use when several audience-specific contact routes are necessary; keep the lower visual handoff separate from legal utilities.

### Atmospheric next-story handoff

**Only for:** case-study endings

**Observed:** Defocused image stage fills 640px. Sharp image over blurred duplicate places pale, compact identity/category/year metadata left and an isolated sharp image right; this replaces the contact footer at the end of the project.

**Transfer:** Send readers to the next related story with a complete art-directed preview rather than a small related-card grid.

## Page flow

**Storyline:** identity and positioning → immersive visual proof → concise interpretation or capabilities → indexed or quantified proof → graphic contact or next-story handoff

### Image-led marketing landing page

1. **Identity and promise** — Monumental identity, tiny introduction, contours and reading cues.
2. **Demonstration** — Alternating full-bleed and paired media with catalogue-style captions.
3. **Interpretation** — One short sentence-case statement in a narrow column.
4. **Additional proof** — Secondary index with one large preview rather than more cards.
5. **Closing action** — Spacious three-zone emblem contact scene and fine utility baseline.

**Transfer:** Let original product imagery do most of the persuasion; adapt the amount of proof to the product, not a fixed section count.

### Expressive campaign case study

1. **Context** — Sticky compact dossier states identity, category, date and a poetic concept.
2. **Immersive demonstration** — Long right-hand mosaic combines colorful 3D environments, film and paired stills.
3. **External action and recognition** — Underlined experience link and small award markings remain in the dossier.
4. **Next story** — A full-width blurred-image stage previews a different project.

**Transfer:** Use for an expressive launch or experience; carry descriptive copy and recognition only when relevant.

### Product and design case study

1. **Context** — Sticky right-aligned dossier gives a brief functional explanation and external action.
2. **Product demonstration** — Wide lead frame, paired object views, portrait and wide closing media in a shorter mosaic.
3. **Next story** — A new product artwork is isolated over its blurred enlargement.

**Transfer:** Use the same dossier grammar for a focused, shorter product story; scale gallery length to available proof.

### Company credibility and capabilities

1. **Identity** — Sparse graphic field opens into a widely tracked ruled chapter.
2. **Positioning** — Right-weighted prose and a split photographic interlude.
3. **Capabilities** — Three columns of brief services with a fine progress indicator.
4. **Quantified proof** — Relationship names and small duration values in ruled rows.
5. **Closing action** — Expanded contact composition, contours and a small closing phrase.
6. **Return to demonstration** — A saturated illustrated banner links back to the work after the utility baseline.

**Transfer:** Preserve the graphic breathing room and modest numeric proof for a company's own capabilities and relationships.

## Writing

Confident, art-directed and restrained. Institutional copy is plain and craft-oriented; campaign descriptions become sensuous and evocative without turning the navigation into advertising.

**Do not copy:** Do not reuse the brand wordmark, its letter emblem, addresses, named customers, award counts, relationship durations, project names, campaign claims or proprietary artwork. Example phrases illustrate voice; write original claims for the new product.

- **Addressing the reader:** Use first-person plural for the maker and third person for the product or project. Direct address appears sparingly in invitation verbs, not in repeated benefit slogans.
- **Rhythm:** Labels are mostly one to four words. Institutional paragraphs use one or two clear sentences; campaign prose can stretch into a brief lyrical passage. Uppercase is a visual treatment, not a reason to write in a shouting tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning | State what kind of maker this is, where it operates and its focused expertise. | One compact paragraph | “We are a full-service creative agency, based in Paris, specializing in luxury, beauty and lifestyle.” |
| Chapter heading | A concise noun pair or three active verbs. | 2–4 words | “Think, create, produce”<br>“Ideas & strategy” |
| Editorial statement | Connect craft to an emotional purpose in one sentence. | 12–20 words | “Created at the heart of Paris, we craft emotions to connect brands with their audiences.” |
| Campaign concept | A brief atmospheric phrase, more like an exhibition title than a list of benefits. | 4–8 words | “The essence of a summer day.” |
| Action | Short invitation or direct contact verb. | 2–5 words | “Contact us”<br>“Discover the full experience”<br>“Light Up” |

**Words and phrasing to use:** craft; bespoke; emotional connections; experience; concepts; strategy; art direction; quality over quantity

**Avoid:** 10x; game-changing; crush it; ultimate solution; limited-time offer; effortlessly revolutionize

**Rules:**

- Let the image carry spectacle; use captions to identify rather than explain.
- Ground institutional claims in a specific practice or relationship.
- Keep catalogue titles factual and concept lines evocative.
- Reserve lyrical sensory language for immersive campaign stories.

## Do's and Don'ts

### Do

- Keep the structural palette to light grey and dark ink; concentrate saturation inside media.
- Set small uppercase navigation at 10px with 0.22em tracking.
- Fit the opening word sculpture to the 1312px content width with a 130px cap height.
- Use 1px rules to connect tiles and organize rows.
- Keep caption padding at 16px vertically and 32px horizontally.
- Balance 650px-high media fields with genuinely spacious text pauses.
- Carry both the contour field and original letter-and-arrow emblem into a new page.
- Use 24px/36px normal-tracked prose for the standalone interpretive statement.

### Don't

- Do not add a permanent bright accent color to section backgrounds or navigation.
- Do not round every media tile into a 16px or 24px app card.
- Do not replace triangle-bracket actions with 44px-high filled pills.
- Do not turn the fine 1px dividers into thick decorative borders.
- Do not center all body copy; the editorial composition depends on narrow offset columns.
- Do not make relationship durations into giant colored statistics.
- Do not add soft card shadows or glass panels to the flat gallery scaffold.
- Do not apply 0.22em tracking to sentence-case reading paragraphs.

## Motion and responsive

### Motion

**Observed:**

- Action opacity transitions are declared at 0.2s cubic-bezier(0.4, 0, 0.2, 1), with hover opacity 0.6.
- Compact header transform rules include 1s cubic-bezier(0.19, 1, 0.22, 1) and a 0.4s cubic-bezier(0.55, 0.055, 0.675, 0.19) variant.
- Clip-path reveals are declared at 0.8s ease-in-out and 0.4s cubic-bezier(0.55, 0.055, 0.675, 0.19).

**Transfer:**

- Keep interaction emphasis in subtle opacity, directional reveals and changes between large and compact identity states, rather than decorative bouncing.
- Treat media as cinematic fields; retain a well-composed still image when moving content is unavailable.

**Unknown:**

- Exact scroll triggers, contour animation paths and sequencing of the graphic scenes are unspecified.

### Responsive

**Observed:**

- Root rem sizing scales with 1.11111vw. Explicit display-label formulas include calc(1vw*1.38889) and calc(1vw*.55556).
- Declared width breakpoints are 460px, 640px, 767px, 768px, 1024px, 1200px and 2400px.

**Transfer:**

- On narrow screens, preserve the edge-to-edge identity and scale its vector artwork rather than wrapping it into a prose headline.
- Recommended adaptation: stack paired proof fields and move the project dossier above its gallery; retain the triangle links, caption rails and emblem as recognizable anchors.
- Protect small text from becoming illegible when adapting the fluid desktop scale.

**Unknown:**

- Exact mobile sizing, side insets, menu behavior and sticky-rail rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
