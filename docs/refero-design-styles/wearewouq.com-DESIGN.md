# WOUQ — sculptural digital editorial

## Overview

An understated white editorial frame gives cinematic digital objects room to feel tactile and expensive. Light grotesk typography, black text and faint gray rules surround richly lit CGI, product still lifes and occasional natural photography. The density alternates between short conversational introductions and immersive image galleries, making the style especially suited to design-led products and creative technology.

### Essentials

- Headlines behave like enlarged conversation rather than slogans: light grotesk at 45px, 50px line height and normal tracking, left aligned across almost the full content width.
- The opening is a statement above an immersive material study: a 75px white navigation bar, 30px side margins, 45px introductory top padding and 60px below the statement; the main image starts at 280px on desktop.
- Actions are typography, not capsules: 18px underlined links with separate arrow glyphs; prominent invitations use the same 45px recipe as headings, without a filled button surface.
- The frame stays monochrome while media carries the color: white canvas, black text and 1px #efefef rules; sage #ccd5ae is reserved for link hover and selection, not decorative bands.
- A tactile hero-scale image is a signature device: reflective curved metal, translucent warm surfaces or a dramatically lit product fill a 1380px-wide frame with 10px corners. Without bespoke CGI, use a carefully lit macro photograph of a relevant material or product.
- Media labels invert the usual hierarchy: a 27px descriptor sits above a 45px subject name, both white, inset 30px at the lower left of an edge-to-edge image.
- The ending feels like a studio's calling card: a thin rule, 90px of preceding air, and four sparse columns pairing a location/local-time note with arrow-led social and legal links at 18px/27px.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sage interaction | `#ccd5ae` | `--color-hover` | link, accent | Link hover color and text-selection background; selection text is white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border | All primary editorial text, arrows and active navigation underlines. |
| Pale rule | `#efefef` | `--color-rule` | border | Single-pixel section and footer dividers. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Page and fixed header background; inverse lettering on image cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| film-led project narratives | Video black | `#000000` | `--color-video-base` | surface | Backing behind moving media, never a replacement for the poster or film. |
| extended project narratives | Silver text | `#dbdbdb` | `--color-secondary` | text | Large secondary benefit lines and tiny media captions. |

## Typography

- **ESAllianz** — All visible editorial typography and navigation, using the Light cut. A light, open grotesk with uncomplicated forms; hierarchy comes from scale rather than weight contrast. If unavailable, use **Inter**. Use weight 300 and normal tracking; preserve the broad line lengths. Font stack: "ESAllianz", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ESAllianz | 300 | 45px | 1.111 | normal | Opening statements, section headings and prominent text actions. |
| media-title | ESAllianz | 300 | 45px | 1 | normal | White subject name on image cards. |
| media-descriptor | ESAllianz | 300 | 27px | 1 | normal | White descriptor immediately above the image-card subject name. |
| body | ESAllianz | 300 | 18px | 1.5 | normal | Paragraphs, contact links and footer information. |
| navigation | ESAllianz | 300 | 18px | 1 | normal | Short header destinations; current destination receives a fine underline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| extended project narratives | media-caption | ESAllianz | 300 | 12px | 1.5 | normal | Small pale labels underneath individual films or studies. |

**Notes:**

- Use the Light cut throughout; do not add bold emphasis to manufacture hierarchy. The declared Light family has a CSS weight of 400 but its visual weight is light.
- Opening prose and chapter headings share the same 45px recipe. Body text is 18px; image descriptors are the intermediate 27px size.
- Keep tracking normal even on the largest text. Preserve sentence case and natural multi-line wraps.
- Underlining identifies actions, not headings. Arrows sit outside the underlined phrase.

## Layout

