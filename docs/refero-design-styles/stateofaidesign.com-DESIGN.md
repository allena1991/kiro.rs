# State of AI Design — botanical signal, editorial scale

## Overview

An oversized editorial identity pairs experimental botanical graphics with sober, research-minded typography. White reading fields, black closing panels, lilac, coral and pale sage create a publication-like marketing language rather than a conventional software dashboard. Tight grotesk headlines, tiny monospaced labels and warm documentary portraits make it suitable for ambitious tools, creative platforms and substantial product stories; density alternates between spacious visual stages and compact reading columns.

### Essentials

- The opening behaves like an animated publication cover: a full-width botanical collage above a split white title strip, with 120px/0.95 medium grotesk type tracked at -0.06em on the right and 20px/1.2 support on the left.
- Headlines are compressed without becoming heavy: weight 500, -0.04em tracking at 40px and 50px, and -0.06em at 80px and 120px. Small section markings use 13px/1 Geist Mono capitals with normal tracking.
- Color arrives as entire editorial territories, not scattered decoration: coral #fe7141, lilac #cdabfe and sage #d1ddd3 fill chapter-size panels of about 900px height, while explanatory reading stays white and the common ending turns black.
- Actions are cut rectangles, not pills: navigation is 56px high; the orange submit action is 123px wide and 63px high. Long black action bars place their label at the left and a simple arrow at the far right.
- Organic imagery is translated into digital specimens: soft coral and lilac flowers, sage foliage, grayscale enlargements and hard rectangular sample windows. Include this natural/digital contrast even without custom video, using a recolored macro photograph and a glyph-grid derivative.
- The grid is conspicuously off-center: 16px outer gutters and 16px column gaps over 12 columns; the main reading lane begins around the sixth column, leaving a broad left field for labels and navigation.
- The ending is a typographic poster, not just utility links: a black 680px signup band leads into ruled 120px statistics, an almost full-width white wordmark graphic, small lower-left link groups and an oversized lower-right date or edition marker.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lilac territory | `#cdabfe` | `--color-lilac` | background, surface, accent, action | Navigation blocks, proof tiles, whole capability panels and primary chart bars. |
| Coral territory | `#fe7141` | `--color-coral` | background, surface, action, accent | Main navigation emphasis, submission action and whole capability panels. |
| Sage territory | `#d1ddd3` | `--color-sage` | surface, background, accent | Large quotation field, secondary proof tiles and capability territory. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-paper` | background, text, surface | Reading canvas, input surface and reversed text. |
| Soft rule | `#999999` | `--color-rule` | border, text | Visible result of black at 0.4 opacity over white in resource separators and secondary directory roles. |
| Secondary gray | `#666666` | `--color-muted` | text | Secondary captions and role labels; black at 0.6 opacity also produces this gray on white. |
| Black ink | `#000000` | `--color-ink` | text, background, action | Default text, black action bars and the closing canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form articles and institutional profiles | Cold paper | `#f5f9fc` | `--color-panel` | surface | Quotation groups and practical editorial callouts. |
| data-rich editorial pages | Chart ink | `#111111` | `--color-chart-ink` | text, border | Chart headings and 1px or 2px upper rules. |

## Typography

