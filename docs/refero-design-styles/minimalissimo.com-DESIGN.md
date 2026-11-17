# Minimalissimo — objects before rhetoric

## Overview

A light, image-led editorial style that feels like a carefully arranged collection rather than a sales presentation. Regular grotesk text, white space and pale gray staging give photography the authority; color belongs to the objects and environments, not the interface. It suits design-conscious products, portfolios and curated collections, with dense visual browsing balanced by an unusually spare closing area.

### Essentials

- The collection is the headline: a 56px white navigation strip leads directly into four image columns, with no oversized slogan or opening conversion panel.
- Titles behave like museum labels rather than advertising: GeistSans at 16px, weight 400, 1.4 line height and normal tracking sits 12px below the image; navigation stays at the same size with 1.5 line height.
- Small objects and large environments share one modular field: 336×224px object images alternate with 688×506px feature images across a four-column desktop grid with 16px gutters and 24px row gaps. Preserve this alternating scale even when the imagery is product demonstrations rather than physical objects.
- The interface abstains from chromatic color: white canvas, pale gray media backing and a #f7f7f7 closing band account for all structural surfaces. Natural color appears only within imagery, as isolated material or scene accents rather than full-page brand fills.
- Actions are small rectangular interruptions, not rounded badges: controls are 42px tall with 4px corners; the solitary black continuation button has 24px horizontal padding, while the closing form uses pale gray controls.
- A dissolving continuation edge and a half-empty closing band are signature devices: a 180px transparent-to-white veil carries a centered black action, and the closing area reserves its left half for a small text identity while forms and links occupy the right. Use a glimpse of further work or product detail beneath the veil when there is no collection to extend.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Primary labels, identity and the filled continuation action; also the hover destination for gray links and the subscription control. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navigation gray | `#888888` | `--color-navigation` | text, link | Resting navigation and search labels. |
| Secondary text | `#999999` | `--color-secondary` | text, link | Footer links and consent text. |
| Control edge | `#e5e5e5` | `--color-edge` | border | Faint 1px outlines around closing-form controls. |
| Object ground | `#e9e9e9` | `--color-media` | surface | Neutral backing behind object photography, not an empty content panel. |
| Control gray | `#efefef` | `--color-control` | surface, action | Name and email fields and the resting subscription button. |
| Closing gray | `#f7f7f7` | `--color-closing` | background | Full-width subscription and footer band. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Page and fixed navigation background; reversed button text and the continuation veil. |

## Typography

- **GeistSans** — All editorial labels, identity, navigation, forms and supporting copy. Neutral contemporary grotesk, regular throughout, with no display-family contrast. Font stack: "GeistSans", "GeistSans Fallback", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| editorial-label | GeistSans | 400 | 16px | 1.4 | normal | Image titles, paragraph-length invitations and any restrained heading needed for new content. |
| interface | GeistSans | 400 | 16px | 1.5 | normal | Text identity, navigation, buttons and footer links. |
| consent | GeistSans | 400 | 12px | 1.4 | normal | The short subscription reassurance below the closing form. |

**Notes:**

- Hierarchy comes from image area, placement and neutral text color, not a descending ladder of headline sizes.
- There is no separate display headline or prominent section-heading treatment. When a new page needs a heading, keep it in the editorial-label recipe and let the accompanying image establish its importance.
- Use sentence case, regular weight and normal tracking throughout; desktop card labels truncate rather than becoming multi-line headlines.

## Layout

**Density:** Visually dense in the collection, spacious in the closing band; narrow, consistent image gutters coexist with a deliberately unoccupied half-width footer.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Closing-form column gaps and vertical gaps between footer links. |
| 12px | Image-to-caption margin. |
| 16px | Collection column gutters, header grid gaps and narrow-screen side padding. |
| 20px | Navigation link spacing. |
| 24px | Desktop side padding and collection row gaps. |
| 32px | Invitation paragraph to subscription form. |
| 48px | Footer link-region vertical padding and final bottom padding. |
| 64px | Desktop subscription-region top and bottom padding. |
| 80px | Additional separation before the closing band. |

### Containers and grids

- **wide-container**: max width 2000px · side padding 24px. Shared centered frame for collection, header and footer; at 1440px the usable width is 1392px.
- **collection-grid**: 4 columns · gap 16px. Equal-width desktop columns with 24px vertical gaps; feature images span two columns and two rows, shifting between left, center and right rather than forming a separate hero section.
- **alignment-grid**: 12 columns · gap 16px. Header and footer alignment: identity spans the left six columns, while navigation or closing content spans the right six.
- **subscription-row**: 3 columns · gap 8px. Equal name, email and action columns within the 688px right-hand footer area.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 4px |
| image-frames | 0px |

