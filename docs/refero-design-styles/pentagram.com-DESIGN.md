# Pentagram — work as exhibition

## Overview

An image-led editorial style that feels like a living design exhibition rather than a sales funnel. White galleries alternate with charcoal curatorial chapters and a black closing signature, while saturated color belongs to the work on display. Regular grotesk typography, tiny factual captions and a monumental serif wordmark balance visual abundance with an unusually restrained interface. It suits visually demonstrable products, creative tools and portfolios with substantial proof to show.

### Essentials

- The work is the opening headline: a 60px white navigation strip sits above a full-width 617px photographic stage, with a centered 44px translucent sentence-filter and 16px corner captions rather than a giant sales slogan.
- Curatorial headlines are large but never heavy: Plain 52px/1.05, weight 400, -0.02em tracking; supporting catalog copy remains 16px/1.25 at the same regular weight.
- The interface stays achromatic while the exhibits carry the color: white galleries, #222222 thematic bands and a #000000 footer; colorful photography and graphics occupy most of the visual field inside those frames.
- Exhibits alternate in scale: 3:2 images span 456px, 924px or the full 1392px content width at desktop, separated by 12px gutters; titles sit only 8px below the image.
- Actions resemble compact editorial controls, not conversion badges: 4px corners, 28px category chips and 34px secondary buttons; only slideshow dots are circular.
- Include a curated black tray and a monumental closing signature: the tray has 24px padding and 8px corners inside a charcoal chapter; the closing white wordmark spans the content width in an approximately 1392×264px SVG. Use an original typographic signature and product evidence when equivalent artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Exhibition black | `#000000` | `--color-black` | background, surface, action | Inset exhibit trays, active controls and closing footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#1a1a1a` | `--color-ink` | text, link | Headings, body copy and navigation on white. |
| Charcoal chapter | `#222222` | `--color-chapter` | background | Full-width thematic editorial bands. |
| Dark separator | `#333333` | `--color-rule-dark` | border | Fine separators in the black closing area. |
| Charcoal control | `#3d3d3d` | `--color-control-inverse` | surface, action | Visible secondary-control fill on charcoal, made with white at 12% opacity. |
| Secondary gray | `#767676` | `--color-secondary` | text, link | Descriptions on white and inactive navigation. |
| Footer gray | `#8c8c8c` | `--color-muted-inverse` | text, link | Footer utility links and subdued exhibit captions. |
| Charcoal support | `#9e9e9e` | `--color-support-inverse` | text | Visible supporting text on charcoal, made with white at 56% opacity. |
| Light separator | `#e3e4e5` | `--color-rule-light` | border | Light section rules, notably the next-story boundary. |
| Pale control | `#ededed` | `--color-chip` | surface, action | Visible result of 7% black over white for category controls. |
| Frosted control | `#ededed` | `--color-glass` | surface | Neutral translucent filter; source fill is rgba(232,232,232,0.8), whose appearance follows the image beneath. |
| Gallery white | `#ffffff` | `--color-canvas` | background, text | Main canvas and inverse headings. |

## Typography

- **Plain** — All live headings, descriptions, captions and controls. Matter-of-fact contemporary grotesk with open counters; regular weight does almost all the work. OpenType features: "case". If unavailable, use **Inter**. Use 400 and 500; preserve the restrained weights and negative headline tracking. Font stack: "Plain", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Plain | 400 | 52px | 1.05 | -0.02em | Curatorial chapter headings and detail-page titles. |
| statement | Plain | 400 | 32px | 1.2 | -0.01em | Offset editorial quotations and explanatory passages. |
| body | Plain | 400 | 16px | 1.25 | normal | Navigation, descriptions, exhibit names, actions and hero corner captions. |
| footer-heading | Plain | 500 | 16px | 1.25 | normal | Small functional headings in the closing information rows. |
| chip-label | Plain | 400 | 16px | 1 | normal | Category chips within centered collection introductions. |
| caption | Plain | 400 | 13px | 1.25 | normal | Years, dates and small classification labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| organization and team directories | directory-heading | Plain | 400 | 41px | 1.2 | -0.02em | Names of people-directory groups. |

**Notes:**

- Large headings tighten to -0.02em without increasing weight; the 32px statement uses -0.01em and all small text retains normal tracking.
- Card names and descriptions share the same 16px recipe. Color and line order, not size or boldness, separate them.
- The oversized serif closing signature is artwork, not another body font or a live heading recipe.

## Layout