- **Beausite Classic** — All main headings, numbers, paragraphs and actions; regular, medium and bold cuts. A crisp grotesk with compact proportions and strongly tightened display spacing. If unavailable, use **Inter**. Use 400 and 500 primarily; preserve the narrow measure and negative tracking. Font stack: "Beausite Classic", "Inter", Arial, sans-serif.
- **Geist Mono** — Uppercase editorial labels, section markings and contributor roles. Small technical monospace, sober and closely set. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Beausite Classic | 500 | 120px | 0.95 | -0.06em | Main landing title and large editorial cover titles. |
| proof-number | Beausite Classic | 500 | 120px | 1 | normal | Large white numerals in the black closing proof band. |
| chapter-marker | Beausite Classic | 500 | 80px | 0.95 | -0.06em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Large stacked section number and short category title in colored panels. |
| statement | Beausite Classic | 500 | 50px | 1 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Manifesto-sized statements, major quotation and centered closing heading. |
| heading | Beausite Classic | 500 | 40px | 1.1 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Section headings and capability descriptions. |
| lead | Beausite Classic | 500 | 32px | 1.2 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Introductory statements and proof-band lead-in. |
| card-title | Beausite Classic | 500 | 24px | 1.2 | -0.03em | Case titles, resource titles and medium-size quotation text. |
| support | Beausite Classic | 400 | 20px | 1.2 | -0.03em | Hero support and centered signup explanation. |
| navigation | Beausite Classic | 500 | 18px | 1 | -0.03em | Navigation and short rectangular actions. |
| submit | Beausite Classic | 500 | 18px | 1.28 | -0.03em | Form submit label. |
| body | Beausite Classic | 400 | 16px | 1.4 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Default narrative paragraphs and capability summaries. |
| caption | Beausite Classic | 400 | 14px | 1.4 | -0.01em | Case subtitles, secondary explanations and form notes. |
| eyebrow | Geist Mono | 500 | 13px | 1 | normal, uppercase | Section labels and small editorial navigation markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial chapter summaries | stat-number | Beausite Classic | 500 | 85px | 1 | normal | Percentages in three-up summary strips. |
| long-form articles | article-heading | Beausite Classic | 500 | 30px | 1.4 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Subsection headings within the right-side reading lane. |
| attributed quotations and contributor directories | role-label | Geist Mono | 500 | 13px | 1.2 | -0.03em, uppercase | Role and organization below a speaker name. |

**Notes:**

- Use the medium cut as visual weight 500, not bold. Display tracking is tighter than body tracking; the large proof numerals deliberately retain normal tracking.
- Headings remain sentence case. Uppercase belongs to small monospaced markings, not the main message.
- The full-width closing identity is artwork rather than another 120px heading: size an SVG wordmark to the available 1408px width and preserve its proportions.

## Layout

**Density:** Airy at the page scale, compact within text groups; enormous left-hand negative space contrasts with close-set paragraphs and ruled lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Name-to-role and title-to-subtitle separation. |
| 10px | Small link groups and utility stacks. |
| 16px | Outer gutter, grid gap and standard panel inset. |
| 20px | Paragraph separation in articles and form-button vertical inset. |
| 24px | Introductory paragraph separation and small section-label padding. |
| 32px | Capability title-to-body gap and resource-group opening. |
| 40px | Image-to-case-title group separation. |
| 48px | Article subsection breathing room. |
| 56px | Signup explanation-to-form gap. |
| 60px | Article block trailing space. |
| 88px | Space below an introductory statement. |

### Containers and grids

- **page grid**: max width 1920px · 12 columns · gap 16px · side padding 16px. Full-width editorial grid. At 1440px, content occupies 1408px; the major right lane begins at 609px and spans 815px.
- **reading lane**: max width 696px. Article charts and quotation panels align to the right lane; paragraph measure is narrower at about 554px.
- **intro lane**: max width 577px. Landing-page introductory copy occupies a narrow right lane beside a largely empty left field.
- **case grid**: 3 columns · gap 16px · side padding 16px. Three 460px-wide case tiles in a horizontal strip; article recommendations use two larger tiles instead.
- **signup measure**: max width 670px · side padding 16px. Centered heading and supporting copy; the form itself is 664px wide.
- **closing proof grid**: 4 columns · gap 0px · side padding 16px. One lead-in cell and three numerical proof cells, each 352px wide at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | rectangular panels and actions | 0px |
| attributed quotations | speaker portraits | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default landing and narrative background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat white with no raised-card effect.

**Transfer:** Let typography and thin separators establish hierarchy.

#### Colored territory · level 0

**Use:** Capability-sized stage and high-impact proof field.

**CSS:** `background: #fe7141; color: #000000; border-radius: 0px; box-shadow: none`

**Observed:** Flat edge-to-edge color; lilac and sage are equal-status alternate territories. Text stays black.

**Transfer:** Assign one hue to a whole content territory instead of multicoloring individual words.

#### Black closing canvas · level 0

**Use:** Conversion, quantified proof and monumental identity.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Signup and footer form one uninterrupted dark ending. White rules structure the proof cells and bottom credits.

**Transfer:** Keep this a deliberate reversal of the white reading canvas.