## Surfaces and depth

### Surfaces

#### White field · level 0

**Use:** Main page and fixed header.

**CSS:** `background-color: #ffffff; box-shadow: none`

**Observed:** An uninterrupted white field connects all collection modules; there are no card shells or horizontal separator rules.

**Transfer:** Use spacing and image scale to group content instead of adding panels.

#### Object stage · level 0

**Use:** Backing for individually photographed or rendered objects.

**CSS:** `background-color: #e9e9e9; border-radius: 0px; overflow: hidden`

**Observed:** The gray is visible around centered objects, with soft grounded shadows belonging to the image itself.

**Transfer:** Prepare imagery on a matching gray ground; keep the surrounding caption on white.

#### Closing field · level 0

**Use:** The combined invitation, subscription and footer area.

**CSS:** `background-color: #f7f7f7; box-shadow: none`

**Observed:** A single continuous pale band, not separate form and footer cards.

**Transfer:** Keep utility links and the closing invitation in one architectural field.

#### Continuation veil · level 1

**Use:** A finite preview of further visual content above the continuation action.

**CSS:** `height: 180px; background-image: linear-gradient(to bottom, rgba(255,255,255,0) 0px, rgba(255,255,255,0.8) 50%, #ffffff 100%); pointer-events: none`

**Observed:** The next imagery remains perceptible near the upper edge, then dissolves completely into white; the action is a separate foreground layer.

**Transfer:** Use an actual continuation preview under this surface, with an interactive control above it.

## Components

### Fixed navigation

**Use:** Persistent orientation without displacing the visual collection.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 56px; z-index: 40; background-color: #ffffff`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** The small black text identity anchors the left edge. Navigation begins at the page midpoint and search sits at the far right; all align to the shared container.

**Transfer:** Use a text identity rather than a large logo lockup and offset main content by the bar height.

### Navigation link

**Use:** Category and search actions.

**CSS:** `color: #888888; font-size: 16px; line-height: 24px; font-weight: 400`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** Unadorned text, with no background, outline, icon or active pill; the category group uses 20px gaps.

**States:** Declared: hover color #000; focus-visible unknown.

**Transfer:** Keep category labels short and reserve the far-right slot for search.

### Object card

**Use:** Repeated compact visual entries.

**CSS:** `display: block; color: #000000; border-radius: 0px; text-decoration: none`

**Text style:** `editorial-label` — GeistSans 400 · 16px/1.4

**Observed:** A 3:2 image frame is followed by a caption with 12px top margin. At desktop the image is 336×224px and the complete entry is 258px tall. There is no enclosing border, padded panel or inline button.

**States:** Declared: hover opacity 0.8; focus-visible unknown.

**Transfer:** Make the whole entry the link; show one concrete object, detail or product capability per image.

### Feature card

**Use:** Larger editorial punctuation within the same collection grid.

**CSS:** `display: flex; flex-direction: column; color: #000000; border-radius: 0px; text-decoration: none`

**Text style:** `editorial-label` — GeistSans 400 · 16px/1.4

**Observed:** The image spans two columns and two rows; a 688×506px frame fills the available height. The caption places the title at left and an optional short category at right on the same baseline.

**States:** Declared: hover opacity 0.8; focus-visible unknown.

**Transfer:** Use an environmental, portrait or use-context image with more narrative depth than neighboring object studies.

### Continuation button

**Use:** The compact filled action over the dissolving collection edge.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 42px; padding: 0px 24px; background-color: #000000; color: #ffffff; border-radius: 4px`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** Centered over the veil near its lower edge, with no leading icon or trailing arrow. The label determines width; the two-word action occupies 126px.

**States:** Declared: hover background-color #262626; focus-visible unknown.

**Transfer:** Use the filled treatment for the one action that continues exploration.

### Subscription input

**Use:** Name and email entry in the closing invitation.

**CSS:** `width: 100%; height: 42px; padding: 0px 16px; background-color: #efefef; border: 1px solid #e5e5e5; border-radius: 4px`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** Two text fields share the row with an equally sized action; muted placeholder text carries the visible field prompt.

**Transfer:** Keep accessible field names while preserving the compact single-row appearance.

### Subscription button

**Use:** Closing-form submission.

**CSS:** `width: 100%; height: 42px; padding: 0px 16px; background-color: #efefef; color: #000000; border: 1px solid #e5e5e5; border-radius: 4px`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** At rest this matches the input surfaces instead of competing with the black exploration action; text is centered.

**States:** Declared: hover border-color #000; background-color #000; color #fff; focus-visible unknown.