**Density:** Airy between collections, compact inside each catalog entry; narrow gutters make the pictures read as one exhibition.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Image-to-caption gap and small icon separation. |
| 12px | Horizontal gallery gutter and compact metadata gaps. |
| 16px | Paragraph separation in institutional introductions. |
| 24px | Desktop side inset, tray padding, navigation gaps and footer row top padding. |
| 32px | Detail explanation top and bottom padding. |
| 48px | Dark chapter top padding, action separation and footer module gaps. |
| 64px | Dark chapter lower padding and separation before category introductions. |
| 96px | Major collection separation and space above the closing wordmark. |

### Containers and grids

- **gallery-container**: max width 1728px · side padding 24px. Centered main container; at 1440px the usable content width is 1392px.
- **project-grid**: 3 columns · gap 12px. Three equal 456px columns; a featured image spans two columns at 924px, with small and large exhibits top-aligned.
- **editorial-split**: 2 columns · gap 12px. Two 690px halves. Labels or titles occupy the left half while institutional prose, contact information and detail commentary occupy the right.
- **tray-grid**: 4 columns · gap 12px · side padding 24px. Four portrait exhibits inside a black tray; entire trays can form a horizontally continuing sequence.
- **portrait-grid** (only for organization and team directories): 4 columns · gap 12px. Four 339px square portraits across the content width, with 48px between rows.

## Corner radius

| Element | Radius |
| --- | --- |
| compact-controls | 4px |
| exhibit-tray | 8px |
| slide-dots | 50% |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Unframed catalog and detail content.

**CSS:** `background: #ffffff; color: #1a1a1a`

**Observed:** Images and captions sit directly on the page, without individual card shells.

**Transfer:** Let the media determine color and texture.

#### Curatorial band · level 0

**Use:** Thematic collections and editorial interludes.

**CSS:** `background: #222222; color: #ffffff; padding-top: 48px; padding-bottom: 64px`

**Observed:** Full-bleed band with content aligned to the gallery container; supporting prose is white at 56% opacity.

**Transfer:** Use to group evidence under an editorial idea rather than to decorate every other feature.

#### Exhibit tray · level 1

**Use:** A grouped set of portrait exhibits within a curatorial band.

**CSS:** `background: #000000; border-radius: 8px; padding: 24px; box-shadow: none`

**Observed:** A black mat surrounds several images together; the pictures themselves stay square-cornered.

**Transfer:** Group related outputs or product details as a single collection.

#### Frosted sentence control · level 2

**Use:** Filter sentence over the opening imagery.

**CSS:** `background: rgba(232,232,232,0.8); backdrop-filter: blur(7.5px); border-radius: 4px`

**Observed:** A small neutral translucent control remains legible without a large dark scrim.

**Transfer:** Keep the effect local to controls.

#### Closing black · level 0

**Use:** Contact, updates and closing signature.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** A substantial information section, not a narrow legal bar.

**Transfer:** Give practical next steps the same editorial alignment as the gallery.

## Components

### Navigation strip

**Use:** Persistent visual identity at the top of each page.

**CSS:** `height: 60px; display: flex; align-items: center; justify-content: space-between; padding: 0px 24px; background: #ffffff; color: #1a1a1a`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** Small wordmark on the left; compact text navigation and search on the far right, with 24px gaps. Secondary pages mute inactive links.

**States:** Declared: hover navigation text changes to #767676; focus-visible not specified.

**Transfer:** Use a small original identity, not a large navigation CTA.

### Sentence filter

**Use:** Central interactive proposition over the opening image.

**CSS:** `height: 44px; padding: 0px 16px; border-radius: 4px; background: rgba(232,232,232,0.8); backdrop-filter: blur(7.5px)`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** One natural-language sentence contains two dropdown choices and small chevrons; it begins centered on the image and also appears near the viewport bottom during gallery browsing.

**Transfer:** Turn capability and audience into two meaningful choices within a short sentence.

### Category chip

**Use:** A category embedded between a count and the word describing the collection.

**CSS:** `padding: 6px 8px; border-radius: 4px; background: rgba(0,0,0,0.07); color: #1a1a1a; height: 28px`

**Text style:** `chip-label` — Plain 400 · 16px/1

**Observed:** Centered above white galleries, with a small downward arrow below the collection line.

**States:** Declared: hover background rgba(0,0,0,0.15); focus-visible not specified; active background #000000 and text #ffffff.

### Show more control

**Use:** Continue a dark editorial collection.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 7px 8px 7px 12px; height: 34px; border-radius: 4px; background: rgba(255,255,255,0.12); color: #ffffff`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** Centered under the exhibit strip, with a small directional icon after the label.

