# Clase — images over interface

## Overview

An image-led, editorial style with the directness of a gallery checklist and the scale of a street poster. A regular neo-grotesk carries unusually big explanatory text, while white and black framing lets photographs, printed matter and moving images supply the color. It suits visually distinctive products and creative services: spare in interface, dense in visual proof.

### Essentials

- The promise is a sentence, not a billboard slogan: regular 45px/50px grotesk, normal tracking, left aligned in a 1200px intro with 20px side padding.
- The first image arrives almost immediately: a 70px navigation and 130px introduction give way to an edge-to-edge 900px media stage; its title and explanation share the same 45px/50px recipe.
- Actions have no button silhouette: 28px/34px case links and 45px/50px continuation links are bare text, with a simple right arrow and no pill, border or shadow.
- The interface stays monochrome while media owns the color: white navigation, gray links and a black closing band frame full-width imagery occupying most of the landing page. Color belongs to photographed objects and artwork, not a repeated accent button.
- Proof is staged at architectural scale: use full-bleed photography or video behind a top-left text overlay inset 20px. When no finished media exists, create a close-up composition of real product artifacts or a bold original typographic specimen rather than a generic interface card.
- A running sentence and a conversational black ending are signature devices: include a 110px-high ticker in 45px type and a contact paragraph in 45px/50px white type with #aaaaaa inline links, followed by a 28px/34px social sentence.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Daylight link gray | `#939393` | `--color-link-muted` | link, action, text | Inactive navigation, continuation actions and inline ticker links; changes to black on hover. |
| Black ink | `#000000` | `--color-ink` | text, background | Primary text on light media and canvas; solid closing band. |
| Night link gray | `#aaaaaa` | `--color-inverse-link` | link, text | Contact and social links within the black closing band; changes to white on hover. |
| Light photographic backing | `#e8e8e8` | `--color-media-base` | background | Backing beneath the opening full-bleed photograph; the image itself supplies the visible material and shading. |
| Archive strip gray | `#f1f1f1` | `--color-ticker` | background | Light gray backing for the archive ticker. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Navigation, editorial canvas and newsletter ticker; inverse text over dark media and closing band. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| exhibition-led visual proof | Exhibition green | `#43d491` | `--color-art-green` | background, accent | Media-specific green backing and the vivid green note within exhibition artwork; not a global action color. |
| editorial proof galleries | Credit gray | `#aeaeae` | `--color-caption` | text | Small image credit beneath an editorial proof image. |

## Typography

- **SuisseIntl** — All navigation, headlines, paragraphs, captions and actions. Even, neutral neo-grotesk with open counters and a regular weight throughout; hierarchy depends on size and placement rather than boldness. If unavailable, use **Inter**. Use weight 400 and normal tracking; preserve line breaks through container width tuning. Font stack: "SuisseIntl", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | SuisseIntl | 400 | 45px | 1.111 | normal | Opening promise, media titles and descriptions, large continuation action and closing contact sentence. |
| ticker | SuisseIntl | 400 | 45px | 2.444 | normal | Single-line running sentences with links embedded in the sentence. |
| support | SuisseIntl | 400 | 28px | 1.214 | normal | Case links, secondary contact sentence and supporting text; also section headings on editorial information pages. |
| navigation | SuisseIntl | 400 | 28px | 2.009 | normal | Primary navigation links, with current destination black and other destinations gray. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| project or product catalogues | catalogue-caption | SuisseIntl | 400 | 24px | 1.167 | 0.0167em | Centered short titles beneath catalogue media. |
| editorial proof galleries | image-credit | SuisseIntl | 400 | 14px | 1.43 | normal | A discreet credit or recognition caption below a proof image. |

**Notes:**

