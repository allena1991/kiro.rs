# Little Troop — objects with personality

## Overview

A white gallery with a mischievous streak: tiny condensed labels sit beside oversized objects, vivid moving artwork and monumental lettering. Hairline black rules and unusually tight, fine serif statements give the exuberant imagery an editorial counterweight. It suits visually distinctive products and creative businesses with something tangible to show; the interface is sparse while the work itself is richly colored. Extended storytelling can move into a black exhibition space without changing the underlying typographic language.

### Essentials

- The object is the headline: a 900px-tall white opening holds a roughly 800px circular moving image, with a 14px/16px bold condensed promise at the lower left rather than a conventional giant hero heading. Use a circular product study or a typographic object when there is no photographic equivalent.
- Tiny navigation surrounds a character: four 14px/12px bold links spread across the fixed top edge, with a small expressive emblem on the central axis. Keep this emblem as a recurring personality device, using an original simple face or product symbol.
- Fine serif prose is compressed almost to collision: Times Now at 76px/60px, weight 250, -5px tracking makes statements read as sculptural text. Small functional copy stays Arial Narrow at 14px/16px with normal tracking.
- Color belongs to exhibits, not interface furniture: the default canvas, text and 1px rules are pure white and black. Saturated color can occupy most of an image or moving object, but does not become a general button or section-heading accent.
- Thumbnails are soft capsules, not boxed cards: 264×170px media with 50px corners sit in a five-column grid with 20px horizontal and 40px vertical gaps. Put 14px captions 8px below the image, with the key name in bold.
- Actions are typographic, not chunky: bold 14px underlined links carry navigation into work and contact. The 104×42px translucent rounded sound control belongs only over a film.
- The ending is a graphic event: an 865×573px centered wordmark artwork is flanked by small contact and follow links, then a ruled 165px band carries a two-line 76px serif statement. Make an equally monumental composition from the new identity, even when the rest of the page is short.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Character red | `#ee3038` | `--color-character-red` | accent | Small warm-red facial details in the recurring identity character; can expand inside the profile character film, never into interface buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, link | All default text, contact links and hairline separators; also the background of the extended exhibition variant. |
| Gallery white | `#ffffff` | `--color-canvas` | background, text | Default page canvas; reversed text and rules in the black exhibition variant. Navigation uses white with difference blending so it reads black over white. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| film sound controls | Smoked film control | `#161616` | `--color-film-control` | surface | Visible result of rgba(217,217,217,0.1) over black; translucent over the changing film beneath it. |

## Typography

- **Arial Narrow** — Navigation, captions, paragraphs, index labels and contact details. Utilitarian condensed sans-serif, deliberately small; regular and bold do most of the work. If unavailable, use **Roboto Condensed**. 400 and 700; preserve compact width and normal tracking. Font stack: "Arial Narrow", "Roboto Condensed", "Arial Narrow", sans-serif.
- **Times Now** — Large editorial statements and closing prose. Fine, narrow serif with sharp contrast, tightly packed lines and emphatically negative tracking. If unavailable, use **Cormorant Garamond**. 300; tune width and line breaks before increasing weight. Font stack: "Times Now", "Cormorant Garamond", "Times New Roman", serif.
- **HelveticaNeueLT** (only for editorial introductions with inline name emphasis) — Sans-serif words embedded in a large serif sentence. Neutral neo-grotesk; its blunt forms interrupt the finer serif text. If unavailable, use **Inter**. 400 for profile names, 700 for project names. Font stack: "HelveticaNeueLT", "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Times Now | 250 | 76px | 60px | -0.0658em | Monumental closing prose and editorial introductions; not a substitute for the object-led opening. |
| body | Arial Narrow | 400 | 14px | 16px | normal | Captions, support paragraphs, years and ordinary descriptive copy. |
| label-bold | Arial Narrow | 700 | 14px | 16px | normal | Opening promise, small section titles, emphasized names and contact links. |
| navigation | Arial Narrow | 700 | 14px | 12px | normal | Fixed top-edge navigation. |
| status-italic | Arial Narrow | 400 italic | 14px | 14px | normal | Short changing activity line at the lower right of the opening. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| profile introductions | profile-name | HelveticaNeueLT | 400 | 76px | 60px | -0.0658em | Inline people or entity names in the opening serif sentence. |
| case-study introductions | project-name | HelveticaNeueLT | 700 | 66px | 60px | -0.053em | Inline subject emphasis inside a 76px serif project introduction. |
| extended case studies | chapter-statement | Times Now | 250 | 48px | 40px | -0.0625em | Longer explanatory chapter leads on black. |
| film sound controls | film-action | Arial Narrow | 400 | 16px | 16px | normal | Sound control over full-screen film. |
| profile and information pages | section-label | Arial Narrow | 400 | 14px | 16px | normal, uppercase | Centered headings above prose, tables and contact sections. |
| profile and information pages | list-cell | Arial Narrow | 400 | 14px | 30px | normal, uppercase | Compact ruled capability and customer lists. |
| news and recognition lists | news-detail | Arial Narrow | 400 italic | 14px | 16px | normal | Italic description inside a dated news row. |
| news and recognition lists | news-source | Arial Narrow | 700 | 14px | 16px | normal, uppercase | Publication or organization name inside a dated news row. |

