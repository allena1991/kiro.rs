# Haleys.design — playful cathedral marginalia

## Overview

A dark, bookish style that pairs angular calligraphic display letters with delicate editorial serifs and mischievous personal copy. Forest green and warm cream dominate, with muted metallic line drawings, worn-paper texture and architectural frames giving the pages an intimate, handcrafted atmosphere. It suits creative tools, independent products and portfolios whose personality matters as much as their capabilities; text is sparse in indexes and expansive in personal essays.

### Essentials

- An inscription rather than a sales banner: Wispy at 96px/1, weight 100 and -0.01em tracking sits centered between two 21.6px serif descriptors in a three-part masthead.
- Dark dyed paper carries the whole composition: #143930 canvas and #f8f2de type remain continuous across sections; #bead89 is reserved for small metadata, while saturated imagery stays confined to framed feature art.
- Navigation resembles an engraved cartouche, not a row of CTA pills: a 66px outer band encloses a 55px, 64px-radius inner outline, pointed end caps, cross ornaments and 24px shortcut keys.
- Architecture is the main visual device: fine pointed arches and radial rosettes span nearly the full content width behind centered text links. Recreate them as SVG geometry even when the product has no illustration assets.
- Sections read like chapter inscriptions: centered 27.2px italic serif labels interrupt 1px rules with cross-shaped terminals; entries use 32px or 27.2px serif titles and 16px dates, not boxed feature cards.
- The ending is a personal invitation with theatrical lettering: an upward-arched phrase inside a 600×135px SVG, a teasing small aside, distributed text links, a 27.2px cursive sign-off and a 19px checkerboard hem.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest paper | `#143930` | `--color-canvas` | background | Default continuous marketing canvas. |
| Muted sage engraving | `#456859` | `--color-rule` | border, accent | Visible sage linework over forest paper; source hue #5a7c6b at 70% opacity. |
| Deep forest | `#12332b` | `--color-recess` | surface | Navigation backing and shortcut keys. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Old gold | `#bead89` | `--color-metadata` | text | Dates and small category labels rather than large fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm ivory | `#f8f2de` | `--color-ink` | text, link | Default titles, copy and text actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| personal or company story pages | Petrol paper | `#122835` | `--color-personal-canvas` | background | Personal long-form canvas. |
| personal or company story pages | Petrol recess | `#10232d` | `--color-personal-recess` | surface | Personal navigation and shortcut keys. |
| editorial archives and featured essays | Dusty blue | `#8da7ce` | `--color-editorial-meta` | text | Editorial years. |
| personal or company story pages | Peach parchment | `#f2e1ce` | `--color-personal-ink` | text, link | Visible warm text made with rgba(244,227,208,0.99) over petrol paper. |
| editorial archives and featured essays | Slate violet | `#3f455f` | `--color-editorial-rule` | border, accent | Editorial outlines and architectural drawing. |
| personal or company story pages | Blue grey engraving | `#4c5d67` | `--color-personal-rule` | border, accent | Personal outlines and footnote rules. |
| editorial archives and featured essays | Ink recess | `#1b1d27` | `--color-editorial-recess` | surface | Editorial navigation and shortcut keys. |
| editorial archives and featured essays | Charcoal indigo | `#1f222d` | `--color-editorial-canvas` | background | Continuous editorial canvas. |
| editorial archives and featured essays | Lilac white | `#e7eaf9` | `--color-editorial-ink` | text, link | Editorial titles and copy. |

## Typography

