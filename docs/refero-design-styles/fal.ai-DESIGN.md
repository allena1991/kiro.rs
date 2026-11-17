# fal.ai — pixels at platform scale

## Overview

A buoyant technical style where oversized grotesk typography shares a bright cyan stage with pixel creatures and fluorescent geometric fragments. White working sections and flat pastel panels keep the information practical, while an occasional near-black chapter and deep purple callout add weight. It suits developer platforms and ambitious software products that want enterprise credibility without losing experimental energy.

### Essentials

- The opening is a cyan playground, not a software dashboard: a full-width #99ecff stage about 880px tall puts a left-aligned 120px/100px, weight-500 headline in front of cropped graphic fragments.
- Headlines feel almost too big for their allotted space: display tracking is -0.04em, while 60px/60px section titles wrap into narrow left-hand rails beside much wider content.
- Actions are small rectangular tools against giant language: 4px corners, 44px height and 20px side padding by default; the opening pair grows to 48px with 24px side padding.
- Color comes in entire flat territories: cyan at the entrance and footer, white through the working middle, pastel capability cards, one near-black proof chapter and a contained deep-purple conversion panel. Fluorescent yellow, lime and violet stay chiefly in artwork rather than paragraphs.
- Pixel organisms and blunt geometric bars are signature punctuation: combine crisp square-cell patterns with oversized rounded diagonal strokes, clipping them at page edges. Repeat smaller pixel clusters through later sections; use an abstract product-shaped pixel silhouette when no suitable media exists.
- The ending is a designed destination: dense directory columns give way to a huge right-aligned identity graphic, about 563×225px on desktop, with a 6px segmented color strip along the bottom. Use the new product's own identity at the same monumental scale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion purple | `#4a17b0` | `--color-violet` | surface | Contained conversion stage with white text. |
| Cyan stage | `#99ecff` | `--color-sky` | background, surface | Default opening and directory-footer fields. |
| Announcement plum | `#2b0b6a` | `--color-announcement` | background | Slim announcement strip. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid lime | `#adff00` | `--color-acid` | accent | Graphic contour accents and pixel-pattern artwork; not body text. |
| Electric yellow | `#ffff00` | `--color-yellow` | accent | Fluorescent bars and sparse highlighted pixel cells. |
| Pixel violet | `#ab77ff` | `--color-pixel-violet` | accent | Crisp pixel clusters, geometric bars and footer stripe. |
| Capability cyan | `#99edff` | `--color-capability-blue` | surface | Capability cards and selected tall proof columns. |
| Bubblegum pink | `#ffc4d8` | `--color-pink` | surface, accent | Small diagram accents; full footer field in the infrastructure variant. |
| Lime wash | `#f1ffd2` | `--color-lime-wash` | surface | Companion capability cards and proof columns. |
| Capability lavender | `#f3e8ff` | `--color-lavender` | surface | Wide leading capability card. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action charcoal | `#202022` | `--color-action` | text, action | Default primary button fill and editorial body text. |
| Headline black | `#000000` | `--color-ink` | text | Large headings and graphic silhouettes. |
| Proof charcoal | `#121216` | `--color-night` | background | Full-width enterprise proof chapter; also the source hue for faint edges. |
| Strong text | `#19191a` | `--color-strong` | text | Introductory copy and closing prompts. |
| Muted caption | `#787881` | `--color-soft-text` | text | Trust captions and supporting labels. |
| Visible panel edge | `#dbdbdc` | `--color-edge` | border | Visible 15% proof-charcoal edge on white; use rgba(18,18,22,0.15). |
| Quote gray | `#f3f4f6` | `--color-quote` | surface | Pale cool neutral quote cards. |
| Feature gray | `#f4f4f5` | `--color-card` | surface | Feature card backing, without a drop shadow. |
| Off-white action text | `#fafafa` | `--color-button-text` | text, action | Text on dark buttons and light action in purple panels. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Working sections, secondary buttons and reversed text on dark chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| infrastructure product pages | Infrastructure olive | `#403700` | `--color-olive` | background | Dark proof band and closing contact section. |
| infrastructure product pages | Infrastructure blue | `#c5e9ff` | `--color-infra-sky` | background, text | Opening field and reversed text on olive. |
| editorial pages | Secondary gray | `#494950` | `--color-muted` | text | Editorial navigation and secondary explanations. |

