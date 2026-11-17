# A24 — cinema meets the index

## Overview

An image-led editorial style that moves between enormous cinematic titles and the matter-of-fact order of a cultural catalogue. White and near-black structure the page, while naturalistic photography and physical objects carry nearly all the color. Tight grotesk headlines, miniature monospaced labels and flat rectangular controls suit visually rich products, collections and launches with a confident, low-explanation voice.

### Essentials

- Titles behave like opening credits laid over a still: white grotesk at 225px/0.8, weight 485, with -11.2px tracking; short titles expand as far as 400px rather than sitting in a conventional text column.
- The first impression is almost entirely image: a 1428px-wide cinematic scene inside a 6px white frame, with a transparent fixed navigation above and a small outlined action beside the oversized lower title. Use a richly lit product-in-context photograph when narrative footage is unavailable.
- The interface stays monochrome while the work supplies color: white catalogue fields, #f1f1f1 object stages and #0e0e0d editorial bands; saturated color belongs within images, not colored UI panels.
- Editorial rails unite tiny labels and substantial headings: 1px rules, 24px outer gutters and column gaps, 56px headings, and 10px uppercase monospaced wayfinding with a compressed 7px line height.
- Controls look typeset rather than molded: square corners, 1px outlines, uppercase grotesk labels at 14px, 16px or 24px; large conversion controls use 18px 21.6px padding.
- Media shelves feel like a continuing collection: tall posters or square close-ups, captions directly beneath, fine vertical dividers and a next item cut by the viewport rather than compressed to fit.
- The ending contains a monumental material word sculpture: reflective extruded lettering occupies roughly two thirds of a near-black closing panel beside a 48px invitation and a white rectangular action. Render the new identity as metal lettering; a beveled SVG with layered silver shading is the minimum fallback.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0e0e0d` | `--color-ink` | text, background, border, action | Default text and rules on light fields; inverted editorial bands and footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dark image divider | `#383836` | `--color-dark-rule` | border | Visible low-contrast divider on dark fields; implemented with rgba(206,204,201,0.22) over near-black. |
| Secondary gray | `#9c9791` | `--color-secondary` | text, link | Product prices, subdued title qualifiers and active utility links. |
| Warm muted text | `#b2ada6` | `--color-muted` | text, link | Secondary closing copy, release years and hovered footer links. |
| Pale warm rule | `#f2f0ed` | `--color-light-rule` | border | Vertical media dividers and archive row separators. |
| Object stage gray | `#f1f1f1` | `--color-object-stage` | surface, background | Physical product photography stages and featured commerce bands. |
| Warm media backing | `#fcfbfa` | `--color-media-backing` | surface | Subtle backing beneath fully rendered poster and square-image media. |
| White | `#ffffff` | `--color-paper` | background, text, border, action | Default catalogue canvas; titles and rules on dark imagery; solid closing actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| commerce features | Purchase qualifier | `#6f6d6a` | `--color-price` | text | Secondary monetary label inside a large purchase action. |

## Typography

