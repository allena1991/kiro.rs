# Fonts in Use — specimen-led editorial index

## Overview

An independent-publication aesthetic where a restrained black-and-white interface gives vivid collected work the stage. Condensed sans navigation, tiny factual annotations and a dense image index create the feeling of a working reference library rather than a sales presentation. It suits products whose examples, collections or customer output can carry the story through photography, printed matter and graphic specimens.

### Essentials

- The masthead behaves like a publication, not a hero banner: a 140×118px stacked black wordmark sits beside a small 12px mission line and 36px condensed section navigation.
- Browsing is the main invitation: 16px bold category headings sit in a 43px horizontal strip, followed by right-aligned 12px filters and sorting rather than a dominant conversion button.
- The interface stays entirely neutral: white canvas, black text and #999999 secondary controls; saturated color belongs inside square artwork, never broad interface bands.
- Proof arrives as an aligned image index: an 1180px container holds five 220px square images with 20px gutters, followed by exposed specimen labels separated by #f0f0f0 hairlines.
- Editorial selection has a physical corner mark: a black 75px triangular fold with white 18px condensed lettering rotated 45deg. Carry this device onto selected examples even when the product has no physical artifacts.
- Actions retain an older web utility: underlined text links and compact 30px gray buttons with 2px corners, ending in a 5px black footer rule instead of a promotional closing panel.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, accent | Primary type, structural rules and editorial corner badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, text, surface | Canvas and search field; reversed type on badges and gray controls. |
| Media backing and specimen rules | `#f0f0f0` | `--color-media-backing` | surface, border | Backing beneath loaded imagery and fine dividers between specimen rows; not an empty tile treatment. |
| Field edge | `#dddddd` | `--color-field-edge` | border | Search outline and occasional edges around pale artwork. |
| Strip edge | `#cccccc` | `--color-strip-edge` | border, surface | Lower edge of category strip and inactive layout controls. |
| Secondary gray | `#999999` | `--color-secondary` | text, action, surface | Inactive section navigation, sponsor annotations and pagination fills. |

## Typography

- **BentonSansRE** — Interface, support lines, filters and footer. Compact, readable grotesk with a substantial bold and a pragmatic small-text texture. If unavailable, use **Libre Franklin**. Use 400 and 700; preserve compact sizes and normal tracking. Font stack: "BentonSansRE", "Libre Franklin", Verdana, sans-serif.
- **RelayCond** — Major section navigation and editorial corner labels. Narrow, upright sans with emphatic bold shapes; contrasts with the wide utility text. If unavailable, use **Barlow Condensed**. Use 400 for inactive sections and 700 for active labels. Font stack: "RelayCond", "Barlow Condensed", Arial, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| section-title | RelayCond | 700 | 36px | 1 | normal | Primary section name, simultaneously a navigation link and the largest live interface heading. |
| section-title-inactive | RelayCond | 400 | 36px | 1 | normal | Sibling section navigation in secondary gray. |
| selection-label | RelayCond | 700 | 18px | 1.6 | normal | White diagonal editorial selection lettering. |
| category-heading | BentonSansRE | 700 | 16px | 1.2 | normal | Category-strip headings; the section-heading role stays compact. |
| body-link | BentonSansRE | 400 | 14px | 1.6 | normal | Footer links and ordinary reading text; navigation links are underlined. |
| utility | BentonSansRE | 400 | 12px | 1.6 | normal | Mission line, filters and pagination. |
| utility-strong | BentonSansRE | 700 | 12px | 1.6 | normal | Active filter, chosen sort label and short sponsor name. |
| micro-link | BentonSansRE | 400 | 10px | 1.6 | normal | Sign-in and small supporting links. |

**Notes:**

- Normal tracking is the rule throughout; hierarchy comes from condensed versus regular width, boldness and placement rather than letter spacing.
- The wordmark and diverse specimen labels are graphic content, not additional global heading fonts. Keep general interface copy in the two core families.

## Layout

**Density:** Compact interface above a spacious, image-led index; short utility lines contrast with variable-depth specimen rows.

### Spacing

**Spacing system:**

- **vertical rhythm** 10px, vertical — Main vertical margins and section separation; 5px is used for compact control padding.
- **horizontal step** 20px, horizontal — Grid gutters and footer group separation.

| Value | Use |
| --- | --- |
| 5px | Vertical padding of compact gray actions. |
| 10px | Footer top padding, control grouping and search side padding. |
| 20px | Column gutters, masthead-to-category separation and gallery bottom margin. |
| 30px | Outer top and bottom margins, gallery-cell bottom margin and separation before footer. |