- Use the statement recipe for both a title and its explanatory line, with no size or weight contrast between them. The smaller action below provides the hierarchy.
- Large editorial paragraphs retain the same statement recipe as the opening; they are not reduced to conventional small body text.
- Keep normal tracking in all core text. The slight positive tracking belongs only to catalogue captions.
- Navigation has its own loose line box; do not substitute it for the tighter support recipe in media overlays.

## Layout

**Density:** Spare interface and compact headline stacks, contrasted with immense media fields and airy editorial chapters.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Catalogue image-to-caption gap. |
| 15px | Separation between primary and secondary footer sentences. |
| 20px | Media stage inset, case-link top margin and editorial paragraph spacing. |
| 30px | Space below the opening statement before the first media stage. |
| 50px | Editorial chapter padding and margins; catalogue row separation. |
| 100px | Catalogue top and bottom padding; separation between repeated ticker runs. |

### Containers and grids

- **full-bleed stage**: side padding 20px. Media extends to both viewport edges; text is inset from the edges rather than placed in a separate card.
- **intro measure**: max width 1200px · side padding 20px. Left-anchored opening sentence; its right edge stays short of the viewport edge.
- **catalogue grid** (only for project or product catalogues): max width 1200px · 3 columns · gap 75px. Centered grid of 350px-wide slots with 50px row spacing. Each slot has a 350px-square media area, often containing a narrower portrait image.
- **editorial split** (only for company and long-form information pages): 2 columns · side padding 20px. A narrow label column begins around 155px from the left at desktop; the large reading column begins around 534px and extends to the right inset. Labels use support type and prose uses statement type.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and flat interface | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page frame and editorial content.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat and undecorated, with no panel outlines, rounding or raised layers.

**Transfer:** Let alignment and type establish groups instead of card containers.

#### Media stage · level 0

**Use:** Large visual proof chapters.

**CSS:** `background-color: #e8e8e8; background-size: cover; background-position: 50% 50%; position: relative; padding: 20px`

**Observed:** Photographs fill the entire stage; video also runs edge to edge. Backing colors vary with the media but are not independent decorative sections.

**Transfer:** Use subject-specific images with a readable upper-left area; choose black or white overlay text according to the actual scene.

#### Archive strip · level 0

**Use:** Running sentence near the end of an image-led or catalogue page.

**CSS:** `background: #f1f1f1; overflow: hidden; height: 110px`

**Observed:** A light interruption between visual content and the black ending; text extends past both edges.

**Transfer:** Use an ongoing resource or update invitation as the repeated sentence.

#### Black closing band · level 0

**Use:** Contact ending shared across page types.

**CSS:** `background: #000000; color: #ffffff; padding: 20px`

**Observed:** A compact full-width paragraph block, 189px high with the desktop contact copy, rather than a multi-column sitemap.

**Transfer:** Let the height follow the new contact sentence, keeping the two-level text hierarchy.

## Components

### Navigation link

**Use:** Primary destinations in the 70px-high header.

**CSS:** `color: #939393; text-decoration: none; font-size: 28px; font-weight: 400; line-height: 56.3px`

**Text style:** `navigation` — SuisseIntl 400 · 28px/2.009

**Observed:** Text-only brand and destinations are grouped at the left with 25px between items; a language choice is pushed to the far right. The current destination is black.

**States:** Declared: hover color #000000, text-decoration none, outline 0px; focus-visible unspecified; active outline-width 0px.

**Transfer:** Keep the product name typographic and short; prioritize a small number of destinations.

### Media chapter

**Use:** Full-width proof or demonstration scene.

**CSS:** `position: relative; height: 900px; padding: 20px; background-size: cover; background-position: 50% 50%`

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

**Observed:** A linked text stack contains a title, an immediate explanatory line and a smaller Case link. The header is sticky within its scene and sits above the media.

**Transfer:** Give each stage one concrete product application or outcome, not a collection of feature cards.

### Case link

**Use:** Drill into the story associated with a media chapter.

**CSS:** `color: #000000; font-size: 28px; line-height: 34px; margin-top: 20px`