**Density:** Airy around editorial blocks and tightly packed within media sequences; narrow image seams make the artwork feel continuous.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Media-grid seams and space beneath individual gallery items. |
| 20px | Footer divider-to-content spacing. |
| 25px | Header vertical padding, horizontal navigation-link padding and heading-to-paragraph separation. |
| 30px | Page side inset and image-overlay inset. |
| 35px | Footer bottom padding and selected chapter heading top padding. |
| 45px | Opening statement top padding after the header. |
| 60px | Opening statement-to-hero-image padding. |
| 90px | Air before the footer rule and top/bottom padding around the gallery's closing invitation. |

### Containers and grids

- **editorial container**: max width 1460px · side padding 30px. Centered page frame; at 1440px the visible content is 1380px wide. Header, prose, gallery and footer share its edges.
- **alternating media grid**: 2 columns · gap 10px. Alternate full-width anchor images with paired half-width images; cards remain image-only except for overlaid labels.
- **calling card grid**: 4 columns · gap 10px. One location/time column, two social-link columns and one legal-link column. Keep only two lines of content per column where possible.
- **study grid** (only for extended project narratives): 3 columns · gap 10px. Two- and three-up rows punctuate full-width films and stills.
- **editorial pair** (only for company and contact narratives): 2 columns · gap 10px. Two equally weighted text columns, with internal text measures allowed to be narrower than the column.
- **masonry wall** (only for experimental galleries): 4 columns · gap 10px. Four independent image columns with varied native image heights; portrait tiles can be 338px by 600px at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| media frames | 10px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** The uninterrupted base of every page.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** White extends through the header, narrative spaces and footer. No drop-shadow card system separates the content.

**Transfer:** Let differences in image scale and whitespace provide the section changes.

#### Clipped media · level 1

**Use:** Still-image and moving-image frames.

**CSS:** `position: relative; border-radius: 10px; overflow: hidden; box-shadow: none`

**Observed:** The artwork itself provides the surface color and depth; it meets the frame edges without internal padding or a decorative border.

**Transfer:** Preserve image-led surfaces rather than putting artwork inside padded UI cards.

#### Film backing · level 1

**Only for:** film-led project narratives

**Use:** The backing beneath video content.

**CSS:** `background: #000000; border-radius: 10px; overflow: hidden`

**Observed:** Large films and smaller companion videos share the same rounded frame.

**Transfer:** Always supply a strong poster so the backing is not the visual content.

## Components

### Fixed masthead

**Use:** Persistent brand and three-destination navigation.

**CSS:** `position: fixed; top: 0px; height: 75px; padding: 25px 0px; box-sizing: border-box; background: #ffffff; z-index: 120`

**Observed:** Compact black wordmark on the left, text destinations on the far right; both align to the editorial container. It remains visible while media scrolls beneath it.

**Transfer:** Use a compact original wordmark, not an oversized logo or a navigation pill.

### Navigation link

**Use:** Top-level destinations.

**CSS:** `color: #000000; background: transparent; padding: 0px 25px; text-decoration: none`

**Text style:** `navigation` — ESAllianz 300 · 18px/1

**Observed:** The final destination omits right padding. The current destination has a 1px black underline beneath the text; other destinations have no visible underline.

**States:** Declared: hover color #ccd5ae; focus-visible styling is unknown.

### Inline arrow link

**Use:** Contact, social and legal destinations.

**CSS:** `color: #000000; background: transparent; text-decoration: underline; transition: color 0.2s linear`

**Text style:** `body` — ESAllianz 300 · 18px/1.5

**Observed:** A simple right arrow precedes the link as separate text; the arrow is not underlined. Links can stack at the body line height.

**States:** Declared: hover color #ccd5ae; focus-visible styling is unknown.

### Prominent arrow action

**Use:** Large invitation or return navigation.

**CSS:** `color: #000000; background: transparent; text-decoration: underline; transition: color 0.2s linear`

**Text style:** `display` — ESAllianz 300 · 45px/1.111

**Observed:** A full-size arrow sits to the left of the underlined phrase. Return navigation points left; contact and onward exploration point right. There is no button enclosure.

**States:** Declared: hover color #ccd5ae; focus-visible styling is unknown.

