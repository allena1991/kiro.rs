# Moffitt.Moffitt. — culture on a stage

## Overview

An image-led creative-office style with the scale of a cultural campaign and the restraint of an editorial index. White, black and cool greys hold a compact grotesk hierarchy, with tiny serif labels providing an unexpected human detail. Cinematic portraits, tactile print objects, architectural photography and richly coloured identity films carry the emotional weight; the surrounding interface is sparse and matter-of-fact. It suits design-conscious products and services whose quality can be demonstrated visually.

### Essentials

- The opening is a campaign, not a text pitch: a full-bleed 900px media stage carries a bottom-left 40px/1 headline, tiny 25px pills, a 40px slide counter and an isolated forward arrow.
- Small serif controls punctuate a grotesk editorial system: Lyon 13px/1 at weight 100 inside 25px-high, 50px-radius pills; Suisse supplies 24px pullouts and 40px section titles.
- Colour belongs to the work: the interface remains white, black and grey while saturated photographs and films can occupy almost the entire opening and most of subsequent proof sections.
- Proof alternates intimacy and spectacle: pair 660px-wide media cards across a 40px gutter, then let selected scenes span the 1360px content width; clip media with only 5px corner rounding.
- Captions behave like exhibition labels: put a 24px/28px title 50px below media, with a 16px grey outcome line directly beneath and 20px horizontal inset.
- Every page resolves into a black contact stage and a repeating social strip: a 387px footer holds small 12px contact columns above a 44px-high ticker with alternating grey prompts and white 22px/44px handles.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action, border | Primary headings, filled pills and the black closing stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ticker grey | `#595b60` | `--color-ticker-grey` | text, border | Repeated social prompt and top edge of the footer ticker. |
| Caption grey | `#888888` | `--color-muted` | text, link, border | Body support, project summaries, footer links and newsletter underline. |
| Cool rule | `#d8d8da` | `--color-rule` | border, background | Feed dividers, service list rules and the substantial closing invitation band. |
| Light media bed | `#f5f5f5` | `--color-media-bed` | surface | Backing behind staged media and small utility tiles, not a substitute for imagery. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas; reversed text over dark media and footer handles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company profile directories | Profile rule | `#c3c3c3` | `--color-profile-rule` | border | Thin separators in the client directory. |
| company profile pages and filter hover | Office grey | `#dddddd` | `--color-profile-grey` | background | Continuous grey editorial canvas before switching to white; also the filter hover fill. |
| reversed media labels and capability carousel bands | Pale grey band | `#ebecec` | `--color-soft-grey` | surface, border, text | Light outline treatment over dark media. |

## Typography

- **Suisse** — All headings, paragraphs, project names, dates and contact details. Direct neo-grotesk with compact proportions, unforced sentence case and medium-to-semibold emphasis. If unavailable, use **Inter**. Use weights 400, 500 and 600 with normal tracking. Font stack: "Suisse", "Inter", Arial, sans-serif.
- **Lyon** — Tiny action labels and outlined category pills. Fine editorial serif that deliberately contrasts with the practical grotesk. If unavailable, use **Source Serif 4**. Use the lightest available cut at 13px; preserve short labels and compact line height. Font stack: "Lyon", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stage-title | Suisse | 600 | 40px | 1 | normal | Two-line campaign headline and carousel counter on the opening media stage. |
| heading | Suisse | 600 | 40px | 1.125 | normal | Main section titles and closing invitation headings. |
| pullout | Suisse | 500 | 24px | 1.167 | normal | Introductory statement, project title link, editorial explanation and testimonial text. |
| ticker | Suisse | 600 | 22px | 2 | normal | Alternating repeated social prompts and linked handles. |
| body | Suisse | 400 | 16px | 1.39 | normal | Supporting paragraphs and concise outcome captions. |
| body-strong | Suisse | 600 | 16px | 1.39 | normal | Feed titles and service/tool group labels. |
| pill-label | Lyon | 100 | 13px | 1 | normal | Filled action pills and outlined metadata. |
| caption | Suisse | 400 | 12px | 1.333 | normal | Dates, footer contacts and supporting tool descriptions. |
| filter-label | Suisse | 400 | 12px | 1.25 | normal | Small filter control above an image index. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company profile chapters | profile-heading | Suisse | 600 | 40px | 0.85 | normal | Compressed chapter headings beside office photographs. |
| case study openings | case-title | Suisse | 600 | 22px | 1.59 | normal | Small right-column project name above a longer narrative. |

