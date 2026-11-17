# Unknown, Untitled — objects at editorial scale

## Overview

An almost monochrome design-office aesthetic with unusually large, light grotesk prose and edge-to-edge portfolios of objects. Off-white pages, near-black lettering and cool grey imagery feel analytical but sensuous, mixing atmospheric CGI, workshop photography and working drawings. The density alternates between tightly packed image sequences and expansive pauses, suited to design-led products and substantive visual case studies.

### Essentials

- Prose carries the headline's authority: titles, paragraphs, navigation and actions share SCTO at 47.5px, weight 300, line height 1.035 and tracking -0.05em.
- The opening is an editorial record rather than a sales billboard: a left-aligned title and metadata, a right-aligned identifier, a full-width introductory paragraph and paired portrait media beginning within the first 900px.
- Actions remain typeset rather than enclosed: plain near-black text, about 49.2px line height, without filled buttons, rounded containers or decorative arrows.
- Color belongs to the objects, not the page furniture: the canvas stays #f9f9f9 and text #080807; cool blue-grey, muted violet, material browns and occasional stronger hues live inside photographs, renders and diagrams.
- Media behaves like an oversize contact sheet: 10px outer margins and gutters, 705px half-width panels at 1440px, square edges, asymmetric image heights and occasional 467px centered portraits.
- A monumental typographic signature anchors the page: a single-line wordmark spanning approximately 1400px with a 165px-high graphic box, separated from prior content by a substantial pause. Render the new identity as fitted vector lettering when no custom artwork exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool object backing | `#b5bdc8` | `--color-cool-media` | background | Cool blue-grey ground associated with softly lit object imagery; keep it inside the image plane. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#080807` | `--color-ink` | text, link, action | Default lettering across titles, long prose and unboxed links. |
| Charcoal media backing | `#161616` | `--color-dark-media` | background | Dark image-backed technical studies; contained within media, never a replacement page theme. |
| Current-item grey | `#a0a0a0` | `--color-current` | text | Current entry within a related-work index, not a general secondary body-text color. |
| Drawing ground | `#e0e0e0` | `--color-diagram` | background | Pale ground for fine-line explanatory artwork inside a media panel. |
| Off-white canvas | `#f9f9f9` | `--color-canvas` | background | Continuous page field, including the closing index and footer. |

## Typography

- **SCTO** — All live editorial text, titles, navigation, metadata and links. Light neo-grotesk with open round forms, a tall lowercase and tightly joined word texture. If unavailable, use **Inter**. Use weight 300 and retain -0.05em tracking; fit line breaks to the available width. Font stack: "SCTO", "Inter", "Noto Sans SC", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| editorial | SCTO | 300 | 47.5px | 1.035 | -0.05em | Full-width introductory and explanatory paragraphs, along with equally weighted sentence-case section labels. |
| title | SCTO | 300 | 47.5px | 1.035 | -0.05em | Product titles and metadata. Deliberately identical in scale and weight to editorial prose; position establishes hierarchy. |
| text-action | SCTO | 300 | 47.5px | 1.035 | -0.05em | Related-work index links and direct-contact destinations, retaining the same scale as prose rather than forming a smaller UI tier. |

**Notes:**

- Keep the same light recipe through the whole editorial hierarchy; section headings are ordinary sentence-case text rather than bold display inserts.
- Long paragraphs span nearly the entire viewport. Narrow columns occur in directory-like information sections, not as the default body measure.
- The monumental wordmark is a fitted graphic, not a second live-text heading scale. Preserve its thin strokes and near-full-width silhouette.

## Layout

**Density:** Airy between narrative chapters and concentrated within image runs; paragraph blocks are large in scale but tightly led.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Gap between media panels and adjacent media rows. |
| 16.2px | Editorial side inset for text, metadata and indexes; visually 16.2px. |
| 20px | Header top padding and ordinary wordmark side inset. |
| 49.2px | One editorial line of separation between prose and media, or between paragraph blocks. |
| 98.4px | Two editorial lines for larger chapter breaks and the research-gallery lead-in. |
| 147.6px | Three editorial lines of breathing space above the closing wordmark. |

### Containers and grids