### Footer link

**Use:** Utility, contact, social and legal destinations.

**CSS:** `display: block; color: #999999; margin-bottom: 8px`

**Text style:** `interface` — GeistSans 400 · 16px/1.5

**Observed:** Two compact stacks sit in the right half of the closing field. Legal links share a horizontal line below; no column headings or icon badges are added.

**States:** Declared: hover color #000; focus-visible unknown.

**Transfer:** Group destinations by function without introducing extra labels or visual containers.

## Imagery and graphics

### Isolated object studies

**Use:** The dominant repeated visual unit.

**Observed:** Furniture, tools and small products appear as singular, carefully lit objects on near-uniform light gray. Metal, translucent glass, matte black and pale wood remain materially legible. Objects are centered with breathing room; scale varies to suit their silhouette, and subtle cast shadows sit close beneath them. Occasional blue or coral objects interrupt the otherwise neutral collection.

**Transfer:** Photograph or render the new product with broad soft light on pale gray, keeping its material texture and original color. For software, use a tightly edited single feature view on the same neutral ground, not a dense dashboard wall. The minimum acceptable equivalent is one clean product image per tile, composed at consistent scale.

### Immersive context images

**Use:** Two-column feature cards distributed through the collection.

**Observed:** Warm wood staircases, plaster interiors, concrete courtyards, a street scene and restrained portraits fill the rectangular frame edge to edge. Light is natural and directional, with generous spatial depth. The wider cards provide warm or atmospheric contrast to the small gray object stages without adding colored interface surfaces.

**Transfer:** Show the product in a real environment, or use a well-composed full-frame workflow scene. Preserve believable light and material detail rather than applying an overall desaturation filter. A simple environment photograph with one clear focal point is preferable to a synthetic collage.

## Section recipes

How recurring sections are built.

### First screen: Collection-first opening

**Observed:** Back to front: white field, fixed 56px navigation, then a collection grid starting immediately below it with 24px side padding. Four equally sized 3:2 images form the first row; their captions, not a separate slogan, supply the opening text at 16px regular. The next row begins after a 24px gap: a two-column environmental image fills the left half while four small entries occupy the right half in two rows. Within the first 900px, the navigation, first row and nearly all of this second composition including captions are visible. More collection entries continue below. Images occupy most of the screen; there is no introductory paragraph or hero button, and each image card is the exploration action.

**Transfer:** Open a new product page with a curated suite of product views, details and one contextual scene. Treat the short labels as the headline system rather than adding an advertising banner above the collection. A focused detail page can begin with fewer, larger images but retain the small navigation and caption-scale text.

**Avoid:** Do not insert a giant centered promise, a split-screen sales hero or a large blank spacer between navigation and the first images.

**Text style:** `editorial-label` — GeistSans 400 · 16px/1.4

### Alternating visual chapters

**Observed:** Object card modules are punctuated by Feature card modules spanning two columns and two rows. Large cards move between left, center and right positions. Captions remain below images on the White field, with category labels on the right of larger entries; there are no large section headings.

**Transfer:** Organize product capabilities or proof as a sequence of image scales, using short names and concise attribution in place of heading-and-paragraph blocks.

**Text style:** `editorial-label` — GeistSans 400 · 16px/1.4

### Dissolving continuation

**Observed:** A further row is partially revealed under Continuation veil. Continuation button is centered in front of it; the 180px veil ends in the White field, followed by open white separation before the closing band.

**Transfer:** Preserve the fading visual horizon as a signature transition. For a finite landing page, let it reveal a related detail or next-step preview and give its action an honest destination.

### Half-empty closing invitation

**Observed:** Closing field spans the full width. Its top region has 64px vertical padding, a small text identity in the left half, and a three-line invitation in the right half. After 32px comes the three-column form with 8px gaps, then consent text after 16px. Utility and social links sit further down in two right-hand columns with 8px inter-link gaps; legal links finish the right half above 48px bottom padding. The left side remains almost entirely open.

**Transfer:** Close with a modest invitation to an ongoing relationship rather than a second hero. Keep the unequal distribution of occupied space even when the action changes from newsletter signup to an inquiry form.

**Text style:** `editorial-label` — GeistSans 400 · 16px/1.4

## Page flow

**Storyline:** Visual invitation → repeated object-level proof punctuated by context → glimpse of further exploration → relationship invitation and utility closure.

### Image-led discovery and an ongoing relationship with a curated offering