**Notes:**

- There are two dramatically different reading speeds: 14px condensed annotations and 76px fine serif statements. Do not fill the gap with a generic ladder of medium-weight sans headings.
- The 76px serif uses a shorter 60px line height; the 48px chapter lead uses 40px. Preserve their compressed leading and negative tracking together.
- Bold names in thumbnails stay the same size as the surrounding sentence. Inline grotesk display emphasis changes family and sometimes weight, not the paragraph's baseline rhythm.

## Layout

**Density:** Airy at exhibition scale, compact at annotation scale: large image intervals surround tightly packed labels and tables.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Caption padding below thumbnail media and news-cell vertical padding. |
| 12px | Top navigation inset and index-heading top padding. |
| 20px | Page side gutters, media-column inner padding and common text gaps. |
| 40px | Thumbnail row gap and supporting caption separation. |
| 100px | Breathing room between spotlight exhibits. |
| 130px | Default image-chapter top interval in the exhibition variant. |
| 170px | Longer image intervals in product identity stories. |
| 240px | Case-study tail and credits breathing room. |
| 250px | Profile capability-section lead-in. |

### Containers and grids

- **edge-to-edge gallery**: max width 1440px · side padding 20px. Default desktop composition: full viewport media alternates with content aligned to narrow edge gutters.
- **thumbnail index**: 5 columns · gap 20px · side padding 20px. Five equal 264px columns at 1440px, with 40px row gaps; captions remain outside the rounded image.
- **editorial column** (only for profile and information pages): max width 589px · side padding 20px. Centered small prose on information pages.
- **ruled table** (only for profile and information pages): max width 966px · 4 columns · gap 0px. Centered capability and customer lists; recognition rows use the same width as a single column.
- **paired exhibits** (only for extended case studies): max width 1160px · 2 columns · gap 40px. Two 560px images centered on black. Other image stages use 720px, 920px or 1040px centered widths, or go full bleed.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | index media | 50px |
| rounded case-study photographs and media | case-study media | 30px |
| film sound controls | film control | 87px |

## Surfaces and depth

### Surfaces

#### White gallery · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** A flat, untextured white field; images and text sit directly on it without raised panels.

**Transfer:** Let the exhibits supply color and material.

#### Ruled band · level 0

**Use:** Section boundaries, index transitions and closing statement.

**CSS:** `border-top: 1px solid #000000`

**Observed:** Full-width rules carry the hierarchy rather than shaded cards.

**Transfer:** Separate meaningful editorial bands with a single thin line.

#### Black exhibition · level 0

**Only for:** extended case studies

**Use:** Immersive image and process chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black continues across many consecutive media sections, then switches decisively to the white related-work area.