**Notes:**

- Scale comes from the media rather than enormous interface typography: the largest recurring text recipe is 40px.
- Keep tracking normal throughout. Do not impose the tight negative tracking of a contemporary software display system.
- The 24px pullout bridges introductory prose and image captions; it is not an oversized hero headline.
- Serif text is confined to small labels and controls, not long paragraphs or major titles.

## Layout

**Density:** Airy at section level and compact within labels and lists; large image fields and 140px chapter breaks contrast with tightly packed caption stacks.

### Spacing

**Spacing system:**

- **vertical rhythm** 10px, vertical — Primary non-fluid chapter spacing, margins and padding.
- **horizontal step** 20px, horizontal — Media insets, outer gutters and column separation.

| Value | Use |
| --- | --- |
| 10px | Space below a compact bold label and vertical padding of directory rows. |
| 20px | Media overlay inset, caption side inset and feed-card separation. |
| 30px | Space before the closing invitation action; leading padding of carousel intro tiles. |
| 40px | Page side padding, main grid gutter, heading-to-content and intro-to-action gaps. |
| 50px | Media-to-project-title gap. |
| 70px | Capability carousel band padding. |
| 80px | Feed and project index top padding. |
| 140px | Intro top and bottom padding and major project/chapter separation. |
| 280px | Open space below the content of a closing invitation band. |

### Containers and grids

- **editorial container**: max width 1440px · 12 columns · gap 40px · side padding 40px. Centered desktop grid with a 1360px usable content field.
- **paired proof**: 2 columns · gap 40px. Two 660px media cards share a row; a featured scene takes both columns.
- **intro measure**: max width 660px. Left-half statement with the right half deliberately open.
- **contact columns**: 4 columns · gap 40px · side padding 40px. Four 310px columns hold contact, location, subscription and small social icons.
- **capability chapter** (only for capability pages): 3 columns · gap 40px. A narrow left title rail and a two-thirds-width media/detail region; media is 893px wide and inner lists use a 60px gutter.
- **culture triptych** (only for company culture chapters): 3 columns · gap 30px. Text and two portrait photographs, each approximately 433px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 50px |
|  | media and utility tiles | 5px |
| capability carousels | carousel arrows | 50% |

## Surfaces and depth

### Surfaces

#### White editorial canvas · level 0

**Use:** Default marketing page surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, untextured and free of elevation; the images supply depth.

**Transfer:** Let typography and varied media scale establish hierarchy.

#### Media bed · level 0

**Use:** Staging for photographs, film and device compositions.

**CSS:** `background: #f5f5f5; border-radius: 5px; overflow: hidden`

**Observed:** The subtle backing recedes behind the actual artwork. Large images extend to their clipped edges.

**Transfer:** Use for composed product proof, with honest material lighting rather than ornamental UI shadows.

#### Black contact stage · level 0

**Use:** Closing contact zone shared across page types.

**CSS:** `background: #000000; padding-top: 40px`

**Observed:** A deep empty field separates the small contact row from the social ticker at the bottom.

**Transfer:** Maintain the empty black interval even when there are only a few contact destinations.

#### Invitation band · level 0

**Use:** A direct invitation above the contact stage.

**CSS:** `background: #d8d8da; padding: 40px 40px 280px`

**Observed:** Title at left; statement and a tiny action at right. The lower part is intentionally open.

**Transfer:** Adapt to the primary next step without making the action visually louder than the copy.

#### Office canvas · level 0

**Only for:** company profile pages

**Use:** An extended introductory editorial chapter.

**CSS:** `background: #dddddd`

