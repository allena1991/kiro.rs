# Platform — gallery meets release poster

## Overview

A spare, image-led gallery identity with the energy of a release poster. White space, black grotesk type and tiny factual captions let richly colored objects and candid studio photography dominate. Compact floating navigation and oversized centered announcements suit curated products, cultural launches and collections; editorial stories can switch to red type or an electric green canvas without changing the underlying typography.

### Essentials

- A photograph is the opening proposition: a full-width 1440×810px scene carries centered white 72px/1 headlines and a lower 20px/1.2 description with an arrow text action. Use a real environment or an honestly lit product scene when portrait photography is unavailable.
- Navigation floats like a narrow gallery label: a centered 540×36px square-edged strip, 15px/18px links, 9px 8px link padding and a diffuse shadow, rather than a full-width masthead.
- Announcements become posters, not benefit cards: centered 48px/1.2 medium-weight capitals stack names or statements and dates on separate lines. Include a text-only poster moment even when the subject has no release calendar.
- Objects are given gallery space while facts stay small: contained imagery, no enclosing card chrome, and centered 12px/14.4px captions with 0.02em tracking; names are uppercase while titles and material details are mixed case.
- Actions remain typographic or sharply rectangular: arrow-led 20px text links for exploration, and a white 106×34px sign-up button with a 1px black border and 7px 20px padding for the form.
- The default shell is overwhelmingly white and black; color belongs primarily to photography. Red #fd251d typography on white and an uninterrupted #6ff433 green field with black type are whole-story editorial variants, not a mixture of accent cards.
- The ending is a compact publication colophon: a 1px black rule introduces an inline newsletter, followed by a 1px #dddddd rule and two low horizontal link groups, all inside 36px side gutters.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-canvas` | background, surface, text, action | Default page ground, navigation and form button; reversed text over photographs and black calls. |
| Input gray | `#f5f5f5` | `--color-field` | surface | Newsletter email field and the pale carousel progress track. |
| Footer rule | `#dddddd` | `--color-rule` | border | Fine separator above the final link row. |
| Print black | `#000000` | `--color-ink` | text, border, background, link | Default typography, strong rules and the dark closing call. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog navigation | Inactive gray | `#999999` | `--color-muted` | text, link | Inactive collection navigation labels. |
| red-ink editorial stories | Editorial red | `#fd251d` | `--color-editorial-red` | text, link | Headlines, questions, answers and captions share one red on a white ground. |
| electric-green editorial stories | Electric green | `#6ff433` | `--color-campaign-green` | background | Continuous background for a complete interview, including its image and merchandise chapters; returns to white at the footer. |

## Typography

- **MediumLLWeb** — All main marketing text, captions, navigation and editorial reading. Plain, medium-weight grotesk with open, familiar shapes; dramatic scale rather than bold weight establishes hierarchy. If unavailable, use **Inter**. Use weight 500 and normal tracking for display; retain the small positive tracking on labels. Font stack: "MediumLLWeb", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | MediumLLWeb | 500 | 72px | 1 | normal | Centered uppercase photographic hero headline and editorial subject title. |
| poster | MediumLLWeb | 500 | 48px | 1.2 | normal | Centered stacked announcements and the closing archive-style call. |
| body | MediumLLWeb | 500 | 20px | 1.2 | normal | Descriptions, editorial questions and answers, section headings and arrow-led exploration links. |
| utility | MediumLLWeb | 500 | 15px | 1.2 | normal | Navigation, footer links, form label and dense alphabetical lists. |
| eyebrow | MediumLLWeb | 500 | 15px | 1.2 | 0.02em, uppercase | Small mastheads, wordmark-like text and section index labels. |
| button | MediumLLWeb | 500 | 15px | 1.2 | 0.02em | Outlined sign-up button. |
| newsletter-copy | MediumLLWeb | 500 | 15px | 1.2 | 0.01em | Short subscription proposition beside the email field. |
| caption | MediumLLWeb | 500 | 12px | 1.2 | 0.02em | Object title, year, material, dimensions and price. |
| caption-name | MediumLLWeb | 500 | 12px | 1.2 | 0.02em, uppercase | Creator or collection name at the top of a product caption. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| directory pages | directory-featured | MediumLLWeb | 500 | 40px | 1.2 | 0.01em | Large centered names in the featured directory list. |
| editorial stories | caption-title-italic | MediumLLWeb | 500 italic | 12px | 1.2 | 0.02em | Title embedded within a factual editorial image caption. |