## Typography

- **Focal** — Headlines, body, navigation and quotes; the upright variable cut is used for infrastructure pages. Firm grotesk with open counters, broad display presence and a friendly rather than mechanical voice. If unavailable, use **Inter**. Use weights 400–700; preserve compressed display leading and tracking. Font stack: "Focal", "Inter", Arial, sans-serif.
- **Public Sans Rounded** — Conversion-button labels. Compact rounded sans with a fuller semibold texture than the body face. OpenType features: "ss01". If unavailable, use **Public Sans**. Use 600 and -0.01em tracking. Font stack: "Public Sans Rounded", "Public Sans", system-ui, sans-serif.
- **chivoMono** (only for code demonstrations) — Visible technical code illustrations. Straightforward monospaced type with restrained syntax colors. Font stack: "chivoMono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Focal | 500 | 120px | 100px | -0.04em | fixed | Default landing headline, stacked into three emphatic lines. |
| proof-display | Focal | 500 | 80px | 70px | normal | fixed | Large white heading in the dark proof chapter. |
| testimonial-display | Focal | 500 | 80px | 0.9 | -0.04em | size min(80px, 6vw) | Two-line statement surrounded by floating testimonial cards. |
| section | Focal | 500 | 60px | 1 | normal | fixed | Narrow rail section titles and the large centered conversion heading. |
| gallery-heading | Focal | 500 | 48px | 1 | normal | fixed | Gallery introduction paired with explanatory copy. |
| media-title | Focal | 500 | 40px | 0.9 | -0.04em | fixed | White titles pinned low in portrait media cards. |
| capability-heading | Focal | 500 | 36px | 40px | normal | fixed | Large pastel capability-card titles. |
| card-heading | Focal | 500 | 30px | 1.2 | normal | fixed | Feature cards with short explanatory text. |
| footer-prompt | Focal | 500 | 30px | 1.2 | -0.02em | fixed | Single-line prompt above directory links. |
| closing-support | Focal | 400 | 24px | 32px | normal | fixed | Centered supporting paragraph in the purple conversion stage. |
| lead | Focal | 400 | 18px | 28px | normal | fixed | Hero support copy in a narrower measure than the heading. |
| body | Focal | 400 | 16px | 1.5 | normal | fixed | Feature paragraphs and capability descriptions. |
| button | Public Sans Rounded | 600 | 16px | 1.5 | -0.01em, features "ss01" | fixed | Primary and secondary conversion labels. |
| directory-link | Focal | 500 | 16px | 1.25 | -0.02em | fixed | Footer link lists. |
| quote | Focal | 400 | 14px | 1.4 | -0.02em | fixed | Compact testimonials; identity sits underneath. |
| nav | Focal | 500 | 13px | 1 | normal | fixed | Compact desktop navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| infrastructure product pages | infrastructure-display | Focal | 500 | 86.4px | 0.86 | -0.0347em | size 6vw | Centered product promise and oversized colored category labels. |
| infrastructure product pages | infrastructure-heading | Focal | 500 | 54.7px | 0.96 | -0.0263em | size 3.8vw | Chapter leads and the closing contact pitch. |
| editorial pages | article-title | Focal | 500 | 48px | 1.25 | -0.02em | fixed | Left-aligned title in the compact cyan editorial masthead. |
| editorial pages | article-heading | Focal | 700 | 30px | 40px | normal | fixed | Major article divisions. |
| editorial pages | article-subheading | Focal | 600 | 24px | 36px | normal | fixed | Practical technique subsections. |
| editorial pages | article-body | Focal | 400 | 18px | 32px | normal | fixed | Long-form explanatory paragraphs and example lists. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display scale is established by leading and measure, not boldness: weight 500 carries the large marketing headings; only editorial section hierarchy moves to 600 and 700.
- Tight -0.04em tracking belongs to the largest compressed statements and media-card titles. Ordinary paragraph and card-heading tracking remains normal.
- Keep the hero support line to 480px while the headline occupies roughly 764px at desktop; the difference in measures is a defining hierarchy.

## Layout

