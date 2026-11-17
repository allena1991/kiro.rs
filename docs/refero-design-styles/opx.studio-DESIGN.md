# OPX Studio — black stage, oversized statements

## Overview

A dark, image-led editorial style with an assured, creative-studio presence. White geometric grotesk typography sits on near-black space while photography, physical mockups and moving identity work carry the color. It suits design-conscious products and portfolios that can demonstrate their value visually, with sparse framing and unusually substantial paragraph type.

### Essentials

- A two-line promise floats above the work: regular-weight geometric type at 80px/97px, normal tracking, centered across roughly two thirds of the desktop width.
- Navigation behaves like stage furniture rather than a toolbar: two 50px/1 labels sit at opposite edges, 50px from the sides, with inactive white lettering at 0.3 opacity.
- Proof arrives as an irregular procession of sharp rectangles: alternate left and right alignment and widths of 541px, 655px, 883px, 1112px and 1340px at a 1440px viewport, with about 100px between exhibits.
- Color belongs to the exhibits, not the interface: the default canvas is #020202 with #ffffff text; saturated color occupies image rectangles while the surrounding field remains black. Full-page burgundy is reserved for themed case studies.
- Actions are deliberately small beneath large work: a 1px white outline, 45px radius and 7px 30px inner padding contain 14px text beneath 35px captions.
- Every page ends with a monumental typographic signature: three contact columns at 20px/1.4 precede white wordmark artwork spanning the 1340px content width. Create an equally broad text-based SVG signature when no custom mark exists.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White lettering | `#ffffff` | `--color-white` | text, border, action | Headlines, paragraphs, signature artwork and action outlines. |
| Media black | `#000000` | `--color-black` | background, text | Video backing and declared action-hover ink. |
| Near-black stage | `#020202` | `--color-canvas` | background, surface | Default page field and shared closing area. |
| Dimmed navigation | `#4e4e4e` | `--color-nav-muted` | text, link | Visible inactive white navigation at 0.3 opacity over the near-black stage; implement with white plus opacity. |
| Contact gray | `#9b9b9b` | `--color-muted` | text, link | Contact destinations and secondary footer information. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expressive campaign case studies | Burgundy narrative | `#7e0212` | `--color-burgundy` | background | Continuous saturated background supporting warm, theatrical imagery. |
| monochrome case studies | Charcoal narrative | `#191919` | `--color-charcoal` | background | Continuous background for a restrained, monochrome project narrative. |
| monochrome case studies | Charcoal cover | `#1c1c1c` | `--color-cover-charcoal` | background | Slightly lighter opening media stage. |
| monochrome case studies | Dark dotted edge | `#424242` | `--color-dark-rule` | border | Subtle portrait-video outlines. |
| monochrome case studies | Light dotted edge | `#999999` | `--color-soft-rule` | border, text | Large video edges and subdued testimonial role labels. |

## Typography

- **OPX** — All principal editorial text, navigation and contact information. Broad geometric sans with circular counters and eccentric, squared details; a consistent medium-looking cut declared at regular weight. If unavailable, use **Space Grotesk**. Use 400–500 and preserve broad proportions and normal tracking. Font stack: "OPX", "Space Grotesk", sans-serif.
- **Untitled** — Small outlined action labels. Neutral, compact sans that contrasts with the expressive editorial face. If unavailable, use **Inter**. Use 500 for compact action lettering. Font stack: "Untitled", "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| feature-display | OPX | 400 | 111px | 119px | normal | Oversized editorial series or content-series link. |
| opening-display | OPX | 400 | 80px | 97px | normal | Centered two-line opening promise. |
| navigation | OPX | 400 | 50px | 1 | normal | Two persistent top-level destinations. |
| editorial | OPX | 400 | 35px | 45px | normal | Main paragraphs, large exhibit captions and inline project links. |
| secondary-caption | OPX | 400 | 26px | 37px | normal | Longer titles in the compact three-column proof row; default smaller caption recipe. |
| contact | OPX | 400 | 20px | 1.4 | normal | Footer contact columns and secondary links. |
| button-label | Untitled | 500 | 14px | 1.66667 | normal | Outlined exhibit actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| about pages, case studies and immersive indexes | page-title | OPX | 400 | 100px | 1 | normal | Left-aligned page title or overlaid exhibit name. |
| case studies | project-premise | OPX | 400 | 60px | 65px | normal | Short proposition below the case-study title. |
| case-study testimonials | testimonial | OPX | 400 | 29px | 37px | normal | Quote, author and role at one scale; role alone changes to gray. |