- **neueMontreal** — Titles, headings, captions, prose and actions. Closely set contemporary grotesk with plain forms and a slightly firm regular weight. If unavailable, use **Inter**. Use variable weights 420–485 and retain the close tracking; fit large titles to their lines. Font stack: "neueMontreal", "Inter", system-ui, sans-serif.
- **neueMontrealMono** — Micro labels, dates and prices. Compact utilitarian monospace contrasting with expansive grotesk titles. OpenType features: "zero". If unavailable, use **IBM Plex Mono**. Use regular and medium weights; preserve the unusually tight numeric tracking. Font stack: "neueMontrealMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-short | neueMontreal | 485 | 400px | 0.8 | -0.05em | Short photographic titles enlarged to fill the available line. |
| display-wide | neueMontreal | 485 | 354.5px | 0.8 | -0.05em | Single long word stretched by type fitting across a cinematic panel. |
| display-feature | neueMontreal | 485 | 304.6px | 0.8 | -0.05em | Large image-led promotional title within the body of a page. |
| display | neueMontreal | 485 | 225px | 0.8 | -0.0497em | Default multiword photographic opening title, broken into deliberately composed lines. |
| heading-xl | neueMontreal | 485 | 96px | 0.87 | -0.04em | Major catalogue heading or image-backed feature title. |
| heading | neueMontreal | 485 | 56px | 1.1 | -0.018em | Recurring media-shelf headings. |
| invitation | neueMontreal | 485 | 48px | 1 | -0.018em, features "zero" | Closing invitation and compact collection feature headings. |
| footer-link | neueMontreal | 420 | 27px | 1.1 | -0.005em | Closely stacked footer navigation. |
| card-title | neueMontreal | 485 | 24px | 1.1 | -0.005em | Names beneath cinematic square media and posters. |
| action-large | neueMontreal | 485 | 24px | 1 | -0.005em, uppercase, features "cpsp" | Major purchase and closing conversion actions. |
| release-year | neueMontrealMono | 420 | 24px | 1.1 | -0.05em, features "zero" | Muted year aligned to the far side of a media caption. |
| body | neueMontreal | 420 | 18px | 1.1 | 0.005em | Compact descriptions, credits and merchandise captions. |
| action-hero | neueMontreal | 485 | 16px | 1 | normal, uppercase, features "cpsp" | Outlined image-overlay action. |
| support-small | neueMontreal | 420 | 14px | 1.1 | 0.0075em | Narrow closing benefit paragraph. |
| action | neueMontreal | 485 | 14px | 1 | 0.005em, uppercase, features "cpsp" | Small shelf buttons and newsletter submission. |
| eyebrow | neueMontrealMono | 485 | 10px | 0.7 | 0.01em, uppercase, features "zero" | Section labels, status labels and small directional links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| commerce features | commerce-heading | neueMontreal | 485 | 48px | 0.95 | -0.018em | Featured physical product title above the object stage. |
| catalogue index pages | index-title | neueMontreal | 485 | 42px | 1 | -0.0125em | Text-first archive item title with inline version qualifier. |
| catalogue index pages | index-year | neueMontrealMono | 485 | 42px | 1 | -0.06em, features "zero" | Year marking the beginning of an archive group. |
| commerce shelves | product-price | neueMontrealMono | 420 | 18px | 1.1 | -0.04em, uppercase, features "zero" | Right-aligned price in a merchandise caption. |

**Notes:**

- The text weight is firm but not bold: headings and actions use 485, prose 420. Preserve this contrast rather than replacing titles with heavy display weights.
- Tracking tightens dramatically with scale: body text is slightly open, 56px headings use -0.018em, major 96px headings -0.04em, and giant titles approximately -0.05em.
- The giant titles are fitted to their copy and line lengths, not one universal size. Maintain the 0.8 line height and compose line endings deliberately.
- Micro labels have a compressed line box; provide surrounding spacing in their containing row so they remain distinct from titles.

## Layout

**Density:** Image-dense with compact annotations, balanced by substantial white intervals between shelves.

### Spacing

| Value | Use |
| --- | --- |
| 6px | White frame around the cinematic opening and icon-to-label gaps. |
| 8px | Space above tiny ruled labels. |
| 12px | Rule-to-heading padding and merchandise image-to-caption gaps. |
| 24px | Outer gutters, grid gaps and divider-side padding. |
| 48px | Heading-to-media separation on recurring shelves. |
| 64px | Separation after featured bands and top padding in the footer. |
| 84px | Bottom breathing room after the tall-poster shelf. |
| 106px | Bottom breathing room after square-image shelves. |

### Containers and grids

- **editorial-container**: max width 1800px · side padding 24px. Broad centered content container. At 1440px, the inner field is 1392px wide.
- **editorial-grid**: 12 columns · gap 24px. Shared alignment for section headers, feature spreads, footer and index.
- **poster-grid**: 3 columns · gap 24px. Three equal shelves; each occupies 448px at desktop including its divider-side padding.
- **feature-copy**: max width 324px. Compact description beside a large physical object.
- **closing-copy**: max width 240px. Small benefit paragraph below the closing invitation.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 0px |
| media | 1px |

## Surfaces and depth

### Surfaces