**Transfer:** Use one sustained dark story, not alternating arbitrary dark cards.

#### Film glass · level 1

**Only for:** film sound controls

**Use:** Sound toggle over moving imagery.

**CSS:** `background: rgba(217, 217, 217, 0.1); backdrop-filter: blur(15px); border-radius: 87px; color: #ffffff`

**Observed:** A small translucent pill lets the underlying movie remain visible.

**Transfer:** Keep this treatment confined to controls that belong to a film.

## Components

### Edge navigation

**Use:** Persistent navigation without a heavy header bar.

**CSS:** `position: fixed; z-index: 15; height: 24px; width: 100%; mix-blend-mode: difference; color: #ffffff`

**Text style:** `navigation` — Arial Narrow 700 · 14px/12px

**Observed:** Four links are spread across the top, two on either side of the central emblem. The inner bar has 12px top and 20px side padding. Difference blending reverses the lettering over light and dark content.

**States:** Declared: hover unspecified; focus-visible outline none.

**Transfer:** Use four short destinations and preserve the open middle rather than adding a boxed logo-and-menu strip.

### Underlined action

**Use:** Project visits, contact and follow actions.

**CSS:** `color: #000000; font-weight: 700; text-decoration: underline; background: transparent`

**Text style:** `label-bold` — Arial Narrow 700 · 14px/16px

**Observed:** An ordinary text link, not a filled button. Reverses to white in dark chapters; contact and follow links sit at opposite bottom corners of the wordmark stage.

**Transfer:** Use a direct verb or the destination address; keep visual emphasis at text scale.

### Index media tile

**Use:** Dense visual discovery grid.

**CSS:** `width: 264px; height: 170px; border-radius: 50px; overflow: hidden; object-fit: cover`

**Text style:** `body` — Arial Narrow 400 · 14px/16px

**Observed:** The CSS describes the media frame, not the whole tile. A video and poster occupy the same frame; the caption follows with 8px top padding and bold inline subject name. There is no enclosing card fill.

**Transfer:** Pair each offering with a strong colored image and one short descriptive sentence.

### Filter index

**Use:** Filter a visual collection without prominent pills.

**CSS:** `display: grid; grid-template-columns: repeat(8, auto); row-gap: 12px; column-gap: 30px; padding: 20px 20px 47px`

**Text style:** `body` — Arial Narrow 400 · 14px/16px

**Observed:** Small hollow circles precede category labels; the active choice is filled black. A title sits at the left and a filtering prompt at the right above the options.

**Transfer:** Use this only when the content genuinely supports categories; keep the circles and unboxed label treatment.

### Closing statement band

**Use:** Large editorial sign-off beneath the identity artwork.

**CSS:** `border-top: 1px solid #000000; padding: 23px 0px 21px; text-align: center`

**Text style:** `statement` — Times Now 250 · 76px/60px · tracking -0.0658em

**Observed:** A centered two-line sentence spans almost the whole page. Two smaller ruled strips below it contain a compact identity sentence and production or copyright details.

**Transfer:** Use a brief belief plus a concrete origin or product fact rather than a large conversion button.

### Capability cell

**Only for:** profile and information pages

**Use:** List offerings or customers in an austere table.

**CSS:** `border-bottom: 1px solid #000000; padding-right: 20px; line-height: 30px`

**Text style:** `list-cell` — Arial Narrow 400 · 14px/30px · uppercase

**Observed:** Four columns share a centered 966px table; each cell is about 242px wide and 31px tall including its rule. No vertical grid lines or decorative logos.

**Transfer:** Keep short, parallel nouns and let the repeated rules create texture.

### Recognition row

**Only for:** news and recognition lists

**Use:** Chronological proof and announcements.

**CSS:** `display: flex; justify-content: space-between; column-gap: 20px; border-top: 1px solid #000000; height: 33px`

**Text style:** `body` — Arial Narrow 400 · 14px/16px