- **Wispy** — Mastheads, featured editorial titles and curved closing artwork. Narrow, angular, calligraphic letterforms with medieval terminals; light rather than heavy blackletter. If unavailable, use **Almendra**. Use regular with tight tracking; preserve the pointed calligraphic character. Font stack: "Wispy", "Almendra", serif.
- **EditorialOld** — Titles, paragraphs, navigation and links. Tall, narrow, high-contrast old-style serif with delicate strokes and a flowing italic. If unavailable, use **Cormorant Garamond**. Use light weights and restrain width to maintain the slender setting. Font stack: "EditorialOld", "Cormorant Garamond", serif.
- **Old Standard TT** — Dates, categories and shortcut letters. Bookish serif with traditional numerals. Font stack: "Old Standard TT", serif.
- **altesse-std-24pt** — Footer signature. Fine formal cursive, contrasting with the angular display face. If unavailable, use **Pinyon Script**. Font stack: "altesse-std-24pt", "Pinyon Script", cursive.
- **GTA** (only for personal or company story footnotes) — Small explanatory footnotes, not main paragraphs. Light utilitarian grotesk. If unavailable, use **Public Sans**. Font stack: "GTA", "Public Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Wispy | 100 | 96px | 1 | -0.01em | size clamp(4rem, 7vw, 6rem) | Centered primary masthead. |
| project-title | EditorialOld | 200 | 32px | 1.2 | 0.005em | size clamp(1.7rem, 3vw, 2rem) | Selected work or primary capability links. |
| entry-title | EditorialOld | 200 | 27.2px | 1.3 | 0.005em | size clamp(1.5rem, 2vw, 1.7rem) | Secondary index titles and archive support lines. |
| chapter-label | EditorialOld | 200 italic | 27.2px | 1.3 | 0.005em | fixed | Section names centered across rules. |
| signature | altesse-std-24pt | 300 | 27.2px | 1.1 | normal | size clamp(1.5rem, 2vw, 1.7rem) | Handwritten closing sentence between ornaments. |
| descriptor | EditorialOld | 200 | 21.6px | 1.3 | 0.005em | size clamp(1.3rem, 1.5vw, 1.6rem) | Masthead side descriptors and one-line feature descriptions. |
| social-link | EditorialOld | 200 | 20.8px | 1.2 | 0.005em | fixed | Distributed footer destination links. |
| aside | EditorialOld | 200 | 20.8px | 1.5 | 0.005em | fixed | Small closing aside and footer utility links. |
| navigation | EditorialOld | 200 | 19.2px | 1.5 | 0.004em | fixed | Top navigation labels. |
| metadata | Old Standard TT | 200 | 16px | 1.5 | normal | fixed | Years and category labels. |
| shortcut | Old Standard TT | 200 | 12.8px | 1.5 | normal, capitalize | fixed | Single shortcut letter within a keycap. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| editorial archives and featured essays | feature-title | Wispy | 100 | 70.4px | 1 | -0.01em | size clamp(3.7rem, 5.2vw, 4.4rem) | Featured editorial title. |
| personal or company story pages | story-body | EditorialOld | 100 | 28.8px | 1.2 | 0.0028em | size clamp(1.5rem, 2vw, 1.8rem) | Large intimate long-form paragraphs. |
| personal or company story pages | story-emphasis | EditorialOld | 200 italic | 28.8px | 1.2 | 0.005em | fixed | A reflective question inside the narrative. |
| personal or company story footnotes | footnote | GTA | 300 | 14.4px | 1.4 | normal | fixed | Small explanatory notes below ruled narrative. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep display letters angular and thin; weight 100 is not an invitation to use a heavy gothic face. The serif text is unusually slender throughout.
- Display tracking is -0.01em, while most editorial text uses +0.005em. Navigation and story body retain their distinct 0.1px tracking.
- The personal story masthead shares the display size but uses clamp(3.8rem, 7vw, 6rem) and wraps into two centered lines.
- Curved closing lettering is artwork on an SVG path, not another ordinary paragraph style; preserve the arc and the small aside beneath it.

## Layout

**Density:** Airy in the masthead and between chapters; index entries remain text-only and relatively compact around large ornamental drawings.

### Spacing

| Value | Use |
| --- | --- |
| 10.6px | Title-to-date gaps in index entries. |
| 12px | Archive heading-to-subheading gap. |
| 12.8px | Navigation label-to-key gap and footnote row spacing. |
| 25.6px | Main side gutters, grid columns and wrapped footer link gaps. |
| 51.2px | Primary index row gaps and chapter-to-content separation. |
| 76.8px | Expanded editorial section spacing. |
| 102.4px | Breathing room around masthead and chapter transitions. |

### Containers and grids