**Text style:** `support` — SuisseIntl 400 · 28px/1.214

**Observed:** Sits beneath the description and uses a plain right arrow. White is the inverse variant over dark scenes. The entire heading stack is linked, not merely this line.

**Transfer:** Use a short verb-object action appropriate to the proof.

### Continuation link

**Use:** Move from selected visual proof into a larger collection.

**CSS:** `color: #939393; font-size: 45px; line-height: 50px; text-decoration: none`

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

**Observed:** A single left-aligned line inside a 90px-high white strip with 20px padding; no surrounding button shape.

**States:** Declared: hover color #000000, text-decoration none, outline 0px; focus-visible unspecified; active outline-width 0px.

### Sentence ticker

**Use:** Recurring invitation to subscribe or explore a resource.

**CSS:** `height: 110px; overflow: hidden; white-space: nowrap; color: #000000; font-size: 45px; line-height: 110px`

**Text style:** `ticker` — SuisseIntl 400 · 45px/2.444

**Observed:** Repeated runs stretch beyond the viewport with 100px separation. A gray action is embedded inside the black sentence. The newsletter version is white and includes a small outlined envelope; the archive version uses Archive strip.

**States:** Declared: hover on inline action color #000000, text-decoration none, outline 0px; focus-visible unspecified; active outline-width 0px.

**Transfer:** Keep the action grammatically part of the sentence and repeat a complete, readable thought.

### Inline contact link

**Use:** Phone, email and location within the closing paragraph.

**CSS:** `color: #aaaaaa; text-decoration: none; font-size: 45px; line-height: 50px`

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

**Observed:** Links remain inline with white prose and wrap naturally across the full band. Secondary social links repeat the same color behavior using support type.

**States:** Declared: hover color #ffffff, text-decoration none, outline 0px; focus-visible unspecified; active outline-width 0px.

**Transfer:** Offer direct contact methods in ordinary sentences rather than a contact-card grid.

### Category link row

**Only for:** project or product catalogues

**Use:** Browse a collection by discipline or category.

**CSS:** `display: flex; flex-wrap: wrap; padding-left: 20px; padding-right: 20px; background: #ffffff`

**Text style:** `support` — SuisseIntl 400 · 28px/1.214

**Observed:** A second navigation row immediately follows the main header. Items are plain text separated by 25px; selected All is black and other filters are gray.

**Transfer:** Use a concise taxonomy; preserve the visual distinction between current and available categories.

### Catalogue tile

**Only for:** project or product catalogues

**Use:** Repeated image-and-title links.

**CSS:** `position: relative; width: 350px; text-align: center; margin-top: 50px; margin-left: 75px`

**Text style:** `catalogue-caption` — SuisseIntl 400 · 24px/1.167 · tracking 0.0167em

**Observed:** A square media slot centers a portrait image or isolated logo; a title follows 10px below and wraps to a second line when needed. There is no visible card backing or border.

**Transfer:** Normalize the slot, not the artwork: preserve portrait photography, cutout shapes and wordmarks as distinct image types.

## Imagery and graphics

### Full-bleed artifact photography

**Use:** Primary visual proof, including the opening scene.

**Observed:** Close views of white packaging with oversized printed letters, stacked books and printed campaigns fill the screen. Soft directional light reveals paper thickness, folds and shadows; objects run beyond the edges. Other scenes show real interiors with pale architecture and colored sculptural objects. Text is superimposed without a tinted panel.

**Transfer:** Photograph the new product or its tangible outputs at close range, emphasizing surfaces and scale. For a digital product, arrange original interface printouts or a tightly art-directed enlarged interface composition; the minimum is a sharp, full-width specimen with genuine product content.

### Typographic media composition

**Use:** Graphic variation within the large proof stages.

**Observed:** Rotated printed rectangles and oversized typography overlap on dark backing, with saturated red, green and blue carried by the artwork. Another scene presents a huge black letterform with visible vector handles on white. These are media subjects rather than additional site fonts.

