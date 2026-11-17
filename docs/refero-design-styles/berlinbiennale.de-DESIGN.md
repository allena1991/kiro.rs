# Berlin Biennale — electric typographic sculpture

## Overview

An electric, poster-like identity combines a cyan field, enormous black abstract letterforms and matter-of-fact typography. Regular grotesk lettering meets literary serif text, with small utilitarian controls and asymmetrical editorial composition. It suits cultural, research-led and idea-driven products that can sustain a strong graphic identity rather than a conventional product mockup. The experience alternates a saturated graphic stage with dense, white editorial space and unembellished documentary photography.

### Essentials

- Identity becomes architecture: a flat black typographic sculpture fills most of a 900px-tall opening against #00ecec, with cyan identity text crossing its center. Carry this device into every new design as an original monogram or geometric word sculpture, even without photography.
- Headlines behave like a movable poster composition rather than a centered sales pitch: regular grotesk identity lettering at 61.8px with a 1.025 line height, a short upper-right slogan split across offset lines, and tiny 14.3px centered section labels.
- Content floats over the identity field: 672px-wide white panels occupy the right half of a 1440px composition, using 12px vertical and 18px horizontal padding, without borders or shadows.
- Controls are deliberately undersized: a 35px-high black Guide pill with cyan type sits beside a white Menu control; white 34px utility actions and gray 22–25px chips provide the rest of the navigation.
- Color is structural, not decorative confetti: the landing canvas is entirely cyan beneath black artwork and white panels; editorial variants restrict one electric hue to a 360px left identity rail beside a white 1080px reading field.
- Editorial information changes register: serif panel copy is 23.2px/1.15, primary event titles 30.2px/1.15, while metadata uses 12.1–14.3px grotesk. Photography remains rectangular and documentary, accompanied by small numbered captions.
- The closing gesture returns to identity rather than a conversion banner: an enlarged black sculpture precedes a compact footer with uppercase 14.3px links, two small partner marks and a 12.1px factual credit paragraph.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric cyan | `#00ecec` | `--color-electric` | background, text, accent | Default full-page field, reversed identity lettering and Guide text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Text, monumental identity artwork and the Guide pill. |
| Utility gray | `#f2f2f2` | `--color-chip` | surface, action | Small secondary actions and metadata chips. |
| White | `#ffffff` | `--color-canvas` | surface, background, action | Floating information panels and utility actions; the reading canvas for editorial variants. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form feature pages | Acid yellow | `#e1ff14` | `--color-lime` | background, text, accent | Left identity rail and Guide lettering for long-form feature content. |
| organization pages | Hot magenta | `#fa23ff` | `--color-magenta` | background, text, accent | Left identity rail and Guide lettering for institutional storytelling. |
| directory pages | Electric violet | `#7373ff` | `--color-violet` | background, text, accent | Left identity rail and Guide lettering for alphabetical directories. |

## Typography