- **page grid**: max width 1720px · 12 columns · gap 25.6px · side padding 25.6px. Centered shared grid; wide decorative artwork can occupy all columns while text aligns within it.
- **masthead thirds**: 3 columns · gap 25.6px. Equal thirds hold a centered descriptor, the main title and another descriptor.
- **primary index**: 4 columns · gap 25.6px. Four centered entries across the upper row; a shorter lower row balances either side of the central arch.
- **secondary index**: 6 columns · gap 25.6px. Six small entries across the top, with later entries following the sides and base of a large central ornamental medallion.
- **footer invitation**: max width 600px. Centered curved closing artwork with a smaller aside below.
- **story columns** (only for personal or company story pages): 2 columns · gap 25.6px. Two 446px text columns within a ten-column span, separated by a slender 178px architectural illustration.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation outline | 64px |
| shortcut keys | 4.8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| key ledge | `0px 2.4px 0px 0px #12332b` | Only shortcut keycaps; recolor to the recess color of scoped themes. |

### Surfaces

#### Dyed paper canvas · level 0

**Use:** Default page background across every chapter.

**CSS:** `background: #143930; color: #f8f2de`

**Observed:** Subtle mottled fibers and aged speckling run across the whole page, including the navigation; the texture never competes with letters.

**Transfer:** Keep the ground continuous and matte. Add a very low-contrast paper-grain layer as described in Paper grain.

#### Engraved navigation backing · level 1

**Use:** Slightly recessed backing for the fixed header.

**CSS:** `background: #12332b; border-top: 1px solid rgba(90, 124, 107, 0.7); border-bottom: 1px solid rgba(90, 124, 107, 0.7)`

**Observed:** Double contours and pointed end caps make the band read as an engraved plaque rather than a floating glass panel.

**Transfer:** Keep the backing close to the canvas value; no blur or bright raised-card effect.

#### Editorial paper · level 0

**Only for:** editorial archives and featured essays

**Use:** Alternate coordinated theme.

**CSS:** `background: #1f222d; color: #e7eaf9`

**Observed:** Rules become slate violet, navigation becomes ink recess and dates become dusty blue.

**Transfer:** Swap the complete theme together, not one isolated section.

#### Personal paper · level 0

**Only for:** personal or company story pages

**Use:** Alternate warm-on-petrol theme.

**CSS:** `background: #122835; color: rgba(244, 227, 208, 0.99)`

**Observed:** Blue-grey rules and deeper petrol navigation support the warm parchment text.

**Transfer:** Reserve the treatment for expansive narrative content.

## Components

### Cartouche navigation

**Use:** Persistent top-level navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 55px; border: 1px solid rgba(90, 124, 107, 0.7); border-radius: 64px; padding: 4.3px 18.3px; gap: 25.6px`

**Text style:** `navigation` — EditorialOld 200 · 19.2px/1.5 · tracking 0.004em

**Observed:** A fixed outer header starts 13px from the viewport edges and is 66px high. Its inner contour surrounds three evenly spread destinations; pointed SVG caps extend outward and small cross ornaments sit at the ends. Each destination pairs text with a Shortcut key. The active label has a wavy underline.

**States:** Seen: active destination carries a muted wavy underline.

**Transfer:** Use three short navigation destinations and keep the ornamental silhouette.

### Navigation link

**Use:** Top-level destination inside Cartouche navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12.8px; color: #f8f2de`

**Text style:** `navigation` — EditorialOld 200 · 19.2px/1.5 · tracking 0.004em

**Observed:** Plain serif text rather than a filled button; shortcut sits to its right.

**Transfer:** For conversion, use the same text-link vocabulary rather than introducing an unrelated solid CTA.

### Shortcut key

**Use:** Keyboard hints beside navigation and footer utility links.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 24px; height: 24px; border: 1px solid rgba(90, 124, 107, 0.7); border-radius: 4.8px; background: #12332b; box-shadow: 0px 2.4px 0px 0px #12332b`

**Text style:** `shortcut` — Old Standard TT 200 · 12.8px/1.5 · capitalize

**Observed:** A tiny physical key ledge and soft-light highlight make the key feel tactile. Letter is subdued; it does not look like a tag.

**Transfer:** Include hints only for shortcuts that really work.

### Chapter divider

**Use:** Introduce each major index or feature chapter.