**Observed:** Year at left, centered bold uppercase source followed by italic description, and a simple right arrow at the far edge. Rows share a 966px maximum width; text cells have 8px vertical padding.

**States:** Declared: hover unspecified; focus-visible outline none.

**Transfer:** Use a dated release, review or milestone. Keep the publication emphasis and italic detail as separate typographic roles.

### Film sound control

**Only for:** film sound controls

**Use:** Enable audio on a full-viewport opening film.

**CSS:** `width: 104px; height: 42px; background: rgba(217, 217, 217, 0.1); backdrop-filter: blur(15px); border-radius: 87px; color: #ffffff; position: absolute`

**Text style:** `film-action` — Arial Narrow 400 · 16px/16px

**Observed:** Centered near the bottom of the film, above its edge. It is the exception to the otherwise text-only action vocabulary.

**States:** Declared: hover unspecified; focus-visible outline none.

## Imagery and graphics

### Circular moving exhibit

**Use:** Signature opening object.

**Observed:** A large circular image fills most of the screen height on white. The visible scene is a softly lit lavender product world with pink accents, distorted around a sphere-like surface; the surrounding field stays completely white.

**Transfer:** Create a single circular product world with warm personality: real product detail, a material study or expressive typography, not a generic abstract gradient.

**Build:** Use an approximately 800px circular mask centered in a 1440×900px white stage. Fill it with a close product image or a simple SVG composition of the product's silhouettes; clip at 50% radius. For a dimensional version, map the image to a sphere with soft broad highlights and restrained distortion. Keep all lighting inside the circle; do not add a floating drop shadow.

### Identity word sculpture

**Use:** Signature monumental ending.

**Observed:** An enormous two-tier black identity artwork fills an 865×573px central area. A tall fine serif upper word meets a heavy uppercase sans lower word, with almost no gap; small contact links sit at its lower corners.

**Transfer:** Make a word sculpture from the new name or a short product phrase. The minimum is two tightly fitted, contrasting type treatments rendered as clean SVG, preserving the same dramatic central mass.

**Build:** Create an 865×573 SVG viewBox. Fit the upper line in a high-contrast serif and the lower line in bold grotesk capitals, using black fills and shared visual width. Adjust glyph spacing and baselines so the two lines form a single compact silhouette. Keep white behind it and avoid a container border.

### Central character emblem

**Use:** Small recurring personality marker in the navigation.

**Observed:** A tiny black, white and red face changes expression at the central top edge, visibly separate from the text links. Its simple silhouette reads even against complex media.

**Transfer:** Design an original expressive product symbol or simple face with only a few shapes; retain a small recurring mark even when the main product is abstract.

**Build:** Draw a compact SVG with a white oval or irregular rounded silhouette, a black cap-like upper shape and two simple black facial marks. Add one small colored spot from the new identity's artwork palette. Keep the silhouette legible around 50px wide and let expression changes alter only a few shapes.

### Spotlight object compositions

**Use:** Large proofs after the index.

**Observed:** Printed matter, packaging, motion studies and product scenes are isolated on white or shown full bleed. Some objects overlap at slight angles; paper grain, folds and print texture remain visible. Exhibit widths vary from roughly 752px to the full 1440px, with long open intervals.

**Transfer:** Show the product as a crafted physical or visual object. Use real textures and close details; for a digital service, make a high-quality interface or typography study rather than a generic device mockup.

### Dark documentary exhibits

**Only for:** extended case studies

**Use:** Show process, applications and real-world evidence.

**Observed:** Black margins surround rounded street photographs, printed book spreads, worn merchandise and bright campaign graphics. Images alternate between single narrow portraits, paired 560px photographs, large centered scenes and full bleed. Saturation lives inside the exhibits; natural light and tangible paper or fabric texture stay intact.

**Transfer:** Mix controlled product compositions with honest contextual photography. Preserve different image scales rather than repeating one full-width template.

### Glossy character studies

**Only for:** playful product identity case studies

**Use:** Demonstrate a character or product's expressive range.