#### White editorial field · level 0

**Use:** Default marketing and catalogue background.

**CSS:** `background: #ffffff; color: #0e0e0d`

**Observed:** Flat canvas; grouping comes from rules rather than raised containers.

**Transfer:** Let image edges and editorial alignment define modules.

#### Object stage · level 0

**Use:** Feature band and merchandise-image backing.

**CSS:** `background: #f1f1f1`

**Observed:** Light neutral field gives photographed books, records and objects a physical setting.

**Transfer:** Use gray behind an actual object rendering, keeping its own soft contact shadow inside the image.

#### Dark editorial field · level 0

**Use:** Inverted media feature and closing area.

**CSS:** `background: #0e0e0d; color: #ffffff`

**Observed:** Near-black replaces white completely across the band; thin white rules and pale text maintain hierarchy.

**Transfer:** Reserve inversion for a meaningful visual chapter and the monumental ending.

#### Media skin · level 1

**Use:** Poster and square-image wrappers.

**CSS:** `background: #fcfbfa; border-radius: 1px; overflow: hidden`

**Observed:** Poster wrappers add an inset 1px edge using rgba(131,126,119,0.1); the image remains the content, not an empty tinted card.

**Transfer:** Use a full-coverage image and a faint inset edge where image boundaries need definition.

#### Image detail rail

**Use:** Columns of text over dark photographic features.

**CSS:** `border-top: 1px solid rgba(206,204,201,0.22); padding-top: 12px; padding-bottom: 48px`

**Observed:** Fine translucent rules partition the lower information strip without obscuring the scene.

**Transfer:** Use restrained rules rather than opaque text boxes.

## Components

### Overlay navigation

**Use:** Persistent top-level orientation over media or a light field.

**CSS:** `position: fixed; z-index: 4; display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); column-gap: 24px; padding: 12px 24px; height: 77px`

**Observed:** Small uppercase category links sit left, the identity is centered independently, and account actions sit right. White links sit over the opening photograph; mixed light and dark backgrounds use local contrast.

**Transfer:** Keep the header visually subordinate to the scene, with no opaque full-width toolbar.

### Hero outline action

**Use:** Conversion without interrupting the cinematic opening.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; color: #ffffff; background: transparent; border: 1px solid #ffffff; border-radius: 0px; padding: 10.7px 11.6px`

**Text style:** `action-hero` — neueMontreal 485 · 16px/1 · uppercase

**Observed:** A thin right arrow follows the label. The control is aligned near the right end of the title composition rather than centered below a support paragraph.

**States:** Declared: hover background #141313, color #fff, border-color #fff.

### Small outline button

**Use:** Actions attached to media captions and compact feature content.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #0e0e0d; border: 1px solid #0e0e0d; border-radius: 0px; padding: 7.7px 8.8px`

**Text style:** `action` — neueMontreal 485 · 14px/1 · tracking 0.005em · uppercase

**Observed:** Sits beside the media name rather than in a separate centered row. Dark-band variant reverses text and border to white on near-black and can add an arrow.

**States:** Declared: hover background #0e0e0d, color #fff, border-color #0e0e0d; the containing card can trigger the same state. Dark-band variant hovers to white with near-black text.

### Large conversion button

**Use:** Closing invitation and substantial purchase actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #0e0e0d; border: 1px solid #ffffff; border-radius: 0px; padding: 18px 21.6px`

**Text style:** `action-large` — neueMontreal 485 · 24px/1 · tracking -0.005em · uppercase

**Observed:** Solid white rectangle on dark fields. Commerce variant has a near-black border and may append a muted mono price after the label.

**States:** Declared: hover background #0e0e0d, color #fff, border-color #fff.

### Ruled section heading

**Use:** Introduce a media shelf or editorial chapter.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 12px; border-top: 1px solid #0e0e0d; padding-top: 12px; margin-bottom: 48px`

**Text style:** `heading` — neueMontreal 485 · 56px/1.1 · tracking -0.018em

**Observed:** The heading occupies the left edge; a micro uppercase mono link or thin carousel chevrons occupy the right. Dark-field variant uses a white rule.