**CSS:** `display: flex; align-items: center; height: 50px; padding: 0px 22.4px; color: #f8f2de`

**Text style:** `chapter-label` — EditorialOld 200 italic · 27.2px/1.3 · tracking 0.005em

**Observed:** The italic label sits on a canvas-colored backing with 25.6px horizontal inset; 1px rules extend on both sides, terminating near 20px crosses. Label opacity is 0.9 with hard-light blending.

**Transfer:** Use short, human chapter names; rules stretch to accommodate the words.

### Index entry

**Use:** A primary project, capability or proof destination.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: flex-end; gap: 10.6px; text-align: center`

**Text style:** `project-title` — EditorialOld 200 · 32px/1.2 · tracking 0.005em

**Observed:** A title followed by old-gold metadata, with no card background or enclosing border. Secondary entries use entry-title and may add a small category above the name. Editorial entries reverse the stack so the year appears first.

**Transfer:** Make each entry a concise title plus a true date or category, and arrange it around the architectural art.

### Social text link

**Use:** Distributed footer destinations.

**CSS:** `display: flex; align-items: center; justify-content: center; color: #f8f2de`

**Text style:** `social-link` — EditorialOld 200 · 20.8px/1.2 · tracking 0.005em

**Observed:** Eleven destinations wrap into a broad row of eight and a centered row of three. The parent uses 25.6px gaps; links remain text rather than social-logo buttons.

**Transfer:** Use the destinations that matter to the new product and preserve the centered wrapping rhythm.

### Signature row

**Use:** Footer's final human sign-off, flanked by utilities.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 28px; color: #f8f2de`

**Text style:** `signature` — altesse-std-24pt 300 · 27.2px/1.1

**Observed:** The cursive sentence occupies the center between small floral ornaments; utility links with Shortcut key sit far to either side.

**Transfer:** Write one gently cheeky sentence instead of adding a corporate legal paragraph.

### Footnote content

**Only for:** personal or company story footnotes

**Use:** Explanatory asides after long-form narrative.

**CSS:** `display: flex; gap: 3.5px; opacity: 0.7; color: rgba(244, 227, 208, 0.99)`

**Text style:** `footnote` — GTA 300 · 14.4px/1.4

**Observed:** Notes sit in two columns between long cross-terminal rules. Superscript anchors in the prose connect to small numbered explanations.

**Transfer:** Use for genuine side comments; keep the main narrative in serif type.

## Imagery and graphics

### Architectural linework

**Use:** Signature illustration behind and between text indexes; include a substantial architectural drawing on every new landing page.

**Observed:** A nearly full-width cathedral facade rises beneath the main index. Repeated pointed lancets contain radial rose windows, nested arches and rectilinear mullions. Muted sage contours are fine and low contrast, allowing ivory text to remain foreground. The main SVG occupies 1389×822px; a secondary central medallion occupies 917×535px.

**Transfer:** Use an original architectural system of arches and rosettes rather than needing a photograph or product render. A simplified facade with one central arch and mirrored side bays is the minimum acceptable equivalent.

**Build:** Use an SVG viewBox around 1400×820. Draw a tall central pointed arch and mirrored narrower bays with no fill, 1px muted sage strokes. Duplicate major outlines a few px inward. Construct rose windows from concentric circles and rotated petal paths, then add vertical mullions and nested smaller arches. Use rgba(90,124,107,0.7), reducing group opacity where it crosses text. Keep all geometry symmetrical and avoid filled glass colors.

### Paper grain

**Use:** Continuous tactile material across the page and header.

**Observed:** Fine irregular dust, fibers and cloudy variations soften the otherwise flat dark canvas; there are no glossy gradients or heavy distressed edges.

**Transfer:** Keep the texture subordinate to the delicate serif strokes.

**Build:** Create a seamless SVG noise tile with feTurbulence and a soft contrast curve, combining fine grain with a larger low-frequency mottling layer. Overlay it on the forest canvas at low visual strength; use overlay blending. The navigation texture layer uses opacity 0.5 with mix-blend-mode overlay; tune generated noise contrast down rather than making visible static.

### Ornamental medallion frame

**Use:** A second signature geometric device for a central feature or decorative pause.