**Notes:**

- Keep the same medium grotesk across the hierarchy; do not turn the display into a heavy advertising face.
- Large type uses normal tracking. Only labels and captions open out to 0.02em; directory names and newsletter copy use 0.01em.
- Uppercase provides the poster voice, while descriptions and most object details retain sentence case. Long-form prose stays sans serif at 20px/24px.

## Layout

**Density:** Airy around imagery and poster statements, compact within navigation and factual captions.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Caption padding and gap under editorial images; a deliberate small-spacing exception. |
| 18px | Form grid gaps, footer link spacing and small container insets. |
| 36px | Default side gutters, editorial column gap and footer top padding. |
| 54px | Wide editorial figure side insets and inset media top space. |
| 72px | Separation between editorial blocks and product-rail top padding. |
| 108px | Directory group row gaps and major directory breathing room. |

### Containers and grids

- **page gutters**: max width 1440px · side padding 36px. White content shell with 1368px usable width at desktop; full-bleed hero escapes the gutters.
- **floating navigation**: max width 540px. Centered compact navigation, detached from both page edges.
- **editorial hero** (only for editorial stories): max width 710px. Centered portrait stage; 710×605px image area above the large subject title.
- **editorial columns** (only for editorial stories): max width 1188px · 2 columns · gap 36px · side padding 36px. Alternating offset images and image-plus-biography rows. Keep empty space intentional rather than filling every column.
- **catalog grid** (only for catalog pages): 3 columns · gap 0px. Three equal 456px item tracks inside the 1368px content width; each object has breathing room within its track.
- **directory index** (only for directory pages): max width 576px · 2 columns · gap 36px · side padding 18px. Two narrow alphabetical columns with 252px text blocks and 108px row gaps.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation and cards | 0px |
| form button | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating navigation | `rgba(0, 0, 0, 0.2) 0px 2px 80px 1px` | Diffuse lift beneath the compact fixed navigation; not a card shadow system. |

### Surfaces

#### Gallery canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** An uninterrupted ground around free-standing images and type.

**Transfer:** Let media carry the color; separate sections with space and occasional rules instead of panels.

#### Navigation glass · level 2

**Use:** Floating navigation surface.

**CSS:** `background: #ffffff; backdrop-filter: blur(24px); border-radius: 0px; box-shadow: rgba(0, 0, 0, 0.2) 0px 2px 80px 1px`

**Observed:** Opaque white is the default. Catalog and directory navigation uses white at 0.4 alpha; editorial navigation uses white at 0.25 alpha, each with the same blur.

**Transfer:** Keep translucency limited to the floating utility strip, with content remaining readable underneath.

#### Hero legibility fade · level 1

**Use:** Bottom of photographic hero.

**CSS:** `background-image: linear-gradient(rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.79) 100%); opacity: 0.75; height: 203px`

**Observed:** A localized fade behind the lower description and action rather than a dark wash over the entire photograph.

**Transfer:** Preserve the photograph's upper light and use the fade only where white reading text needs contrast.

#### Black call band · level 1

**Use:** High-contrast closing exploration call.

**CSS:** `background: #000000; color: #ffffff; padding: 10px; border-radius: 0px`

**Observed:** Broad horizontal text field, 1152px wide and 174px high within a larger white section, carrying centered poster type.

**Transfer:** Use a direct invitation to the deeper collection or resource library.

#### Green editorial field · level 0

**Only for:** electric-green editorial stories

**Use:** A complete campaign reading environment.

**CSS:** `background: #6ff433; color: #000000`

**Observed:** The same green flows behind the portrait, interview, object rail, captions and closing portrait; footer switches to white.

**Transfer:** Choose this as a coherent story theme, never as disconnected feature-card fills.

#### Red editorial paper · level 0

**Only for:** red-ink editorial stories

**Use:** Long-form interview with vivid typographic identity.

**CSS:** `background: #ffffff; color: #fd251d`

**Observed:** All story text including small captions shares the red; the global footer remains black on white.

**Transfer:** Apply the color to a whole editorial voice, retaining natural image color.

## Components

### Floating navigation