**Density:** Airy between chapters, compact within tools: long white intervals surround tightly grouped text, buttons and illustrations.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Footer list rhythm. |
| 8px | Icon-to-label and compact navigation gaps. |
| 12px | Rail heading to explanatory line. |
| 16px | Card gutters, action-pair gap and ordinary card content gaps. |
| 24px | Hero heading/support/action separation and quote-card inset. |
| 32px | Feature-card inset, footer perimeter and purple-stage content gap. |
| 40px | Directory grid top padding. |
| 48px | Editorial sidebar-to-body and footer column gap. |
| 96px | Gallery introduction top space. |
| 112px | Separation after major white content chapters. |
| 128px | Vertical breathing room around dark proof content. |

### Containers and grids

- **marketing-container**: max width 1200px · side padding 16px. Centered working chapters; a narrow left heading rail is separated from a right content field by a pronounced open gutter.
- **feature-grid**: 2 columns · gap 16px. Right-hand field about 820px wide with paired 402px cards. Heading rail remains outside the grid.
- **gallery-strip**: gap 16px · side padding 24px. Horizontal run of 288×360px portrait cards; retain horizontal overflow rather than squeezing the media.
- **footer-grid**: max width 1280px · 6 columns · gap 48px · side padding 32px. A wider first directory group splits internally into two lists; five narrower groups follow. Large empty space below protects the identity artwork.
- **editorial-layout** (only for editorial pages): max width 1280px · 2 columns · gap 48px · side padding 16px. A 272px metadata/contents rail beside a flexible main region containing a 768px reading column.
- **related-grid** (only for editorial pages): max width 1248px · 3 columns · gap 24px. Three equal 400px editorial discovery cards.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons and feature panels | 4px |
| media cards | 6px |
| testimonials | 8px |
| conversion stage and proof columns | 12px |

## Surfaces and depth

### Surfaces

#### Working canvas · level 0

**Use:** The middle of ordinary marketing and editorial pages.

**CSS:** `background: #ffffff; color: #19191a`

**Observed:** Flat white, not a textured paper or elevated application shell.

**Transfer:** Let white intervals separate the colorful chapters.

#### Cyan stage · level 0

**Use:** Opening and directory-footer territories.

**CSS:** `background: #99ecff; color: #000000`

**Observed:** Unbroken flat color reaches both viewport edges.

**Transfer:** Treat cyan as a structural field rather than a small link accent.

#### Feature panel · level 1

**Use:** Reusable capability and technical-benefit cards.

**CSS:** `background: #f4f4f5; border-radius: 4px; padding: 32px; box-shadow: none`

**Observed:** Neutral variants contain a smaller illustration on a slightly darker inset backing; capability variants use lavender, cyan or pale lime across the whole card.

**Transfer:** Keep simple diagrammatic proof inside the panel instead of adding an application-sized toolbar.

#### Dark proof field · level 0

**Use:** A high-contrast chapter for reliability, scale or deeper assurance.

**CSS:** `background: #121216; color: #ffffff`

**Observed:** A flat dark field contains staggered pastel columns and translucent charcoal explanation blocks. White at 5% creates the explanation-block fill.

**Transfer:** Reserve it for a meaningful change in narrative weight.

#### Purple conversion stage · level 1

**Use:** Large contained conversion appeal.

**CSS:** `background: #4a17b0; color: #ffffff; border-radius: 12px; overflow: hidden`

**Observed:** A 1168×535px panel centered inside the working container; pixel fragments sit behind the typography.

**Transfer:** Use a concentrated statement and two actions rather than a feature list.

#### Infrastructure olive band · level 0

**Only for:** infrastructure product pages

**Use:** Production proof and contact-form closing section.

**CSS:** `background: #403700; color: #c5e9ff; padding: 80px 144px`

**Observed:** Dark olive paired with pale-blue type; a white form panel sits alongside the closing pitch.

**Transfer:** Use only within the lighter-blue infrastructure variant, not as the default dark chapter.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #202022; color: #fafafa; height: 44px; padding: 0px 20px; border: 1px solid transparent; border-radius: 4px; gap: 8px`

**Text style:** `button` — Public Sans Rounded 600 · 16px/1.5 · tracking -0.01em

**Observed:** Opening actions use the taller 48px variant with 24px side padding; compact editorial product cards use 40px height. A white-filled inverse variant leads on purple.