**Transfer:** Use the new product's own original labels, specimens or construction drawings to create equally bold visual proof.

**Build:** Create an SVG with several rectangular specimen sheets rotated at opposing angles, some extending beyond the viewBox. Place oversized words, numbers and short labels inside each sheet; use black and white as anchors and the product's artwork colors within the sheets. Clip the composition to a full-width stage. Alternatively enlarge one original vector letterform until it runs beyond the frame and show a few control points and handles as part of the artwork.

### Atmospheric moving scenes

**Use:** Motion-based visual proof among static chapters.

**Observed:** Full-width moving media ranges from dusk-blue architecture and silhouetted people to gray striated coastal rock and typographic construction sequences. The treatment is cinematic or process-led rather than a video inside a rounded player.

**Transfer:** Use footage of the product's environment, materials or making process; choose a strong still with the same framing when footage is unavailable.

### Editorial workplace photograph

**Only for:** company and long-form information pages

**Use:** Large establishing image after the opening sentence.

**Observed:** A wide black-and-white interior shows exposed timber, worktables and task lamps. It occupies almost the full width inside 20px side margins, with natural grain and no color overlay.

**Transfer:** Use a truthful environmental photograph with architectural depth and working details rather than a stock group portrait.

### Contained catalogue artwork

**Only for:** project or product catalogues

**Use:** Media in the Catalogue tile.

**Observed:** Portrait photographs, posters, bottles, books and isolated marks are centered in square white slots. Many portrait images are 250px wide by 350px high; logo art retains generous surrounding white.

**Transfer:** Keep aspect ratio and original backing; do not force every asset into a cover crop.

### Editorial proof still

**Only for:** editorial proof galleries

**Use:** Recognition or detailed outcome beside a narrow section label.

**Observed:** A single upright shrink-wrapped book sits against a charcoal-to-light-gray studio backdrop. The 792px by 634px image is followed by a very small gray credit, separated by 20px.

**Transfer:** Show one credible outcome or artifact with restrained studio lighting and attach a factual credit, not a badge cluster.

### Icons

**Observed:** Very sparse: simple right arrows accompany text actions, and a black outlined envelope appears inline in the newsletter ticker. No decorative feature-icon system.

**Transfer:** Use a plain text arrow and a minimal outline envelope; keep icons subordinate to the surrounding type rather than enclosing them in circles.

## Section recipes

How recurring sections are built.

### First screen: Sentence and image opening

**Observed:** White canvas supports a 70px-high header: text brand and navigation sit left, language sits far right. Immediately below, a two-line statement in statement type occupies a left-anchored 1200px measure, with 30px below it. The first Media chapter begins 200px down the page and fills the remaining 700px of the first 900px viewport, continuing below the fold. Its background is a close, softly lit view of white printed packaging. Above that media, a 20px-inset black title and explanatory line use the same statement recipe; the Case link sits 20px below. The first screen contains the full promise, the chapter label, description, action and most of the first photograph, not the next scene.

**Transfer:** Lead with a complete positioning sentence and put real visual proof directly beneath it. If no photography exists, use an original oversized product specimen with equivalent edge-to-edge scale. Information pages retain the compact sentence then introduce a framed environmental photograph; collection pages replace the sentence with Category link row and a centered catalogue.

**Avoid:** Do not turn this into a centered oversized headline above a pair of filled buttons, or place the first image inside a rounded browser mockup.

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

### Immersive proof chapter

**Observed:** Media chapter occupies a full 900px desktop stage; heading and support line are adjacent at the top left, with Case link beneath. Chapters meet edge to edge with no white gutters, alternating black and white overlay text according to the media.

**Transfer:** Use one visually distinct application per scene; vary photography, process and graphic media without varying the interface treatment.

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

### Resource interruption