**Observed:** A horizontally stretched plaque has curved lobed sides, stepped shoulders, double hairline contours and a rosette in its center. Index links follow its perimeter rather than filling it with a conventional grid.

**Transfer:** Use the center for a product illustration when available, or retain an intentionally drawn geometric rosette.

**Build:** Build a symmetric SVG path with a shallow top arc, short stepped corners, broad convex side lobes and a mirrored bottom. Add an inset contour and a center flower assembled from four overlapping circles, rotated petal outlines and cross axes. Match the chapter-rule color; keep the fill equal to the canvas.

### Curved invitation and checker hem

**Use:** Signature closing artwork on every page.

**Observed:** Warm angular lettering arches upward at the middle of a centered 600×135px SVG. A small serif aside sits below. The bottom edge ends in a subtle, full-width 19px-high two-row checker pattern rather than a solid footer band.

**Transfer:** Write a short invitation in the new voice and preserve both the upward arch and checker hem.

**Build:** Use SVG textPath on a shallow upward quadratic arc; center the text and use the display family with enough letter spacing to avoid collisions. Keep the artwork inside a 600×135 viewBox. For the hem, repeat staggered rectangular cells in two rows, using muted sage at low opacity over the canvas. The graphic should read as trim, not a high-contrast racing flag.

### Iridescent editorial collage

**Only for:** featured editorial content

**Use:** Large framed artwork beneath a featured title.

**Observed:** A 1040×606px lobed plaque contains a near-black stage, cyan illumination and a collage of reflective musical instruments, floating interface fragments, notation sheets, bubbles and star glints. Purple, teal and pearlescent surfaces remain contained inside the ornamental frame.

**Transfer:** Combine a small number of subject-relevant objects with interface fragments in a dark illuminated collage; minimum version is a carefully layered 2D composition, not an empty frame.

**Build:** Clip the collage to the stepped-lobed SVG frame. Back it with a near-black field and a broad cyan radial light beneath the central objects; overlap three main cutouts at differing scales, with one dominant diagonal object on the right. Add a few small specular stars and thin double frame contours. Keep these vivid colors local to the artwork.

### Slender story window

**Only for:** personal or company story pages

**Use:** Illustration between two prose columns.

**Observed:** A 178×347px narrow gothic window is drawn in blue-grey hairlines, with a rose detail at its pointed crown and vertical panes below. Its transparency and restraint preserve the reading rhythm.

**Transfer:** Use a smaller member of the same architectural drawing system rather than a headshot card.

**Build:** Draw a pointed arch with a doubled outline, circular floral tracery at the top and thin vertical mullions below; no filled panes. Center it between the prose columns.

### Icons

**Observed:** The ornament language is typographic and architectural: 20px cross terminals at dividers, elongated crosses inside the navigation, floral fleuron glyphs at the signature and pointed SVG header caps. Colors follow the local rule color rather than primary ivory.

**Transfer:** Use small SVG crosses and original rosette/fleuron geometry. Functional icons should not displace the site's characteristic text links and shortcut letters.

## Section recipes

How recurring sections are built.

### First screen: Inscribed masthead opening

**Observed:** The forest Dyed paper canvas runs behind a fixed Cartouche navigation near the top. After a substantial blank interval, a 96px display name is centered in the middle third with 21.6px descriptors centered in the outer thirds. The masthead begins around 179px down and occupies a 96px line. A Chapter divider follows after about 103px; four primary Index entries begin roughly 51px below it, with two more balancing the next row. Architectural linework rises centrally behind these links and fills the lower half of the first screen. Within 900px the complete navigation, masthead, divider, six text entries and upper cathedral drawing are visible; the drawing's base and secondary index remain below. There is no filled primary CTA: destinations are the actions.

**Transfer:** Use a short product name or compact promise in the center, a category on one side and an unexpected human descriptor on the other. If no media exists, draw the Architectural linework as the principal object. An editorial archive instead opens with a centered title and a 27.2px support line 12px beneath it; a story page uses a wider two-line display statement before its prose.

**Avoid:** Do not replace this composition with a left-aligned SaaS headline, two filled CTA buttons and a rectangular browser screenshot. Do not stretch the title across the whole width and erase the side descriptors.