**Transfer:** Use short editorial labels, with a tiny action rather than an equally large competing heading.

### Media shelf item

**Use:** Cinematic image and directly attached caption in a continuing horizontal collection.

**CSS:** `padding-right: 24px; margin-left: 24px; border-right: 1px solid #f2f0ed`

**Text style:** `card-title` — neueMontreal 485 · 24px/1.1 · tracking -0.005em

**Observed:** Square imagery is 541px wide inside a 566px slide; the title and muted release year or partner mark share the line beneath. Tall-poster variant uses a 423px by 635px image inside a 448px slide, status label, title and small action.

**Transfer:** Use consistent aspect ratios within one shelf and let the last visible item continue beyond the edge.

### Footer navigation link

**Use:** Dense directory of destinations in the closing field.

**CSS:** `color: #ffffff; text-decoration: none`

**Text style:** `footer-link` — neueMontreal 420 · 27px/1.1 · tracking -0.005em

**Observed:** Closely stacked links form editorial columns with no individual button boxes. Groups share the main grid with a newsletter to the right.

**States:** Declared: hover color #b2ada6.

### Joined email field

**Use:** Newsletter signup integrated into the footer directory.

**CSS:** `background: #0e0e0d; border-top: 1px solid #ffffff; border-bottom: 1px solid #ffffff; border-left: 1px solid #ffffff; border-right: 0px; padding: 12px 10px; border-radius: 0px`

**Observed:** A 43px-tall field shares a single uninterrupted row with a white submission button. A tiny mono subscription label sits above. The field occupies the flexible track, with a 75px submission cell at desktop.

**Transfer:** Keep the input and action edge-to-edge rather than separate rounded widgets.

### Archive row

**Only for:** catalogue index pages

**Use:** High-density text-first browsing of a large collection.

**CSS:** `display: grid; grid-template-columns: repeat(10, minmax(0px, 1fr)); column-gap: 24px; padding-top: 8px; padding-bottom: 16px; border-top: 1px solid #f2f0ed`

**Text style:** `index-title` — neueMontreal 485 · 42px/1 · tracking -0.0125em

**Observed:** A year column sits outside the ten-column content rail in the shared twelve-column grid. The name takes most of the rail, followed by compact contributor text and a pale partner mark. Inline version text is much lighter than the title. Most rows are about 83px high, with taller rows for wrapped titles.

**Transfer:** Adapt to grouped editions, case studies or releases; show the grouping label only when the group changes.

## Imagery and graphics

### Cinematic close-ups

**Use:** Opening scene, photographic feature panels and square media shelves.

**Observed:** Human faces and emotionally charged gestures fill the frame, with natural grain, deep shadow, warm skin and selective strong color. Wide imagery is full-bleed within a thin white frame; square cuts retain an intimate close-up rather than a miniature complete poster.

**Transfer:** Photograph the product being used in a real environment with a strong focal subject, directional light and textured shadows. If there is no footage, a single carefully lit still must carry the same scene-setting weight.

### Poster artwork

**Use:** Tall collection shelf.

**Observed:** Three portrait images mix close-up photography with title artwork embedded within the image. Each remains a complete designed object rather than a generic thumbnail.

**Transfer:** Commission distinct portrait artwork for each offering, preserving common dimensions and caption alignment without forcing all art into one color scheme.

### Physical objects on gray

**Use:** Merchandise shelves, commerce spread and inverted product chapter.

**Observed:** Open books, printed covers, nesting objects and colored vinyl records appear isolated on light gray, with restrained contact shadows. The commerce spread gives the open book roughly two thirds of the width; the inverted chapter staggers a larger lower object against a smaller upper object.

**Transfer:** Render packaging, hardware or printed matter with honest material texture and soft studio lighting. For a digital-only product, stage a tangible artifact of use rather than inventing a floating dashboard.

### Reflective word sculpture

**Use:** Signature closing invitation.

**Observed:** Huge silver extruded identity letters rise toward the right, with deep reflective sides, bright bevels and cool gray faces. The sculpture is clipped at the right and bottom of the near-black panel, dwarfing the adjacent invitation; it is an image approximately 1026px by 407px within a 443px-tall rail.