**Notes:**

- Scale and placement establish hierarchy, not a ladder of font weights. Keep normal tracking throughout.
- The same 35px/45px recipe serves substantial prose and project captions; do not shrink all descriptive copy to ordinary interface body size.
- The compact proof row also contains a 26px/36px caption variant; use the 37px line-height default consistently for new longer captions.
- The closing signature is artwork rather than ordinary heading text; size its vector box to the container instead of trying to reproduce it with a 100px heading.

## Layout

**Density:** Airy, with large unoccupied black regions between image-led exhibits and dense, large-letter paragraphs inside narrow columns.

### Spacing

**Spacing system:**

- **vertical rhythm** 10px, vertical — Main editorial offsets and section spacing use multiples of 10px; smaller type-dependent gaps are exceptions.

| Value | Use |
| --- | --- |
| 15px | Column inner padding on each side, creating 30px gutters. |
| 20px | Image-to-caption separation and caption-to-action block offset. |
| 30px | Column gutters and quote-to-attribution separation. |
| 50px | Desktop side margins and paragraph-group separation. |
| 100px | Primary exhibit-to-exhibit and narrative-to-media spacing. |
| 150px | Large opening pause before the first image. |
| 200px | Contact-section top padding after the final content. |

### Containers and grids

- **outer container**: max width 2100px · side padding 50px. Full editorial container; 1340px usable width at a 1440px viewport.
- **editorial grid**: 12 columns · gap 30px. Use fractional column spans for staggered exhibits: about four, five, six, eight, ten or twelve columns. Align image, caption and action to the same leading edge.
- **contact grid**: 3 columns · gap 30px. Equal thirds hold address, enquiry destinations and social/sign-off information; each text area is 427px wide at desktop.
- **inset narrative** (only for about pages): max width 1112px · 2 columns · gap 30px · side padding 0px. About-page prose and square process photographs pair in two 541px columns inside an inset editorial band.
- **immersive index** (only for immersive portfolio indexes): max width 1440px · 1 column · gap 0px · side padding 0px. Edge-to-edge 1440px × 900px image scenes stacked without gutters.

## Corner radius

| Element | Radius |
| --- | --- |
| outline actions | 45px |
| media rectangles | 0px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default marketing canvas and shared footer.

**CSS:** `background: #020202; color: #ffffff`

**Observed:** A continuous flat field; imagery and typography sit directly on it without raised cards.

**Transfer:** Treat the page as a gallery wall rather than a dashboard.

#### Media stage · level 0

**Use:** Video backing and dark imagery framing.

**CSS:** `background: #000000; border-radius: 0px; box-shadow: none`

**Observed:** Rectangular media boundaries remain crisp; shadows and depth belong inside the photographs.

**Transfer:** Use real lighting or rendered material in the image, not a shadow on its container.

#### Charcoal story · level 0

**Only for:** monochrome case studies

**Use:** A low-chroma long-form narrative variant.

**CSS:** `background: #191919; color: #ffffff`

**Observed:** The cover uses #1c1c1c; the body remains charcoal until the common black ending.

**Transfer:** Carry a single restrained project atmosphere through the narrative.

#### Burgundy story · level 0

**Only for:** expressive campaign case studies

**Use:** An expressive long-form narrative variant.

**CSS:** `background: #7e0212; color: #ffffff`

**Observed:** The color fills the full narrative, while individual media rectangles add pink, red, purple and warm light.

**Transfer:** Use one deep project hue as a sustained atmosphere, then return to the Black stage for the ending.

#### Dotted motion frame · level 1

**Only for:** monochrome case studies

**Use:** Delicate framing around selected videos.

**CSS:** `border: 1px dotted #999999; border-radius: 0px`

**Observed:** Wide motion uses the light dotted edge; portrait motion uses #424242.

**Transfer:** Reserve this technical edge for a considered motion or process specimen, not every photograph.

## Components

### Edge navigation

**Use:** Two top-level destinations above the editorial stage.

**CSS:** `position: fixed; top: 50px; left: 50px; right: 50px; z-index: 120; color: #ffffff`

**Text style:** `navigation` — OPX 400 · 50px/1