**Observed:** Squishy square faces have shiny plastic or clay-like skins, soft bevels, high highlights and large cartoon eyes. They appear alone on black, in graphic collages and in object applications; subtle grain prevents sterile CGI.

**Transfer:** Use a simple object with a strong silhouette and a limited expressive vocabulary. A carefully lit physical model or a flat vector study with consistent expressions is preferable to weak complex 3D.

### Floating profile ephemera

**Only for:** profile and information pages

**Use:** Counterpoint to centered prose and tabular lists.

**Observed:** Small tilted documentary photographs and project images float near the right edge while the main text stays centered. A later oversized black, white and red character film breaks out across the full width before the smaller closing wordmark.

**Transfer:** Pair a restrained information page with personal project fragments and one large identity animation; keep the floats peripheral so they do not replace the reading column.

### Icons

**Observed:** Icons are mostly typographic: right arrows at the ends of recognition rows and outlined or filled circles before filters. The illustrated central face is an identity device rather than a utility icon set.

**Transfer:** Use simple arrows and circles in current text color. Avoid adding a library of feature pictograms to the otherwise image-led gallery.

## Section recipes

How recurring sections are built.

### First screen: Object-led first screen

**Observed:** A white 1440×900px stage is occupied by one roughly 800px circular moving exhibit centered horizontally and almost filling the available height. Edge navigation floats above it, with the character emblem on the central axis. There is no oversized text headline: the actual promise is a bold 14px/16px two-line label anchored at the lower left, while a short activity label and italic status sit at the lower right. The object, navigation and both annotations are visible within the first 900px; the ruled category index begins below the fold. No prominent filled call-to-action interrupts the object.

**Transfer:** Start a new marketing page with a visually memorable circular product study and a very short factual promise. Without product photography, put expressive type or a simplified product silhouette inside the circular scene. Information pages instead open with a small welcome strip and centered 76px serif sentence; case studies open with full-screen film and put their large introduction beneath it.

**Avoid:** Do not turn this into a centered headline, paragraph and two-button SaaS hero, or place a rectangular screenshot inside a gradient card.

**Text style:** `label-bold` — Arial Narrow 700 · 14px/16px

### Index to spotlight

**Observed:** The Ruled band introduces a small title and Filter index, followed by Index media tiles on the White gallery. A second small bold section label introduces much larger standalone spotlight images, with annotations and an Underlined action extending across the image stage.

**Transfer:** Offer a compact visual overview, then slow the reader down with a few high-impact exhibits. The contrast in scale matters more than the number of exhibits.

**Text style:** `body` — Arial Narrow 400 · 14px/16px

### Identity-scale closing

**Observed:** On White gallery, the Identity word sculpture is flanked by Contact and Follow at the baseline. Closing statement band follows, then two smaller ruled strips. The standard ending is 875px tall; the profile variant is 467px tall with a much smaller wordmark after its preceding character film. Dark stories first return to a white related-work index before this ending.

**Transfer:** Close with an enlarged identity artwork, a memorable short statement and direct contact links. Keep the ruled editorial strips even when there is little legal or production copy.

**Text style:** `statement` — Times Now 250 · 76px/60px · tracking -0.0658em

### Mixed-family editorial introduction

**Only for:** profile and case-study introductions

**Observed:** A 76px serif sentence runs in compressed lines, with selected names inserted in grotesk type. Profile prose is centered within 1389px; case-study text aligns to 20px gutters on Black exhibition beneath a thin category strip.

**Transfer:** Use a concrete introduction that names the product, its purpose and the intervention. Reserve the family switch for genuinely important names or phrases.

**Text style:** `statement` — Times Now 250 · 76px/60px · tracking -0.0658em

### Centered information island

**Only for:** profile and information pages

**Observed:** A small uppercase heading introduces centered 14px prose, with a 589px reading column. Later sections use much larger top intervals, including 250px before capabilities, then 966px ruled tables. Contact is a short centered block, followed by full-width character film and a compact 259px-wide wordmark ending.