### Containers and grids

- **publication container**: max width 1180px. Centered desktop wrapper shared by masthead, filters, gallery and footer; 130px side margins at 1440px.
- **example index**: 5 columns · gap 20px. Equal 220px desktop columns. Each row shares its image top edge and advances below the deepest caption stack, with 30px cell bottom margin.
- **masthead**: 2 columns · gap 100px. A 140px wordmark block at left and a 940px right region. The right region has a mission line above section navigation, with search and account access at its far right.

## Corner radius

| Element | Radius |
| --- | --- |
| compact actions | 2px |
| search field | 3px |
| media and specimen rows | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| category-strip inset | `rgba(0, 0, 0, 0.3) 0px 8px 8px -5px inset` | A shallow shaded lip immediately beneath the masthead rule. |
| search inset | `rgba(0, 0, 0, 0.05) 1px 1px 3px 1px inset` | Subtle recessed search field, not an elevated panel. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous background for the whole page.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No alternating colored section backgrounds.

**Transfer:** Let the content images supply color and material.

#### Square media stage · level 0

**Use:** Uniform picture frames inside the index.

**CSS:** `background: #f0f0f0; width: 220px; height: 220px; overflow: hidden; position: relative`

**Observed:** Images fill the frame; some pale works use a faint outline. Cards have no surrounding container panel.

**Transfer:** Use real, loaded examples of equal visual scale.

#### Category lip · level 0

**Use:** Full-width category navigation under the masthead.

**CSS:** `height: 43px; border-bottom: 1px solid #cccccc; box-shadow: rgba(0, 0, 0, 0.3) 0px 8px 8px -5px inset`

**Observed:** A black masthead rule above it and compact bold category names make a publication-like threshold.

**Transfer:** Use this as a shallow navigational band, not a feature card.

## Components

### Section navigation

**Use:** Choose the primary content area.

**CSS:** `color: #000000; font-size: 36px; line-height: 36px; font-weight: 700`

**Text style:** `section-title` — RelayCond 700 · 36px/1

**Observed:** Large condensed words sit along the lower masthead baseline; the inactive sibling is regular weight and secondary gray.

**Transfer:** Use short content-area nouns, not promotional slogans.

### Category trigger

**Use:** Expose a browsing taxonomy.

**CSS:** `display: flex; align-items: center; color: #000000; font-size: 16px; font-weight: 700; line-height: 19.2px`

**Text style:** `category-heading` — BentonSansRE 700 · 16px/1.2

**Observed:** A small solid downward triangle immediately follows the text. Several headings share the Category lip.

### Search field

**Use:** Direct lookup at the far right of the masthead.

**CSS:** `width: 220px; height: 32px; padding: 0px 10px; background: #ffffff; border: 1px solid #dddddd; border-radius: 3px; box-shadow: rgba(0, 0, 0, 0.05) 1px 1px 3px 1px inset`

**Observed:** Light magnifying glass at the right edge, with a tiny advanced-search helper directly below.

### Filter and sort line

**Use:** Narrow a collection without a separate control panel.

**CSS:** `display: flex; gap: 10px; font-size: 12px; line-height: 19.2px; color: #000000`

**Text style:** `utility` — BentonSansRE 400 · 12px/1.6

**Observed:** Right-aligned above the gallery. Counts sit in parentheses; active filter and chosen sort are bold, with small layout-toggle squares at the end.

### Example card

**Use:** Primary proof unit.

**CSS:** `width: 220px; overflow: hidden`

**Observed:** Square media comes first, then one or more full-width visual specimen labels with pale horizontal separators. Caption stacks vary in depth; there is no padded shell or drop shadow.

**Transfer:** Show the new product's output or use case, followed by concise visual identifiers. If no specimen artwork exists, make high-contrast text strips in the core sans rather than introducing unrelated display families.

### Selection corner

**Use:** Editorial emphasis on a minority of examples.

**CSS:** `position: absolute; top: 0px; right: 0px; width: 0px; height: 0px; border-top: 75px solid #000000; border-left: 75px solid rgba(0, 0, 0, 0)`

**Text style:** `selection-label` — RelayCond 700 · 18px/1.6

**Observed:** The black upper-right fold carries a separate white lettering layer rotated 45deg and clipped with the picture.

**Transfer:** Use a short, credible curation label.

### Compact gray button

**Use:** Sequential browsing actions.

**CSS:** `display: inline-flex; align-items: center; height: 30px; padding: 5px 10px; background: #999999; color: #ffffff; border-radius: 2px`