**States:** Declared: hover background-color hsl(240 5% 30%); focus-visible outline-style none and zero box-shadow; active scale 0.98.

**Transfer:** Keep labels literal and brief; pair one self-service action with one assisted action.

### Secondary button

**Use:** Supporting action beside a dark primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #202022; height: 48px; padding: 0px 24px; border: 1px solid rgba(18,18,22,0.15); border-radius: 4px; gap: 8px`

**Text style:** `button` — Public Sans Rounded 600 · 16px/1.5 · tracking -0.01em

**Observed:** The opening version is taller; ordinary content uses 44px height and 20px side padding. On purple, the secondary action is dark with a pale outline.

**States:** Declared: hover border-color rgba(18,18,22,0.2) and background-color rgba(18,18,22,0.05); focus-visible outline-style none and zero box-shadow; active scale 0.98.

### Navigation label

**Use:** Compact top-level product and resource navigation.

**CSS:** `display: flex; align-items: center; color: #000000; height: 23px; border-radius: 4px`

**Text style:** `nav` — Focal 500 · 13px/1

**Observed:** Identity sits at far left; links and two compact account/sales actions align right. Dropdown triggers have a small dot before the text rather than a prominent chevron. The 36px utility actions have squarer 2px corners.

**States:** Declared: hover background-color #d9d9d9 and text color rgb(25 25 26); focus-visible zero box-shadow.

**Transfer:** Keep the navigation visually subordinate to the giant opening type.

### Feature card

**Use:** Repeated technical benefits with illustrated proof.

**CSS:** `display: flex; flex-direction: column; height: 564px; padding: 32px; background: #f4f4f5; border-radius: 4px; overflow: hidden`

**Text style:** `card-heading` — Focal 500 · 30px/1.2

**Observed:** Heading and short paragraph occupy the top, an action appears only when useful, and a flat illustration fills the lower area. Cards pair in a two-column right-side grid.

**Transfer:** Show a small comparison, code excerpt or capacity diagram that makes one benefit tangible.

### Capability card

**Use:** Larger product-family or capability overview.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 32px; min-height: 472px; background: #f3e8ff; border-radius: 4px; overflow: hidden`

**Text style:** `capability-heading` — Focal 500 · 36px/40px

**Observed:** Wide leading card has an identity label above the message; two narrower cyan and pale-lime cards follow. Main content is bottom-weighted, with bold graphic illustration occupying a corner.

**Transfer:** Give each capability its own pastel territory while keeping construction identical.

### Testimonial card

**Use:** Human evidence around a large social-proof statement.

**CSS:** `padding: 24px; background: #f3f4f6; border-radius: 8px`

**Text style:** `quote` — Focal 400 · 14px/1.4 · tracking -0.02em

**Observed:** Compact quotation, organization identity and small square portrait with name and role; cards of unequal widths float above and below a central two-line statement.

**Transfer:** Use genuine short quotations; preserve the asymmetry rather than a uniform review grid.

### Announcement strip

**Use:** Thin launch or update notice above navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 32px; padding: 6px 44px; background: #2b0b6a; overflow: hidden`

**Observed:** One centered short link, a tiny graphic mark, and a dismiss control at the far right; text is pale lavender.

**Transfer:** Keep it a slim utility strip rather than a second hero.

### Directory link

**Use:** Dense footer navigation.

**CSS:** `color: rgba(22,22,24,0.8); line-height: 20px`

**Text style:** `directory-link` — Focal 500 · 16px/1.25 · tracking -0.02em

**Observed:** Short links form narrow ragged-right columns with 6px row gaps; some wrap into two lines. Group headings are smaller and subdued.

**States:** Declared: hover underline; focus-visible underline.

### Related article card

**Only for:** editorial pages