**Transfer:** Use the island for philosophy, scope or practical details. Let a Capability cell table or Recognition row supply structured proof rather than making every fact a card.

**Text style:** `section-label` — Arial Narrow 400 · 14px/16px · uppercase

### Exhibition chapter

**Only for:** extended case studies

**Observed:** Black exhibition carries a small bold chapter label, a 48px/40px serif explanation and large media stages. Text commonly has 20px gutters; media arrives after 130px or 170px top intervals. Captions use 14px/16px with a bold subject and compact descriptive text, sometimes centered at 720px or 920px widths. Full-width images alternate with narrow portraits and paired exhibits.

**Transfer:** Divide a product story by problem, system, application and experience. Use images as the principal argument and text to explain the specific decision, not to narrate every frame.

**Text style:** `chapter-statement` — Times Now 250 · 48px/40px · tracking -0.0625em

## Page flow

**Storyline:** visual intrigue → compact overview → enlarged proof → context and craft → identity-led sign-off

### Visual discovery and brand introduction

1. **Visual promise** — Circular moving product world with tiny lower-corner annotations.
2. **Overview** — Category controls and a five-column image index.
3. **Proof** — Large standalone spotlights at varied scales, with small project links.
4. **Closing call** — Monumental identity artwork, contact corners and ruled statement bands.

**Transfer:** Use a visually strong opening, a browsable range of examples and a few deep visual proofs; adapt the amount of work to the product.

### Explain the people, point of view and practical offering behind a brand

1. **Introduction** — Small welcome strip and oversized centered serif prose with grotesk name emphasis.
2. **Positioning** — Narrow centered paragraphs describing approach.
3. **Capabilities and proof** — Four-column ruled offerings, dated recognition rows and customer names, with tilted peripheral images.
4. **Contact** — Simple centered enquiry text and direct email.
5. **Identity reinforcement** — Large character film followed by a compact version of the ruled closing.

**Transfer:** Use this for an about or product-background page; emphasize real expertise and useful contact information rather than expanding the sales pitch.

### Explain a visual system through its applications and evolution

1. **Demonstration** — Full-screen real-world campaign film.
2. **Context** — Category strip, large mixed-family introduction and small external links.
3. **Craft explanation** — Brief, character system and typographic decisions interleaved with visual evidence on black.
4. **Application proof** — Printed artifacts, documentary photos, merchandise and digital demonstrations at multiple scales.
5. **Evolution** — Further editions introduced with large serif titles and paired or centered graphics.
6. **Continuation and closing** — White related-work grid and standard monumental footer.

**Transfer:** Show how one product idea holds together across contexts and versions; use actual outcomes where available.

### Present a product identity as an expressive world and a usable digital experience

1. **Demonstration** — Full-screen playful film with sound control.
2. **Context** — Large serif introduction, inline bold name and small publication links.
3. **System explanation** — Mascot, palette and type studies against black.
4. **Application proof** — Collages, object photography and glossy character variations.
5. **Experience proof** — Large site demonstrations, paired views and short explanatory captions.
6. **Credits and continuation** — Small centered credits with deep black breathing room, then white related-work index and monumental sign-off.

**Transfer:** Keep the character-led work distinct from the site's own interface; transition from emotional appeal to real product use before the closing.

## Writing

Assured and culturally literate, but playful rather than grandiose. Concrete descriptions of making and intent sit alongside occasional odd, tactile or mischievous words.

**Do not copy:** Do not reuse Little Troop's name, wordmark, character art, project artwork, client roster, founder names, dates, locations, awards, impression counts or quoted client claims. Source examples illustrate tone only; write claims and identity assets specific to the new product.