**Transfer:** Use one clear onward action after an image sequence or integrate it directly into a conversational introduction.

### Media tile

**Use:** Clickable visual proof on landing and collection pages.

**CSS:** `position: relative; border-radius: 10px; overflow: hidden; transition: box-shadow 0.3s`

**Observed:** The whole frame links onward. Full-width anchors alternate with paired landscape tiles; the image or video fills the frame and carries the color.

**Transfer:** Use benefits, outcomes or product chapters as the card subjects, with very little text.

### Media label

**Use:** Lower-left identification on visual cards.

**CSS:** `position: absolute; padding: 30px; color: #ffffff; z-index: 10`

**Text style:** `media-descriptor` — ESAllianz 300 · 27px/1

**Observed:** Descriptor first, then the larger media-title beneath with 5px top padding. Labels remain inside the artwork, not in an external caption bar.

**Transfer:** Place the text over a naturally legible region of the artwork rather than adding a large gradient scrim.

### Hairline divider

**Use:** Separate chapters, credit rows and the footer without enclosing panels.

**CSS:** `height: 1px; background: #efefef`

**Observed:** A full-content-width line under a heading or above footer information; smaller credit groups repeat the line at their own width.

**Transfer:** Use sparingly to organize editorial information, never as a dense table grid.

### Calling card footer

**Use:** The shared page ending.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: flex-end; color: #000000`

**Text style:** `body` — ESAllianz 300 · 18px/1.5

**Observed:** Four aligned columns follow the Hairline divider: location and live local time at left, two pairs of social links in the middle, legal links at right. Each link uses Inline arrow link. The surrounding section leaves 35px at the bottom.

**Transfer:** Include a useful local or availability detail to retain the personable studio signature.

### Study caption

**Only for:** extended project narratives

**Use:** Identify individual film variants beneath a media frame.

**CSS:** `color: #dbdbdb`

**Text style:** `media-caption` — ESAllianz 300 · 12px/1.5

**Observed:** Short, low-emphasis labels follow the image rather than floating over it; roman numerals distinguish related variations.

**Transfer:** Reserve this very pale treatment for secondary identifiers, not instructions or essential product information.

## Imagery and graphics

### Sculptural material study

**Use:** A signature hero-scale visual and recurring full-width gallery anchors.

**Observed:** Curving metallic ribbons and folded translucent sheets are photographed as if real, with sharp reflective edges, fine surface texture, copper and peach illumination, graphite shadows and gray studio backings. Close framing lets forms extend beyond the image edges. Images occupy much more area than text.

**Transfer:** Create a relevant material metaphor for the product, or use a macro product photograph with reflective edges, warm transmitted light and deep shadow. A single convincing physical object is better than a complicated low-quality render.

**Build:** For a minimum graphic equivalent, use an SVG inside a clipped 10px frame: draw two broad overlapping S-curves that extend past opposite edges, fill one with a multi-stop gray metallic gradient and the other with warm peach rgba(235,169,128,0.65) fading to rgba(255,255,255,0.2). Add thin white edge strokes and a darker offset duplicate behind each curve. Place a broad, soft white ellipse behind them and use a subtle repeated dot texture at low opacity on the translucent curve. Keep highlights local to the object rather than washing the whole page.

### Cinematic product tableau

**Use:** Supporting visual proof in full-width and paired tiles.

**Observed:** Products are staged like advertising stills: a close laptop corner with glossy pastel spheres, warm sunlight across shelving, cards standing in a mauve landscape, and a bicycle head-on in near-black blue light. Backdrops belong to each image and are cropped flush to the tile.

**Transfer:** Choose a coherent lighting story per image. Keep the actual product large and tangible; pair a contextual view with a close material or detail view.

### Geometric process studies

**Only for:** extended project narratives

**Use:** Films, industry chapters and research galleries.

**Observed:** Modular cubes, grids, spheres, flowing metallic ribbons and particle-like structures create metaphors for invisible digital processes. Pale gray stages, charcoal environments and localized warm or pink light unify the images; a later research sequence includes cream, gold and chrome experiments.