**Use:** Persistent global wayfinding.

**CSS:** `display: flex; width: 540px; height: 36px; background: #ffffff; backdrop-filter: blur(24px); border-radius: 0px`

**Text style:** `utility` — MediumLLWeb 500 · 15px/1.2

**Observed:** Brand text on the left, three category links in the middle, then region and compact account, favorite, bag and search controls. Link padding is 9px 8px. The bar sits centered near the top with a diffuse shadow.

**Transfer:** Use a short brand label and only the essential categories; preserve the narrow toolbar silhouette.

### Arrow text action

**Use:** Exploration from hero and section introductions.

**CSS:** `display: flex; color: #ffffff`

**Text style:** `body` — MediumLLWeb 500 · 20px/1.2

**Observed:** A tiny right arrow precedes the label with about 6px between them. No button container. White over media; black on the white canvas.

**Transfer:** Use a short verb plus destination; keep conversion forms visually distinct.

### Outline sign-up button

**Use:** Newsletter submission.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 0px; padding: 7px 20px; height: 34px`

**Text style:** `button` — MediumLLWeb 500 · 15px/1.2 · tracking 0.02em

**Observed:** An uppercase label in a compact rectangle aligned beside, rather than inside, the email field.

**States:** Declared: hover background-color #000000 and color #ffffff; focus-visible unknown.

**Transfer:** Use the same rectangular construction for a short form action.

### Object caption

**Use:** Factual text beneath gallery products.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding-top: 10px; padding-bottom: 10px`

**Text style:** `caption` — MediumLLWeb 500 · 12px/1.2 · tracking 0.02em

**Observed:** Uppercase creator line in caption-name, then title and year, materials and price on separate tight lines. A small outline favorite sits well below the details. Editorial captions are left-aligned and can italicize the title.

**Transfer:** For a different product, show maker or category, model, construction and price without turning the caption into sales copy.

### Contained object image

**Use:** Product rail and collection items.

**CSS:** `max-width: 500px; height: 350px; object-fit: contain`

**Observed:** The complete object silhouette is visible. White or pale photographed backing supports irregular shapes and framed pieces; each item is followed by Object caption, without a surrounding box.

**Transfer:** Use cleanly lit cutouts or straight-on product photographs and preserve their aspect ratios.

### Newsletter row

**Use:** Shared final subscription invitation.

**CSS:** `border-top: 1px solid #000000; padding-top: 36px; padding-bottom: 18px`

**Text style:** `newsletter-copy` — MediumLLWeb 500 · 15px/1.2 · tracking 0.01em

**Observed:** A short two-line proposition occupies the left 396px track; the right region begins with a 380px email field and the Outline sign-up button separated by 18px. The entire row spans the page gutters.

**Transfer:** Keep one specific reason to subscribe, one input and one action.

### Email field

**Use:** Inline newsletter entry.

**CSS:** `background: #f5f5f5; display: flex; position: relative; justify-content: center; height: 36px; width: 380px`

**Text style:** `utility` — MediumLLWeb 500 · 15px/1.2

**Observed:** A plain pale rectangle with its label at the left, using 10px label padding; no rounded shell or heavy outline.

**Transfer:** Retain the subdued fill so the adjacent outlined action remains distinct.

### Footer link row

**Use:** Final site navigation and practical information.

**CSS:** `border-top: 1px solid #dddddd; padding-top: 36px; padding-bottom: 18px`

**Text style:** `utility` — MediumLLWeb 500 · 15px/1.2

**Observed:** Two horizontal link groups sit at opposite ends: brand and organizational links on the left; account, service, legal and a small social icon on the right. Links are separated with 18px right padding rather than individual columns.

**Transfer:** End with a compact colophon instead of a tall multi-column sitemap.

### Featured directory name

**Only for:** directory pages

**Use:** Current or featured entries above the full index.

**CSS:** `color: #000000; text-align: center; height: 48px`

**Text style:** `directory-featured` — MediumLLWeb 500 · 40px/1.2 · tracking 0.01em

**Observed:** One name per line in a centered 504px-wide column inside a 540px container; a small uppercase section label sits above.

**Transfer:** Use for a curated shortlist, then change to utility-sized alphabetical entries for the complete directory.

## Imagery and graphics

### Environmental hero photography

**Use:** The dominant first-screen image.