**Text style:** `display` — Wispy 100 · 96px/1 · tracking -0.01em

### Engraved chapter heading

**Observed:** Chapter divider spans the content width with italic wording on a canvas-colored interruption, symmetric hairlines and cross terminals.

**Transfer:** Introduce a body of evidence, capabilities or resources with one compact label rather than a large stacked heading.

### Perimeter index

**Observed:** Primary Index entries float above a cathedral facade; secondary entries sit in six columns across the top and then down the sides of an Ornamental medallion frame. Titles are centered, dates subdued, and entries have no enclosing card.

**Transfer:** Organize capabilities or proof examples around the drawing with enough breathing room to preserve its silhouette.

### Invitational ending

**Observed:** After a broad pause, Curved invitation and checker hem supplies the closing focal point. The curved SVG is centered above a small aside; Social text link destinations wrap below, followed by Signature row and distant utility links. The composition occupies about 559px; a 19px checker hem closes the canvas. Editorial pages use the same ending with an additional 52px top offset.

**Transfer:** Retain the curved invitation, modest aside, distributed destinations, cursive sign-off and patterned edge; adapt the number of links to real destinations.

### Featured editorial scene

**Only for:** editorial archives and featured essays

**Observed:** A Chapter divider precedes a centered year, 70.4px feature-title and 21.6px single-line description. The title group uses about 20.5px gaps; an Iridescent editorial collage sits 76px below the supporting line.

**Transfer:** Use one major story with a framed visual payoff rather than a uniform stream of rectangular cards.

**Text style:** `feature-title` — Wispy 100 · 70.4px/1 · tracking -0.01em

### Two-column personal narrative

**Only for:** personal or company story pages

**Observed:** A centered two-line display statement spans ten grid columns. About 102px below it, story-body text fills two 446px columns flanking the Slender story window. Inline references receive wavy underlines, an italic question closes the prose, and a ruled Footnote content area follows.

**Transfer:** Describe the people and motivations behind the new product in a direct personal voice; keep contextual notes below rather than inserting UI cards.

**Text style:** `story-body` — EditorialOld 100 · 28.8px/1.2 · tracking 0.0028em

## Page flow

**Storyline:** identity and personality → curated destinations → deeper exploration or a featured story → personal invitation and useful exits

### A personality-led marketing or portfolio landing page

1. **Identity** — Centered display masthead between two short descriptors beneath an engraved persistent navigation.
2. **Curated proof** — A chapter label and a small set of centered title/date destinations above architectural linework.
3. **Breadth** — Smaller categorized entries arranged around a central ornamental frame.
4. **Closing invitation** — Curved invitation, teasing aside, distributed links, cursive signature and checker hem.

**Transfer:** Use the index to introduce the new product's capabilities or proof; its architectural presentation matters more than retaining the original section count.

### Editorial archive with one featured long-form idea

1. **Orientation** — Centered display title plus a short archive description.
2. **Exploration** — Chapter label and year-first editorial entries around arched linework.
3. **Featured idea** — A large display title, single-line summary and vivid collage inside a stepped ornamental plaque.
4. **Closing invitation** — The shared playful footer in the charcoal-indigo theme.

**Transfer:** Use the scoped editorial palette and feature one substantial idea instead of making every entry equally loud.

### Personal or company story

1. **Character** — A broad two-line display sentence mixes professional identity with a human detail.
2. **Narrative** — Two generous serif text columns flank a slender architectural window; inline links and a reflective italic question keep the prose conversational.
3. **Aside** — Small grotesk footnotes sit between ornamental rules.
4. **Closing invitation** — The shared arched invitation and playful footer in the petrol theme.

**Transfer:** Translate the personal storytelling into the product team's own motivations and details without turning it into a generic values-card grid.

## Writing

Cultured, playful and unguardedly human. Craft confidence is expressed through specific work and considered opinions, while small jokes prevent the formal typography from becoming pompous.

**Do not copy:** Do not reuse the designer's name, project names, employer history, dates, biographical details, exact invitations or personal claims. Examples illustrate tone and structure; write original copy for the new product.