**Observed:** Grey joins the intro, alternating text/image rows and client list; culture chapters switch to white.

**Transfer:** Reserve the continuous grey for a sustained company narrative.

#### Capability band · level 0

**Only for:** capability carousels

**Use:** Backs the portrait-image slider and white intro tile.

**CSS:** `background: #ebecec; padding-top: 70px; padding-bottom: 70px`

**Observed:** The row reaches past the right edge, allowing the next image to imply more content.

**Transfer:** Use for curated demonstrations or applications, not a standard boxed feature grid.

## Components

### Minimal navigation

**Use:** Persistent brand and menu access.

**CSS:** `position: fixed; padding-top: 30px; padding-bottom: 15px; z-index: 100`

**Observed:** A 78px header contains a compact 49px by 33px identity at the left and two horizontal menu strokes at the far right, aligned to the editorial container. White over the dark opening scene, black over light pages. No desktop link list or large CTA.

**Transfer:** Use a compact original identity with the same visual footprint and a restrained menu trigger.

### Primary pill

**Use:** Small editorial actions, including the main next step.

**CSS:** `display: inline-flex; align-items: center; height: 25px; padding: 0px 11px; background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 50px`

**Text style:** `pill-label` — Lyon 100 · 13px/1

**Observed:** Content-width pills cluster after introductory copy. On a dark campaign image the action becomes white with black text.

**States:** Declared: hover and focus-visible unspecified; active color #ffffff.

**Transfer:** Keep the visual pill small even for the principal action; extend the accessible hit area without enlarging its visible silhouette.

### Category pill

**Use:** Classifies an image or project without competing with it.

**CSS:** `display: flex; align-items: center; height: 25px; padding: 0px 11px; border: 1px solid #000000; border-radius: 50px; color: #000000`

**Text style:** `pill-label` — Lyon 100 · 13px/1

**Observed:** Outlined label sits 20px inside the upper-left media corner. Dark media uses white or pale-grey text and outline.

**Transfer:** Use one short category or release status rather than a cloud of badges.

### Project caption

**Use:** Names a visual proof item and leads into its outcome.

**CSS:** `display: block; padding: 0px 20px; margin-top: 50px; color: #000000`

**Text style:** `pullout` — Suisse 500 · 24px/1.167

**Observed:** The linked title is followed immediately by a grey body-size outcome sentence. It is separate from the image rather than a boxed card footer.

**Transfer:** Use a short product/application name plus a single specific result.

### Feed card

**Use:** Dated editorial news in a horizontally continuing row.

**CSS:** `width: 350px; padding-right: 20px; border-right: 1px solid #d8d8da`

**Text style:** `body` — Suisse 400 · 16px/1.39

**Observed:** Portrait-ish image first, outlined status in its upper-left corner, then date, bold title and grey paragraph. Images are about 329px by 385px. Cards continue offscreen rather than shrinking to fit.

**Transfer:** Use releases, field notes or customer stories with the same editorial density.

### Filter control

**Use:** Utility action opposite an image-index heading.

**CSS:** `display: inline-flex; align-items: center; height: 29px; padding: 7px 14px; background: #f5f5f5; color: #000000; border-radius: 5px`

**Text style:** `filter-label` — Suisse 400 · 12px/1.25

**Observed:** A small plus precedes the word; the control is aligned to the right edge of the section heading row.

**States:** Declared: hover background #dddddd; focus-visible unspecified; active color currentcolor.

### Newsletter link

**Use:** Lightweight subscription action in the footer.

**CSS:** `color: #888888; border-bottom: 1px solid #888888; transition: color 0.5s`

**Text style:** `caption` — Suisse 400 · 12px/1.333

**Observed:** Underlined text link, not a prominent form or button; grouped under a small white contact heading.

**States:** Declared: hover color #bbbbbb; focus-visible unspecified.

### Social ticker

**Use:** Signature closing strip.

**CSS:** `height: 44px; background: #000000; border-top: 1px solid #595b60; overflow: hidden; display: flex; align-items: center`

**Text style:** `ticker` — Suisse 600 · 22px/2