**Transfer:** Create an original typographic sculpture from the new product's name or initials. Retain the metallic mass, oblique depth and edge clipping, not the original letterforms.

**Build:** Preferred build: extrude bold outline lettering in 3D with substantial depth, narrow bevels, a reflective silver material and broad white studio lights against transparent black. Rotate the word so its right side appears larger and its depth recedes upper-left; render on transparency. Minimum SVG fallback: convert original lettering to paths, stack offset copies toward upper-left to form deep sidewalls, shade faces with alternating pale-gray and charcoal linear gradients, add thin bright bevel outlines and broad blurred white reflection bands clipped inside the side faces. Fill the right two thirds of the closing rail and clip its bottom and right edges; keep the left invitation unobstructed.

### Place as a feature backdrop

**Only for:** location-led or experiential promotions

**Use:** Full-width promotional feature before the ending.

**Observed:** A frontal brick facade and vivid red entrance fill a 1440px by 720px panel. White title, credits, description and a solid action occupy a low horizontal rail; a subtle darkening at the bottom protects legibility.

**Transfer:** Use a strongly identifiable real setting associated with the offering, preserving its architectural texture and placing information along the lower edge.

### Icons

**Observed:** Thin right arrows at 12px or 16px accompany actions and tiny links. Carousel chevrons use a 36px square graphic with 1px round-capped strokes inside a 44px by 42px target. Partner marks are pale filled wordmarks, not colorful badges.

**Transfer:** Use simple 1px directional SVGs with no enclosing circles or decorative icon tiles. Keep partner identities visually secondary.

## Section recipes

How recurring sections are built.

### First screen: Cinematic title opening

**Observed:** The first 900px are dominated by a photographic scene, approximately 1428px wide by 837px high, framed in 6px white. Back to front: edge-to-edge image, bottom-aligned white display title and a small Hero outline action, then Overlay navigation. The image focal point remains high enough to read above the lower title. The 225px title spans almost the entire width in two close lines: the first reads from the left, and the second is anchored toward the right. The action sits to the right just above the title. There is no supporting paragraph. The full first panel and a small slice of the next image appear above the fold; collection headings remain below.

**Transfer:** Make the new offering's name or concise promise the overlaid title, paired with an expressive original scene. Fit short titles up to the display-short scale. Use a product-in-use still if footage is unavailable. Catalogue pages instead use a white left third with a 96px category heading near the top and a 48px item name near the bottom, beside a square image spanning the right two thirds.

**Avoid:** Do not substitute a centered headline-and-paragraph hero with a small image below; do not put the giant title in a separate white box or obscure the subject with a heavy universal gradient.

**Text style:** `display` — neueMontreal 485 · 225px/0.8 · tracking -0.0497em

### Ruled collection shelf

**Observed:** White editorial field contains Ruled section heading and a continuing row of Media shelf items, separated by 24px gutters. Large square crops show two full items and part of a third, while the tall-poster variant fits three columns. Captions sit immediately beneath media; 84px or 106px bottom spacing separates the next chapter.

**Transfer:** Use this for several offerings or proofs that benefit from their own visual identities, choosing one consistent image shape per shelf.

### Featured object spread

**Observed:** Object stage begins with a split ruled header: tiny category link in the left quarter and a 48px commerce heading in the remaining width. A large open object fills approximately two thirds below; a narrow description and Large conversion button sit low on the right, with a 44px separation between description and action.

**Transfer:** Give one physical product, artifact or deliverable a materially convincing spread rather than surrounding it with small feature cards.

**Text style:** `commerce-heading` — neueMontreal 485 · 48px/0.95 · tracking -0.018em

### Promotional image interlude

**Observed:** A broad photograph returns between white shelves with a 304.6px white title fitted into the image. A compact metadata rail and joined email action add release timing and an update invitation without becoming a long explanatory section.

**Transfer:** Use one strong scene to introduce a future capability, launch or special project; keep date and update information terse.

**Text style:** `display-feature` — neueMontreal 485 · 304.6px/0.8 · tracking -0.05em