**Transfer:** Translate an abstract capability into one repeatable physical system, then show wide, close and structural views instead of unrelated decorative art.

**Build:** Create an SVG isometric grid of equal parallelograms and a few extruded cubes using three face tones. Keep most faces gray, illuminate a small connected path using warm translucent fills, and add a blurred duplicate of only that path beneath the sharp geometry. Vary viewpoint and detail between gallery images, not the underlying material language.

### Experimental still-life wall

**Only for:** experimental galleries

**Use:** Dense, uncaptioned four-column masonry collections.

**Observed:** Portrait and landscape compositions mix chrome folds, fabric, ropes, machined fittings, travel objects, sport equipment, perfume and architectural details. Muted stone, cream, olive and silver tones are interrupted by water blue and warm light. Independent column heights make the wall feel collected rather than tiled.

**Transfer:** Curate studies of the new product's materials, context and adjacent objects. Keep a restrained photographic grade and preserve native aspect ratios.

### Natural team portrait

**Only for:** company and contact narratives

**Use:** A single wide humanizing image between text sections.

**Observed:** Two people smiling outdoors, framed from the waist upward on a tree-lined street. Soft daylight, natural green and dark clothing contrast with the polished CGI elsewhere; the portrait uses the same rounded, edge-to-edge frame.

**Transfer:** Use an authentic environmental portrait with unforced expressions and a softly receding background, not isolated avatar circles.

### Icons

**Observed:** The editorial interface is nearly icon-free. Plain text arrows are sized with their adjacent 18px or 45px text and point right, left or down according to destination.

**Transfer:** Use typographic arrows rather than boxed icon buttons; keep any media-player controls inside the media itself.

## Section recipes

How recurring sections are built.

### First screen: Statement and material opening

**Observed:** The white Fixed masthead is the top layer over a white Editorial canvas. Below its 75px height, the left-aligned display statement begins after 45px of top padding and wraps to two lines across most of the 1380px content width. It is black, light and sentence case. After 60px of bottom padding, the Clipped media hero starts at 280px and fills the width within 30px side margins. The warm metallic sculpture is close-framed and extends below the first 900px. The first screen contains the wordmark, three navigation links, the complete statement and the upper 620px of the artwork; the lower-left Media label sits below the fold. There is no separate supporting paragraph or conversion button in this default opening.

**Transfer:** Lead with a complete positioning sentence and an equally immersive material or product image. If bespoke artwork is unavailable, light and tightly frame a relevant real object. Collection variants add a short display-size invitation and down arrow; company/contact variants turn the statement into a linked invitation; project narratives open with subject and descriptor on separate display lines.

**Avoid:** Do not replace this composition with a centered slogan, two-column software hero, badge row or button cluster. Do not shrink the artwork to a floating thumbnail.

**Text style:** `display` — ESAllianz 300 · 45px/1.111

### Visual proof gallery

**Observed:** Media tile and Media label form a tightly joined sequence: full-width visual anchors alternate with two-up landscape rows, using 10px seams and the shared 10px radius. Image titles stay lower left; media carries nearly all the visual complexity.

**Transfer:** Mix a hero outcome with secondary product views or related applications. Adjust gallery length to the story instead of adding filler.

### Editorial chapter

**Observed:** A display heading sits above a Hairline divider, followed by body paragraphs with about 25px separation from the heading. The text spans the main frame in long-form narratives; wide media follows below.

**Transfer:** Use for explanation between image sequences. Keep headings short and prose specific to the underlying problem, process or capability.

**Text style:** `display` — ESAllianz 300 · 45px/1.111

### Calling card ending

**Observed:** The final image is followed by white breathing space, 90px before Hairline divider and 20px from rule to the four-column Calling card footer. The footer stays small and informational rather than becoming another visual campaign.

**Transfer:** Make the final contact information easy to scan and give the closing artwork room to resonate.

### Benefit heading pair

**Only for:** extended project narratives