**Observed:** A continuous repeated line alternates the grey invitation and white linked handle. It clips through both edges and sits at the bottom of the contact stage.

**Transfer:** Repeat a genuine community destination or publication name with an action phrase; retain the alternating text values.

### Capability intro tile

**Only for:** capability carousels

**Use:** Anchors a horizontal set of portrait demonstrations.

**CSS:** `width: 467px; height: 600px; padding: 30px 40px 40px 30px; background: #ffffff; border-radius: 5px; position: relative`

**Text style:** `heading` — Suisse 600 · 40px/1.125

**Observed:** Heading, short bold subheading and grey paragraph stay at top; two 40px circular arrow controls sit at bottom-right. Adjacent portrait photographs share its height.

**Transfer:** Explain the group in the tile and let the adjacent images carry individual examples.

### Case close pill

**Only for:** case study pages

**Use:** Returns from an immersive project story.

**CSS:** `position: fixed; display: flex; align-items: center; height: 25px; padding: 0px 11px; background: #ebecec; color: #000000; border-radius: 50px; z-index: 4`

**Text style:** `pill-label` — Lyon 100 · 13px/1

**Observed:** Pinned at the upper-right, paired with the small identity at upper-left; a 9px diagonal cross precedes the label.

**States:** Declared: hover and focus-visible unspecified; active color currentcolor.

## Imagery and graphics

### Cinematic campaign stage

**Use:** The opening's dominant emotional and visual device.

**Observed:** A full-bleed film-like scene fills the viewport: a standing performer on the right, a monumental projected portrait near the centre, deep shadow at left and warm yellow light at right. Human skin, fabric and flooring remain tangible rather than airbrushed; type overlays a dark lower-left area.

**Transfer:** Create a full-frame scene of the product in use, or its human consequence, with strong directional light and an intentionally calm dark area for white copy. If film is unavailable, use a single excellent art-directed photograph rather than a UI collage.

**Build:** Use an edge-to-edge image/video with object-fit: cover in a 900px desktop stage. Compose the main subject toward the centre/right and reserve the left third for low-detail shadow. If needed, overlay a left-to-right black-to-transparent gradient using rgba(0,0,0,0.45) and rgba(0,0,0,0), then place headline and pills above it; retain natural light rather than adding synthetic neon.

### Alternating exhibition proof

**Use:** Dominant body imagery in the landing-page index.

**Observed:** Large fashion portraits, printed identities, architectural exteriors and identity films alternate between paired landscapes and near-full-width scenes. Colours range from red and violet to green, but remain inside artwork. Some images carry a large original wordmark; others are purely photographic. Rounded corners are barely perceptible.

**Transfer:** Combine close product details, real-world applications and designed artefacts. Make at least one scene visually monumental; for an abstract service, photograph its outputs as tangible objects rather than repeating abstract gradients.

### Tactile application studies

**Only for:** case study galleries

**Use:** Explains the breadth and craft of a transformation.

**Observed:** Open books, stacked collateral, embossed paper, packaging, fabric, signage and devices are staged against pale grey or black backdrops. Soft cast shadows belong to the photographed objects, not to CSS cards. Broad overview spreads alternate with tight texture details and real-world installations.

**Transfer:** Show the new product's materials, physical touchpoints or composed interfaces in several scales. Stage simple paper or device mockups on a neutral ground when custom photography is unavailable.

### Architectural craft study

**Only for:** architectural case studies

**Use:** Connects an identity to built form.

**Observed:** Spiral and switchback stairs, red balustrades, warm timber grain and cream walls are shown with sharp geometry and occasional motion-blurred people. Saturated red stationery and debossed burgundy paper echo the building details.

**Transfer:** Choose a coherent material/colour relationship between real product details and its applications, without making that campaign palette the surrounding site theme.

### Office and human context

**Only for:** company profile pages

**Use:** Humanises the editorial company narrative.

**Observed:** Warm wood shelving, polished concrete, curated books and art, daylight portraits and local street scenes. Colour is softened; occasional black-and-white photographs sit alongside restrained natural colour. Mix wide interiors with paired tall details.