- **editorial field**: side padding 16.2px. Fluid, almost full-window text with no capped central reading container. At 1440px the text field is approximately 1408px wide.
- **media grid**: 12 columns · gap 10px · side padding 10px. Fluid underlying grid; six-column images form 705px halves, four-column images form 467px thirds and eight-column images form 943px studies at 1440px. Keep some deliberate unoccupied columns beside genuine media.
- **information pair** (only for company or capability directory pages): 2 columns · gap 30px · side padding 16.2px. Equal approximately 689px columns for lists beside longer descriptions.
- **research masonry** (only for research and inspiration collections): 4 columns · gap 10px · side padding 10px. Approximately 348px-wide image columns with independent vertical stacking and natural aspect ratios.

## Corner radius

| Element | Radius |
| --- | --- |
| media and actions | 0px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** All editorial pages and their closing regions.

**CSS:** `background: #f9f9f9; color: #080807`

**Observed:** One uninterrupted matte field; media edges and whitespace divide content instead of panel borders.

**Transfer:** Use the same continuous ground behind prose, navigation and the closing signature.

#### Image plane · level 0

**Use:** Photographs, renders and video within the editorial grid.

**CSS:** `border-radius: 0px; box-shadow: none; overflow: hidden`

**Observed:** Artwork is rectangular and flush to its allocated grid area. Ground colors belong to the artwork; there is no independent card chrome.

**Transfer:** Export the complete object and its backing as one composed image, rather than laying a cutout on a generic UI card.

#### Dark study plane · level 0

**Use:** Structural renders and fine-line technical studies.

**CSS:** `background: #161616; border-radius: 0px`

**Observed:** Pale components float in a dark rectangular image with large negative space; the surrounding page remains off-white.

**Transfer:** Stage structural or internal detail with restrained edge lighting, not neon accents.

#### Drawing plane · level 0

**Use:** Explanatory image panels.

**CSS:** `background: #e0e0e0; border-radius: 0px`

**Observed:** Fine grey linework and compact embedded labels sit on a flat pale ground.

**Transfer:** Keep technical explanations diagrammatic and visually subordinate to the object studies.

## Components

### Editorial header

**Use:** Name the product or project with record-like supporting information.

**CSS:** `padding: 20px 16.2px; color: #080807`

**Text style:** `title` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

**Observed:** Title occupies the left of the first line, a short reference identifier anchors the right, and category metadata runs beneath the title. The title persists over subsequent media with difference blending, while the other metadata scrolls away.

**Transfer:** Use a meaningful product descriptor or release reference on the right; do not invent technical codes just for decoration.

### Narrative paragraph

**Use:** Introduce a brief, explain a design decision or connect visual chapters.

**CSS:** `color: #080807; margin: 0px; font-weight: 300; line-height: 1.035; letter-spacing: -0.05em`

**Text style:** `editorial` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

**Observed:** A broad paragraph uses the same type as the header and wraps into roughly two to five lines. It stands alone rather than sharing a block with an eyebrow and separate oversized slogan.

**Transfer:** Give one substantive idea to each paragraph and let subsequent imagery show its consequences.

### Paired media row

**Use:** Show complementary aspects of the product.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 10px; margin-top: 49.2px`

**Observed:** Two six-column media items align at the top. Images can have different heights, leaving visible canvas under the shorter one; later image-only rows use a 10px top separation.

**Transfer:** Pair a finished view with context, process or detail, not two interchangeable beauty shots.

### Centered documentary figure

**Use:** Pause the media sequence with a smaller human-scale or process image.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 10px; margin-top: 10px`

**Observed:** A portrait fills only the central four columns, approximately 467px wide. Empty flanking columns frame a real photograph of construction, scale or use.

**Transfer:** Use a workshop, user or prototype photograph as a small physical counterpoint to the larger renders.

### Index text link

**Use:** Offer related projects or further product stories at the end.

**CSS:** `position: relative; color: #080807; transition: color 0.2s cubic-bezier(0.215, 0.61, 0.355, 1)`

**Text style:** `text-action` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

**Observed:** Links stack as single typographic lines aligned to the left without rules, containers or icons. The current entry is grey while the remaining entries stay near-black.

**Transfer:** Name the destination plainly; use a small relevant collection rather than filling the closing region with unrelated links.

### Monumental signature

**Use:** Provide the recurring typographic closing device.

**CSS:** `position: relative; padding-top: 147.6px`