- **ABCMonumentGroteskWeb** — Identity lettering, headings, controls, dates and metadata. Neutral, compact neo-grotesk with a plain regular cut; authority comes from scale rather than weight. If unavailable, use **Roboto**. Use 400; retain tight tracking and compare line wraps. Font stack: "ABCMonumentGroteskWeb", "Roboto", Helvetica, "Helvetica Neue", Arial, sans-serif.
- **BradfordLLSub** — Editorial prose, panel descriptions, event titles and directory names. Bookish, compact serif with a substantial x-height and crisp contrast. If unavailable, use **Source Serif 4**. Use 400 and tune width before changing the size. Font stack: "BradfordLLSub", "Source Serif 4", TexGyreTermesWeb, "Times New Roman", Times, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | ABCMonumentGroteskWeb | 400 | 61.8px | 1.025 | -0.02em | size calc( 56 * 0.95 / 1240 * 100vw ) | Large identity lettering and primary editorial page titles. |
| event-title | BradfordLLSub | 400 | 30.2px | 1.15 | -0.01em | size calc(26 / 1240 * 100vw) | Main title within a featured program card. |
| date | ABCMonumentGroteskWeb | 400 | 28.7px | 1.15 | -0.01em | size calc( 26 * 0.95 / 1240 * 100vw ) | Prominent numeric dates at the top of featured cards. |
| card-heading | ABCMonumentGroteskWeb | 400 | 25.4px | 1.15 | -0.01em | size calc( 23 * 0.95 / 1240 * 100vw ) | Names within compact information lists. |
| panel-prose | BradfordLLSub | 400 | 23.2px | 1.15 | -0.01em | size calc(20 / 1240 * 100vw) | Prominent prose in floating panels and secondary event titles. |
| action | ABCMonumentGroteskWeb | 400 | 22.1px | 1.025 | -0.004em | size calc( 20 * 0.95 / 1240 * 100vw ) | Guide pill, utility actions and download links. |
| menu | ABCMonumentGroteskWeb | 400 | 18.8px | 1.025 | -0.004em | size calc( 17 * 0.95 / 1240 * 100vw ) | Menu toggle. |
| small-action | ABCMonumentGroteskWeb | 400 | 16.5px | 1.025 | -0.004em | size calc( 15 * 0.95 / 1240 * 100vw ) | Secondary panel actions and view toggles. |
| label | ABCMonumentGroteskWeb | 400 | 14.3px | 1.025 | -0.004em | size calc( 13 * 0.95 / 1240 * 100vw ) | Centered section labels, tiny navigation labels and compact chips. |
| footer-link | ABCMonumentGroteskWeb | 400 | 14.3px | 1.025 | 0.01em, uppercase | size calc( 13 * 0.95 / 1240 * 100vw ) | Footer contact, social and legal links. |
| caption | ABCMonumentGroteskWeb | 400 | 12.1px | 1.15 | normal | size calc( 11 * 0.95 / 1240 * 100vw ) | Image captions, numbers and factual footer credits. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and organization pages | large-link | ABCMonumentGroteskWeb | 400 | 48.5px | 1.025 | -0.01em | fixed | Large staggered destinations and related-section links. |
| organization pages | section-heading | ABCMonumentGroteskWeb | 400 | 33.1px | 1.025 | -0.01em | size calc( 30 * 0.95 / 1240 * 100vw ) | Chapter headings above institutional prose. |
| long-form feature pages | statement | ABCMonumentGroteskWeb | 400 | 22.1px | 1.25 | -0.004em | size calc( 20 * 0.95 / 1240 * 100vw ) | Extended quoted statement with alternating paragraph offsets. |
| editorial and organization pages | editorial-body | BradfordLLSub | 400 | 17.4px | 1.25 | -0.004em | size calc(15 / 1240 * 100vw) | Long-form prose in inset, staggered reading columns. |
| organization pages | intro-body | ABCMonumentGroteskWeb | 400 | 16.5px | 1.25 | -0.004em | size calc( 15 * 0.95 / 1240 * 100vw ) | Brief factual introduction before the serif chapters. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep all text at regular weight. Use scale, offset and the contrast between grotesk and serif to create hierarchy.
- The largest titles tighten to -0.02em; most interface and body text uses -0.004em. Serif display and intermediate headings use -0.01em.
- The graphic opening also carries an approximately 72px grotesk slogan on staggered lines and approximately 52px date lettering; preserve its visual proportion to the central identity text.
- Long prose is not a single full-width wall: alternating paragraph insets and distinct serif versus grotesk passages are part of the hierarchy.

## Layout

**Density:** Airy at the page scale, compact inside controls and panels; large unoccupied identity fields contrast with tightly packed information.

### Spacing

**Spacing system:**

- **rhythm** 12px — Main spacing rhythm; 6px is the declared half-step.

| Value | Use |
| --- | --- |
| 6px | Half-step for utility-strip padding and tiny control gaps. |
| 12px | Panel vertical padding, featured-card padding and caption separation. |
| 18px | Panel horizontal padding and large-link vertical margins. |
| 24px | Landing-page outer inset and list-item separation. |
| 36px | Editorial side padding and panel copy/action separation. |
| 48px | Floating-module separation and directory group spacing; 4 × 12px. |
| 72px | Editorial block separation; 6 × 12px. |
| 96px | Space after editorial title regions; 8 × 12px. |

### Containers and grids