**Observed:** One label sits at each edge. Inactive labels have 0.3 opacity; on destination pages the active label moves toward the center and becomes fully white. The navigation has no painted bar.

**Transfer:** Choose two meaningful destinations rather than adding a conventional multi-link toolbar.

### Outline action

**Use:** A small action beneath a work caption.

**CSS:** `color: #ffffff; background: transparent; border: 1px solid #ffffff; border-radius: 45px; padding: 7px 30px; text-align: center; transition: 0.2s linear`

**Text style:** `button-label` — Untitled 500 · 14px/1.66667

**Observed:** A bordered wrapper encloses the label; the complete control is about 163px × 39px for this label. It follows the caption, rather than floating on the image.

**States:** Declared: hover text #000000; ancestor hover text #020202; focus-visible and active treatments are unspecified.

**Transfer:** Keep actions visually subordinate to their exhibits, including for a product-detail action.

### Exhibit caption

**Use:** Name the preceding image-led proof block.

**CSS:** `color: #ffffff; padding-top: 20px`

**Text style:** `editorial` — OPX 400 · 35px/45px

**Observed:** Caption is flush with the image edge; an Outline action follows beneath. Compact three-column exhibits use secondary-caption for longer titles.

**Transfer:** Use a concise object or outcome name, not a multi-line explanatory card.

### Editorial paragraph

**Use:** Explain a proposition or design decision beside media.

**CSS:** `color: #ffffff; margin-bottom: 50px`

**Text style:** `editorial` — OPX 400 · 35px/45px

**Observed:** Large text wraps into narrow half-width or five-column blocks; empty columns carry equal compositional weight.

**Transfer:** Explain one decision and its purpose in each paragraph.

### Contact link

**Use:** Email and social destinations within the closing contact grid.

**CSS:** `color: #9b9b9b; transition: 0.2s linear`

**Text style:** `contact` — OPX 400 · 20px/1.4

**Observed:** White category labels precede gray destination links; enquiry and career blocks stack in the middle column.

**States:** Declared: hover text #000000; focus-visible and active treatments are unspecified.

**Transfer:** Preserve the white-label/gray-destination distinction without turning the footer into a sitemap.

### Closing signature

**Use:** Monumental final brand impression beneath the contact grid.

**CSS:** `width: 1340px; max-width: 100%; padding-top: 49px`

**Observed:** White vector-like wordmark artwork has a 1340px × 358px image box, occupying almost the full width. It is a standalone final band rather than a small footer logo.

**Transfer:** Fit a new brand name into a broad SVG word sculpture; preserve its silhouette and the oversized final impression.

### Testimonial block

**Only for:** case-study testimonials

**Use:** Human proof inside a long visual narrative.

**CSS:** `color: #ffffff; padding-top: 50px`

**Text style:** `testimonial` — OPX 400 · 29px/37px

**Observed:** A roughly 883px-wide inset quote is followed by the author and then a gray role label at the same type size; no avatar badge or quote card.

**Transfer:** Use a real attributed quotation and let the text itself provide the emphasis.

### Immersive cover link

**Only for:** immersive portfolio indexes

**Use:** Navigate from a full-screen visual scene into a detail story.

**CSS:** `color: #ffffff; position: absolute; left: 50px; bottom: 50px; transition: text-decoration-color 0.3s`

**Text style:** `page-title` — OPX 400 · 100px/1

**Observed:** The title anchors to the lower-left edge over a cover-fitted photograph. The top navigation remains above the image. The visible treatment is unadorned despite a declared underline.

**States:** Declared: hover text #000000 with #ffffff background; ancestor hover retains white text and transparent background and border; focus-visible is unspecified.

**Transfer:** Choose a short title that remains legible over the image without adding a boxed caption.

## Imagery and graphics

### Physical product proof

**Use:** Primary exhibits throughout marketing pages.

**Observed:** Hands holding tablets and phones, screens on real desks and printed work in use. Neutral gray or black environments, directional natural light, believable reflections and skin tones; media is much larger than its caption and presented as an uncropped rectangular photograph where possible.

**Transfer:** Photograph the new product in use, or composite its interface into one high-quality device photograph. Minimum acceptable treatment is a sharply rendered interface on a single device against a restrained neutral backing.

### Staggered gallery

**Use:** Signature image arrangement for a marketing page.

**Observed:** Independent images alternate across the black field instead of filling a masonry grid. Landscape, portrait and near-square formats retain different widths and unequal empty space; occasional full-width media resets the scale.