### Inverted staggered objects

**Observed:** Dark editorial field carries a ruled 56px heading in its left two thirds. A larger object plate sits lower and inset on the left, while a smaller square plate aligns high on the right. White captions and Small outline buttons follow their own images.

**Transfer:** Create a contrasting chapter using two differently scaled objects or artifacts, preserving the asymmetric vertical staging.

### Directory and monumental invitation

**Observed:** Dark editorial field begins with grouped Footer navigation links and a Joined email field across the twelve-column grid. Below, a 0.5px white rule introduces a 443px invitation rail. Left: a two-line 48px invitation, 240px-wide muted support and Large conversion button. Right: Reflective word sculpture, oversized and clipped. Tiny monospaced legal lines form the final bottom strip, not another call to action.

**Transfer:** Keep both the practical directory and the expressive material identity. Adapt the invitation to ongoing participation, subscription or contact; the sculpture gives the ending its memorable visual weight.

**Text style:** `invitation` — neueMontreal 485 · 48px/1 · tracking -0.018em

### Photographic information rail

**Only for:** location-led or experiential promotions

**Observed:** A full-width 720px-high scene carries a tiny ruled top label and a lower twelve-column information strip. A two-line 96px title occupies four columns, credits two, compact prose four and a solid action two. Image detail rail and subtle vertical rules separate information without opaque panels.

**Transfer:** Use a real environment to hold richer contextual detail while retaining a single image as the section's main message.

**Text style:** `heading-xl` — neueMontreal 485 · 96px/0.87 · tracking -0.04em

### Collection catalogue opening and index

**Only for:** catalogue index pages

**Observed:** A split first screen sets a 96px category heading in the white left third and a 920px-square focal image on the right; a 48px item name sits low in the left column. Three-column square media previews lead into a ruled 96px archive heading, tiny column labels and Archive rows grouped by 42px mono years. The last group is followed by substantial white breathing room before the shared dark ending.

**Transfer:** Use this alternate opening when browsing a collection matters more than a single campaign promise. Follow visual selections with a text-first index for depth.

**Text style:** `heading-xl` — neueMontreal 485 · 96px/0.87 · tracking -0.04em

## Page flow

**Storyline:** Immersive visual hook → selected collection → deeper editorial or product features → practical directory and monumental invitation.

### Image-led marketing and discovery landing page

1. **Visual promise** — Oversized titles over successive framed cinematic scenes.
2. **Current selection** — Ruled heading and a three-column tall-artwork shelf.
3. **Focused product demonstration** — Gray object spread with a narrow description and purchase action.
4. **Breadth of offering** — Continuing square-image shelves with restrained captions.
5. **Future invitation** — Large photographic interlude and compact update form.
6. **Related offerings** — Merchandise shelf and staggered inverted object chapter.
7. **Contextual feature** — Full-width place photograph with lower information rail.
8. **Closing invitation** — Dark directory, newsletter, metallic identity sculpture and participation action.

**Transfer:** Borrow the alternation between immersive scenes, structured shelves and focused objects; choose the number and order that serve the new offering.

### Collection discovery with a deep searchable-looking editorial archive

1. **Featured selection** — Asymmetric split opening with category heading and a dominant square image.
2. **Visual browsing** — Three-column grid of square previews with inline qualifiers.
3. **Depth and completeness** — Large ruled index heading followed by year-grouped typographic rows, contributors and pale partner marks.
4. **Closing invitation** — The same dark directory, joined subscription form and monumental sculpture invitation.

**Transfer:** Use for release histories, portfolios or large collections; keep the archival typography scoped to browsing rather than turning ordinary landing-page sections into a table.

## Writing

Understated, culturally assured and concrete. Names and images do most of the persuasion; supporting copy adds specificity rather than declaring superiority.

**Do not copy:** Do not reuse A24, AAA24, its marks or sculpture letterforms, film and programme titles, creator names, artwork, membership benefits, prices, dates or claims. Source examples illustrate phrasing only.