**Observed:** A near-full-width SVG wordmark follows the content. Its enclosing logo clips overflow and has 20px bottom padding; the graphic is shifted downward by 17%, allowing its bottom to meet or slightly exceed the lower edge.

**Transfer:** Fit the new identity as one thin-stroked vector line. For a short name, increase letter size until the line has comparable width instead of inserting unrelated symbols.

### Contact text link

**Only for:** contact and company information pages

**Use:** Make direct contact and social destinations part of the text block.

**CSS:** `color: #080807`

**Text style:** `text-action` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

**Observed:** The email occupies its own line; address and social references follow. Credit lines appear after a paragraph-sized break. Links have the same visual scale as surrounding prose.

**Transfer:** Replace a button-based contact panel with a readable contact destination and concise practical details.

### Masonry image item

**Only for:** research and inspiration collections

**Use:** Mix reference material, experiments and working imagery.

**CSS:** `position: absolute; margin-bottom: 10px`

**Observed:** Four independently packed desktop columns preserve varied image heights. Images have no permanent caption bars or elevated card surfaces.

**Transfer:** Preserve aspect ratios and juxtapose sketches, tools, material studies and finished objects instead of normalizing every item to a square.

## Imagery and graphics

### Atmospheric object studies

**Use:** Primary visual proof in openings and major product chapters.

**Observed:** Pale industrial objects are framed close against cloudy blue-grey skies, with occasional lavender reflections and dark undersides. Some compositions show the full form; others cut tightly into an edge or joint. Half-width portrait panels dominate the page more than text does.

**Transfer:** Photograph or render the new object with diffuse daylight, cool surroundings and restrained saturation. For a digital product, use a clean screen presentation paired with a physical or contextual photograph; the minimum is one carefully lit real image and one close detail.

### Structural and process studies

**Use:** Explain how the product was conceived and made.

**Observed:** Exploded structures, translucent shells, faint CAD outlines on black, modular line diagrams on pale grey, notebook sketches and monochrome factory photographs interrupt the polished renders. Single centered portraits add people or recognizable scale.

**Transfer:** Show genuine construction or workflow alongside finished work. A photographed working sketch and an original simplified assembly diagram are acceptable substitutes for high-end CGI.

### Monumental wordmark artwork

**Use:** The signature graphic repeated at the page ending.

**Observed:** Thin black grotesk lettering spreads across almost the full page width, approximately 1400px by 165px, without a badge or background panel. The bottom is deliberately close to the clipping edge.

**Transfer:** Use the new product's identity in the same expansive typographic role.

**Build:** Create a tightly fitted SVG viewBox around a single-line light grotesk name, convert lettering to paths if possible, and scale to the content width. Use the ink color, retain natural letter proportions and trim internal SVG whitespace. Put it in an overflow-hidden wrapper with 20px bottom padding and translate the graphic down by 17%.

### Research contact sheet

**Only for:** research and inspiration collections

**Use:** Present creative breadth without a conventional portfolio-card taxonomy.

**Observed:** A four-column mosaic mixes product renders, everyday photographs, pencil drawings, graphic references and occasional bright blue, yellow or pink objects. The color is more varied than the principal product stories but remains confined to the images.

**Transfer:** Collect original or licensed references with a shared interest in form and material; keep varied ratios and no decorative overlays.

### Icons

**Observed:** The editorial interface is effectively icon-free. A text heart formed as <3 serves as a research-page marker; no recurring pictogram or button-arrow system appears.

**Transfer:** Use words and typographic punctuation instead of importing a general-purpose icon set.

## Section recipes

How recurring sections are built.

### First screen: Editorial product opening

**Observed:** The Canvas is the back layer. Editorial header occupies roughly the first 138px: title upper left, identifier upper right and metadata directly below. All live text uses the editorial recipe at 47.5px. A full-width introductory paragraph begins after one line of separation, wraps into three lines over about 148px and is followed by another line of space. Paired media row begins about 384px down: two 705px-wide portrait studies with a 10px gutter, one cool atmospheric close view and one monochrome contextual video. Within the first 900px the title, metadata, complete introduction and upper 516px of both images are visible; the media continues below the fold. No separate conversion button or support-caption tier competes with the images. The persistent title is the topmost layer when the page scrolls.