**Transfer:** Photograph actual working environments, people and nearby places with natural light and uncluttered framing. Prefer lived-in material specificity over generic smiling-team stock.

### Icons

**Observed:** Navigation uses a compact identity and two-line menu. Utility plus and close cross use 1.5px butt-ended strokes at 11px and 9px; the opening forward arrow is an isolated white 48px by 40px shape. Capability tools use black 33px symbols inside 45px pale-grey squares.

**Transfer:** Keep utility icons simple, monochrome and subordinate. Use the larger arrow only for stage navigation; reserve symbolic tool tiles for capability explanations.

## Section recipes

How recurring sections are built.

### First screen: Campaign stage opening

**Observed:** A 900px full-bleed Cinematic campaign stage fills the first screen with no following section visible. Back-to-front: photographic scene, any local contrast shading, Minimal navigation, then bottom controls. The compact identity occupies the upper-left and menu the upper-right within 40px side margins. The main subject dominates the centre/right. The white 40px/1 stage-title sits low at left in two short lines, with Category pill and reversed Primary pill immediately above; the headline occupies roughly the left third rather than spanning the image. A large two-digit current/total counter and ring sit toward the lower middle, and an isolated forward arrow sits at the lower-right. Supporting company prose starts below the first screen.

**Transfer:** Use one compelling product-use scene and a brief editorial promise. With no film, art-direct a still around the same light/dark composition. Supporting informational pages instead open with a 660px-wide left-aligned pullout, 140px vertical padding and compact pill links; case studies open with a right-half narrative and a small case-title before the first wide image.

**Avoid:** Do not replace the stage with a centred giant headline, a floating dashboard or a row of oversized conversion buttons.

**Text style:** `stage-title` — Suisse 600 · 40px/1

### Editorial statement

**Observed:** On White editorial canvas, a left-half pullout uses 140px top and bottom padding; Primary pills follow after 40px. The other half remains open.

**Transfer:** Explain the product's point of view in a compact paragraph, then provide a few genuine reading routes.

**Text style:** `pullout` — Suisse 500 · 24px/1.167

### Dated horizontal feed

**Observed:** A 40px heading begins a horizontal row after a 40px gap. Feed cards retain their width and thin right dividers, with the last item extending beyond the viewport.

**Transfer:** Use as a current-activity signal, with specific dates and short reports rather than decorative testimonials.

**Text style:** `heading` — Suisse 600 · 40px/1.125

### Exhibition index

**Observed:** A heading and Filter control introduce Paired proof. Alternate pairs of landscape images with featured 1360px by 880px scenes, using Media bed and Category pill. Project caption sits below each image, and the next row begins after a 140px break.

**Transfer:** Give the strongest proof more area instead of assigning every item identical importance.

### Closing invitation and contact

**Observed:** The image index and case galleries end with their final visual proof, then Black contact stage. Informational pages first add Invitation band: heading left, 24px statement and Primary pill right, with 280px of lower breathing room. The shared 387px black footer holds contact columns at its top and Social ticker at its bottom.

**Transfer:** Close with a direct next step appropriate to the product. Always preserve the black field, small contact row and repeating social strip; use the grey invitation when a conversational conversion prompt is needed.

**Text style:** `heading` — Suisse 600 · 40px/1.125

### Capability chapter

**Only for:** capability pages

**Observed:** A left title rail carries a 40px heading and short bold subhead. The right two-thirds starts with a wide 893px by 536px image, then divides into explanatory/list content and tool rows. List entries use thin cool-grey rules; tool rows pair 45px symbol tiles with bold names and 12px explanations.

**Transfer:** Organise a product's capabilities by purpose and useful tools, allowing detailed information without building a dense dashboard.

**Text style:** `heading` — Suisse 600 · 40px/1.125

### Portrait demonstration carousel

**Only for:** capability pages

**Observed:** Capability band backs a Capability intro tile and a continuing row of 600px-high portrait images. Small captions sit at image top-left; arrows stay in the introductory tile. A thin horizontal rule separates adjacent carousel chapters.