- **Landing overlay**: 2 columns · side padding 24px. Full-width identity stage with information concentrated in the right half. At 1440px, a 720px half contains a 672px panel between 24px insets. The artwork is behind, not boxed into the other column.
- **Map and list overlap**: 2 columns. A 672px-wide map sits on the right, while a 338px white list overlaps its left edge and the identity sculpture. Avoid equal-width, neatly separated cards.
- **Editorial split** (only for editorial, directory and organization pages): 2 columns · side padding 36px. A fixed 360px identity rail occupies one quarter of the 1440px desktop. The white 1080px main area has 36px side padding, leaving 1008px of content.
- **Inset reading column** (only for editorial and organization pages): max width 732px. Serif prose starts 168px into the 1008px reading field; other paragraphs can return to the left edge or shift farther right.

## Corner radius

| Element | Radius |
| --- | --- |
| Utility actions | 5px |
| Small chips | 3px |
| Guide pill | 44.1px |
| Map frame | 7px |

## Surfaces and depth

### Surfaces

#### Electric field · level 0

**Use:** Default landing-page canvas.

**CSS:** `background: #00ecec`

**Observed:** Unbroken cyan continues behind the artwork, panels and footer.

**Transfer:** Keep the field flat and saturated; do not convert it into a gradient.

#### White information panel · level 1

**Use:** Descriptions and featured information floating over the identity field.

**CSS:** `background: #ffffff; padding: 12px 18px; border: 0px; box-shadow: none`

**Observed:** Rectangular, unframed panels appear on the right and overlap the black artwork.

**Transfer:** Give the content a paper-like interruption without introducing a dashboard-card aesthetic.

#### Utility chip surface · level 1

**Use:** Secondary actions and metadata.

**CSS:** `background: #f2f2f2; border-radius: 3px; box-shadow: none`

**Observed:** A very light gray fill distinguishes small actions without outlines.

**Transfer:** Keep these chips visually subordinate to the black Guide pill.

#### White reading field · level 0

**Only for:** editorial, directory and organization pages

**Use:** Main reading canvas beside the colored identity rail.

**CSS:** `background: #ffffff`

**Observed:** The accent stays in the left quarter while text and photos fill the other three quarters.

**Transfer:** Use this variant for information-heavy pages, retaining a strong left identity anchor.

## Components

### Guide pill

**Use:** Persistent primary navigation into the main experience.

**CSS:** `background: #000000; color: #00ecec; border-radius: 44.1px; padding: 6.6px 22.1px 5.5px; height: 35px; box-sizing: border-box`

**Text style:** `action` — ABCMonumentGroteskWeb 400 · 22.1px/1.025 · tracking -0.004em

**Observed:** Sits beside Menu in a compact fixed cluster at the upper left. A pseudo-element provides a 1px accent outline at 0.3 opacity. Editorial variants use their rail hue for the lettering.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

**Transfer:** Use a short destination noun rather than an inflated sales CTA.

### Menu toggle

**Use:** Global navigation access.

**CSS:** `color: #000000; background: #ffffff; padding: 0px 18.8px 0px 46.9px; height: 35px`

**Text style:** `menu` — ABCMonumentGroteskWeb 400 · 18.8px/1.025 · tracking -0.004em

**Observed:** Small rectangular toggle with three fine horizontal bars at the left. It shares the top cluster with Guide, not a full-width navigation bar.

**States:** Declared: hover background-color #fff; focus-visible outline blue solid 2px, outline-offset 2px.

### Utility action

**Use:** Short practical links in the horizontally scrollable action strip.

**CSS:** `background: #ffffff; color: #000000; border-radius: 5px; padding: 6.6px 11px 4.4px; height: 34px; box-sizing: border-box`

**Text style:** `action` — ABCMonumentGroteskWeb 400 · 22.1px/1.025 · tracking -0.004em

**Observed:** Consecutive actions sit tightly together inside a white strip with rounded outer ends. The strip occupies the right half and clips overflowing labels rather than becoming a large grid.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

**Transfer:** Use for practical product resources such as access, documentation and support.

### Secondary action

**Use:** Small centered link below panel prose.

**CSS:** `background: #f2f2f2; color: #000000; border-radius: 3px; padding: 5px 8.3px 3.3px; height: 25px; box-sizing: border-box`

**Text style:** `small-action` — ABCMonumentGroteskWeb 400 · 16.5px/1.025 · tracking -0.004em