**Observed:** People and work inhabit a real studio or gallery: pale walls, uneven natural textures, paintings and objects, with a person prominent in the frame. The landscape scene occupies the whole opening rather than being enclosed beside a text column. Color is natural and subdued enough for white overlaid type.

**Transfer:** Photograph a founder, maker or user within a meaningful environment. Minimum acceptable equivalent: one well-lit real product in a contextual room, with room for a centered title and lower caption.

### Isolated gallery objects

**Use:** Repeated product rails and collections.

**Observed:** Straight-on artwork, framed pieces, garments and sculptural objects retain their full outlines. Pale neutral photographic backgrounds and modest real shadows give physical scale. Images dominate the card area while information is very small underneath.

**Transfer:** Create honest high-resolution object photographs on white or pale neutral backing, with consistent visual height rather than forced image cropping.

### Editorial portrait and material detail

**Only for:** editorial stories

**Use:** Story opening, interleaved visual chapters and biographical ending.

**Observed:** A centered portrait begins the story. Large images then alternate left, center and right; narrow works preserve their tall shape, while details expand almost edge to edge at 1332px. Studio portraits and candid working photographs retain ambient light, lived-in surroundings and visible material grain.

**Transfer:** Alternate the whole product or person with meaningful details of material or process. Close a story with a working-environment image or portrait; do not replace the image rhythm with a uniform card grid.

### Icons

**Observed:** Small black utility glyphs and outlines, generally 12–15px, with mostly 1px strokes. Search, bag and favorite controls live in the floating strip; tiny arrows lead exploration labels and outlined stars sit beneath product details.

**Transfer:** Use simple monochrome SVGs with no colored icon discs. Keep the icons subordinate to the 15px navigation and 12px object facts.

## Section recipes

How recurring sections are built.

### First screen: Photographic poster opening

**Observed:** A full-bleed landscape image forms an 810px-high opening. Back to front: environmental photography, Hero legibility fade only at the bottom, centered white display headline in the middle, lower centered body description, Arrow text action, and a thin 540×3px carousel progress line. Floating navigation sits above the scene, centered about 34px from the top. The 72px/72px uppercase headline wraps in a roughly 606px-wide block; supporting copy occupies about 684px and finishes above the action near the bottom. Within the first 900px, the complete scene, title, description, action and the beginning of the next white section are visible; product imagery begins below this opening strip.

**Transfer:** Use a new environmental photograph or a carefully staged real product scene with equally strong physical presence. Keep the short title centered and the practical description lower. Editorial stories instead open with a centered 710×605px portrait, then a 72px subject title and small masthead; catalog pages begin directly with products after utility space, and directories with a small label and large name list.

**Avoid:** Do not substitute a left-copy/right-dashboard SaaS hero, a colored pill CTA, or a giant logo in place of the photographic scene.

**Text style:** `display` — MediumLLWeb 500 · 72px/1

### Horizontal section introduction

**Observed:** Inside 36px gutters, a 20px uppercase label anchors the left, a short body statement occupies a middle 540px block, and a black Arrow text action is pushed to the right. The product rail follows; the introductory content begins 51px below the section edge.

**Transfer:** Use for a new collection, capability group or release selection. Keep heading and support at the same modest size so the media remains dominant.

**Text style:** `body` — MediumLLWeb 500 · 20px/1.2

### Object rail and collection grid

**Observed:** Contained object image and Object caption repeat without enclosing panels. Landing rails show several items with the next one cut by the viewport edge; catalogs switch to three equal columns and many rows. Small favorite controls follow the details, and thin neutral rules terminate the rail.

**Transfer:** Use a lateral rail for a curated taste of the offering and a regular three-column layout for exhaustive browsing. Maintain image-first hierarchy.

### Text-only release poster

**Observed:** Centered black poster type occupies an expansive white section. Uppercase names or short labels alternate with numeric date lines, all at 48px/57.6px rather than a small table or timeline. The long block is visually narrow despite the broad surrounding container.

**Transfer:** Include this signature typographic pause using release names, a concise program, a sequence of product principles or milestones. Separate lines deliberately and keep the list short enough to read as a composition.

**Text style:** `poster` — MediumLLWeb 500 · 48px/1.2

### Broad exploration call