#### Sage quotation field · level 0

**Use:** Oversized perspective statement beside a black attribution panel.

**CSS:** `background: #d1ddd3; color: #000000; padding: 16px`

**Observed:** A large uninterrupted pale field, aligned flush to the adjacent black block.

**Transfer:** Preserve the asymmetrical split and the abundant empty area beneath the quotation.

#### Cold editorial panel · level 1

**Only for:** long-form articles and institutional profiles

**Use:** Quoted testimony and in-practice notes.

**CSS:** `background: #f5f9fc; color: #000000; border-radius: 0px; box-shadow: none`

**Observed:** Single panels or two/three columns with thin vertical dividers; no decorative border shell.

**Transfer:** Use for detailed supporting voices rather than every marketing feature.

## Components

### Navigation block

**Use:** Primary destinations in a horizontal editorial header.

**CSS:** `height: 56px; background: #cdabfe; color: #000000; display: flex; align-items: center; justify-content: center; gap: 8px; border-radius: 0px`

**Text style:** `navigation` — Beausite Classic 500 · 18px/1 · tracking -0.03em

**Observed:** Compact black identity at the left, a broad colored destination block beside it, and secondary destinations at the right. Plus signs mark expandable destinations. Secondary-page headers put the right destinations on white; the broad colored block can follow the active territory.

**Transfer:** Use few destinations and preserve the block construction rather than a floating navigation capsule.

### Submit button

**Use:** Conversion action joined to the email field.

**CSS:** `background: #fe7141; color: #000000; width: 123px; height: 63px; border-radius: 0px; border: none; display: flex; align-items: center; justify-content: center`

**Text style:** `submit` — Beausite Classic 500 · 18px/1.28 · tracking -0.03em

**Observed:** The action occupies the right end of the white form with no gap, outline or rounded container.

### Email strip

**Use:** Single-field signup on the black canvas.

**CSS:** `background: #ffffff; height: 63px; max-width: 664px; padding: 12px 12px 12px 20px; border-radius: 0px; display: flex; align-items: center; overflow: hidden`

**Observed:** The text input expands across the strip, with Submit button flush right. A centered explanatory note sits beneath at a 16px gap.

**Transfer:** Reserve horizontal room for the action; do not turn the entire form into a raised card.

### Case tile

**Use:** Human proof and entry into a deeper story.

**CSS:** `background: #ffffff; display: flex; flex-direction: column; align-items: flex-start; gap: 40px; border-radius: 0px`

**Text style:** `card-title` — Beausite Classic 500 · 24px/1.2 · tracking -0.03em

**Observed:** Wide documentary still, a narrow lilac strip under the image, then title and a muted subtitle separated by 8px. The default strip presents three tiles, without a card outline.

**Transfer:** Lead with people using or discussing the product, not miniature dashboards.

### Closing proof cell

**Use:** Large-number substantiation before the identity poster.

**CSS:** `padding: 16px; display: flex; flex-direction: column; align-items: flex-start; justify-content: space-between; color: #ffffff`

**Text style:** `proof-number` — Beausite Classic 500 · 120px/1

**Observed:** A large number sits over a short descriptive label. Vertical hairlines divide the cells; a lead-in occupies the first cell rather than a fourth metric.

**Transfer:** Use real measures of the new product's reach, output or reliability.

### Chapter stage

**Use:** Large-scale capability overview.

**CSS:** `background: #fe7141; color: #000000; padding: 16px; border-radius: 0px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `chapter-marker` — Beausite Classic 500 · 80px/0.95 · tracking -0.06em

**Observed:** A top rule, stacked number/category at left and heading/body at right sit above an image and a ruled contents list. The list ends in a full-width black link bar with a right arrow. Lilac and sage provide sibling variants.

**Transfer:** Use the construction for distinct capabilities rather than repeating small feature cards.

### Footer link groups

**Use:** Utility navigation below the monumental wordmark.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(50px, 1fr)); gap: 10px; color: #ffffff`

**Text style:** `body` — Beausite Classic 400 · 16px/1.4 · tracking -0.01em

**Observed:** Small link groups sit at lower left with mono labels above them, opposed to the large edition marker at lower right. A final ruled line holds credits.