**Observed:** A single low-emphasis action is centered below a paragraph. The same construction serves as a view toggle in directories.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

### Metadata chip

**Use:** Compact contextual links under a named item.

**CSS:** `background: #f2f2f2; color: #000000; border-radius: 3px; padding: 4.3px 5px 2.9px; height: 22px; box-sizing: border-box`

**Text style:** `label` — ABCMonumentGroteskWeb 400 · 14.3px/1.025 · tracking -0.004em

**Observed:** Tiny actions wrap in a centered row below the name; related event metadata also appears as cyan chips on a dark tinted field.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

### Information panel

**Use:** Prominent descriptive introduction.

**CSS:** `background: #ffffff; padding: 12px 18px; width: 672px; box-sizing: border-box`

**Text style:** `panel-prose` — BradfordLLSub 400 · 23.2px/1.15 · tracking -0.01em

**Observed:** Centered section label, then a serif paragraph with a conspicuous first-line inset, then a centered Secondary action. The panel is placed over rather than next to the graphic background.

**Transfer:** Use one substantial paragraph, not a stack of short feature bullets.

### Featured program card

**Use:** Dated featured content or an upcoming product milestone.

**CSS:** `background: #ffffff; padding: 12px; width: 672px; box-sizing: border-box`

**Text style:** `event-title` — BradfordLLSub 400 · 30.2px/1.15 · tracking -0.01em

**Observed:** A top row combines prominent date, uppercase weekday and small time. A serif title sits below, followed by contextual chips. One white featured card is followed by smaller translucent dark cards with cyan text.

**Transfer:** Translate the hierarchy to launches, demos or editorial updates while retaining date/title/metadata order.

### Footer link

**Use:** Contact, social and policy navigation.

**CSS:** `color: #000000; border-radius: 3px; text-decoration: none`

**Text style:** `footer-link` — ABCMonumentGroteskWeb 400 · 14.3px/1.025 · tracking 0.01em · uppercase

**Observed:** Two short links stack at the left, with social links below and policy links in a neighboring column; credits and partner marks occupy the right half.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

### Directory name

**Only for:** directory pages

**Use:** Individual destinations within alphabetical groups.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `event-title` — BradfordLLSub 400 · 30.2px/1.15 · tracking -0.01em

**Observed:** Names flow as inline blocks with substantial horizontal separation. Some groups begin at the horizontal midpoint, then wrap back to the left edge. Long names span multiple lines rather than being truncated.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

### Large destination link

**Only for:** editorial and organization pages

**Use:** Related sections or important destinations presented as typography.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `large-link` — ABCMonumentGroteskWeb 400 · 48.5px/1.025 · tracking -0.01em

**Observed:** Large regular grotesk labels with a tiny right arrow are staggered across the reading field. Each occupies its own row; these are not uniform cards.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px, outline-offset 2px.

## Imagery and graphics

### Typographic sculpture

**Use:** Signature graphic in the opening, persistent identity layer and closing gesture.

**Observed:** Huge black filled shapes combine rectangular stems, stepped edges and a large quarter-round terminal. They read as abstract letterforms, not a conventional text heading. Cyan numerals and a two-line identity inscription sit over the solid form. The sculpture changes proportions through the page and is compressed vertically into the editorial left rail.

**Transfer:** Create an original silhouette from the new product's initial or a simple two-part geometric monogram. The minimum equivalent is a crisp SVG of interlocked black rectangles and one quarter-circle, overlaid with live identity text and small numeric markers.

**Build:** Use an SVG viewBox of 1440 900 behind content. Combine 3–5 #000000 rectangles into a stepped, mostly continuous silhouette occupying about 80% of the opening width and 95% of its height. Add one broad quarter-circle terminal using an SVG arc; retain cyan negative space at the upper right for the slogan. Place #00ecec live text across the middle and a numeric marker above and below. For editorial variants, redraw to a narrow 360px-wide vertical composition rather than squeezing the full landscape artwork.

### Tinted street diagram

**Use:** Large information graphic alongside an overlapping list.

**Observed:** A detailed black-line street map sits on cyan with muted teal land and water, rounded slightly at its corners. White diamond markers contain small black letters. The adjacent white list overlaps the map's left edge.

**Transfer:** Use a product ecosystem, process or location diagram with the same black-line density, single cyan backing and simple white markers.