**States:** Declared: hover background rgba(0,0,0,0.14); focus-visible not specified.

### Project caption

**Use:** Identify and explain an image-led exhibit.

**CSS:** `display: block; padding: 8px 24px 0px 0px; background: #ffffff; color: #1a1a1a`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** Title first, description immediately below in secondary gray; both remain regular weight. No border surrounds the entry.

**Transfer:** Name the output, then state its purpose in one factual sentence.

### Collection tray

**Use:** Group several exhibits as a curated set.

**CSS:** `display: flex; gap: 12px; padding: 24px; border-radius: 8px; background: #000000`

**Observed:** Four tall pictures sit side by side with captions underneath. The tray is inset from the page edge and may reveal another tray to the right.

**Transfer:** Use four coherent demonstrations, objects or applications instead of four generic feature icons.

### News row

**Use:** Dated updates within the closing area.

**CSS:** `position: relative; border-top: 1px solid #333333; padding-top: 24px`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** Rows occupy the right half opposite a small section label. Some include a 222px square thumbnail; a small category chip and date precede the title and muted description.

**Transfer:** Use recent releases or editorial updates rather than a large promotional card.

### Footer utility link

**Use:** Social and secondary links beneath the closing signature.

**CSS:** `color: #8c8c8c`

**Text style:** `body` — Plain 400 · 16px/1.25

**Observed:** A compact horizontal list with 24px gaps; legal utilities sit on the opposite side.

**States:** Declared: hover text changes to #ffffff; focus-visible not specified.

### Closing signature

**Use:** The final visual statement above utility links.

**CSS:** `width: 100%; height: auto; margin-top: 96px; color: #ffffff`

**Observed:** A wide high-contrast serif SVG wordmark occupies almost the entire content width. It contrasts sharply with the small grotesk information above and below.

**Transfer:** Set an original product or company name as fitted vector lettering, preserving an expansive horizontal silhouette.

## Imagery and graphics

### Immersive opening photograph

**Use:** The lead visual proposition.

**Observed:** A low-angle architectural photograph fills the stage edge to edge: strong converging geometry, natural blue sky, gray stone and embedded typographic texture. The picture dominates the opening; white factual text occupies only its lower corner.

**Transfer:** Use one striking product-in-context photograph with a clear silhouette and generous scale. Without photography, create a tightly art-directed full-frame product render or a real interface composition; do not substitute a collage of tiny mockups.

### Color-rich exhibit media

**Use:** Catalog entries and curated trays.

**Observed:** Photography, packaging, graphic identities, posters and product renders retain their own vivid colors and backgrounds. White galleries favor 3:2 rectangles; black trays use portrait formats around 286×400px. Media is sharp-edged and large, with very small external captions.

**Transfer:** Show actual outputs and use cases with varied but deliberate art direction. For software, display meaningful interface states and applications rather than inventing a uniform decorative background for every image.

### Closing wordmark artwork

**Use:** Required monumental brand signature.

**Observed:** White high-contrast serif lettering stretches across black, with pronounced thick-thin contrast, fine serifs and a lively descender. The artwork is approximately 1392×264px at desktop.

**Transfer:** Use the new brand's own name. The minimum equivalent is an elegantly fitted serif typographic signature rather than an enlarged sans-serif body heading.

**Build:** Create an SVG with a 1392×264 viewBox and white vector lettering. Start from a high-contrast display serif such as Bodoni Moda, fit the full name to the width while preserving aspect ratio, and adjust the viewBox around ascenders and descenders. Keep it flat white on black with no outline, glow or texture.

### Monochrome portrait wall

**Only for:** organization and team directories

**Use:** Human proof after the institutional introduction.

**Observed:** Square head-and-shoulder portraits use mostly dark studio backgrounds and black-and-white treatment, with varied expressions and poses. Four columns show names in ink and locations in gray, separated from the next row by open white space.

**Transfer:** Photograph real people consistently but preserve personality; retain square framing, grayscale and the simple name/location caption.

### Icons

**Observed:** Sparse functional symbols: search, dropdown chevrons, arrows and a plus. Most occupy 20×20px boxes; secondary arrows can be 16px. They inherit text color rather than introducing a separate accent.

**Transfer:** Choose small plain line symbols and keep them subordinate to words and media; avoid feature-icon medallions.

## Section recipes

How recurring sections are built.

### First screen: Image as proposition