### Quote panel

**Only for:** long-form articles

**Use:** Attributed testimony in the reading lane.

**CSS:** `background: #f5f9fc; color: #000000; display: flex; align-items: center; border-radius: 0px`

**Text style:** `body` — Beausite Classic 400 · 16px/1.4 · tracking -0.01em

**Observed:** Opening quotation mark sits in a small left column; the text, circular portrait, name and uppercase role stack in the larger right column. Multi-voice variants split the same pale panel into two or three equal columns with vertical rules.

**Transfer:** For anonymous voices, use a circular botanical sample instead of a fabricated portrait.

### Resource row

**Only for:** long-form articles and case studies

**Use:** Further reading and external resources.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px; padding: 16px 0px; border-bottom: 1px solid rgba(0,0,0,0.4); border-radius: 0px`

**Text style:** `card-title` — Beausite Classic 500 · 24px/1.2 · tracking -0.03em

**Observed:** Title above a smaller domain line with northeast arrow; rows align in the broad right lane beside a left-side section heading.

## Imagery and graphics

### Botanical specimen collage

**Use:** Signature cover art and recurring capability media.

**Observed:** Macro flowers are softened and recolored coral and lilac with pale sage foliage and charcoal or gray shadows. Hard rectangular windows enlarge fragments, sometimes in grayscale, with small white specimen labels. Art dominates the opening; it is not an illustration beside a software mockup.

**Transfer:** Use a natural macro subject related by metaphor rather than literally to the product. Minimum version: a recolored flower, mineral or leaf photograph, three rectangular detail windows and a black typographic identity tile.

**Build:** Fill a wide stage with an enlarged macro image. Remap light regions toward white/lilac, midtones toward coral and shadows toward dark sage. Overlay three to five unrounded rectangles of different sizes using differently positioned copies of that image; make some grayscale, give selected windows a 1px white edge, and attach tiny white mono labels at their lower corners. Place a black identity rectangle over the image, with compact white lettering. Use subtle softening inside the image, never blur the window edges.

### Glyph-grid translation

**Use:** Digital counterpoint to organic imagery in cover media and sample windows.

**Observed:** Botanical forms resolve into dense plus, cross and grid-like glyphs. Black/white variants sit against the colored photographic version; coral/lilac variants appear in institutional bands.

**Transfer:** Generate a glyph rendition of the same macro subject used in the cover so the two languages remain connected.

**Build:** Use an SVG pattern or canvas grid at about 8px intervals. Sample luminance from the botanical image and choose a dot, cross, plus or tightly intersecting strokes per cell; use black backing with gray-to-white glyphs. For the two-color version, use coral backing and lilac glyphs. Keep the field rectangular and aligned to the editorial grid.

### Documentary portraits

**Use:** Case tiles, film stills and explanatory media.

**Observed:** Warm natural-light interviews and people collaborating at tables, with wood, plants and office details. Medium portraits and wide scenes have subdued cinematic contrast, square corners and generous uninterrupted framing.

**Transfer:** Show real practitioners in their environment, at eye level and mid-conversation. Favor a warm, believable scene over isolated studio cutouts.

### Monumental identity poster

**Use:** Signature closing device on the black canvas.

**Observed:** A white wordmark spans 1408px by 278px as a graphic; a separate 591px by 201px edition graphic anchors the lower right. The small navigation looks almost like marginalia beside them.

**Transfer:** Create an equally broad typographic identity using the new product name. If no custom wordmark exists, typeset a short identity phrase in a tightly fitted medium grotesk SVG, with a large edition, release or short closing marker below.

**Build:** Create an SVG with a wide text or outlined-letter viewBox, fit its width to the page grid without distorting letters, and fill it white on black. Separate a second compact SVG for the lower-right marker; keep the link groups on the opposite side and leave substantial black space between the two graphic levels.

### Icons

**Observed:** Mostly solid black arrows, plus signs, play triangles and quotation marks, generally around 22–26px; next-section arrows grow to about 52px. Circular crops belong to speaker portraits, not icon containers.

**Transfer:** Use simple filled directional symbols with no colored icon badges. Keep arrows at the far edge of action rows and plus signs beside expandable labels.

## Section recipes

How recurring sections are built.

### First screen: Publication cover opening

**Observed:** A full-bleed organic specimen collage occupies roughly the upper 700px of the initial 900px view. Hard sample rectangles and a black identity tile layer above the recolored flower field. Beneath, a white title strip divides into a small left support line and a two-line, right-aligned-in-the-grid headline occupying about seven twelfths of the width; the text itself is left aligned at 120px/0.95 with -0.06em tracking. Within the initial 900px, the art, support line and most of the title are visible; its lower line continues below the fold. The scroll prompt and credit sit lower in the title area. Navigation uses Navigation block rather than a central floating button group, and does not need to compete with the cover.

**Transfer:** Make the cover art a product-specific natural/digital visual metaphor using Botanical specimen collage and Glyph-grid translation, then set the product promise in the split title strip. Detailed editorial pages can open on a solid colored title field, with a small chapter marking above 120px type and a split glyph/photo strip below. Case studies instead use a tall glyph field at left and a 50px title over documentary film at right; institutional pages use a shallow glyph banner above a right-lane statement.

**Avoid:** Do not replace this cover with a centered headline and a small laptop render, or put all explanatory content and conversion buttons inside the artwork.

**Text style:** `display` — Beausite Classic 500 · 120px/0.95 · tracking -0.06em

### Ruled editorial statement

**Observed:** A fine horizontal separator introduces a 13px mono label, followed by a 50px statement at about 815px measure. The left-aligned statement has about 40px separation from the label and 88px trailing space.

**Transfer:** Use a concise change-in-the-world statement to set up the product need rather than an unsupported superlative.

**Text style:** `statement` — Beausite Classic 500 · 50px/1 · tracking -0.04em

### Human proof mosaic

**Observed:** A wide warm documentary scene sits next to stacked lilac and sage statistic tiles. The tiles use oversized black numbers, short supporting lines and 16px insets; all edges meet as a flat mosaic.

**Transfer:** Pair one real use-context photograph with two verified proof points; the colored blocks should be substantial, not tiny badges.

### Asymmetrical perspective

**Observed:** A black attribution block occupies the narrower left side, with a small portrait and mono role. Sage quotation field fills the broader right side with a 50px tightly set quotation; the combined field is about 615px tall.

**Transfer:** Give a strong user or expert point of view the scale of a headline instead of making every testimonial a small card.

**Text style:** `statement` — Beausite Classic 500 · 50px/1 · tracking -0.04em

### Capability territory

**Observed:** Chapter stage fills about one desktop viewport. The 80px stacked index/title occupies the left five columns; a 40px heading and narrow body occupy the right. The lower edge brings the macro-art rectangle and ruled contents list into alignment above the black action bar.

**Transfer:** Retain a bold colored territory and a large index even with fewer capabilities; let the narrative determine how many stages it needs.

### Signup and identity ending

**Observed:** Black closing canvas starts with a 680px conversion band: centered 50px heading, 20px support after 28px and Email strip after 56px. Closing proof cell forms a four-column ruled band below. Monumental identity poster follows, with small footer links lower left, edition marker lower right and a bottom credit rule.

**Transfer:** Keep the black ending, quantified band and monumental identity device; adapt the signup promise and proof to the new product. Their frequency elsewhere is flexible, not a fixed page sequence.

### Article reading system

**Only for:** long-form articles and case studies

**Observed:** Full-width upper rules and small far-left labels mark major sections. A 40px heading and paragraphs occupy the right-side lane; subsections use 30px headings and 60px trailing gaps. Charts and Quote panel interrupt the text rhythm. Long chapters retain a small left-side contents rail; case studies use a lower-left watch-video prompt instead.

**Transfer:** Use the narrow-right reading system for depth, with a wider chart breakout when the proof needs comparison.

### Data as editorial illustration

**Only for:** data-rich editorial pages

**Observed:** Charts use flat lilac/coral bars, thin rules, direct labels and a small gray source line. A 24px tightly tracked chart heading sits above a dark top rule. Comparison columns break wider than the paragraph measure, with 64px numbers above blocks; chapter-summary percentages grow to 85px.

**Transfer:** Prefer directly labeled bars and proportional filled areas over dashboard framing, shadows or complex legends.

### Recommendations and onward link

**Only for:** long-form articles and case studies

**Observed:** Resource row groups precede a broader onward section. Article chapters use a 40px left title and a right 815px by 300px botanical strip, followed by an 85px chapter name and large arrow. Case studies use two larger documentary tiles.

**Transfer:** Close deep reading with a visually substantial next destination instead of an isolated text link.

## Page flow

**Storyline:** visual proposition → context for change → human and quantified proof → capability territories or detailed demonstrations → onward discovery → conversion and identity poster

### Flagship marketing landing page

1. **Visual proposition** — Full-width specimen art above a split support/title composition.
2. **Context** — Partner strip, ruled statement and right-lane explanation.
3. **Proof** — Documentary mosaic, large number tiles and a split perspective statement.
4. **Capabilities** — Viewport-sized colored territories with oversized indexes, organic art and contents links.
5. **Human demonstration** — Three documentary case tiles followed by a larger film invitation.
6. **Conversion and brand memory** — Black signup, ruled proof band and monumental identity ending.

**Transfer:** Use a publication-cover first impression and a few deep capability stages rather than a generic feature matrix.

### Customer case study

1. **Human hook** — Glyph art beside a title and documentary portrait film.
2. **Situation** — Organization mark, short context, right-lane narrative and photograph.
3. **Learning** — Large numbered insights beside compact supporting paragraphs.
4. **Demonstration** — Ruled narrative sections, attributed quotes, office scenes and concrete work examples.
5. **Onward discovery** — Contributor directory, black team invitation, resource rows and related cases.
6. **Conversion and brand memory** — The shared black signup, proof band and identity poster.

**Transfer:** Make the reader understand how real work changed before presenting related destinations.

### Evidence-led capability chapter

1. **Topic framing** — Lilac cover with oversized title and paired glyph/botanical media.
2. **Quantified summary** — Solid-color introduction with three large percentages.
3. **Detailed proof** — Numbered major sections, narrow right-side paragraphs, direct-label charts and pale quotation groups.
4. **Interpretation** — Practical callouts balance measured benefits with risks and open questions.
5. **Synthesis and onward discovery** — Numbered takeaways, resource rows and a large next-chapter artwork link.
6. **Conversion and brand memory** — Shared signup and monumental black footer.

**Transfer:** Use the chapter format for a major capability or problem space requiring nuanced explanation, not an ordinary short landing page.

### Comparative capability chapter

1. **Topic framing** — Coral cover with large title and split digital/organic media.
2. **Quantified summary** — Three large metrics over a colored introduction.
3. **Comparison** — Usage comparisons, direct-label bar charts and square category controls interrupt right-lane reading.
4. **Practical demonstration** — Pale in-practice panels, quotations and examples of actual workflows.
5. **Synthesis and onward discovery** — Open questions, numbered takeaways, resource rows and a botanical next destination.
6. **Conversion and brand memory** — Shared black signup, proof strip and identity poster.

**Transfer:** Apply the comparative variant when readers need to understand behavior or adoption, keeping the data accountable and the layout editorial.

### Institutional background and methodology

1. **Context** — Shallow two-color glyph banner above a right-lane statement.
2. **Trust and attribution** — Black field with lilac partner tiles, pale organization profiles and ruled contributor credits.
3. **Methodology** — Return to white for explanatory text and directly labeled charts.
4. **Depth of proof** — Black interview panel and a coral source-count panel paired with glyph art.
5. **Contact and conversion** — Small contact line, shared black signup and monumental footer.

**Transfer:** Use the darker institutional middle only for substantial attribution, provenance or methodology content; keep ordinary marketing sections on the default white canvas.

## Writing

Editorial, curious and confident without pretending the subject is settled. Concrete observations, practitioner voices and acknowledged tradeoffs carry the persuasion.

**Do not copy:** Do not reuse the source identity, wordmarks, report title, partner logos, customer names, numerical claims, quotes or proprietary artwork. Replace them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly an informed editorial we describing what people do; direct you appears in practical guidance and actions rather than every headline.
- **Rhythm:** Short chapter labels sit beside longer, sentence-case claims. Headlines can be compact or run over several tight lines; paragraphs develop an argument with specific examples and occasional questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the publication or a substantial change, without a hype adjective. | 4–9 words | “AI in Design Report 2026”<br>“The great toolstack shakeup” |
| Supporting line | Explain who is changing, how and in what dimensions. | 12–20 words | “How designers are evolving their tools, craft, and teams with AI” |
| Section statement | Use a before/after contrast or a specific tension. | 10–22 words | “In 2025, designers were experimenting with AI. In 2026, they’re rebuilding around it.”<br>“Confidence in tools is up, but so is the noise” |
| Action | Plain verb plus destination or benefit; no grand promise. | 1–8 words | “Read the Report”<br>“Get notified when they’re released”<br>“Submit” |
| Interpretation | Name the practical finding or leave a genuine open question. | 5–12 words | “What we learned”<br>“Where do we go from here?” |

**Words and phrasing to use:** craft; workflows; judgment; in practice; what we learned; a closer look; working differently; tradeoffs

**Avoid:** revolutionary; 10x everything; magic; effortless perfection; unlock limitless potential

**Rules:**

- Tie a metric to a short human-readable description, not a standalone percentage.
- Balance the benefit with its constraint when the argument warrants it.
- Use concrete examples of work rather than lists of abstract platform qualities.
- Keep small labels functional; the personality comes from the large headline and art, not jokey navigation.

## Do's and Don'ts

### Do

- Keep default outer gutters and column gaps at 16px even beside very large imagery.
- Set the main display at weight 500 with -0.06em tracking and 0.95 line height.
- Use 13px uppercase Geist Mono for editorial markings and sentence case for large headings.
- Dedicate whole 900px-scale territories to coral, lilac or sage instead of spreading small accent boxes everywhere.
- Join the 63px-high email strip and orange action without a gap.
- Give white proof numerals 120px size with normal tracking.
- Make the closing wordmark almost as wide as the 1408px desktop content field.
- Use flat 0px-radius panels and hard image edges, with circular portraits as the specific exception.

### Don't

- Do not turn the 56px navigation blocks into rounded capsules or floating glass.
- Do not use 700-weight headings throughout; the broad scale and tight spacing supply the emphasis.
- Do not center all sections: the right reading lane and left marginal field are fundamental.
- Do not add box shadows to case tiles or quotation panels.
- Do not make lilac an always-on page tint; white reading and black closing fields need their own full territories.
- Do not substitute tiny outlined icons for the large organic/digital art language.
- Do not style charts as isolated analytics widgets with rounded shells.
- Do not reduce the entire footer to small columns; the giant identity and edition marker carry its visual weight.

## Motion and responsive

### Motion

**Observed:**

- Colored capability stages use sticky positioning and overlap as the page advances.
- Declared link transitions use 0.2s cubic-bezier(0.44, 0, 0.56, 1) for color and underline properties; some use 0.4s with the same curve.
- Declared editorial case reveals include textReveal and revealImageMask at 0.7s and imageScaleDown at 1s, using cubic-bezier(0.22, 1, 0.36, 1).
- Inline editorial links declare hover black at 0.6 alpha, underline thickness 0.05em and offset 0.2em; subscription partner links declare coral hover and 4px underline offset.

**Transfer:**

- Use the sticky colored stages to make capabilities feel like successive publication covers.
- Keep animated organic art within hard rectangular stages; motion should not soften the grid.
- Reserve masked text/image reveals for the deeper editorial variant rather than making every utility control perform.

**Unknown:**

- Exact playback and scroll-trigger choreography, header reveal thresholds and focus-visible treatments are unspecified.

### Responsive

**Observed:**

- CSS width breakpoints include 768px, 810px, 900px, 1200px and 1440px, with larger-screen variants up to 2560px.

**Transfer:**

- On narrow screens, stack the split support/title strip while keeping the title prominent and artwork full width.
- Convert left marginal navigation into a compact contents control before the article; retain the reading order of heading, prose, chart and quote.
- Stack colored-stage columns and proof cells rather than compressing 120px text into narrow desktop columns.

**Unknown:**

- Exact mobile font sizes, artwork rearrangements, navigation behavior and breakpoint-to-layout mappings are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