**Build:** Build a 4:3 SVG on #00ecec with thin rgba(0,0,0,0.35) intersecting paths and a few heavier black routes at 0.6 opacity. Add white 47px diamond markers using rotated squares and counter-rotate their text. Clip into a 7px-radius frame; pair with the overlapping white list.

### Documentary photography

**Only for:** editorial and organization pages

**Use:** Visual evidence within long-form content.

**Observed:** Unfiltered installation views and a casually posed group portrait appear as clean rectangular photographs on white. The group photograph uses a pale wall and full natural clothing colors, with no decorative frame. A landscape image can occupy 720×480px with its numbered caption immediately to the right; the gallery mixes landscape and portrait aspect ratios.

**Transfer:** Show the real people, working environment or physical result behind the product. Preserve natural light and color; use small factual credits instead of promotional overlays.

### Icons

**Observed:** Black utility marks are sparse: three 16px-wide, 1px-high menu bars, small right arrows appended to large destinations, and lettered white diamond map markers. Typography carries most of the interface.

**Transfer:** Use simple line marks and small arrows; reserve larger symbolic shapes for the identity artwork and diagram markers.

## Section recipes

How recurring sections are built.

### First screen: Electric poster opening

**Observed:** A 900px-tall cyan stage places an oversized black Typographic sculpture behind all content. The silhouette spans most of the left and lower field, with cyan identity lettering around 61.8px across its middle and small numeric markers above and below. An offset, short grotesk slogan occupies the upper-right negative space at roughly 72px, followed by a stacked numeric date around 52px. The fixed Guide pill and Menu toggle occupy the upper-left. Within the first 900px, the right-side Utility action strip appears around the lower quarter and the top of an Information panel enters beneath it. Most supporting prose and subsequent content continue below the fold.

**Transfer:** Use an original geometric identity as the main object, a short product promise in the upper-right and a few practical actions below. No product photography is needed: the monogram is the visual demonstration of identity. Editorial pages instead open with a 360px colored sculpture rail and white reading field, a 61.8px title and an inset introduction. Directories open with a tiny filter, not a huge title.

**Avoid:** Do not replace the graphic stage with a centered headline, paragraph and oversized CTA above a mockup. Do not leave the initial navigation expanded as a permanent overlay.

**Text style:** `display` — ABCMonumentGroteskWeb 400 · 61.8px/1.025 · tracking -0.02em

### Floating editorial panel

**Observed:** The White information panel occupies the right half over the electric field and black artwork. A centered label precedes a serif paragraph; a 36px separation leads to the Secondary action. The label is visually smaller than the prose, not a second headline.

**Transfer:** Use this for a compact explanation of what the product does, allowing the graphic identity to remain visible on the left.

**Text style:** `panel-prose` — BradfordLLSub 400 · 23.2px/1.15 · tracking -0.01em

### Dated proof cluster

**Observed:** A centered section label introduces the Featured program card. Smaller dark tinted cards follow in a horizontal row, reversing their title and metadata into cyan. The white card carries a date and serif heading with the strongest hierarchy.

**Transfer:** Use dated proof, releases or upcoming activities; vary emphasis through a single white featured item rather than many equal cards.

**Text style:** `event-title` — BradfordLLSub 400 · 30.2px/1.15 · tracking -0.01em

### Overlapping diagram and index

**Observed:** A 672×504px Tinted street diagram dominates the right half, while a narrow white list overlaps its left edge and the sculpture. Each list item combines a tiny centered letter, a 25.4px name and Metadata chips; the list has its own vertical scroll area.

**Transfer:** Pair a dense functional diagram with a concise navigable index. Preserve the intentional overlap and the contrasting gray chips.

**Text style:** `card-heading` — ABCMonumentGroteskWeb 400 · 25.4px/1.15 · tracking -0.01em

### Identity return and compact credits

**Observed:** The landing close brings the black sculpture back to near full width before the electric-field footer. Footer links form small left-side stacks, social and policy links sit lower, and partner marks plus factual credits occupy the right half. Editorial endings retain the colored rail, place a tiny stacked identity mark above the footer and allow a broad white pause; footer padding is 128px 36px 36px instead of the landing's 6px 24px 24px.