- **Addressing the reader:** Mostly third-person descriptive prose, referring to the studio by name or initials; occasional first-person plural in project introductions. Direct contact language is polite and unforced.
- **Rhythm:** Very short navigation and labels; compact one- or two-line thumbnail sentences; longer flowing editorial introductions and occasional parenthetical comparisons. Exclamation marks are not needed.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A plain factual description of what the organization is, followed by its three-part motivation. | One short sentence | “[Brand] is a design studio driven by craft, culture and imagination.” |
| Project caption | Active making verb or service, then a specific subject; the subject is visually emphasized. | About 5–12 words | “Creating a covetable container company for Clik”<br>“Building bite-sized magic for Minis” |
| Chapter label | Short literal subject; avoid promotional slogans in navigation through a story. | 1–5 words | “The Brief”<br>“Typographic System & Color Palette” |
| Action | Name the destination or use a minimal verb plus object. | 1–5 words | “View Project”<br>“See More Lt News”<br>“Sound on” |
| Closing statement | A belief followed by a grounded origin line, balanced as two large lines. | Two compact sentences | “Driven by craft, culture and imagination. Est. 2019, Brooklyn, New York City.” |
| Contact support | Polite practical instruction, with no high-pressure conversion rhetoric. | One short clause | “For all enquiries, please contact” |

**Words and phrasing to use:** craft; play; world; identity; built; created; eye-popping; larger than life; a little odd; curated chaos

**Avoid:** revolutionary platform; unlock your potential; best-in-class solution; 10x everything; frictionless synergy

**Rules:**

- Describe what was made before describing how impressive it is.
- Allow one vivid, tactile or funny phrase inside an otherwise precise description.
- Name the design decision and explain its purpose; keep proof factual.
- Keep small labels literal so expressive imagery can do the emotional work.

## Do's and Don'ts

### Do

- Use pure #ffffff and #000000 for the interface and its 1px separators.
- Keep functional copy condensed at 14px/16px; use weight 700 selectively for names and links.
- Preserve the 76px/60px serif statement with -5px tracking as one inseparable recipe.
- Keep 20px desktop edge gutters even beside expansive imagery.
- Use 50px corners on the small index media, not on an enclosing caption card.
- Change image scale between full bleed, paired 560px views and narrower centered studies.
- Give the closing identity artwork comparable visual force to the opening object.
- Let a genuine product or material image occupy the bulk of the opening rather than explanatory text.

### Don't

- Do not introduce a colored primary-button system; ordinary actions are underlined text.
- Do not turn image colors into alternating colored interface bands.
- Do not replace the small condensed labels with widely tracked mono capitals.
- Do not add drop shadows to the flat gallery or thumbnail tiles.
- Do not set the fine serif statements in bold or normalize their compressed leading to 1.2.
- Do not wrap every paragraph in a rounded panel; the page canvas is the surface.
- Do not make all images identical full-width rectangles; that removes the exhibition rhythm.
- Do not use the glossy character artwork's lettering or palette as the website's general type and color system.

## Motion and responsive

### Motion

**Observed:**

- The opening uses a canvas-based moving exhibit; spotlight and case-study media include video loops with poster images.
- The central face changes expression across the page experience.
- A source rule declares transform, height and width transitions of 0.5s on one element; a specific global interaction curve is not established.

**Transfer:**

- Keep motion inside the exhibit and the small identity character; preserve readable, stable edge annotations.
- For static delivery, retain the circular composition and a strong still rather than replacing the exhibit with a text hero.

**Unknown:**

- Exact canvas behavior, pointer response, loop durations and playback sequencing are not established.
- No general hover appearance beyond the declared focus-outline suppression is established.

### Responsive

**Observed:**

- Desktop composition uses five index columns, four table columns and a full-screen opening.
- Styles declare width breakpoints at 450px, 576px, 768px, 992px, 1024px, 1200px, 1280px and 1400px.

**Transfer:**

- On narrower screens, preserve the single-object opening and move its tiny annotations out of collision with the object.
- Reduce grid columns while preserving image-to-caption attachment and rounded media; keep the word sculpture proportional to the available width.
- Reflow the serif statements by phrase and tune their size as a unit with leading and tracking, rather than only shrinking the font.

**Unknown:**

- Mobile column counts, exact mobile type sizes, navigation behavior and breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