- **Addressing the reader:** Usually impersonal labels and product names; direct second-person language appears in the closing invitation. Actions are plain imperatives.
- **Rhythm:** One- to four-word section labels and actions contrast with an occasional compact descriptive paragraph. Titles can be long proper names, but explanatory hero prose is absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | Name the featured work directly; let scale and image create the promise. | 1–5 words | “You Can See Everything”<br>“Crystal Lake” |
| Section heading | Plain category or availability phrase, sentence case. | 1–4 words | “Watch at home”<br>“New arrivals”<br>“Now streaming” |
| Supporting line | Describe actual contents or benefits with specific nouns, not a sweeping slogan. | One compact paragraph | “AAA24 members get free tickets on opening weekend, access to special events, monthly credits, Shop discount, exclusive content and more.” |
| Primary action | Short verb plus object, rendered in capitals by styling. | 1–4 words | “Buy Tickets”<br>“Get Updates”<br>“Become a member” |
| Closing invitation | An approachable second-person metaphor connecting access to the whole offering. | 5–7 words | “Your ticket to everything [Brand].” |

**Words and phrasing to use:** New; All; Now; Get; Visit; Listen; plain category names; specific materials and contents

**Avoid:** revolutionary; game-changing; best-in-class; unlock your potential; verbose benefit slogans

**Rules:**

- Let a featured name stand alone instead of attaching a marketing claim to every image.
- Use sentence case for headings and names; uppercase treatment belongs to interface actions and micro labels.
- Keep metadata separate from descriptive sentences: dates, status and prices are small annotations.
- Reserve direct address for useful invitations, not a running conversational monologue.

## Do's and Don'ts

### Do

- Keep the outer editorial gutter and column gap at 24px.
- Use 1px horizontal heading rules with 12px top padding and 48px separation before recurring shelf imagery.
- Keep body descriptions compact at 18px/1.1 with a narrow 324px measure beside large objects.
- Use square-corner controls and preserve the three action scales: 14px, 16px and 24px.
- Let photography and object art carry saturation while interface surfaces remain white, gray and near-black.
- Fit giant image titles to the line while retaining 0.8 line height and very tight tracking.
- Make the dark ending visually substantial with a 443px sculpture rail, not merely a line of copyright text.
- Keep title, year and action attached to the bottom edge of their own image.

### Don't

- Do not round buttons into pills; controls use 0px corners.
- Do not add drop shadows to editorial cards; surface depth belongs to photographed objects and the metallic sculpture.
- Do not replace 10px mono wayfinding with large colored category badges.
- Do not distribute saturated accent fills through the page interface; the chrome remains neutral.
- Do not squeeze a continuing 566px media shelf into three tiny equal cards; preserve the partial next item where this shelf variant is used.
- Do not turn the 27px stacked footer directory into a row of boxed navigation chips.
- Do not use heavy 700-weight headlines as a shortcut for impact; scale and tracking supply it.
- Do not use the 42px year-grouped archive typography for ordinary descriptive marketing paragraphs.

## Motion and responsive

### Motion

**Observed:**

- Some action and surface rules declare transform and opacity transitions at .15s cubic-bezier(.25, .46, .45, .94).
- Outlined controls invert foreground and background on hover; footer links mute to warm gray.
- The navigation is fixed and the media shelves include previous/next controls.

**Transfer:**

- Preserve the direct color inversion of rectangular actions rather than adding bouncing or glowing feedback.
- Keep any movement subordinate to the large photographic and typographic compositions.

**Unknown:**

- Exact playback behavior, slide timing and scroll-animation choreography are not established.

### Responsive

**Observed:**

- The desktop composition uses a twelve-column grid with 24px gutters and a 1800px maximum content width.
- Declared width thresholds include 767px/768px, 899px/900px, 1023px/1024px and 1199px/1200px.

**Transfer:**

- For narrow layouts, preserve the cinematic image and fitted title relationship rather than shrinking a desktop title blindly.
- Retain horizontally continuing media shelves when full-size imagery is important; stack feature copy beneath the object when the side rail no longer fits.
- Keep the closing sculpture visually dominant but separate its clipping region from the invitation text.

**Unknown:**

- Mobile navigation, exact column collapse and type resizing rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