**Transfer:** For a new landing page use the product name, compact factual context and one clear paragraph explaining the task or promise. Pair an authentic full-product view with a contextual or process view; when no custom render exists, two well-composed photographs or a clean interface view plus a working-process image provide the same visual force. Company pages open with a sparse name-and-section header and long prose; research collections open with a short personal introduction above masonry.

**Avoid:** Do not turn this into a centered slogan above a tiny floating product, add a colored hero panel, or insert a pill-button CTA row.

**Text style:** `title` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

### Reasoning between image chapters

**Observed:** Narrative paragraph spans approximately 1408px with 16.2px editorial side insets. One line of vertical space, 49.2px, separates prose from the next media chapter; adjacent image-only rows return to 10px spacing.

**Transfer:** Use short, substantive explanations of the reason behind the next visual evidence. A section heading can use the same type recipe without adding a second scale.

**Text style:** `editorial` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

### Image argument with scale changes

**Observed:** Paired media row alternates with full-width 1420px studies, centered 943px studies and Centered documentary figure. Unequal image heights and deliberately unoccupied grid columns make the sequence feel curated rather than tiled.

**Transfer:** Move between finished form, construction, context and human-scale evidence. Choose the frame width for the image's narrative importance, not for a fixed card count.

### Closing index and signature

**Observed:** The continuous Canvas carries a left-aligned stack of Index text links at the editorial line height. The current entry is grey. Monumental signature follows after 147.6px of top space. Company-information endings instead place direct contact and credits above the same signature; research endings pass directly from imagery to the signature.

**Transfer:** End with relevant onward destinations or direct contact and the expansive identity treatment. The signature device is retained regardless of where else typographic emphasis appears.

**Text style:** `editorial` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

### Company information pair

**Only for:** company or capability directory pages

**Observed:** Two approximately 689px columns with a 30px gap place a plain list under a sentence-case section label on the left and three paragraph-like service descriptions under an equally weighted label on the right. Section labels and descriptions share the editorial recipe.

**Transfer:** Pair credible names or concise facts with detailed capabilities; retain typographic equality rather than introducing logo badges.

**Text style:** `editorial` — SCTO 300 · 47.5px/1.035 · tracking -0.05em

### Research gallery

**Only for:** research and inspiration collections

**Observed:** A three-line introductory paragraph precedes the four-column research masonry with a 98.4px break. A small persistent name overlays the scrolling imagery. The irregular bottom edge gives way to the Monumental signature.

**Transfer:** Use a first-person curatorial introduction and a varied visual collection rather than a commercial benefit grid.

## Page flow

**Storyline:** identity and brief → visual proposition → reasoning and process → context and scale → onward exploration → typographic signature

### Default product or project landing page: make the work itself the proof

1. **Identity and promise** — Record-like title and metadata above a full-width brief, followed by paired product media.
2. **Design reasoning** — A paragraph explains a constraint or decision, then a large structural image and complementary detail studies make it visible.
3. **Process proof** — Alternating renders, drawings, workshop photographs and smaller centered figures connect visual refinement to practical work.
4. **Capability and context** — Use imagery and concise paragraphs to demonstrate real-world scale, extensibility and use.
5. **Onward exploration** — A text-only related-work index, followed by the monumental wordmark.

**Transfer:** Borrow the changes of scale and alternation of statement and visual proof, not the original project's length or subject.

### Portfolio overview: establish a point of view and invite exploration

1. **Positioning** — An expansive introductory statement establishes the office's approach.
2. **Visual breadth** — A long sequence of paired and full-width image and video work replaces conventional feature cards.
3. **Identity close** — A spacious ending contains a near-full-width wordmark.

**Transfer:** Use an introduction and a curated body of substantive work, with the signature as a final visual anchor.

### Company introduction: explain approach, credibility and how to connect

1. **Identity** — A sparse header places the name left and the section label near the center.
2. **Positioning** — Three full-width paragraphs explain the practice and its motivations.
3. **Credibility and capabilities** — Two columns pair a selected-name list with detailed service descriptions.
4. **Direct contact** — Practical contact and social information, a separate credits passage and the monumental signature.

**Transfer:** Use prose and explicit facts to communicate the organization; keep contact as readable text instead of a promotional panel.

### Research collection: reveal creative curiosity through an image-led stream

1. **Curatorial framing** — Sparse header with a text-heart marker and a personal three-line introduction.
2. **Exploration** — Four-column masonry mixes references and experiments without uniform card captions.
3. **Identity close** — The irregular image sequence ends with whitespace and the monumental signature.