**Observed:** A white 60px Navigation strip sits above a full-bleed 617px image stage. The picture is the dominant object and carries the visual promise; there is no large overlaid headline. Front layers are the centered 44px Sentence filter, a bottom-left title and explanatory caption in 16px white text, and 18px circular slide indicators at lower right. In the first 900px the entire stage is visible, followed by 96px of white separation and the beginning of a charcoal chapter with its 52px heading; the chapter's images remain below the fold.

**Transfer:** Use a product scene as the proposition and retain the compact sentence selector as the active entry point. On detail pages, open instead with a 52px title, a short description 48px below, tags and a small right-aligned information control before the lead media. Institutional pages use a left title and right prose split.

**Avoid:** Do not replace the image-first composition with a centered oversized slogan, two large pill CTAs and a small floating dashboard.

**Text style:** `heading` — Plain 400 · 52px/1.05 · tracking -0.02em

### Curated chapter

**Observed:** Curatorial band with a left-aligned heading and 16px muted support copy about half the content width, 24px below the heading. The Collection tray follows after 64px, placing four tall exhibits inside a single black mat. Chapter padding starts at 48px and ends at 64px; gallery chapters are separated by 96px.

**Transfer:** Name a point of view or capability and prove it through a coherent set of outputs.

**Text style:** `heading` — Plain 400 · 52px/1.05 · tracking -0.02em

### Editorial gallery

**Observed:** White Gallery canvas uses Category chip introductions and top-aligned image rows. Alternate three equal columns with a one-third/two-thirds pair and full-width exhibits; all imagery uses Project caption below. Large empty space beneath a smaller image is retained when its neighbor is taller.

**Transfer:** Vary the prominence of proof rather than forcing all features into equal cards.

### Offset statement

**Observed:** A 32px statement is offset to the right, beginning around one third of the gallery width in a dark quotation band. Detail explanations use the right half on white with 32px top and bottom padding.

**Transfer:** Give a short insight room to breathe between visual demonstrations; keep it a statement, not another sales headline.

**Text style:** `statement` — Plain 400 · 32px/1.2 · tracking -0.01em

### Black information close

**Observed:** Closing black organizes information in split rows: small labels on the left, news, direct contacts and concise institutional text on the right. Fine dark separators and 24px row top padding retain the catalog structure. The Closing signature follows with 96px separation, then a small gray utility line. Detail stories omit the news block; directory pages can omit the institutional paragraph.

**Transfer:** End with useful routes to contact, learn or continue, then the original monumental wordmark. Adapt the modules to the product rather than adding a generic newsletter billboard.

### Historical strip

**Only for:** archives and chronological proof

**Observed:** A dark chapter places a title and explanatory paragraph above a horizontally continuing strip of posters or landscape media, with years or titles above each image. Images can run beyond both viewport edges. A Show more control sits 48px beneath.

**Transfer:** Present product evolution, versions or an archive as an editorial sequence; use this variant only when there is a meaningful series.

### Institutional directory

**Only for:** organization and team directories

**Observed:** Left 52px title opposite right 16px prose, followed by a four-column portrait wall. Additional groups open with 41px headings, 48px top padding and 96px separation; text-only names remain in four aligned columns.

**Transfer:** Use for real organization, contributor or expert information, not as a default feature-grid format.

**Text style:** `directory-heading` — Plain 400 · 41px/1.2 · tracking -0.02em

### Next story handoff

**Only for:** case studies and detailed product stories

**Observed:** A light hairline and small gray next-story label introduce another 52px title, a one-sentence description, classification tags and a wide image that leads into the footer.

**Transfer:** Close a deep product story with a related use case or next demonstration rather than an isolated conversion banner.

**Text style:** `heading` — Plain 400 · 52px/1.05 · tracking -0.02em

## Page flow

**Storyline:** Visual proposition → selected proof → editorial framing → deeper demonstrations → practical continuation → monumental signature.

### Image-led marketing and discovery

1. **Visual proposition** — Full-width hero image with sentence-based capability and audience selection.
2. **Curated proof** — Dark thematic collections establish a point of view.
3. **Breadth of capability** — White mixed-scale galleries alternate with editorial chapters, archive strips and statements.
4. **Continuation** — Updates, direct inquiry routes and a short institutional introduction.
5. **Signature** — Oversized white serif wordmark on black, followed by utility links.

**Transfer:** Use the gallery-led rhythm as the default landing-page language; scale its length to the available proof.

### A detailed demonstration or case study

1. **Context** — Plain title, one-sentence remit, small tags and an information action.
2. **Demonstration** — Wide media alternating with paired portrait media and right-half explanatory passages.
3. **Continuation** — A next-story teaser provides another relevant destination.
4. **Contact and signature** — Compact black inquiry and institutional rows, giant wordmark and utility links.