**Observed:** A black display category sits immediately above a #dbdbdb display benefit line, both 45px/50px. A large film follows closely, then a row of smaller companion studies.

**Transfer:** Pair a short capability name with one plain-language outcome. Keep essential details in black body copy rather than relying on the pale benefit line.

**Text style:** `display` — ESAllianz 300 · 45px/1.111

### Two-column human narrative

**Only for:** company and contact narratives

**Observed:** An invitation-led opening gives way to equal-width editorial columns: descriptive prose at left, enquiries and practical contact details at right. Each column starts with a display heading and thin divider. A wide Natural team portrait follows; a full-width partnership paragraph and small contact link close the narrative before Calling card footer.

**Transfer:** Use this arrangement for people, process or service information, with actual contact channels rather than a form-heavy panel.

### Masonry and onward invitation

**Only for:** experimental galleries

**Observed:** Two substantial display paragraphs introduce the wall. Four independent columns of uncaptioned images follow, with 10px seams. After the wall, 90px of padding leads to a two-line display closing: a plain invitation above an arrow-led underlined onward action. Another 90px of padding separates it from the footer region.

**Transfer:** Let this be a browsing-led page type for experiments or a broad visual collection; retain an explicit route back to the primary offering.

### Credits and return

**Only for:** extended project narratives

**Observed:** After the last three-up media row, a display heading introduces three credit columns. Each role/name pair is body-sized with a pale divider. A large left-arrow return action follows in open white space, then Calling card footer.

**Transfer:** Use a compact contributor, specification or responsibility summary when a long story needs attribution; keep it unboxed.

## Page flow

**Storyline:** Positioning or invitation → immersive visual proof → editorial explanation where needed → supporting visual detail → onward route or contact → compact calling-card ending.

### Image-led marketing landing page

1. **Positioning** — A full-width conversational statement introduces the offering.
2. **Visual proof** — A large tactile hero leads into full-width and paired media cards with lower-left labels.
3. **Closing information** — The final cinematic image gives way directly to a ruled four-column footer with local time.

**Transfer:** Use the image gallery as the central argument; introduce only enough copy to orient the viewer.

### Detailed project or product narrative

1. **Identity** — Two display lines name the subject and discipline above a wide image.
2. **Context** — Short paragraphs describe the collaboration and purpose.
3. **Demonstration** — A film chapter alternates wide motion media with smaller supporting studies.
4. **Capabilities** — Category and pale benefit heading pairs lead into illustrated chapters.
5. **Process proof** — Solution demonstrations and a research chapter expose the underlying visual system.
6. **Attribution and onward route** — Three-column credits precede a large left-arrow return link and shared footer.

**Transfer:** Organize a deeper product story into named visual chapters; let demonstrated detail carry the proof.

### Company and contact information

1. **Invitation** — A conversational contact request ends in a large email action.
2. **Explanation** — Two editorial columns combine identity, experience and enquiry information.
3. **Human proof** — One wide environmental portrait interrupts the prose.
4. **Credibility and contact** — A partnership paragraph and email invitation lead into the shared footer.

**Transfer:** Prioritize an approachable contact route and authentic people over decorative metrics.

### Exploratory collection

1. **Framing** — Two display-size paragraphs explain the spirit of the collection.
2. **Discovery** — A dense four-column masonry wall presents uncaptioned material and object studies.
3. **Onward route** — A two-line display invitation links to the primary collection above the shared footer.

**Transfer:** Use native-ratio images and minimal interruption to create a mood-board browsing experience.

### Primary work or application index

1. **Positioning** — A display introduction gains a second display line directing the reader downward.
2. **Visual proof** — Full-width anchors and paired landscape tiles present the collection.
3. **Closing information** — The final image transitions to the same sparse ruled footer.

**Transfer:** Keep this as the landing gallery's close relative, with a clearer browse cue rather than filters or dashboard chrome.

## Writing

Confident, personable and visually minded. The speaker sounds like a small team inviting a conversation, while longer explanations describe collaboration and process in straightforward prose.