**Transfer:** Close with the product's graphic identity and practical contact/credit information. On editorial pages use the miniature identity mark and whitespace, not a new promotional banner.

**Text style:** `footer-link` — ABCMonumentGroteskWeb 400 · 14.3px/1.025 · tracking 0.01em · uppercase

### Staggered long-form chapter

**Only for:** editorial and organization pages

**Observed:** White reading field beside a colored identity rail. A small heading or 33.1px chapter heading introduces serif prose in an inset reading column. Paragraphs shift between left and right alignments with 72px block separation. Feature statements switch to 22.1px grotesk at 1.25 line height. Documentary photography interrupts the text with numbered captions placed above or beside it.

**Transfer:** Use for a product's rationale, research or organization story; alternate typographic register only when the content role changes.

**Text style:** `editorial-body` — BradfordLLSub 400 · 17.4px/1.25 · tracking -0.004em

### Alphabetical constellation

**Only for:** directory pages

**Observed:** A small centered filter and top-right view toggle precede alphabetical groups. Each group has a tiny centered letter, 12px top padding and 48px bottom margin. Directory names wrap through the 1008px reading field with variable starting positions and broad gaps, producing an open constellation rather than columns or table rows.

**Transfer:** Use for people, partners, resources or a catalog whose names matter more than thumbnails.

**Text style:** `event-title` — BradfordLLSub 400 · 30.2px/1.15 · tracking -0.01em

### Typographic destination field

**Only for:** editorial and organization pages

**Observed:** Large destination links at 48.5px sit in individual staggered rows across the white field; some wrap naturally, each ending with a tiny arrow. A small centered section label can introduce the group.

**Transfer:** Turn important related chapters or destinations into spatial typography instead of cards.

**Text style:** `large-link` — ABCMonumentGroteskWeb 400 · 48.5px/1.025 · tracking -0.01em

## Page flow

**Storyline:** Graphic identity → concise orientation → practical entry points → contextual proof or deeper reading → related destinations → identity return and factual credits.

### High-impact landing page

1. **Promise** — Electric poster opening with geometric identity and short offset slogan.
2. **Orientation** — Utility action strip and floating introductory panel.
3. **Current proof** — Dated featured content with secondary entries.
4. **Exploration** — Overlapping diagram and navigable list.
5. **Closing identity** — Sculpture returns before compact cyan-field credits.

**Transfer:** Let the visual identity anchor a product launch, with practical resources and a small amount of current proof.

### Long-form feature or offering explanation

1. **Orientation** — Colored left rail, large page title and inset serif introduction.
2. **Visual proof** — Horizontally scrolling documentary gallery with numbered captions.
3. **Rationale** — Staggered long statement in larger grotesk.
4. **Practical next step** — Small resource download followed by large destination links.
5. **Closing identity** — Tiny stacked mark, long white pause and factual footer.

**Transfer:** Use for a flagship offering that needs editorial depth rather than a feature-card grid.

### Browsable index

1. **Wayfinding** — Small filter and alternate view control.
2. **Exploration** — Alphabetical groups of serif links with offset starts and natural wraps.
3. **Closing identity** — Final letter groups lead into a small identity mark and shared white footer.

**Transfer:** Use a type-only directory when the names themselves carry the content.

### Organization narrative

1. **Orientation** — Large title followed by three staggered destination links.
2. **Summary** — Short factual grotesk introduction.
3. **Context** — Chapter headings and inset serif paragraphs.
4. **Human proof** — Natural group portrait with adjacent numbered caption.
5. **Continuity** — Institutional context, an inline external link, then the small identity mark and shared footer.

**Transfer:** Pair a factual summary with deeper editorial chapters and one honest portrait rather than a tiled team wall.

## Writing

Direct and institutional, with intellectual seriousness and very little salesmanship. Utility copy is plain; editorial copy is discursive and specific, willing to name difficult questions without turning them into slogans.