**Transfer:** Mix product detail, contextual use and outcome imagery. When photography is scarce, create alternating typographic specimens and flat product panels rather than repeating the same device.

**Build:** Use a 12-column CSS grid with 30px gutters inside 50px side margins. Place independent figures on alternating left and right spans of 5, 6, 8 and 10 columns, with 100px vertical separation; insert a 12-column exhibit to break the rhythm. Keep figures borderless and square-cornered.

### Monumental word sculpture

**Use:** Required closing signature on every page.

**Observed:** A single white wordmark stretches nearly edge to edge on black, far larger than nearby contact type. The compressed vertical band makes the name feel architectural.

**Transfer:** Construct an original broad wordmark from the new brand name; a clean text-based SVG fitted to a wide viewBox is the minimum acceptable version.

**Build:** Use a transparent SVG viewBox with the proportions 1340 by 358, white vector lettering and no effects. Fit the lettering across the width while retaining coherent letter proportions; place it below the contact row with a 49px top offset.

### Process photography

**Only for:** about pages

**Use:** Make long editorial statements feel human and grounded.

**Observed:** Square close-ups of people working, hands writing, laptops and bright notes alternate with 35px prose in inset columns; a wide dark studio photograph provides a breathing point.

**Transfer:** Use candid working details with real texture and ambient light, not a uniform wall of corporate headshots.

### Monochrome process specimens

**Only for:** monochrome case studies

**Use:** Show the thinking behind a restrained identity or product.

**Observed:** Black-and-white portrait strips, notebook details, architectural diagrams, devices and white document-layout specimens sit on charcoal. Some diagram lines are white and subdued green; a large quote interrupts the image narrative.

**Transfer:** Use actual working artifacts, line diagrams and reduced-color photographs to explain the product's logic. Keep any artifact typography local to that specimen.

### Theatrical campaign atmosphere

**Only for:** expressive campaign case studies

**Use:** Translate an emotionally vivid project into a sustained visual story.

**Observed:** Rich burgundy supports low-light portraits, warm yellow light streaks, purple haze, reflective metallic clothing, rose-colored typography specimens and richly printed objects. Blurred image-backed panels surround small sharp photographs; full-width mockups alternate with compact three-image rows.

**Transfer:** Match the product's emotional world through directional light, tactile materials and one deep background hue. Keep blur inside the artwork rather than across the marketing copy.

**Build:** For a simple atmospheric panel, duplicate the central photograph as a full-panel background, enlarge it and apply a 60px blur. Layer translucent burgundy at 0.45 opacity over it, then place a sharp portrait rectangle at the center, around one third of panel width. Add small white words to either side; match the soft glow rather than relying on exact gradient stops.

## Section recipes

How recurring sections are built.

### First screen: Floating promise opening

**Observed:** Black stage fills the first screen. Edge navigation occupies the top corners with 50px side margins. A white two-line opening-display promise sits centrally below a large top pause, spanning roughly 924px across the 1440px field and a 194px text band. There is no separate support paragraph or hero button. After about 150px of additional air, the first 883px-wide landscape exhibit is anchored right, its upper 255px visible within the first 900px. Its caption and Outline action fall below the fold. Layers are flat canvas, editorial lettering and rectangular photography, with fixed navigation above.

**Transfer:** Write a strong two-line product promise and let a right-aligned product scene enter the bottom of the first screen. Without photography, use a designed interface specimen at the same scale. Detail stories instead open with an inset media cover, a left-aligned page-title and a smaller premise; an about page opens with an inset title and text/photo pair; an immersive index opens directly on a full-screen image.

**Avoid:** Do not turn this into a centered SaaS hero with eyebrow, support paragraph, paired conversion buttons and a decorative gradient behind a floating dashboard.

**Text style:** `opening-display` — OPX 400 · 80px/97px

### Asymmetric proof procession

**Observed:** Staggered gallery places one exhibit at a time against Black stage. Exhibit caption and Outline action sit below each image; widths range from 541px to 1340px, with large black intervals and occasional full-width motion.

**Transfer:** Alternate different kinds of proof at unequal scales, letting the most persuasive object take the widest span.

**Text style:** `editorial` — OPX 400 · 35px/45px

### Case-study premise and chapters