**Transfer:** Use for applications, programmes or curated examples that benefit from strong vertical imagery.

### Company editorial rows

**Only for:** company profile pages

**Observed:** Office canvas holds alternating half-width image/text rows with 140px between chapters and compact profile-heading titles. A three-column ruled client directory closes that grey chapter. White culture chapters alternate triptychs of text and two portrait images with wider image/text pairs.

**Transfer:** Use a company story to demonstrate environment and character, not as a generic feature-card wall.

**Text style:** `profile-heading` — Suisse 600 · 40px/0.85

### Immersive case story

**Only for:** case study pages

**Observed:** Small case-title and grey body narrative sit in the right half above tags; the left remains open except for identity. A wide initial scene leads into staggered paired media, full-width interludes and detail closeups. A right-column 24px explanation or testimonial can interrupt the image sequence; testimonial attribution follows after 40px.

**Transfer:** Move from context to tangible applications, then craft detail and human proof. Use intentionally composed staggered rows, not empty placeholder cards.

**Text style:** `case-title` — Suisse 600 · 22px/1.59

## Page flow

**Storyline:** visual promise → point of view → editorial activity or capability explanation → concrete applications → invitation or final proof → contact and social continuation

### Image-led marketing and work discovery

1. **Visual promise** — Full-screen campaign stage with a short headline and slide controls.
2. **Positioning** — Left-half pullout and small navigation pills.
3. **Current activity** — Horizontal dated editorial feed.
4. **Product proof** — Alternating paired images and wide featured scenes with exhibition-style captions.
5. **Contact continuation** — Final paired work row gives way to a black contact field and repeating social strip.

**Transfer:** Let the product's best demonstrations establish desire before explaining the full offer.

### Company narrative and human credibility

1. **Positioning** — Compact statement on grey, with one pill action and a wide interior image.
2. **Capability and credibility** — Alternating text/image chapters followed by a three-column ruled directory.
3. **Human context** — White culture chapter with portrait triptychs, local context and founders.
4. **Invitation** — Grey recruitment band with heading left and statement/action right.
5. **Contact continuation** — Black contact stage and social ticker.

**Transfer:** Replace the specific office story with authentic evidence of how the new organisation thinks and works.

### Capability explanation and enquiry

1. **Orientation** — Left-aligned statement and compact category jump pills.
2. **Capability chapters** — Title rail beside broad image, detailed service lists and tool rows.
3. **Breadth of application** — Pale-grey carousel bands with white intro tiles and tall image examples.
4. **Closing call** — Grey invitation band with a direct enquiry action.
5. **Contact continuation** — Black footer and repeated social line.

**Transfer:** Make a complex offer browsable through named purposes, practical lists and visual examples.

### Tactile application case study

1. **Context** — Right-half project narrative and outlined discipline tags, with a fixed close control.
2. **Application proof** — A wide collage opens into staggered print, signage, digital and real-world compositions.
3. **Craft detail** — Material closeups and paired publication spreads establish consistency across touchpoints.
4. **Final proof** — A wide editorial application image concludes the story.
5. **Contact continuation** — Shared black footer and social ticker.

**Transfer:** Show a coherent product across physical and digital contexts rather than merely listing deliverables.

### Transformation case study with architectural and human proof

1. **Context** — Right-half narrative, small title and outlined tags.
2. **Visual demonstration** — Wide architectural scenes mix with identity, paper and material details.
3. **Explanation** — A 24px right-column statement relates the design language to its purpose.
4. **Social proof** — Right-column testimonial with separate attribution.
5. **Application depth** — Device arrangements and long paired website views, then a real-world billboard.
6. **Contact continuation** — Black contact stage and repeating social strip.

**Transfer:** Connect an original design decision to user experience, then substantiate it with applications and an authentic quote.

## Writing

Cultured, assured and collaborative. The language makes creative ambition feel practical, using concrete outcomes and warm invitations rather than hype.