**Text style:** `utility` — BentonSansRE 400 · 12px/1.6

**Observed:** Numbers and Next/Last form a small left-aligned row; the current number is bold black without a filled button.

**Transfer:** Reuse for low-key utility actions rather than adding a large conversion pill.

### Underlined text link

**Use:** Footer navigation and lightweight participation links.

**CSS:** `color: #000000; text-decoration: underline; font-size: 14px; line-height: 22.4px`

**Text style:** `body-link` — BentonSansRE 400 · 14px/1.6

**Observed:** Footer links form short vertical columns. Header participation links use the micro-link recipe.

### Ruled footer

**Use:** Compact institutional close.

**CSS:** `display: flex; border-top: 5px solid #000000; padding-top: 10px`

**Text style:** `body-link` — BentonSansRE 400 · 14px/1.6

**Observed:** Multiple narrow groups cluster at the left with 20px separation; feed links have a plain heading. Copyright is isolated at the far right, leaving the middle open.

**Transfer:** Close with support, policy and subscription destinations rather than an oversized sales pitch.

## Imagery and graphics

### Collected work squares

**Use:** Dominant visual proof across the index, starting in the first screen.

**Observed:** A deliberately mixed collection: printed books, posters, packaging, apparel, lettering compositions and website views. Tight square framing alternates object close-ups, overhead or oblique photography and flat graphic artwork. Concrete, paper grain, embossing, fabric and natural shadows remain visible. Saturated reds, purple, yellow and blue coexist without a shared color grade; text occupies much less area than imagery.

**Transfer:** Gather actual outputs, artifacts or customer applications in equally sized square frames. For a digital-only product, combine crisp interface details with finished export examples or photographed devices; preserve each work's own palette instead of tinting the set.

### Visual specimen captions

**Use:** Distinctive strips immediately beneath example images.

**Observed:** Black specimen lettering on white appears in a range of serif, sans and mono constructions, divided by very pale rules. These are rendered samples of the work rather than the interface typeface.

**Transfer:** Create a compact visual identifier for each output: a word specimen, named result or recognizable product detail. Keep it monochrome and edge-aligned; minimum version is a clear black text strip with the core sans.

**Build:** Create white SVG strips matching the 220px media width, place a short black product-specific label near the left edge, and add a 1px #f0f0f0 top rule between strips. Fit longer labels onto two lines rather than compressing them.

### Stacked masthead mark

**Use:** Strong identity anchor in the opening.

**Observed:** A tall, densely packed black uppercase wordmark is stacked into two lines inside a 140×118px area; it is the visual counterweight to the tiny mission copy.

**Transfer:** Compose a new compact typographic mark in a bold condensed face, or stack a short product descriptor beside the actual logo. Preserve the black rectangular silhouette and strong two-line rhythm.

**Build:** Use a transparent 140×118px SVG viewBox with two left-aligned uppercase lines in a heavy condensed sans. Fit each line to the block width with tight internal leading; use black fills, no outline or background plate.

### Icons

**Observed:** Small utilitarian glyphs: solid downward triangles, a pale search magnifier and 16px grid-layout masks inside 18px gray squares. No decorative icon system.

**Transfer:** Keep icons monochrome, compact and directly attached to their control; use simple square-grid and search geometry.

## Section recipes

How recurring sections are built.

### First screen: Publication index opening

**Observed:** White paper underlies an 1180px centered layout with 30px top margin. A 140×118px stacked mark anchors the left; mission and sponsor lines sit high in the adjacent region, while account access occupies the far right. The lower masthead carries 36px condensed section names and a 220×32px search field. After 20px comes the 43px Category lip with three compact category headings; a small right-aligned Filter and sort line sits above the first images. The gallery begins about 273px down: five 220px squares, visual caption strips and the start of the next row are visible inside 900px. Content is layered as canvas, rules, imagery and occasional diagonal Selection corner. There is no standalone promotional headline or oversized action.

**Transfer:** For a new landing page, let a short mission statement plus an immediately useful example index serve as the promise. Use finished outcomes in the first row; create crisp output or interface specimens when physical media is unavailable. A detail-oriented page can retain this compact masthead and open below it with the chosen work.

**Avoid:** Do not replace the first screen with a centered slogan, floating browser mockup and two giant buttons.

**Text style:** `section-title` — RelayCond 700 · 36px/1

### Curated proof index

**Observed:** Example card units repeat in five equal columns with 20px gutters. Square media tops align while variable caption stacks determine row depth. Selection corner appears only on chosen works; a sponsor tile occupies a normal grid cell and adds tiny factual copy beneath its artwork.