**Observed:** An inset cover image leads to a 100px title close to the outer margin. A 60px premise moves inward; 35px paragraphs occupy one half of the grid, often on the opposite side from the preceding image. Large media and compact strips then alternate with paragraphs. Charcoal story or Burgundy story continues through the narrative.

**Transfer:** Explain the problem, the organizing idea, decisions and outcomes with actual product artifacts; apply the color variant only when the project warrants its own atmosphere.

**Text style:** `project-premise` — OPX 400 · 60px/65px

### Editorial content-series break

**Observed:** A 111px/119px feature-display link introduces an editorial series, followed by three equal exhibit columns with square imagery, mixed 26px and 35px captions and Outline actions.

**Transfer:** Use this as a large link to a collection of learning resources, stories or product applications, not as a row of tiny feature icons.

**Text style:** `feature-display` — OPX 400 · 111px/119px

### About-page alternating argument

**Observed:** The inset narrative band pairs 541px square process photographs with 35px/45px paragraphs, switching image and prose sides. A 1112px-wide landscape image pauses the argument before further pairs.

**Transfer:** Pair each belief or capability with a tangible working detail. End the argument with a direct invitation rather than a separate colored sales panel.

**Text style:** `editorial` — OPX 400 · 35px/45px

### Contacts and monumental sign-off

**Observed:** After the last proof or invitation, a Black stage band adds 200px top padding. Three equal contact columns carry white labels and Contact links at 20px/1.4. Closing signature follows as a separate 407px band with 49px top spacing and a 1340px × 358px artwork box. The same ending follows both colored case-study narratives and full-screen index scenes.

**Transfer:** Use address or company identity, primary enquiry channels, and social/sign-off information in three thirds. Finish with the new brand's Monumental word sculpture; do not replace this device with a generic conversion card.

**Text style:** `contact` — OPX 400 · 20px/1.4

## Page flow

**Storyline:** Bold promise → visual proof → deeper explanation or editorial collection → direct contact → monumental signature.

### Introduce a visually led product or creative offering

1. **Promise** — A centered two-line statement and the upper edge of the first exhibit.
2. **Product proof** — An alternating procession of differently sized media, captions and small outline actions.
3. **Further exploration** — An oversized content-series link and compact three-column proof row.
4. **Closing contact** — Three contact columns and an edge-to-edge typographic signature.

**Transfer:** Use the strongest tangible outcomes as exhibits rather than adding an exhaustive feature grid.

### Explain a restrained product or identity through decisions and artifacts

1. **Project introduction** — Inset physical-device cover, large title, concise premise and narrow explanatory paragraphs on charcoal.
2. **Design rationale** — Wordmark specimen, responsive device work, portrait strips and technical diagrams.
3. **Human proof** — Large inset testimonial followed by material and document-system examples.
4. **Outcome and closing contact** — Final explanation with an external project link, then the shared black contact/signature ending.

**Transfer:** Keep the narrative analytical and low-chroma, using proof artifacts instead of decorative sections.

### Explain an expressive campaign or emotionally rich product

1. **Project introduction** — Inset atmospheric portrait, large title and a compact premise on burgundy.
2. **Product demonstration** — Large device scenes and image-backed motion panels establish the experience.
3. **System explanation** — Narrative paragraphs alternate with color/type specimens, illustration and physical applications.
4. **Outcome and closing contact** — A final system presentation gives way to the shared black contact/signature ending.

**Transfer:** Sustain one project-specific atmosphere but retain the shared editorial scale and ending.

### Let visitors browse work by immersion rather than summaries

1. **Visual discovery** — Full-screen cover photography with a lower-left title and top navigation.
2. **Breadth of proof** — Consecutive edge-to-edge scenes with different products and material contexts.
3. **Closing contact** — The image sequence stops and the shared black contact/signature ending takes over.

**Transfer:** Use this format only for a collection with enough strong visual scenes; avoid turning each scene into a crowded card.

### Communicate the people and convictions behind an offering

1. **Positioning** — A short 100px title introduces a text/photo pair.
2. **Capability and approach** — Large prose and working photographs alternate within an inset grid.
3. **Invitation** — A direct, ambitious closing paragraph leads into contact.
4. **Closing contact** — Shared contact thirds and monumental wordmark artwork.

**Transfer:** Explain how the organization works through concrete details and a collaborative invitation.

## Writing

Confident, declarative and creatively ambitious, with a conversational edge. Short propositions carry the attitude; longer paragraphs explain the thinking and the collaboration behind visible outcomes.