**Transfer:** Let a varied, tightly spaced visual collection carry the story and keep introductory copy candid.

## Writing

Measured, intellectually engaged and materially specific. Confidence comes from explaining the brief, constraints and execution rather than from short promotional superlatives.

**Do not copy:** Do not reuse the original brand name, wordmark paths, client names, contact details, project identifiers, dates, commissions, performance or sustainability claims, credits, or image assets. Source quotations are voice references only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person descriptions of the practice, shifting to 'we' for project decisions and curatorial interests; direct second-person selling is rare.
- **Rhythm:** Names are concise and often comma-separated; paragraphs use complete, sometimes long sentences. Brief declarative transitions introduce practical themes. No exclamation-mark sales rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product title | Organization or collection name followed by a comma and the object or project category. | 3–7 words | “Envision, Wind Turbines” |
| Narrative transition | State a real constraint in a complete sentence instead of a benefit slogan. | 15–45 words | “The studio had to address rational topics such as logistics, supply chain, and manufacturing.” |
| Section label | Plain descriptive noun phrase in sentence or title case. | 1–3 words | “Selected Clients”<br>“Services” |
| Direct action | Expose the destination as ordinary text, not an urgent command. | One short destination or address | “Contact@unknown-untitled.com”<br>“Instagram” |
| Curatorial introduction | Personal, parallel phrases describe what the collection contains and why it matters. | Two complete sentences | “What we love doing, what we love seeing, and what we are pleased to share.” |

**Words and phrasing to use:** material; form; experimentation; development; research; scalable; modular; manufacturing; approach; experiences

**Avoid:** game-changing; unlock your potential; supercharge; effortless magic; limited-time offer

**Rules:**

- State the design task before claiming its success.
- Explain how a particular decision changes construction, use or experience.
- Let concrete nouns carry meaning; avoid stacking abstract adjectives.
- Use named destinations for links and factual descriptors for metadata.
- Keep claims proportional to what the accompanying visuals and verifiable facts can support.

## Do's and Don'ts

### Do

- Use the shared 47.5px, weight-300 editorial recipe for both narrative text and short labels.
- Keep text approximately 16.2px from the viewport edge while media sits 10px in.
- Use a 12-column grid with 10px gutters to align half-, third- and two-thirds-width studies.
- Let unequal image heights reveal the continuous off-white canvas.
- Separate prose chapters by about one 49.2px line and image-only rows by 10px.
- Retain a full-width fitted wordmark graphic as a signature device, around 165px high at 1440px for a comparably long name.
- Keep stronger hues inside image content; maintain near-black text on the off-white editorial field.
- Use direct text links for primary onward navigation.

### Don't

- Do not replace the light editorial face with bold weight-700 headings and small 16px body copy.
- Do not turn image planes into rounded 16px cards with drop shadows.
- Do not impose a 1200px maximum-width container on the desktop media sequence.
- Do not shrink contact information or section labels into a tiny utility-text tier.
- Do not apply the grey current-item color to whole explanatory paragraphs.
- Do not color the whole page with the blue-grey or charcoal media backing.
- Do not standardize every product image to a square or equal-height thumbnail.
- Do not add rating stars, colorful chips or an icon beside every navigation item.

## Motion and responsive

### Motion

**Observed:**

- Related index links declare color 0.2s cubic-bezier(0.215, 0.61, 0.355, 1).
- The product title remains visible while the page scrolls and uses difference blending over changing imagery.
- Video appears as ordinary grid media alongside still images.

**Transfer:**

- Retain the restrained color transition on index links and the persistent lightweight title over the long media story.
- Treat moving imagery as part of the image argument rather than surrounding it with a separate player card.

**Unknown:**

- Hover destination colors and focus-visible styling are not established.
- Video playback rules and scroll-animation timings are not established.

### Responsive

**Observed:**

- A 720px width breakpoint is declared.

**Transfer:**

- On narrower screens, preserve the distinction between text and media insets and keep the wordmark fitted to width.
- Reflow paired studies and directory columns before their content becomes cramped; retain differing image aspect ratios. This is adaptation guidance, not a fixed column-count rule.

**Unknown:**

- Exact narrow-screen font sizes, inset formulas, column counts and persistent-header behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