**Transfer:** Tell one product or use-case story in depth; preserve large media and short offset explanation instead of repeating homepage collections.

### Explain the organization and establish human credibility

1. **Positioning** — Split title and prose introduction with a compact recruitment action.
2. **Human proof** — Four-column grayscale portrait wall.
3. **Organizational depth** — Separated groups of portraits and columnar name lists.
4. **Continuation and signature** — News and inquiry modules on black, followed by the monumental wordmark and utilities.

**Transfer:** Use this variant for actual people and organizational detail, keeping the primary landing page more image-led.

## Writing

Cultured, factual and editorial, with confidence expressed through the work rather than breathless persuasion. Longer thematic passages add interpretation and curiosity without becoming product hype.

**Do not copy:** Do not reuse Pentagram's name, logo artwork, client or partner names, project titles, partner counts, historical claims, descriptions or quotations as claims for another brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal descriptions of the output, with occasional first-person plural in institutional and capability statements; little direct second-person selling.
- **Rhythm:** Short named exhibits, one-sentence descriptions and compact functional actions alternate with longer curatorial paragraphs. Headings often read like essay titles rather than promises.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Chapter heading | An evocative editorial title that gives a collection a point of view. | 3–8 words | “The Secret Life of Things”<br>“Past as Prologue” |
| Exhibit description | Name the discipline or output, then specify whom it serves or what it accomplishes. | One sentence, typically 8–25 words | “Industrial design of computer hardware for professional environments.”<br>“Brand identity for a major new cultural event in Kyoto, Japan.” |
| Action | Literal verb or short destination, without an inflated benefit claim. | 2–4 words | “Show more”<br>“About the project”<br>“See all news” |

**Words and phrasing to use:** identity; system; framework; designed for; a new; inspired by; creating; connecting

**Avoid:** game-changing; supercharge; 10x; unlock your potential; revolutionary; act now

**Rules:**

- Make each caption tell the reader what the object is and why it exists.
- Use an editorial idea to connect a curated set; do not turn every section heading into an imperative.
- Reserve longer prose for context and interpretation; keep card descriptions compact.
- Use verifiable specifics instead of unsupported comparative claims.

## Do's and Don'ts

### Do

- Keep primary headings at 52px, weight 400 and -0.02em tracking.
- Let 16px names and descriptions sit beneath imagery with only 8px top separation.
- Maintain 12px horizontal gutters through galleries, trays and split rows.
- Use 24px desktop outer insets and 96px between major collections.
- Place portrait exhibits together inside one black tray with 24px padding.
- Reserve vivid color for the photographic and graphic evidence, leaving interface chrome neutral.
- Finish with useful information and a full-width original white typographic signature on black.

### Don't

- Do not make every headline bold; even the 52px headings are regular.
- Do not round exhibit images into 16px or 24px cards; reserve 8px for the shared tray.
- Do not introduce a brand-colored button system or brightly tinted feature panels.
- Do not force the one-third/two-thirds image pairs into equal-height card shells.
- Do not enlarge project names into secondary display headlines; keep them at 16px.
- Do not add drop shadows to separate galleries; use black mats, background shifts and space.
- Do not turn the closing signature into a small logo tucked among footer columns.

## Motion and responsive

### Motion

**Observed:**

- Secondary buttons declare background-color 0.2s cubic-bezier(0.25, 0.46, 0.45, 0.94).
- The sentence-filter surface declares a border-radius 0.4s transition.
- Horizontal collections expose draggable or arrow-based continuation; hero pagination exposes active and inactive dots.

**Transfer:**

- Keep control transitions local and restrained; let changes in displayed work, rather than decorative entrance effects, carry the movement.

**Unknown:**

- Autoplay intervals, scroll-trigger behavior and the timing of the sentence filter's repositioning are not established.

### Responsive

**Observed:**

- Desktop layouts use a 1728px maximum container and 24px visible side insets at 1440px.
- Styles declare breakpoint families including 600px, 768px, 800px, 1040px and 1600px; the desktop text navigation is breakpoint-controlled.

**Transfer:**

- On narrow screens, preserve the image-first proposition and compact sentence selector; stack split prose and featured gallery pairs before shrinking text into illegibility.
- Reduce portrait-directory columns and allow exhibit strips to continue horizontally; keep the closing wordmark fitted to the available width.

**Unknown:**

- Exact mobile column counts, gutter changes, navigation replacement and type sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