**Do not copy:** Do not reuse the studio name or wordmark, client identities, project slogans, contact details, distinctive artwork, testimonial quotations or unverified outcome claims. Source examples illustrate sentence construction only.

- **Addressing the reader:** Use we for the maker and you or your for the reader in positioning copy; case narratives refer to the product or client by name and describe what the team did.
- **Rhythm:** Headlines are short declarative propositions, often ending with a full stop. Explanatory prose is substantial but broken into discrete paragraphs, with occasional short sentences for emphasis.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A first-person statement built from forceful parallel verbs. | 6–10 words | “We invent, reinvigorate and transform brands.” |
| Short positioning line | Two or three words carrying an ambitious, memorable proposition. | 2–4 words | “Create great.”<br>“Minimise demand”<br>“Elevated, Everywhere.” |
| Explanatory paragraph | Tie a creative decision to a concrete purpose rather than listing deliverables alone. | 30–70 words | “By uncovering new strategic insights, we build brands where each carefully chosen word is focused on your progress. Where every creative decision drives you towards courageous new ground.” |
| Action | A restrained literal invitation to inspect the work. | 2–4 words | “View case study” |
| Closing invitation | Address the reader's ambition directly, then offer partnership. | 20–35 words | “If, like them, you have a burning ambition to make a real difference, we’ll help make it happen.” |

**Words and phrasing to use:** create; transform; purpose; beyond the obvious; together; clarity; discipline; ambition

**Avoid:** best-in-class; seamless ecosystem; unlock synergies; limited-time offer; revolutionary AI-powered solution

**Rules:**

- Lead with a position, not a taxonomy of services.
- Connect each paragraph to an image or artifact that makes its claim tangible.
- Use plain action labels and reserve expressive language for propositions.
- Give collaborators specific credit through inline links when relevant.
- Keep the closing invitation personal and direct rather than promotional.

## Do's and Don'ts

### Do

- Keep the default field #020202 and primary lettering #ffffff.
- Preserve 80px/97px two-line opening type at desktop.
- Use the same 35px/45px editorial scale for captions and substantial prose.
- Align each image, caption and outlined action on one edge.
- Use 50px outer margins and 30px gutters in the main desktop grid.
- Alternate media widths rather than making all exhibits equal.
- Preserve the 45px action radius and 1px outline.
- Give the closing name a full-width artwork band after the 20px contact columns.

### Don't

- Do not use bold weights as the main hierarchy mechanism; the editorial face stays at 400.
- Do not round photographs or add card shadows around exhibits.
- Do not promote burgundy into the ordinary page background; it belongs to a themed case narrative.
- Do not fill the footer with a many-column sitemap or social icon buttons.
- Do not replace the large paragraph style with 16px gray interface copy.
- Do not apply technical dotted borders to every photograph.
- Do not place a colored button over every image; the small outlined action sits beneath its caption.
- Do not add stock illustrations, icon grids or decorative glows to the default black canvas.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s linear transitions.
- Navigation items declare opacity 0.6s, transform 0.3s and left/right 0.6s cubic-bezier(0.19, 1, 0.22, 1).
- Immersive index covers declare transform 900ms; background-position 900ms is also declared.
- Case-study covers use an upward translation with overlapping layout, producing an inset media opening.

**Transfer:**

- Use the declared navigation movement to distinguish the current destination without adding a tab background.
- Keep motion-led product artwork within its rectangular stage; surrounding copy remains straightforward.
- Retain the contrast between a freely spaced editorial gallery and the full-screen image-index experience.

**Unknown:**

- Exact scroll-trigger choreography, media playback cycles and hover background behavior are not fully specified.
- Focus-visible, active and reduced-motion treatments are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 544px, 600px, 768px, 992px, 1024px, 1170px and 1280px.
- Desktop uses a wrapping column system with 15px inner column padding and a 2100px container maximum.

**Transfer:**

- On narrow screens, stack alternating exhibits in reading order while preserving their caption/action attachment.
- Keep the closing signature fitted to available width as SVG artwork rather than wrapping it like a paragraph.
- Reduce the promise scale enough to retain its short-line composition; allow contact thirds to stack before they become cramped.

**Unknown:**

- Mobile font sizes, margins, destination-navigation placement and exact stacking breakpoints are not established.
- No viewport-relative typography formulas are established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