**Do not copy:** Do not reuse the agency identity, monogram, client identities, project artwork, addresses, contact details, dates, numbers, awards, claims or testimonial wording. Source examples illustrate voice only.

- **Addressing the reader:** Use we for the maker and you or your for the reader when discussing collaboration. Project captions often use impersonal outcome phrases.
- **Rhythm:** Short sentence-case headings and one-line outcomes sit beside longer, flowing explanatory paragraphs. Use full stops and occasional en dashes; avoid exclamatory sales language.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign headline | A compact name or context followed by an evocative proposition. | 4–10 words | “ACO 2027. Life in reflection.” |
| Project outcome | An active phrase that reframes what the work makes possible. | 4–10 words | “Uniting architecture and nature.”<br>“A new step up for architecture.” |
| Capability subhead | A gerund-led explanation of the value of a discipline. | 4–8 words | “Giving purpose to your brand”<br>“Sharing your brand in every way” |
| Primary action | Short verb-led destination or straightforward invitation. | 2–4 words | “Explore our Services”<br>“Get in Touch” |
| Closing heading | An inclusive, human invitation rather than a pressured conversion claim. | 2–4 words | “Let’s work together”<br>“Join us” |

**Words and phrasing to use:** connect; transform; meaningful; purpose; bring to life; together; new direction; human-centred

**Avoid:** disrupt everything; 10x; game-changing; crush it; hurry; unbeatable offer

**Rules:**

- Describe a change or outcome in the caption rather than repeating the category label.
- Pair ambitious language with specific applications, materials or actions.
- Let longer paragraphs explain intent without turning every sentence into a slogan.
- Keep navigation labels literal and short; reserve wordplay for project propositions.

## Do's and Don'ts

### Do

- Use the 40px outer inset and gutter to align navigation, media and contact columns.
- Keep the opening headline at 40px/1 and let the scene provide the scale.
- Preserve 25px visual-height serif pills alongside the larger sans text.
- Give selected proof images the full 1360px content width.
- Use 50px between image and project title, then stack the grey outcome directly beneath.
- Retain 140px pauses between major proof rows.
- Finish with the black contact stage and 44px social strip.
- Use 5px corners for media and utilities, keeping the rest of the page flat.

### Don't

- Do not turn the monochrome interface into a brand-colour navigation bar because an artwork uses red or purple.
- Do not round media into 20px app-like cards; the image edge is nearly square.
- Do not add drop shadows to editorial cards or contact panels; depth lives within photographs.
- Do not replace the Lyon pill labels with uppercase tracked sans badges.
- Do not make every proof image an equal square tile; the scale changes are central to the editorial hierarchy.
- Do not fill the footer's open black field with a sitemap wall or a giant logo.
- Do not promote the 12px filter control into a large primary conversion button.
- Do not imitate typography inside device displays or printed artwork as the marketing type system.

## Motion and responsive

### Motion

**Observed:**

- Media wrappers declare transform 0.3s transitions.
- The filter declares background 0.3s ease-in; footer links declare color 0.5s.
- Navigation declares opacity 0.4s with 0.9s delay and transform 0.4s.
- The opening has carousel controls and a progress ring; the footer social line repeats horizontally.

**Transfer:**

- Keep motion attached to image reveals, stage navigation and the social continuation line rather than adding bouncing decorative UI.
- Retain the strong still composition while media changes.

**Unknown:**

- Carousel autoplay interval, ring timing, ticker speed and complete scroll choreography are unspecified.

### Responsive

**Observed:**

- Declared width boundaries include 576px, 600px, 768px, 992px, 1200px and 1700px, with adjacent min-width boundaries. Desktop uses a 12-column editorial grid.

**Transfer:**

- For narrow layouts, preserve the image-first hierarchy and compact pills; stack paired proof and place capability details below their title rail.
- Keep the campaign's copy over a deliberately low-detail portion of the media; choose an alternate image framing rather than shrinking all content proportionally.
- Retain horizontal continuation for editorial feeds and the social strip.

**Unknown:**

- Exact mobile padding, type sizes, image art direction and column-switch behaviour are unspecified; these transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