**Use:** Discovery after a long-form guide.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid rgba(18,18,22,0.15); border-radius: 4px; overflow: hidden`

**Observed:** A wide 398×223px image sits above category/read-time metadata, a compact title, short description and author/date row. Three cards share a row.

**Transfer:** Maintain a visual-first card with understated metadata, rather than extending the giant marketing type into the reading area.

## Imagery and graphics

### Pixel organisms and geometric bars

**Use:** Required signature graphic language in the opening and repeated as marginal punctuation through the page.

**Observed:** Large irregular animal-like silhouettes use a repeating dot/cross lattice inside stair-stepped outlines. Neon lime contours and cyan interiors sit beside thick rounded yellow/violet diagonal bars. Sparse square clusters float at the upper right and near the bottom. Art can extend offscreen and pass behind type; it is flat, crisp and unshaded.

**Transfer:** Create a new silhouette related to the product's world, or an abstract branching shape if no subject fits. Minimum version: one large clipped lattice silhouette, two crossed rounded bars and two sparse pixel clusters.

**Build:** Use an SVG viewBox with a square grid. Define a repeating 12px pattern of 3px circles connected by short orthogonal bars; clip it to an irregular stepped path about 450px wide. Draw a 4px acid-lime outside contour around the path. Add two 55px round-capped line segments at opposing shallow diagonals, electric yellow over pixel violet, spanning about 330px. Use separate groups of 8–16px square cells in pixel violet and cyan with a few yellow or white cells. Keep edges sharp; no blur, lighting or perspective.

### Portrait media gallery

**Use:** Visual exploration cards in a marketing chapter.

**Observed:** Full-bleed generated imagery ranges from cinematic creatures to blurred portraits and stylized figures. Portrait cards are 288×360px with 6px corners. A black veil darkens the image and white tightly led titles anchor at the bottom.

**Transfer:** Show output, use cases or product-adjacent imagery with similarly varied color and cinematic framing. Preserve legibility over vivid images with a dark overlay, not a white caption box.

### Flat technical diagrams

**Use:** Lower portions of neutral feature cards.

**Observed:** Small bar comparisons, colored square-chip emblems, tiny code excerpts and deployment diagrams sit on gray inset plates. They are illustrative evidence, not complete product windows.

**Transfer:** Translate a real benefit into one simple visual and keep the detail subordinate to the heading. Use plain rectangles and a small number of labels when no interface is available.

### Monumental identity ending

**Use:** Required large-scale identity gesture in the directory footer.

**Observed:** A solid black symbol and lowercase wordmark occupy the lower right, about 563×225px on the default footer, with broad cyan negative space to the left. A pink variant makes the identity larger still. A segmented color strip, 6px tall, finishes the cyan version.

**Transfer:** Use the new identity as vector artwork, not an ordinary footer-sized logo. If the identity is long, enlarge a short product name or symbol to preserve the same visual mass.

**Build:** Place an SVG identity block at the bottom right inside a 32px footer inset, about 40% of desktop width. Keep the fill solid near-black and align legal text to its baseline on the left. Add a full-width 6px flex row of unequal cyan, pink, violet and dark segments; use hard boundaries without gradients.

### Editorial feature imagery

**Only for:** editorial pages

**Use:** Article lead image and related discovery cards.

**Observed:** The lead is a wide scene of a musical ensemble beneath an intense multicolor pixel projection, dark-framed inside a 768px reading column. Related cards mix surreal portrait photography, luminous colored 3D spheres and metallic robot figures. Images retain their own saturated palettes against white surroundings.

**Transfer:** Use one wide conceptual image that dramatizes the article's subject, then more compact visual variations for related reading.

### Atmospheric dashboard stage

**Only for:** infrastructure product pages

**Use:** Large product demonstration immediately after the centered promise.

**Observed:** White analytics panels sit over a luminous blue/cyan tunnel-like moving backdrop. The product stage spans nearly the full page width with 40px side margins; a translucent enclosing panel has a faint white edge.

**Transfer:** Show the real operational interface on a blue atmospheric backing, rather than carrying the flat cartoon treatment into the dashboard itself.

**Build:** For a static substitute, layer a deep-blue base with broad cyan radial pools and several translucent diagonal elliptical light bands converging toward the center. Blur the light layers, not the white interface panels. Enclose the panels with rgba(255,255,255,0.055), a 1px rgba(255,255,255,0.08) edge and backdrop-filter blur(12px) saturate(1.15). Exact light stops are not essential.

### Icons

**Observed:** Small utility arrows and close marks are generally 16×16px with 1.5–2px strokes and square line caps. Larger product emblems use bold filled geometric silhouettes rather than detailed line illustration.

**Transfer:** Use a restrained outline set for interaction and custom filled emblems for capability diagrams; do not let a generic icon grid replace the pixel artwork.

## Section recipes

How recurring sections are built.

### First screen: Cyan playground opening

**Observed:** A 32px plum announcement sits above compact navigation integrated into a full-width cyan field about 880px high. Behind the content, a roughly 457px lattice silhouette clips off the left edge, crossed rounded bars sit above it, a tall bar fragment clips off the right, and pixel clusters occupy the upper right and lower edge. In front, the 120px/100px display headline spans about two thirds of the central working area, left aligned and wrapped into three lines. It begins well below navigation and overlaps the art's visual territory. A 480px-wide support paragraph follows at 18px/28px, then dark and white 48px actions separated by 16px. Within the first 900px, the navigation, headline, support, actions and main artwork are all visible; the trust strip and gallery begin below this first scene.

**Transfer:** Keep typography as the main object and invent a product-relevant pixel silhouette rather than relying on a giant interface window. Editorial pages use a shorter cyan masthead, breadcrumb, 48px title and support, with the wide article image on white below. Infrastructure pages use a centered pale-blue promise at 6vw with a dashboard stage entering below it.

**Avoid:** Do not turn this into a centered headline above a floating laptop, or hide the artwork in small decorative corner icons. Do not shrink the headline merely to keep it on one line.

**Text style:** `display` — Focal 500 · 120px/100px · tracking -0.04em

### Gallery introduction and image run

**Observed:** A 48px heading and explanatory block oppose each other above the media run, with 96px top breathing room and 56px below. A small action row precedes the Portrait media gallery.

**Transfer:** Introduce a visual catalog with one concise contextual promise; keep images as a horizontal browsing experience.

**Text style:** `gallery-heading` — Focal 500 · 48px/1

### Rail and capability field

**Observed:** Inside the marketing-container, a narrow 60px title wraps into a compact vertical block at left. The much wider right field contains one broad Capability card, followed by two narrower pastel siblings with 16px gutters. A pronounced open gutter separates title rail and cards.

**Transfer:** Adapt the number and arrangement to the offering while keeping the lopsided rail-to-content proportion.

**Text style:** `section` — Focal 500 · 60px/1

### Technical benefit grid

**Observed:** Another narrow heading rail faces a two-column grid of Feature cards. Short text sits above diagrams, with 32px insets and 16px gutters. Long white space after the chapter lets the next field feel distinct.

**Transfer:** Pair claims with concrete illustrated mechanisms or comparisons; keep each card focused on one advantage.

**Text style:** `card-heading` — Focal 500 · 30px/1.2

### Dark assurance chapter

**Observed:** Dark proof field carries a large white 80px/70px heading and supporting identities at left. Four narrow 165px columns at right align to a common bottom: muted explanation blocks above pastel assurance blocks with different heights and 12px corners. Small pixel clusters decorate the lower portions. Large lattice art clips into the top-left edge.

**Transfer:** Turn four trust dimensions into a staircase-like composition; give each a concrete explanation rather than four empty colored bars.

**Text style:** `proof-display` — Focal 500 · 80px/70px

### Floating testimonials

**Observed:** Three Testimonial cards of unequal width orbit an 80px tightly tracked two-line statement. A large pixel silhouette balances the far right. The composition is deliberately looser than the preceding card grid.

**Transfer:** Keep compact human proof around one memorable statement; use true customer material and an identity system suitable for the new product.

**Text style:** `testimonial-display` — Focal 500 · 80px/0.9 · tracking -0.04em

### Contained closing appeal

**Observed:** Purple conversion stage centers a 60px/60px multiline statement over a 24px supporting paragraph in a roughly 668px measure, using 32px internal content gaps. A light primary and outlined dark secondary sit below; sparse pixels enter from opposing corners.

**Transfer:** Restate the practical ambition of the product in one expansive sentence and provide self-service and assisted paths.

**Text style:** `section` — Focal 500 · 60px/1

### Directory and identity finish

**Observed:** Cyan stage begins with a 30px closing prompt and right-aligned dark action, then a faint divider. Compact directory groups follow after 40px, while a large lower open area gives the Monumental identity ending room. Legal text sits low left. The 6px segmented strip closes the field.

**Transfer:** Use appropriate resource categories but preserve the dense top / monumental bottom contrast. The infrastructure variant uses pink, a tighter directory and larger black identity instead of repeating the cyan prompt.

**Text style:** `footer-prompt` — Focal 500 · 30px/1.2 · tracking -0.02em

### Editorial reading and onward path

**Only for:** editorial pages

**Observed:** White two-column reading layout places metadata and hierarchical contents in the 272px rail. Cyan highlights identify the active contents item. The 768px prose column begins with a wide feature image, a left-rule summary, then bold 30px headings, 24px subheads and 18px/32px paragraphs. Lists indent 28px and have 12px inter-item gaps. Product cards interrupt the reading before a sign-in continuation, followed by a cyan onward-action band, three Related article cards and the shared directory finish.

**Transfer:** Use the editorial hierarchy for genuinely instructional content. Make continuation and related reading explicit rather than disguising the article as a marketing card grid.

**Text style:** `article-body` — Focal 400 · 18px/32px

### Infrastructure depth and contact

**Only for:** infrastructure product pages

**Observed:** Centered pale-blue opening leads to operational demonstrations, then a left-side chapter index beside long illustrated explanations. A dashed-outline pricing table precedes full-width olive, pink and cyan proof bands. Oversized colored category labels and a dated vertical timeline add rhythm before dashed FAQ rows. The ending pairs a pale-blue pitch on olive with a white contact form, followed by the pink directory and huge identity.

**Transfer:** Borrow this deeper pacing for technical buying decisions, using pricing, implementation and objections where relevant; keep these elements scoped to a detailed product treatment.

**Text style:** `infrastructure-heading` — Focal 500 · 54.7px/0.96 · tracking -0.0263em

## Page flow

**Storyline:** Expansive promise → tangible visual proof → capability choices → reasons to trust → human validation → conversion invitation → directory and oversized identity.

### Broad platform or product landing page

1. **Promise** — Cyan playground with giant left-aligned type, graphic fragments and paired actions.
2. **Visual proof** — Trust caption and an image-first horizontal gallery.
3. **Capability choices** — Narrow heading rail beside a wide pastel card and paired companion cards.
4. **Differentiation** — Neutral two-column cards containing small technical illustrations.
5. **Assurance** — Dark chapter with staggered pastel proof columns.
6. **Social proof** — Floating compact quotes around an oversized statement.
7. **Closing call** — Contained purple invitation, followed by a cyan directory and huge identity.

**Transfer:** Use this as the default composition language, varying the narrative order and number of chapters to match the product.

### Detailed infrastructure product explanation

1. **Promise and demonstration** — Centered pale-blue headline and large atmospheric analytics stage.
2. **Implementation depth** — Indexed demonstration chapters covering setup, operation and scale.
3. **Commercial clarity** — Dashed pricing table with concrete hardware and cost comparisons.
4. **Proof and breadth** — Colored narrative bands, testimonials and oversized category labels.
5. **Objection handling** — Timeline and FAQ with dashed separators.
6. **Closing call** — Olive pitch paired with a white lead form, then a pink directory and giant black identity.

**Transfer:** Support a longer technical evaluation with demonstrations and transparent details, while retaining large type and flat color territories.

### Educational guide that leads readers back to the product

1. **Topic promise** — Compact cyan masthead with breadcrumb, title and descriptive deck.
2. **Instruction** — Wide conceptual lead image, contents rail, summary and spacious prose with worked examples.
3. **Product bridge** — Small pastel product choices and a visible sign-in continuation.
4. **Onward action** — Cyan action band and a three-card related-reading grid.
5. **Directory finish** — Shared cyan closing prompt, link directory and monumental identity.

**Transfer:** Keep long-form reading calm and practical, with branded framing around rather than inside every paragraph.

## Writing

Confident and technically fluent, but approachable enough to say what the system makes easier. Marketing claims are direct and ambitious; guides become explanatory, concrete and sequential.

**Do not copy:** Do not reuse the fal identity, product names, customer names, quotations, benchmark figures, scale claims, prices or branded illustrations. Source examples below illustrate sentence construction only; substitute verified facts and original assets for the new product.

- **Addressing the reader:** Use you and your for practical benefits, we for production experience, and the product name for declarative platform claims.
- **Rhythm:** Short declarative headlines alternate with compact, information-rich supporting paragraphs. Three-verb phrases and paired contrasts create momentum; full stops are welcome in headlines. Instructional prose uses longer explanatory sentences and exact examples.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the category and audience without a metaphor. | 5–9 words | “Generative media platform for developers.” |
| Chapter heading | A three-part verb sequence or a blunt capability statement. | 3–6 words | “Build, deploy, train.”<br>“Built for enterprise scale” |
| Benefit support | Explain the concrete workflow, then remove a specific friction. | 1–3 sentences | “All accessible with a simple API. No fine-tuning or setup needed — just call and go.” |
| Primary action | Plain verb plus object, or a familiar low-friction next step. | 1–3 words | “Get started”<br>“Explore models”<br>“Contact Sales” |
| Technical value heading | Tie a commercial or operational result to a simple action. | 4–9 words | “Pay for what runs”<br>“Deploy to production without managing infrastructure” |
| Instructional heading | Name a technique precisely and describe its place in the process. | 3–9 words | “Genre and Mood as Your Starting Point”<br>“Strategic Descriptor Layering” |

**Words and phrasing to use:** build; deploy; production; on-demand; scale; ready; custom; one place; without managing; from prototype to

**Avoid:** magical; revolutionary journey; unleash limitless potential; synergy; effortless everything

**Rules:**

- Keep each feature claim attached to a mechanism, practical example or verified result.
- Use numerical proof sparingly and specifically rather than decorating every card with a statistic.
- Distinguish self-service exploration from sales assistance with explicit action labels.
- For guides, explain the general rule, give a literal worked example, then explain why it works.

## Do's and Don'ts

### Do

- Keep the default hero at weight 500 with 120px/100px type and -0.04em tracking on desktop.
- Use 4px corners on ordinary buttons and feature panels, preserving their compact rectangular feel.
- Keep ordinary button height at 44px and opening actions at 48px.
- Inset feature text by 32px and separate paired cards by 16px.
- Let 60px headings wrap inside narrow rails rather than stretching every title across the page.
- Repeat crisp pixel motifs beyond the opening so the graphic language connects chapters.
- Use the 563×225px identity gesture and 6px segmented strip to give the footer a real finish.
- Keep instructional prose at 18px/32px within a 768px reading measure.

### Don't

- Do not turn the default page into an all-dark developer template; the long working middle is white.
- Do not use pill-shaped primary actions; the main action system has 4px corners.
- Do not add soft elevation shadows to every card; flat fills supply grouping.
- Do not spread fluorescent yellow into body text or ordinary button fills; it belongs to artwork.
- Do not apply -0.04em tracking to 16px paragraphs; body copy uses normal tracking.
- Do not replace compact 14px testimonials with giant editorial pull quotes; the central statement carries the scale.
- Do not homogenize the pastel cards into one cyan tint; lavender and pale lime define separate capabilities.
- Do not make every chapter a centered headline plus equal-width icon tiles; preserve the rail, asymmetric proof columns and floating quote compositions.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, border-color, color, transform and opacity transitions at 0.16s with cubic-bezier(0.25, 0.46, 0.45, 0.94), and an active scale of 0.98.
- The graphic vocabulary includes canvas pixel clusters and declared connection/generation animations; their exact movement paths are not specified here.

**Transfer:**

- Keep action feedback compact and fast; apply the declared 0.16s treatment to the rectangular action system.
- If animating the pixel art, preserve square-cell edges and keep the text layer stationary and readable.

**Unknown:**

- Timing and choreography of the decorative hero scene, scroll-linked art and dashboard video are not established.

### Responsive

**Observed:**

- Desktop hero uses 120px type; declared classes include a small-screen 46px size with 39.6px leading.
- Capability pairs declare a column-to-row change, feature cards declare one column before two, and editorial reading declares one column before the sidebar layout.
- The testimonial desktop composition is separately gated from smaller-screen treatment.

**Transfer:**

- On narrow screens, stack the heading rail above its cards and preserve the 16px gutters.
- Use the 46px/39.6px opening treatment, keep actions readable, and clip rather than compress the graphic fragments.
- Keep portrait gallery cards at a legible size in horizontal overflow; do not shrink four cards into the phone width.
- Place editorial contents above the reading column and stack footer groups; keep the final identity visibly oversized relative to utility text.

**Unknown:**

- Exact mobile art positions, alternate testimonial composition and all intermediate breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