**Observed:** Sentence ticker cuts across the full width between media chapters or near the ending. White identifies the newsletter invitation; Archive strip identifies the resource invitation. Both hold regular 45px text within a 110px line box.

**Transfer:** Include a running invitation somewhere in the page; its placement should support the new narrative rather than determine the number of chapters.

**Text style:** `ticker` — SuisseIntl 400 · 45px/2.444

### Conversational contact ending

**Observed:** Black closing band holds a statement-sized white sentence with Inline contact link for direct methods. A support-sized sentence follows after 15px, embedding social and newsletter links. Image-led pages precede it with Continuation link and Archive strip; collections use Archive strip; editorial information pages close directly after the last image and credit.

**Transfer:** End in a direct invitation to contact or act, keeping methods inside readable prose. Adjust sentence length to the new offering instead of adding sitemap columns.

**Text style:** `statement` — SuisseIntl 400 · 45px/1.111

### Offset editorial chapter

**Only for:** company and long-form information pages

**Observed:** Editorial split places a support-sized heading in the narrow left column and large statement prose in the right column. Chapters use 50px top and bottom padding and 50px outer margins. Lists switch to support type, with capabilities or people arranged in two subcolumns; collaborator and client proof remain plain text rather than logos in cards.

**Transfer:** Use the split for explanation, capability groupings and human proof. Preserve the unusual large prose and the smaller label hierarchy.

**Text style:** `support` — SuisseIntl 400 · 28px/1.214

### Collection field

**Only for:** project or product catalogues

**Observed:** Category link row leads into the catalogue grid with 100px top padding. Three Catalogue tiles per row combine centered media and captions; 50px row spacing and 75px horizontal spacing produce an airy index. A final 100px of padding separates the grid from the ticker.

**Transfer:** Let the collection itself supply the proof, using short titles and a useful taxonomy rather than introductory promotional cards.

**Text style:** `catalogue-caption` — SuisseIntl 400 · 24px/1.167 · tracking 0.0167em

## Page flow

**Storyline:** Positioning or browsing context → substantial visual or verbal proof → invitation to continue the relationship → direct conversational contact.

### Image-led marketing landing page

1. **Positioning** — Compact sentence beneath a text-only navigation.
2. **Visual proof** — Edge-to-edge media chapters with equal-sized title and description, then smaller case links.
3. **Relationship invitation** — Running newsletter sentence interrupts the image sequence.
4. **Further exploration** — Large gray continuation link and light-gray resource ticker.
5. **Closing action** — Black contact paragraph with inline methods and a smaller social sentence.

**Transfer:** Use the image-led version as the default for a new marketing page; select enough substantial proof to support the promise without reproducing a fixed chapter count.

### Long-form organization or product-background page

1. **Positioning** — Short large sentence and broad monochrome workplace image.
2. **Explanation** — Small left label paired with large right-column prose.
3. **Capabilities** — Plain text groupings in right-side subcolumns.
4. **Human and social proof** — Large contextual paragraph, names with roles, collaborator prose and a long textual client list.
5. **Recognition** — Single proof photograph with a small credit.
6. **Closing action** — Shared black conversational contact ending.

**Transfer:** Borrow the offset information hierarchy for deeper explanation, substituting relevant capabilities, people and credible outcomes.

### Browsable catalogue of products or outcomes

1. **Orientation** — Primary navigation followed immediately by a plain-text category row.
2. **Breadth of proof** — Long three-column image field with short centered titles.
3. **Continued engagement** — Gray running resource invitation.
4. **Closing action** — Shared black contact ending.

**Transfer:** Use for a broad collection where visual recognition matters more than long descriptions.

## Writing

Matter-of-fact, culturally literate and conversational. Confidence comes from naming the work and explaining its purpose, not from promotional superlatives.

**Do not copy:** Do not reuse the brand name, project names, client list, contact details, award claims, history, anniversary numbers, proprietary artwork or source-specific positioning claims. Examples illustrate syntax and tone only.