**Transfer:** Mix types of real proof while keeping the same frame geometry. A partnership or announcement can join the grid without becoming a full-width campaign band.

### Utility ending

**Observed:** After the final image row, a small left-aligned pagination line uses Compact gray button with a plain current number. A 30px separation leads to Ruled footer, whose 5px black top rule restores the opening's publication structure. Underlined columns and a far-right copyright finish the page without a colored closing section.

**Transfer:** Offer continuation or an equivalent small next step, then close with compact grouped navigation. Preserve the heavy footer rule even on shorter pages.

**Text style:** `body-link` — BentonSansRE 400 · 14px/1.6

## Page flow

**Storyline:** identity and purpose → ways to browse → concrete proof → continuation → institutional close

### A browsable showcase that earns interest through accumulated examples rather than promotional claims

1. **Orientation** — Stacked identity, one-line purpose and large condensed content-area links share a compact masthead.
2. **Discovery** — Category strip and small filter/sort controls establish multiple routes into the material.
3. **Product proof** — A long aligned image index mixes colorful outputs with monochrome visual labels and occasional curation folds.
4. **Continuation** — Small gray pagination keeps deeper browsing available.
5. **Institutional close** — Heavy black rule, terse link columns and isolated copyright end the page.

**Transfer:** Translate the index into customer outcomes, templates, projects or product applications. Keep the useful browsing affordances and artifact-led proof; the number of rows can follow the content.

## Writing

Factual, independent and editorial. Confidence comes from precise labeling and accumulated work, with little self-congratulation.

**Do not copy:** Do not reuse the brand wordmark, archive mission, sponsor names, contributor work, collection counts or proprietary specimen artwork and claims. Replace them with the new product's truthful identities, assets and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal nouns and labels; direct address appears only in small participation or browsing actions.
- **Rhythm:** One-word section names, brief utility phrases and one-sentence purpose lines; promotional support is compressed into short factual fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section title | A plain content-area noun that doubles as navigation. | 1 word | “Collection”<br>“Blog” |
| Purpose line | An article, a positioning adjective and an exact description of what the service holds or does. | 6–9 words | “An independent archive of typography.” |
| Browsing action | A concise verb plus the thing to inspect. | 2–4 words | “Explore the catalogue” |
| Utility label | Literal category or chosen ordering, without a benefit claim. | 1–3 words | “Formats”<br>“Contribution Date” |

**Words and phrasing to use:** collection; independent; explore; formats; contribution; selected; contact

**Avoid:** revolutionary; unlock your potential; supercharge; game-changing; ultimate; !!!

**Rules:**

- Name the material clearly before explaining its benefit.
- Use counts only when real and maintainable; put them in parentheses beside filters.
- Keep sponsorship and editorial selection explicitly labeled.
- Make actions describe their destination, not an abstract aspiration.

## Do's and Don'ts

### Do

- Keep the main desktop width at 1180px and align masthead, gallery and footer edges.
- Use 36px condensed section links as the highest live-text hierarchy.
- Keep core interface tracking normal and reserve bold for selected labels.
- Frame examples in 220px squares with 20px column gutters.
- Separate visual specimen rows with 1px pale rules.
- Use a black diagonal corner on selected proof items.
- Finish with a 5px black rule and compact 14px underlined footer links.

### Don't

- Do not turn the neutral shell into a purple or yellow brand theme just because an image uses that color.
- Do not round picture tiles or wrap them in elevated cards.
- Do not enlarge 12px sorting controls into a spacious dashboard toolbar.
- Do not use the many specimen typefaces as global body or navigation fonts.
- Do not substitute pill-shaped 48px actions for the compact 30px utility buttons.
- Do not force every caption stack to the same number of lines; aligned image tops matter more.
- Do not apply one muted color grade to every image; the collection relies on independent palettes.

## Motion and responsive

### Motion

**Observed:**

- No transitions or animations are associated with the principal actions and surfaces.

**Transfer:**

- Keep the index and masthead visually stable; diagonal selection marks are static graphic devices.

**Unknown:**

- Hover and focus styling and interaction timing are not established.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 640px, 768px, 992px, 1024px and 1200px.

**Transfer:**

- Preserve square imagery, left-aligned specimen strips and the heavy closing rule when reducing column count.
- Reflow the masthead's mission, section links and search rather than shrinking the desktop layout as a single block.

**Unknown:**

- Exact mobile column counts, wrapping and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