1. **Visual promise** — A compact fixed identity bar introduces an immediate row of captioned images rather than a written proposition.
2. **Product proof** — Repeated small studies build breadth while alternating large scenes establish context and depth.
3. **Continued exploration** — The collection dissolves into white beneath one small black continuation action.
4. **Closing invitation** — A pale full-width band pairs a small identity with a right-half paragraph, equal-width form controls and reassurance.
5. **Utility closure** — Two muted link stacks and a final legal row complete the same band, with the left half left open.

**Transfer:** For a different offering, make the images establish the proposition, use contextual scenes as chapter breaks, and keep the relationship action less visually assertive than the work itself. Adjust the number and order of collection modules to the content.

## Writing

Matter-of-fact and credit-conscious in labels; considered and gently inviting in longer copy. Quality is implied by selection and description rather than announced with superlatives.

**Do not copy:** Do not reuse the Minimalissimo identity, product names, designer credits, editorial text or community and privacy claims as another brand's assets or promises. Examples illustrate syntax only.

- **Addressing the reader:** Labels are impersonal. Invitation copy uses our and your to establish a direct but unpushy relationship.
- **Rhythm:** Most text consists of short noun phrases, sometimes followed by a by-credit. The closing invitation expands into a few complete sentences, then returns to single-word utility actions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Image title | Object or project name, optionally followed by a maker credit. | 2–9 words | “Shinari incense holder by Bored Eye Design”<br>“Casa Castelar by Solar” |
| Closing invitation | Invite the reader into a shared sensibility, explain the content, finish with a restrained imperative. | Three compact sentences | “Join a global community attuned to clarity and restraint. Our letters are focused on carefully selected work, ideas, and perspectives that reveal the beauty of less. Feed your inbox with intention.” |
| Action | Plain verb or familiar utility term, with no promotional qualifier. | 1–2 words | “Load more”<br>“Subscribe”<br>“Submit” |

**Words and phrasing to use:** selected; work; ideas; perspectives; clarity; restraint; intention; by

**Avoid:** revolutionary; game-changing; unlock; ultimate; hurry; exclusive deal

**Rules:**

- Let specific names and material descriptions do more work than adjectives.
- Use attribution when relevant; keep descriptions brief enough to function as image labels.
- Keep the invitation thoughtful but concrete about what the reader will receive.
- Use sentence case and restrained punctuation; avoid exclamation marks and urgency copy.

## Do's and Don'ts

### Do

- Align the header, collection and footer to the same 24px desktop side padding.
- Preserve the 16px horizontal and 24px vertical collection gutters.
- Use regular 16px grotesk labels even beside the largest feature images.
- Give image captions a consistent 12px separation from their frames.
- Keep the small-object 3:2 framing and let larger scenes span two columns.
- Use the 180px white veil as an intentional transition to the exploration action.
- Match the closing form's three controls at 42px tall with 4px corners.
- Reserve the footer's left half primarily for the small identity.

### Don't

- Do not bold every caption to manufacture hierarchy; the text system stays at weight 400.
- Do not add shadows, outlines or rounded card shells around photography.
- Do not make the subscription control black at rest; its default is #efefef.
- Do not turn neutral navigation links into filled tabs or category chips.
- Do not distribute footer content evenly across four full-width columns.
- Do not apply a monochrome filter to all imagery; natural material color supplies the visual accents.
- Do not place category names in floating tags over photographs.
- Do not enlarge the text identity into a decorative wordmark backdrop.

## Motion and responsive

### Motion

**Observed:**

- Image-card links declare opacity transitions of 0.3s cubic-bezier(.4,0,.2,1), with hover opacity 0.8.
- Text links and controls declare color-related transitions of 0.15s cubic-bezier(.4,0,.2,1).
- Navigation and footer links become black on hover; the subscription control reverses to white on black.

**Transfer:**

- Limit the principal browsing feedback to the declared opacity fade and brief neutral-color changes; keep the photographic layout stable during hover.

**Unknown:**

- No running entrance or scroll animation is established. Focus-visible treatment and active states are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Collection classes specify two columns by default, three from 768px and four from 1024px. Side padding changes from 16px to 24px at 768px.
- The category navigation is hidden below 1024px. The subscription form is one column by default and three columns from 640px.
- Feature cards span two columns; image frames use 3:2 by default and a 7:5 base aspect from 768px, then stretch to their grid allocation. Labels allow up to two lines on smaller screens and truncate from 768px.

**Transfer:**

- Retain the alternation between small studies and larger context images as columns reduce; do not shrink a four-column desktop composition into unreadable tiles.
- Let closing content occupy the available width below the desktop split and stack the controls at the declared narrow-screen breakpoint.

**Unknown:**

- The narrow-screen rendered layout, navigation replacement and exact feature-card placement have not been visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