**Observed:** Black call band centers a white 48px invitation inside a broad white closing section. The band has square edges, a 1152px desktop width and 174px height; it is a graphic statement rather than a small button.

**Transfer:** Point to a deeper library, previous work or complete collection. Preserve the broad typographic invitation without depending on background artwork.

**Text style:** `poster` — MediumLLWeb 500 · 48px/1.2

### Subscription and colophon ending

**Observed:** Newsletter row and Footer link row form a shared 190px-high ending inside 36px gutters. The upper rule is black and the lower rule is pale gray. Typography drops to utility size, with no oversized footer wordmark.

**Transfer:** Keep this practical two-row close across all page types, even when the preceding story uses a colored field.

**Text style:** `utility` — MediumLLWeb 500 · 15px/1.2

### Editorial dialogue and offset figures

**Only for:** editorial stories

**Observed:** Questions and answers use body type with speaker labels in a left lane. Questions begin near the left margin while answers use a more inset reading column; image chapters vary between roughly 638–702px single figures, paired figures with 36px gaps and 1332px-wide details. Blocks are commonly separated by 72px. Caption sits about 10px below each image, with a 1px black bottom edge on linked figures.

**Transfer:** Use interview, walkthrough or first-person commentary as long-form proof. Alternate offsets and image scale rather than repeating a rigid two-column feature row.

**Text style:** `body` — MediumLLWeb 500 · 20px/1.2

### Editorial biographical ending

**Only for:** editorial stories

**Observed:** A small 20px uppercase about heading introduces contextual prose. One story ends with several portrait-and-bio pairs; another uses a prose biography followed by a centered 638px-wide studio portrait. The story theme persists until the shared white footer.

**Transfer:** End an interview or product story with the person, process or organization behind it rather than adding a generic sales panel.

**Text style:** `body` — MediumLLWeb 500 · 20px/1.2

### Curated list to alphabetical index

**Only for:** directory pages

**Observed:** A small centered uppercase label sits above 40px/48px featured names. A second small label introduces a dense two-column alphabetical list at 15px/18px within a 576px container; letter groups are separated by 108px vertically. The final alphabetical groups lead into the shared subscription and colophon.

**Transfer:** Separate a curated shortlist from the exhaustive directory through scale, not through colored cards.

**Text style:** `directory-featured` — MediumLLWeb 500 · 40px/1.2 · tracking 0.01em

## Page flow

**Storyline:** Immersive subject → curated selection → typographic or conversational context → deeper exploration → compact subscription and colophon.

### Image-led marketing landing page

1. **Promise** — Full-width environmental photograph with centered title, brief context and exploration link.
2. **Product demonstration** — Small horizontal introduction and a rail of large objects with tiny facts.
3. **Continuity** — Text-only centered announcement poster conveys an ongoing program.
4. **Range** — Another object rail broadens the offering.
5. **Closing call** — Broad high-contrast invitation to a deeper collection.
6. **Retention** — Inline newsletter and compact footer links.

**Transfer:** Use the hero to establish taste, the rail to make the offering tangible and the poster to communicate an ongoing point of view.

### Exhaustive product collection

1. **Wayfinding** — Floating navigation gains a second grouping and filter row.
2. **Product demonstration** — A long three-column collection uses object photographs, tiny centered details and favorite actions.
3. **Retention** — The final product row gives way directly to the shared newsletter and footer.

**Transfer:** Let the collection itself be the content; avoid adding a marketing hero above every browse page.

### Curator-led long-form editorial

1. **Subject introduction** — Centered portrait, large subject name, small masthead and introduction in red on white.
2. **Personal proof** — Speaker-labeled questions and answers alternate with offset objects and expansive detail photographs.
3. **Context** — About heading and portrait-plus-biography rows identify the contributors.
4. **Retention** — Black-on-white newsletter and colophon reset the global shell.

**Transfer:** Use an informed human voice and material imagery as proof rather than converting the piece into a benefits list.

### Campaign-themed maker interview

1. **Subject introduction** — Portrait and black subject title on a continuous electric-green field.
2. **Product demonstration** — A featured object rail connects the interview to the available work.
3. **Personal proof** — Questions and answers alternate with differently aligned works and candid process photographs.
4. **Context** — A biography and final studio portrait complete the story.
5. **Retention** — White subscription and footer rows end the colored environment.