**Do not copy:** Do not reuse the identity artwork, event title, organization and artist names, dates, funding claims, curatorial quotations or partner logos. Replace all with the new product's own verified identity and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person and impersonal; the organization is named explicitly. First-person plural belongs to attributed statements, not routine promotional copy.
- **Rhythm:** One-word navigation and short declarative titles contrast with long, complete editorial sentences. Compact factual labels support the longer passages; exclamation is reserved for a campaign title rather than spread across interface copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign title | A compact assertion with conceptual tension; typeset as separated words rather than explanatory prose. | 2–4 words | “Still Present!” |
| Section label | A plain category noun, without a decorative eyebrow phrase. | 1–2 words | “Visit”<br>“Program”<br>“Venues” |
| Action | A destination noun or a literal verb plus object. | 1–4 words | “Learn more”<br>“Download floor plans”<br>“Opening Hours” |
| Supporting prose | Begin with what the organization does and who participates, then add its purpose and context. | Several complete sentences per paragraph | “Every two years, the [Brand] for Contemporary Art brings together international artists, theoreticians, and practitioners in exhibitions and accompanying programs.” |
| Image caption | Identify people or work, context, date and credit using factual naming. | One compact factual paragraph | “Ana Teixeira Pinto, Noam Segal, Kader Attia, Đỗ Tường Linh, Rasha Salti, Marie Helene Pereira. Photo: Silke Briel” |

**Words and phrasing to use:** present-tense factual verbs; specific roles and names; program; access; projects; context; questions

**Avoid:** game-changing; unlock your potential; seamless magic; revolutionary solution; sales urgency; unverified superlatives

**Rules:**

- Keep interface labels literal even when the campaign language is conceptual.
- Use exact dates, times and attribution where content requires them.
- Let extended editorial copy articulate an argument instead of splitting every sentence into a benefit bullet.
- Use parentheses for functional qualifiers, such as language or a filter label.

## Do's and Don'ts

### Do

- Keep the main identity at weight 400 and make its scale, not boldness, carry the opening.
- Maintain the 672px right-side panel proportion within a 1440px desktop composition.
- Use 12px panel padding vertically and 18px horizontally for introductory prose.
- Retain the contrast between 30.2px serif titles and small grotesk metadata.
- Keep the Guide pill at 35px high and gray secondary chips at 22–25px.
- Use the 12px rhythm for 36px, 48px, 72px and 96px structural spacing.
- Keep documentary photos rectangular with 12.1px numbered captions.
- Preserve a graphic identity return and compact factual footer in the closing area.

### Don't

- Do not use medium or bold UI headings to imitate hierarchy; the system uses regular cuts.
- Do not soften the cyan into pastel or spread multiple electric hues across one page.
- Do not add card shadows or faint decorative borders to the flat white panels.
- Do not turn all controls into 48px-high conversion buttons; their compactness is intentional.
- Do not round information panels into large soft cards; reserve 3px and 5px radii for small controls and 7px for the map.
- Do not color-grade documentary portraits into the page accent.
- Do not force directory names into equal thumbnail cards or truncate long names.
- Do not add a large promotional CTA block above the credits; the closing emphasis is graphic and institutional.

## Motion and responsive

### Motion

**Observed:**

- The identity sculpture changes its silhouette and scale through different scroll positions while remaining a persistent background or rail.
- Declared transitions include transform at 100ms using var(--easingQuadOut), transform at 500ms using var(--easeInOutQuart), and opacity at 100ms or 150ms. The map image declares a 150ms opacity transition.
- Utility strips and the image gallery have horizontal scrolling; the overlapping information list scrolls vertically.

**Transfer:**

- Treat graphic reshaping as the signature motion, keeping small controls visually stable.
- Preserve horizontal resource strips and gallery movement rather than wrapping them into dense grids.

**Unknown:**

- Exact mapping of scroll positions to sculpture geometry and the timing of its changes.
- Definitions of the named easing variables and complete open-menu motion.

### Responsive

**Observed:**

- Typography uses viewport-relative formulas based on a 1240px design width.
- Declared width breakpoints include 340px, 480px, 520px, 640px, 720px, 767px, 768px, 1024px, 1080px and 1240px.

**Transfer:**

- On narrow layouts, prioritize the sculpture silhouette and compact navigation before fitting the supporting content.
- Adapt the overlapping list and diagram into a readable stacked pair while preserving the cyan backing and lettered markers.
- For narrow editorial layouts, reduce or reposition the identity rail so prose remains readable; retain the single-hue identity anchor.

**Unknown:**

- Exact mobile rail behavior, column collapse rules and minimum font sizes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