- **Addressing the reader:** First-person singular for personal narrative; terse neutral labels for indexes. The footer reaches toward the reader with an informal request rather than a commercial command.
- **Rhythm:** Mostly two-to-five-word labels and titles; longer opinion headlines are allowed in editorial contexts. Prose flows in compact paragraphs, while the footer uses fragments, ellipses and self-aware questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Masthead descriptor | Balance a plain professional category with a lightly ridiculous personal counterpoint. | 2–3 words each | “Software design”<br>“Assorted tomfoolery” |
| Chapter label | Short, literal grouping softened by conversational diction. | 1–2 words | “Work projects”<br>“Lil projects”<br>“Writings” |
| Editorial title | An opinion, personal lesson or contrast rather than an SEO keyword stack. | 5–9 words | “Vibecoding doesn't make your design better”<br>“Designing for feelings, not problems” |
| Supporting line | One compact explanation with concrete themes and a human verb. | One sentence or phrase | “On collaboration, honing craft and taste, and conjuring feelings.” |
| Navigation action | Name the destination directly; no inflated conversion language. | 1–2 words | “Work”<br>“About Me” |
| Closing aside | An invitation undercut by an affectionate, self-conscious joke. | A short fragment or sentence | “haha jk... unless??”<br>“I showed you my footer please respond” |

**Words and phrasing to use:** craft; feelings; little; lil; wandering; first-person observations; specific creative verbs

**Avoid:** revolutionary; unlock your potential; seamless solutions; enterprise-grade excellence; aggressive urgency

**Rules:**

- Let one small joke puncture the formality of a section; do not make every label a punchline.
- Use real nouns and honest specifics in proof entries instead of generic benefit slogans.
- Keep the final invitation relational rather than transactional.
- Reserve extended first-person prose for narrative pages; keep landing indexes short.

## Do's and Don'ts

### Do

- Keep the default canvas forest green and the main lettering warm ivory across section boundaries.
- Set the central masthead at 96px/1 with -0.01em tracking and retain the flanking descriptor roles.
- Use 25.6px gutters and column gaps rather than rounding them to a generic 24px system.
- Keep date text at 16px/1.5 in old gold, separated from titles by 10.6px.
- Draw fine symmetrical arch and rosette linework large enough to organize a section.
- Build 24px shortcut keys with 4.8px corners and a 2.4px bottom ledge.
- Keep section labels italic at 27.2px with symmetric rules and cross terminals.
- Close with curved lettering, cursive signature and a 19px checker hem.

### Don't

- Do not turn the 64px navigation radius into pill-shaped cards throughout the page.
- Do not use heavy blackletter weights in place of the thin angular display face.
- Do not put gold behind whole sections; it is metadata ink, not a fill color.
- Do not add soft elevated shadows to index entries; the only dimensional ledge belongs to shortcut keys.
- Do not replace distributed footer text links with a dense grid of social-logo badges.
- Do not turn the paper texture into high-contrast film noise that breaks thin letter strokes.
- Do not mix the indigo editorial theme and petrol narrative theme into alternating default landing bands.
- Do not apply the small grotesk footnote style to main marketing paragraphs.

## Motion and responsive

### Motion

**Observed:**

- Navigation backing declares background-color and border-color transitions of 0.3s ease-out.
- The inner navigation outline declares border-color transition of 0.4s ease-out.
- The active destination visibly carries a wavy underline.

**Transfer:**

- Keep ornamental contours visually stable; limit declared color transitions to the navigation layers rather than adding moving line art.

**Unknown:**

- Animation timing, keyframe execution and actual hover/focus behavior beyond the declared color transitions are not established.

### Responsive

**Observed:**

- Typography uses the clamp formulas retained in each relevant recipe.
- Stylesheet width breakpoints include 375px, 400px, 560px, 640px, 720px, 768px, 880px, 960px, 1024px, 1080px, 1280px and 1536px.

**Transfer:**

- On narrow screens, preserve the centered inscription and architectural silhouette. Reflow descriptors beneath the name and reduce perimeter-index columns before text collides with the drawing; this is implementation guidance.
- Scale the 600px invitation SVG to the available width while preserving its arc. Let footer destinations wrap into centered rows.

**Unknown:**

- Exact mobile navigation, grid rearrangements and decorative-art visibility at each breakpoint are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