**Do not copy:** Do not reuse the WOUQ name or wordmark, client names, artwork, contact addresses, partnership claims, project credits, experience figures or source-specific product claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the maker, you for an invitation, and the product name when describing a specific capability. Contact language is direct rather than transactional.
- **Rhythm:** Opening copy is a complete flowing sentence, usually long enough for two display lines. Chapter names are short nouns; body paragraphs are explanatory and moderately long. Actions are compact noun phrases or direct invitations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Who we are + what we make + intended reach or audience. | About 20–25 words | “We are a german based creative director duo, crafting captivating digital experiences and visual solutions for a global audience.” |
| Chapter heading | Plain name for a discipline, stage or capability; no promotional superlative. | 1–3 words | “Brand Film”<br>“Research & Development” |
| Benefit line | Verb-led outcome expressed in everyday language. | 5–8 words | “Create a frictionless customer journey” |
| Browse cue | Invite the visitor to view a selection and give a direction. | 7–10 words | “Find a selection of our work below ↓” |
| Prominent action | Name the next collection or the return destination. | 3–4 words | “Back to all”<br>“All client work” |

**Words and phrasing to use:** crafting; visual language; working closely; explore; collaboration; feel free; selection

**Avoid:** growth hacks; 10x everything; buy now!!!; enterprise-grade synergy; limited-time urgency

**Rules:**

- Let imagery carry the emotional pitch; use prose to identify the offering and explain intent.
- Make chapter titles descriptive rather than clever.
- Use real contact destinations as actions when the desired next step is a conversation.
- Keep action labels understandable without their arrow.

## Do's and Don'ts

### Do

- Keep display statements at 45px with normal tracking and the light cut.
- Align header, prose, gallery and footer to the same 30px side inset.
- Give hero and gallery media the same 10px corner radius.
- Use 10px seams inside image grids, not broad card gutters.
- Preserve the 27px descriptor above the 45px subject in media overlays.
- Use 1px #efefef rules for editorial separation.
- Keep the shared footer at 18px/27px and include a useful time or availability detail.
- Stage a tactile object or material at hero scale, even when the offering itself is intangible.

### Don't

- Do not use bold 700 headings; this hierarchy is built almost entirely from light type.
- Do not turn sage #ccd5ae into large background fills or default button fills.
- Do not move image titles into padded white card bodies.
- Do not add shadows to every media frame; depth belongs to the imagery.
- Do not give cards pill-shaped corners; the repeated media radius is 10px.
- Do not use the pale #dbdbdb caption color for essential body copy.
- Do not turn the sparse four-column footer into a dark multi-level sitemap.
- Do not force the experimental wall into identical-height tiles.

## Motion and responsive

### Motion

**Observed:**

- Text links declare color transitions of 0.2s linear to sage on hover.
- Media frames declare box-shadow transitions of 0.3s; no visible hover shadow value is established.
- The white header remains fixed during scrolling; embedded moving media supplies much of the visual activity.

**Transfer:**

- Keep navigation and text-action feedback restrained and color-led.
- Use moving material studies within the same clipped frames as stills rather than adding animated page chrome.

**Unknown:**

- Focus-visible and active-state treatments are not established.
- Playback choreography, scroll animation timing and media hover behavior are not established.

### Responsive

**Observed:**

- The desktop composition uses a 1460px maximum container, 30px side padding and full-, half-, third- and quarter-width media arrangements.
- Styles declare breakpoints including 480px, 600px, 768px, 992px, 1024px and 1170px.

**Transfer:**

- On narrow screens, preserve the statement-above-media relationship and shared edge alignment; reduce column count before compromising the artwork.
- Keep native image proportions in exploratory masonry and keep overlaid labels inside their image frames.
- Allow the footer columns and conversational headline to wrap naturally; retain the distinction between 18px information and display-size invitations.

**Unknown:**

- Exact mobile font sizes, gutters, column changes and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