**Transfer:** Give the story one coherent color identity and keep product facts and editorial prose in the same typographic system.

### Directory and archival navigation

1. **Curation** — A centered shortlist uses large individual names beneath a small current label.
2. **Exhaustive access** — A small all label leads into paired alphabetical columns with dense names and spaced letter groups.
3. **Retention** — The last entries are followed by the shared newsletter and link row.

**Transfer:** Use typographic contrast to distinguish featured choices from a complete index, without thumbnails or card decoration.

## Writing

Informed, curatorial and direct. Product prose supplies tangible facts; editorial prose gives named people room for personal, specific and sometimes colloquial observations.

**Do not copy:** Do not reuse Platform's brand assets, artist names, artworks, campaign names, dates, prices, claims or interview quotations as the new product's content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Marketing descriptions usually speak about the subject in third person; actions address the reader implicitly through verbs. Interviews use direct you questions and first-person answers.
- **Rhythm:** Short uppercase labels and names contrast with full explanatory sentences. Captions break facts into terse lines; interviews can sustain multi-paragraph answers without promotional subheads.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Series or release label, colon, subject name; uppercase and compact. | 4–7 words | “AURA DROP FIVE: LAURA BENSON” |
| Section support | One sentence defines what is offered and its cadence. | About 10 words | “New works by today's most interesting artists, launched weekly.” |
| Exploration action | Plain verb plus destination or now. | 2 words | “Explore now”<br>“Browse artworks” |
| Editorial question | A direct question about motivation, practice or personal experience. | One short sentence | “How do you approach collecting personally?” |
| Subscription proposition | A specific access benefit rather than a generic invitation to join a community. | One sentence | “Subscribe to our newsletter for first access to new artworks & exclusive artist collaborations.” |

**Words and phrasing to use:** Explore; Browse; Current; Featured; About; first access; new releases; material and process names

**Avoid:** revolutionary; game-changing; unlock your potential; all-in-one solution; vague superlatives

**Rules:**

- Use colons to make labels feel like editorial headings.
- Let physical details, named processes and precise context carry credibility.
- Keep action labels short and literal.
- Preserve the difference between a neutral product caption and a person's conversational voice.

## Do's and Don'ts

### Do

- Set the main photographic title at 72px/72px and weight 500.
- Keep the floating navigation 540px wide and 36px high on desktop.
- Use a 48px/1.2 centered text poster as a distinct visual pause.
- Keep object facts at 12px/14.4px with 0.02em tracking.
- Preserve the 36px page gutter and 18px form gap.
- Use the 1px black and #dddddd footer rules for different levels of separation.
- Choose one coherent editorial theme for an entire story rather than many local accents.

### Don't

- Do not make every heading bold; the hierarchy relies on 72px, 48px, 20px and 15px scale changes at medium weight.
- Do not wrap object photos in rounded, shaded feature cards.
- Do not turn the 34px rectangular sign-up control into a 48px pill.
- Do not spread the compact floating navigation into a full-width header band.
- Do not apply the navigation's diffuse shadow to every product tile.
- Do not replace factual 12px captions with large promotional card headlines.
- Do not carry a green editorial ground into the shared white footer.
- Do not expand the final 190px colophon into a giant multi-column brand billboard.

## Motion and responsive

### Motion

**Observed:**

- The fixed navigation wrapper declares transform 0.3s ease-in-out and background-color 0.3s ease-in-out.
- The navigation surface declares a 0.6s ease-in-out transition.
- The hero has multiple slides and a thin progress track; editorial titles declare sticky positioning.

**Transfer:**

- Keep motion associated with the floating toolbar and image-led hero rather than animating every text block.

**Unknown:**

- Carousel dwell time, autoplay behavior and exact user-triggered navigation movement are unknown.
- No reliable focus-visible treatment was established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 576px, 600px, 640px, 768px, 994px, 1260px and 1440px.
- The navigation wrapper has max-width 100%; the hero caption also has max-width 100%.

**Transfer:**

- On narrower screens preserve the detached toolbar silhouette and image-first opening; let the title wrap rather than placing it beside the image.
- Adapt the inline subscription and editorial pairs into stacked groups while retaining the distinction between 20px reading text and 12px object facts.

**Unknown:**

- Mobile type sizes, gutter changes, catalog column counts and navigation substitutions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