- **Addressing the reader:** Use we for the organization, factual third-person descriptions for outcomes, and a gentle you in invitations.
- **Rhythm:** Opening positioning is a complete sentence of roughly 15–20 words. Scene descriptions are usually one concise sentence or phrase; action labels are short. Longer editorial paragraphs remain measured and explanatory.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Identify the organization or offering, its practice and the kind of value it produces. | 15–20 words | “We are a design and creative direction studio building resilient brands on cultural insight.” |
| Proof description | One concrete intervention and its context; let the title identify the subject. | 5–15 words | “Expanding the Mediterranean imaginary”<br>“A constructivist visual language for a Croatian furniture brand” |
| Action | Plain verb and object; arrow supplies direction. | 2–4 words | “See the case”<br>“See more projects” |
| Relationship invitation | Low-pressure invitation in an ordinary sentence, with the action embedded. | 10–20 words | “to our Newsletter if you want to get our updates from time to time.” |
| Section label | Brief descriptive noun, not a slogan. | 1–3 words | “Capabilities”<br>“Selected clients” |

**Words and phrasing to use:** building; shaping; a new approach; commitment; context; conversation; from time to time

**Avoid:** revolutionary; game-changing; unlock your potential; best-in-class; limited-time offer; excessive exclamation marks

**Rules:**

- Use specific objects, contexts and changes to demonstrate value.
- Let descriptions explain what changed rather than repeat a title.
- Write contact instructions as flowing prose.
- Keep invitations hospitable and unhurried rather than urgent.

## Do's and Don'ts

### Do

- Keep statement text at 45px/50px and weight 400 on desktop.
- Align intro and media text to the same 20px side inset.
- Keep title and explanation the same size within media chapters.
- Make the imagery span the viewport, with the first stage beginning after a compact 200px opening frame.
- Use gray text links as the action language and reserve black or white for hover and selected states.
- Include a 110px running-sentence strip as a graphic interruption.
- Close with white conversational prose on black, using #aaaaaa inline contact links.
- For catalogue pages, center preserved-aspect media in 350px-square slots.

### Don't

- Do not use bold display headings to create hierarchy; weight 400 is the consistent voice.
- Do not add rounded card containers or elevated shadows to the flat editorial canvas.
- Do not introduce a permanent saturated UI accent; media carries the chromatic variety.
- Do not reduce editorial explanation to a conventional 16px body column; it uses the statement scale.
- Do not give every project artwork font a matching marketing typeface; the site frame uses one grotesk.
- Do not expand the footer into a multicolumn sitemap; preserve its two-sentence construction.
- Do not turn the category row into filled chips or segmented controls.
- Do not use the navigation's 56.3px line box for the tighter 28px media actions.

## Motion and responsive

### Motion

**Observed:**

- Repeated ticker content runs horizontally beyond the viewport, with marquee animation declarations present.
- Media headings use sticky positioning within their stages.
- Navigation declares a 0.5s transition; text actions declare gray-to-black or gray-to-white hover changes.

**Transfer:**

- Retain the running-sentence device and the feeling of a caption staying with its scene; let moving imagery provide visual change rather than interface effects.

**Unknown:**

- Ticker speed and direction, exact sticky offsets and complete video behavior are not established.
- No focus-visible design is established; provide a visible accessible focus treatment rather than removing it.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 600px, 740px, 767px, 781px, 782px, 992px, 993px and 1440px.

**Transfer:**

- For narrow layouts, preserve the immediate sentence-to-image relationship and edge-to-edge media; let the scene's caption wrap without covering its focal subject.
- Stack editorial label and prose, and reduce catalogue columns before sacrificing the preserved aspect ratios. These are adaptation rules, not a separate visual theme.

**Unknown:**

- Mobile type sizes, navigation transformation and exact grid changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
