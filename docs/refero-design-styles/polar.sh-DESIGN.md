# Polar — monochrome kinetic instruments

## Overview

A near-black, almost entirely grayscale identity that makes technical products feel tangible without turning them into spectacle. Regular-weight grotesk text, compact pill actions and spare interface demonstrations sit beside rippled silver materials and fine geometric drawings. The density alternates between spacious editorial chapters and closely packed product panels, making it well suited to developer tools and infrastructure products.

### Essentials

- Headlines speak in paired tones rather than oversized slogans: 36px/1.25 regular grotesk in white followed immediately by an equally sized #858585 line; chapter headings use 30px/1.375.
- The opening leaves air above a tangible product: a left-aligned introduction and 48px pill action precede a 3:1 product-stage-and-caption split, with the stage starting 431px down the desktop page.
- Actions are small white lozenges in a dark field: 48px tall, 20px horizontal padding, 14px/20px weight 550 labels and a 16px trailing chevron; compact actions are 40px tall.
- Color is withheld from the marketing canvas: #090909 dominates, #111111 raises cards, white and #858585 divide meaning. Light areas belong to grayscale media backdrops and small white actions, not bright section bands.
- Demonstrations feel like instruments resting on rippled silver: 7.6px outer corners, 48px staging inset, a 16px dark inner shell and 0px 16px 40px -12px black shadow. Recreate one real workflow in this treatment if no polished product media exists.
- Fine-line geometry and a radial word sculpture supply the personality: white circles, spokes and hairline diagrams accompany capabilities; a centered 896px square field of repeated, rotated letters expands around a hollow center. Use the new product's letters, with static SVG as the minimum version.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-foreground` | text, action, accent | Headlines, main labels, line artwork and primary button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft white | `#d8d8d8` | `--color-tile-label` | text | Labels beneath technical diagrams. |
| Corner marking | `#8f8f8f` | `--color-corner` | border | Brighter corner brackets on diagram tiles. |
| Editorial gray | `#858585` | `--color-muted` | text | Second headline lines, supporting paragraphs and secondary navigation. |
| Technical index gray | `#7b7b7b` | `--color-index` | text | Small monospace indices on technical-diagram tiles. |
| Diagram tile edge | `#2a2a2a` | `--color-diagram-edge` | border | Square technical-diagram tile outlines. |
| Section rule | `#212121` | `--color-rule` | border, surface, action | Chapter dividers and secondary button fill. |
| Inset edge | `#181818` | `--color-frame-edge` | border, surface | Very dark outlines on media stages and nested application frames. |
| Raised charcoal | `#111111` | `--color-card` | surface, background | Cards, geometry stages and announcement band. |
| Near-black canvas | `#090909` | `--color-canvas` | background, surface | Continuous marketing background and inset application shells. |
| Action black | `#000000` | `--color-action-ink` | text | Black labels and chevrons on white primary actions. |

## Typography

- **PP Neue Montreal** — All marketing text, headings, navigation and actions. Unembellished contemporary grotesk; regular display weights and slightly firmer small labels. OpenType features: "liga" 0, "ss07", "ss08". If unavailable, use **Inter**. Use 400 for headings, 450 for body and 550 for actions; preserve relaxed display tracking. Font stack: "PP Neue Montreal", Inter, sans-serif.
- **GeistMono** — Technical indices, commands and developer-facing labels. Small evenly spaced technical text without colorful syntax decoration. Font stack: "GeistMono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing | PP Neue Montreal | 400 | 48px | 1.25 | normal, features "liga" 0, "ss07", "ss08" | Two centered lines beneath the radial letter sculpture. |
| opening | PP Neue Montreal | 400 | 36px | 1.25 | normal, features "liga" 0, "ss07", "ss08" | Opening headline and its gray continuation. |
| chapter | PP Neue Montreal | 400 | 30px | 1.375 | normal, features "liga" 0, "ss07", "ss08" | Chapter labels, numbers, section headlines and their equally sized continuation. |
| stage-caption | PP Neue Montreal | 400 | 30px | 1.25 | normal | Compact gray continuation alongside the opening product stage. |
| lead | PP Neue Montreal | 400 | 24px | 1.375 | 0.01em, features "liga" 0, "ss07", "ss08" | Editorial support beneath chapter headlines and short centered feature-page closing lines. |
| subheading | PP Neue Montreal | 400 | 20px | 1.375 | 0.012em, features "liga" 0, "ss07", "ss08" | Card titles, explanatory feature-page paragraphs and list-row text. |
| tile-label | PP Neue Montreal | 500 | 17px | 1.5 | -0.01em | Technical-diagram tile labels. |
| body | PP Neue Montreal | 450 | 16px | 1.5 | 0.015em | Card descriptions, navigation and footer links. |
| action | PP Neue Montreal | 550 | 14px | 20px | 0.01em | Primary, secondary and ghost button labels. |
| caption | PP Neue Montreal | 450 | 14px | 1.5 | 0.017em | Announcement text and small supporting attributions. |
| tile-index | GeistMono | 450 | 13px | 1.5 | 0.0185em | Two-digit technical-diagram indices. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| developer-facing content | code | GeistMono | 450 | 14px | 1.5 | 0.017em | Code examples, command names and endpoint labels. |
| product demonstrations | terminal | GeistMono | 450 | 13px | 24px | 0.0185em | Terminal transcripts and prompt demonstrations. |

**Notes:**

- Hierarchy depends on color and composition more than weight. Keep opening and chapter headings regular, including their gray continuation lines.
- Chapter labels are full-size sentence-case headings, not tiny uppercase eyebrows. Preserve the 30px shared baseline across the two halves.
- Use the display alternates on headings and editorial leads; body text and buttons retain their own recipes rather than inheriting those settings.
- Only the small diagram tile labels tighten tracking. Do not apply negative tracking across the entire site.

## Layout

**Density:** Airy between editorial chapters, compact within nested interfaces and comparison groups.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight support-line gaps and clustered testimonial or pricing gutters. |
| 8px | Icon-to-label spacing. |
| 12px | Related action gaps and footer heading-to-link spacing. |
| 16px | Default split-column and four-column card gutters. |
| 20px | Button horizontal padding and diagram tile inset. |
| 24px | Card interiors, navigation vertical padding and list-row vertical padding. |
| 32px | Three-column illustration-card gutters and chapter outer margins. |
| 48px | Hero-to-action gap, stage inset and action-to-adjacent-content spacing. |
| 64px | Chapter headline pair to editorial support. |
| 96px | Major chapter vertical padding and copy-to-demo separation. |

### Containers and grids

- **Main container**: max width 1280px · side padding 48px. Centered desktop content; at 1440px the bounded content has 80px side margins. Outer page padding is a minimum rather than extra padding inside the full-width container.
- **Editorial halves**: 2 columns · gap 16px. Equal 632px halves: label or title on the left, narrative on the right.
- **Opening stage**: 2 columns · gap 48px. A 3fr/1fr split: 924px product backdrop beside a 308px explanatory rail.
- **Illustration triptych**: 3 columns · gap 32px. Three 405px square geometry stages with captions outside and beneath.
- **Capability grid**: 4 columns · gap 16px. Four 308px capability cards or a multi-row directory.
- **Comparison cluster**: 4 columns · gap 4px. Closely joined pricing panels inside one application shell; testimonials use the same tight gutter across three columns.
- **Diagram grid**: 5 columns · gap 16px. Square technical tiles, 243px wide at the desktop content width.
- **Sculpture container**: max width 896px. Centered square letter artwork above the closing action.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions | 9999px (pill) |
| Content cards | 12px |
| Media stages | 7.6px |
| Application shells | 16px |
| Portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Application lift | `0px 16px 40px -12px rgba(0,0,0,0.75)` | Lift the dark demonstration shell above its silver backdrop; not ordinary text cards. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #090909; color: #ffffff`

#### Raised card · level 1

**Use:** Testimonials, capability cards and pricing panels.

**CSS:** `background: #111111; border-radius: 12px; box-shadow: none`

**Observed:** Only a small tonal lift separates these panels from the canvas.

**Transfer:** Keep elevation tonal rather than using bright outlines or large drop shadows.

#### Ruled chapter · level 0

**Use:** Separate major editorial chapters.

**CSS:** `border-top: 1px solid #212121; padding: 96px 0px`

**Observed:** The rule spans the content container, with chapter material arranged below it.

**Transfer:** Use a full-width hairline to organize long pages without alternating background colors.

#### Silver media stage · level 1

**Use:** Frame product demonstrations.

**CSS:** `border: 1px solid #181818; border-radius: 7.6px; padding: 48px; overflow: hidden; position: relative`

**Observed:** A grayscale rippled material fills the rectangle behind the inset product. A black overlay darkens the opening stage by 20%; larger demonstrations often use 40%.

**Transfer:** Use the Rippled silver material recipe as the background, then place the Application shell above it.

#### Application shell · level 2

**Use:** A dark, nested product window inside a media stage.

**CSS:** `background: #090909; border: 1px solid #181818; border-radius: 16px; padding: 4px; box-shadow: 0px 16px 40px -12px rgba(0,0,0,0.75)`

**Observed:** A compact top strip labels the demonstration; content sits in charcoal subpanels.

**Transfer:** Show one short, believable workflow rather than an entire miniature dashboard.

#### Geometry stage · level 1

**Use:** Back fine-line drawings above capability descriptions.

**CSS:** `background: #111111; border: 1px solid #181818; border-radius: 7.6px; padding: 48px; aspect-ratio: 1 / 1; overflow: hidden`

**Observed:** A 307px drawing sits within a 405px stage; captions remain on the bare page below.

**Transfer:** Keep the drawing sparse and centered, surrounded by substantial empty space.

## Components

### Sticky navigation

**Use:** Persistent orientation at the top of marketing pages.

**CSS:** `position: sticky; top: 0px; z-index: 30; background: #090909`

**Text style:** `body` — PP Neue Montreal 450 · 16px/1.5 · tracking 0.015em

**Observed:** A 45px charcoal announcement bar sits above an 88px navigation row. Inside a 1280px container, a 28px symbol leads links separated by 16px; sign-in and a compact white action align right. The row has 24px vertical and 48px outer horizontal padding.

**Transfer:** Use a compact symbol rather than a large wordmark in the navigation.

### Announcement strip

**Use:** One concise product update above navigation.

**CSS:** `background: #111111; display: flex; align-items: center; justify-content: center; gap: 8px; padding: 12px 24px`

**Text style:** `caption` — PP Neue Montreal 450 · 14px/1.5 · tracking 0.017em

**Observed:** Full-width, with a small arrow after the centered sentence.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; padding: 16px 20px; height: 48px; display: inline-flex; align-items: center; justify-content: center; gap: 8px; box-sizing: border-box`

**Text style:** `action` — PP Neue Montreal 550 · 14px/20px · tracking 0.01em

**Observed:** A trailing chevron follows the label. The compact navigation and mid-page variant is 40px tall with 12px 20px padding. The visible label is black.

**States:** Declared: hover background-color #fff and opacity 0.85; focus-visible outline-style none with zero box-shadow.

**Transfer:** Keep the pill content-sized; retain a clear visible focus indicator in an accessible implementation.

### Secondary button

**Use:** Documentation or sales beside the primary conversion.

**CSS:** `background: #212121; color: #ffffff; border: 1px solid rgba(255,255,255,0.05); border-radius: 9999px; padding: 16px 20px; height: 48px; box-sizing: border-box`

**Text style:** `action` — PP Neue Montreal 550 · 14px/20px · tracking 0.01em

**Observed:** Placed 12px beside a primary button. Compact sales actions use 40px height and 12px 20px padding.

**States:** Declared: hover background-color #292929; focus-visible outline-style none with zero box-shadow.

### Ghost button

**Use:** Sign-in and tertiary actions.

**CSS:** `background: transparent; color: #ffffff; border-radius: 9999px; padding: 12px 20px; height: 40px; box-sizing: border-box`

**Text style:** `action` — PP Neue Montreal 550 · 14px/20px · tracking 0.01em

**Observed:** Shares the action label recipe but no resting fill.

**States:** Declared: hover background-color #212121; focus-visible outline-style none with zero box-shadow.

### Diagram tile

**Use:** A compact catalog of technical capabilities.

**CSS:** `border: 1px solid #2a2a2a; padding: 20px; aspect-ratio: 1 / 1; display: flex; flex-direction: column; justify-content: space-between; position: relative`

**Text style:** `tile-label` — PP Neue Montreal 500 · 17px/1.5 · tracking -0.01em

**Observed:** Two-digit mono index at top, centered fine-line SVG, label at bottom. Four 12px corner brackets in #8f8f8f sit across the faint square outline. The drawing occupies about 62% of the inner width.

**Transfer:** Translate the capability into one small diagram: branching nodes, aligned event rows, concentric rings or converging paths.

### Testimonial card

**Use:** Compact proof below a larger editorial quote.

**CSS:** `background: #111111; border-radius: 12px; display: flex; flex-direction: column; height: 100%`

**Text style:** `subheading` — PP Neue Montreal 400 · 20px/1.375 · tracking 0.012em

**Observed:** Three equally tall panels sit across the page with 4px gutters. The quote sits above a bottom-aligned attribution with a 40px circular portrait, white name and gray affiliation.

**Transfer:** Let genuine quote length determine height; align attribution baselines.

### Numbered responsibility row

**Use:** Explain stages, responsibilities or operating principles.

**CSS:** `border-top: 1px solid #212121; padding: 24px 0px`

**Text style:** `subheading` — PP Neue Montreal 400 · 20px/1.375 · tracking 0.012em

**Observed:** The left half combines a gray number with a white title; the right half contains the gray explanation. Feature pages use 20px text; the culture variant uses 24px lead text.

**Transfer:** Use numbering for actual sequence or a short ordered set, not as decorative bullets.

### Footer text action

**Use:** A final low-pressure conversion near copyright.

**CSS:** `color: #ffffff; border-bottom: 1px solid #ffffff; padding-bottom: 2px; width: fit-content`

**Text style:** `body` — PP Neue Montreal 450 · 16px/1.5 · tracking 0.015em

**Observed:** A 16px northeast arrow sits 8px after the label. It anchors the lower left rather than repeating the pill.

### Footer directory

**Use:** Shared final navigation and trust utilities.

**CSS:** `border-top: 1px solid #212121; padding: 96px 0px; max-width: 1280px`

**Text style:** `body` — PP Neue Montreal 450 · 16px/1.5 · tracking 0.015em

**Observed:** A two-half layout leaves the left for the wordmark above, underlined action and copyright below. The right half is a two-column directory with 16px column and 48px row gaps. Gray group labels precede white links, with 12px heading separation and 4px between links.

**Transfer:** Maintain the deliberately empty left half and organize links into a few compact groups.

### Pricing panel

**Only for:** pricing comparisons

**Use:** Compare a small number of packages.

**CSS:** `padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `body` — PP Neue Montreal 450 · 16px/1.5 · tracking 0.015em

**Observed:** Placed on Raised card within a shared Application shell. Plan title uses subheading, price uses chapter, and the billing interval is much smaller gray text. A short fee row and bottom-aligned checked benefits follow. No brightly highlighted recommended plan.

**Transfer:** Keep prices white and comparable, with identical panel structure and restrained checkmarks.

## Imagery and graphics

### Rippled silver material

**Use:** Signature backing for key product stages and occasional brand-scale art.

**Observed:** Grainy grayscale light wraps around an abstract dark curved mass. Closely spaced wavy ridges bend through soft white and silver highlights; the center is dark enough to carry a black interface. The effect is tactile and softly out of focus, not metallic chrome lettering.

**Transfer:** Keep this material in at least one prominent product stage. The minimum equivalent is a grainy monochrome wave field with a soft dark central mass and curved narrow light ridges.

**Build:** Use an SVG at the stage aspect ratio: a pale gray base, one broad dark curved shape blurred about 32px, and 35–60 parallel curved paths spaced roughly 8–14px apart. Stroke paths with white at 0.25–0.5 alpha, blur 2–4px, and mask them into broad diagonal light lobes. Add low-opacity feTurbulence grain over the whole surface. Position a dark oval slightly off center and let the ridges bend around it. Apply a black 0.2 or 0.4 alpha overlay beneath the product shell; match the soft light rather than exact gradient stops.

### Fine-line geometric instruments

**Use:** Capability illustrations and feature-detail opening art.

**Observed:** White spokes, broken radial strokes, nested circles and connecting arcs float on charcoal squares. Drawings are centered and thin, with large untouched margins. Detail openings use concentric circles and one small orbiting white point, in a 632px-wide charcoal area.

**Transfer:** Build a visual metaphor for the new capability from circles, repeated line segments and node paths, without a literal mascot or multicolor illustration.

**Build:** In a square SVG use 1px white strokes, no fill, and round-ended segments where needed. Center a ring of 16–24 radial segments around a hollow center, varying length and opacity; alternatively overlap 3–5 circles with decreasing radii and a common tangent. Add at most one filled white point. Center the SVG inside Geometry stage. A static version must read as a complete illustration.

### Radial letter sculpture

**Use:** Signature large-scale brand art with the closing conversion.

**Observed:** Repeated individual letters form concentric arcs and spoke-like rays around a hollow central opening. Each letter rotates along its ring or ray; spacing expands toward the edges. White glyphs sit directly on near-black, in an 896px square field.

**Transfer:** Include this device using the new product name or a short relevant word. A static SVG composed of letter rings is sufficient; keep the empty center, rotational rhythm and fine letter scale.

**Build:** Use an 896px square SVG viewBox. Around its center place roughly 8–12 rings of letters, starting at radius 55px and extending to about 420px. Repeat a short word with wide spacing and angular offsets so letters also align into rays. Set glyphs near 14–16px in white regular sans; rotate each glyph along the circular direction. Leave a small unpainted center and avoid drawing visible circle outlines.

### Product demonstrations

**Use:** Make an abstract service concrete in the opening and capability chapters.

**Observed:** Dark UI windows show only the relevant workflow, with compact top labels, white primary information, gray metadata, fine separators and minimal monochrome charts. Large dashboard excerpts are mixed with small terminal-like cards. These demonstrations dominate their sections more than the accompanying text.

**Transfer:** Construct a truthful simplified interface for the new product and place it on Silver media stage. If there is no UI, use a credible input-to-output diagram in the same Application shell rather than unrelated stock imagery.

### Documentary monochrome photography

**Only for:** company and culture pages

**Use:** Humanize a technical organization and show design in the physical world.

**Observed:** A candid black-and-white street conversation fills a 632px by 421px rectangle beside the opening copy. Later, a grayscale architectural billboard photograph pairs with square letter art. Images have natural contrast and simple rectangular framing.

**Transfer:** Use candid real people or a real product in its environment; convert to restrained monochrome and preserve the architectural or street context.

### Icons

**Observed:** Utility arrows and chevrons are generally 16px. Outline utility icons use 2px round strokes at 12px, 14px or 16px. Solid symbols remain compact; the navigation symbol is 28px. Colors follow white or the surrounding gray.

**Transfer:** Use one consistent simple icon family. Distinguish small filled directional arrows from the much finer custom geometry artwork.

## Section recipes

How recurring sections are built.

### First screen: Introduction above product stage

**Observed:** A near-black canvas supports the 133px two-level Sticky navigation. Within the 1280px container the introduction begins 48px below it and occupies only the left half: a 36px white headline immediately followed by a gray line of the same size. A Primary button sits 48px below the pair. After 64px of air, a 3:1 Opening stage begins: a 924px-wide Silver media stage holds a dark dashboard, while the 308px right rail has a white chapter-size statement, a gray stage-caption continuation and a short list beneath. Back to front the scene is silver ripples, a darkening layer, then the lifted Application shell. Within the first 900px the headline, support line, action and most of the product object are visible; the lower edge of the stage and subsequent proof fall below the fold.

**Transfer:** For a new product, lead with a short introduction rather than an enormous slogan, then show one useful transformation in a believable interface on the silver stage. Feature-detail pages instead put copy and bottom-aligned actions in the left half beside a charcoal geometry panel. Developer pages use that same half-and-half opening with a framed terminal. Company pages pair a smaller chapter-size introduction and action with monochrome documentary photography.

**Avoid:** Do not center a giant 80px headline over a tiny floating dashboard or fill the introduction's unused right half with decorative badges.

**Text style:** `opening` — PP Neue Montreal 400 · 36px/1.25

### Numbered editorial chapter

**Observed:** Ruled chapter contains Editorial halves. Left: a gray two-digit number adjacent to the white chapter label. Right: a white chapter headline and equally sized gray continuation, then 64px to a 24px gray lead. A full-width Silver media stage follows after 96px.

**Transfer:** Choose one capability and its outcome per chapter; keep the claim and explanation in the right half even when the left is mostly empty.

**Text style:** `chapter` — PP Neue Montreal 400 · 30px/1.375

### Capability illustration triptych

**Observed:** Three Geometry stages sit in Illustration triptych. Each has a fine-line geometric instrument, then a 24px separation to a white 20px title, gray 16px description and plain learn-more arrow link.

**Transfer:** Use the triptych for distinct stages or complementary ways into the product, with captions outside the illustration panels.

### Technical diagram catalog

**Observed:** A standard editorial chapter and compact actions introduce Diagram tile in a five-column desktop grid with 16px gutters. Thin brackets, index numbers and centered SVGs give it the feeling of a technical field guide.

**Transfer:** Use this catalog for a concise set of architecture or workflow concepts. Keep individual drawings equally sparse.

### Testimonial proof

**Observed:** A chapter label sits left and a large white quote with portrait attribution sits right. Below, three Testimonial cards form a nearly joined row with 4px gutters.

**Transfer:** Combine one memorable short quote with a small group of more specific experience reports.

### Sculptural closing call

**Observed:** Ruled chapter centers the 896px Radial letter sculpture. After 48px comes a centered 48px white statement and gray continuation with a 4px gap; another 48px leads to Primary button. The chapter has 96px vertical padding and precedes Footer directory.

**Transfer:** Use the sculpture as a visual exhale before one direct action. On short feature-detail pages, use a compact centered two-line 24px closing statement with a 48px action gap instead of repeating the large sculpture.

**Text style:** `closing` — PP Neue Montreal 400 · 48px/1.25

### Shared footer ending

**Observed:** Footer directory begins under a full-width hairline. The wordmark and low underlined action balance a compact two-by-two link-group arrangement on the right. Copyright and preferences remain subdued. This is the final block across all page types.

**Transfer:** End with navigable structure, not another oversized promotional panel.

### Explanatory split and rows

**Only for:** feature-detail pages

**Observed:** A 30px heading occupies the left half while 20px explanatory paragraphs occupy the right, separated by 96px chapter padding. A four-column row of flat charcoal summary cards follows. Longer coverage sections use Numbered responsibility row across the whole container; narrower reference lists can remain only in the right half.

**Transfer:** Give readers the mental model before enumerating features. Keep the lists editorial, not a dashboard table.

### Restrained pricing comparison

**Only for:** pricing sections

**Observed:** The editorial heading pair and a compact primary/secondary action pair precede a shared Application shell containing four Pricing panels. White 30px prices contrast with subdued fee labels; checked benefits settle near the panel bottoms.

**Transfer:** Compare meaningful package differences without adding a saturated premium-plan banner.

### Company editorial and directory

**Only for:** company and culture pages

**Observed:** Chapter labels and paired headlines use Editorial halves; longer narrative is 24px gray text in the right half. Wide brand artwork provides a visual pause. Numbered operating principles use 24px rows; recruitment uses ruled text links with northeast arrows. A four-column directory of names and subdued affiliations closes the content before Footer directory.

**Transfer:** Replace these topics with the organization's genuine story and people; keep the human content as typographic and monochrome as the product content.

## Page flow

**Storyline:** Introduction → tangible product or mental model → capability chapters → specific proof or practical details → focused action → restrained directory.

### Broad product landing page

1. **Promise** — Small paired-tone introduction and primary action above a dominant staged interface.
2. **Product demonstration** — A large silver-backed dashboard beside a compact explanatory rail.
3. **Social proof** — Editorial quote paired with an understated customer-story link.
4. **Capability chapters** — Numbered split headings, gray explanatory leads and repeated framed demonstrations; geometric triptych and diagram catalog vary the rhythm.
5. **Commercial clarity** — Testimonials, closely joined pricing comparison and a focused offer.
6. **Closing call** — Large radial letter art, centered paired-tone line, single pill action, then shared footer.

**Transfer:** Adapt the number and order of chapters to the new product; preserve the alternation between spare editorial copy and concrete framed proof.

### Explain an abstract service and its responsibilities

1. **Promise** — Two-tone headline and bottom-aligned actions beside a geometric circle study.
2. **Mental model** — Right-aligned opening assertion, then split-column explanation.
3. **Capability summary** — Four flat charcoal cards.
4. **Objection handling** — Numbered full-width rows explain what the provider takes on.
5. **Closing call** — Compact centered white/gray statement and pill before the shared footer.

**Transfer:** Use the rows to clarify boundaries of responsibility for the new service, not just to repeat benefits.

### Teach a technical capability and its implementation model

1. **Promise** — Split opening with paired headline, two actions and circle art.
2. **Mental model** — Explanatory prose in the right half and four summary cards.
3. **Reference detail** — A right-column list of operations followed by numbered strategy rows.
4. **Boundary clarification** — A final split prose section explains what the product deliberately leaves to the user.
5. **Closing call** — Short centered next-step statement, primary action and footer.

**Transfer:** Explain primitives before options, and finish with an honest limitation or integration boundary.

### Turn developer interest into an integration path

1. **Promise** — Half-and-half text and silver-backed terminal with primary and documentation actions.
2. **Wayfinding** — Three square geometric illustrations introduce paths into the tooling.
3. **Implementation chapters** — Numbered editorial chapters combine staged prompts, commands and code with compact capability grids.
4. **Reference breadth** — A four-column endpoint directory demonstrates coverage without a long prose list.
5. **Closing call** — Radial letter sculpture and centered paired-tone invitation, followed by footer.

**Transfer:** Offer a small number of credible integration paths and show working examples in monochrome panels.

### Establish the people, beliefs and credibility behind a technical product

1. **Human introduction** — Small chapter-size copy and hiring action beside candid monochrome photography.
2. **Purpose** — Split mission headline, gray narrative and a wide silver brand artwork.
3. **Operating character** — Numbered principles, design-focused media pair and restrained recruitment links.
4. **Credibility** — Four-column names-and-affiliations directory.
5. **Ending** — Shared footer directly after the people directory, without the large conversion sculpture.

**Transfer:** Use real organizational material while retaining the product site's typographic discipline and grayscale image treatment.

## Writing

Direct, technically literate and calmly assured. Benefits are explained through concrete mechanics and responsibility rather than expansive superlatives.

**Do not copy:** Do not reuse Polar's name, symbols, customer identities, quotes, package names, pricing, market coverage, program offers or performance claims. Replace all demonstrations and letter art with the new product's own truthful content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's work; we for what the provider handles. Name the product when clarifying a concrete action or responsibility.
- **Rhythm:** Headlines are usually short sentence-case phrases; their gray continuation completes or narrows the thought. Support is one compact paragraph, with clipped sentences for process explanations and very little promotional punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the product or state the capability plainly. | 2–8 words | “Meet [Brand]”<br>“Usage-based billing on events” |
| Gray continuation | Specify the audience, mechanism or scope without repeating the headline. | 5–15 words | “Modern billing for AI companies”<br>“Ingest events. Aggregate them into meters. Bill on the result.” |
| Chapter headline | State an outcome, then qualify it in the gray line. | 4–9 words per line | “Know your margin”<br>“for every customer, not just on average” |
| Explanatory support | Describe an input, a transformation and the resulting benefit. | 20–45 words | “Raw events roll up into a live meter for every customer, updated in real time. No batch jobs, no lag.” |
| Primary action | Short verb-led next step. | 2–4 words | “Get Started”<br>“Read the field guide”<br>“Explore the brand” |
| Boundary statement | State clearly what belongs to the product and what remains the reader's decision. | One short paragraph | “One thing [Brand] deliberately does not do is block usage when a customer crosses a quota. That decision belongs in your product, where you know the context.” |

**Words and phrasing to use:** built in; one; every; from … to …; your; recorded; updated; automatically; underneath; in real time

**Avoid:** revolutionary; game-changing; unleash; supercharge; magic; limitless; best-in-class

**Rules:**

- Let the gray continuation add information rather than decorate a slogan.
- Use specific nouns and observable verbs before abstract benefits.
- Explain the mechanism behind claims, especially around automation and ownership.
- Keep technical terms when they help readers decide; explain unfamiliar primitives before listing options.
- Use calm contrasts such as 'not just on average' sparingly to sharpen the outcome.

## Do's and Don'ts

### Do

- Keep display and chapter text at weight 400, with 36px and 30px default sizes.
- Use #858585 for the equal-sized continuation directly beneath a white headline.
- Align chapter narrative to the right 632px half of the desktop container.
- Keep major section insets at 96px and inner card insets at 24px.
- Retain 7.6px stage corners and 16px application-shell corners as distinct nested layers.
- Include rippled grayscale staging and fine-line geometric art in the product narrative.
- Use 4px gutters for tightly grouped proof and comparison panels, but 16px for ordinary capability grids.
- Give the closing letter sculpture breathing room and a single centered action.

### Don't

- Do not turn every title bold or use an oversized condensed display face.
- Do not add saturated gradients, rainbow syntax or bright accent-colored section bands.
- Do not turn chapter labels into 12px uppercase eyebrows; their 30px scale is part of the composition.
- Do not apply the heavy application shadow to ordinary #111111 content cards.
- Do not round technical diagram tiles into soft 24px cards; they are square outlined fields with corner brackets.
- Do not pack all technical explanations into tiny 14px text; detail-page prose is 20px.
- Do not replace the 40px and 48px pills with large rectangular conversion blocks.
- Do not make every section a dense card grid; preserve the bare left half in editorial sections.

## Motion and responsive

### Motion

**Observed:**

- Primary pills declare opacity 0.1s cubic-bezier(.4, 0, .2, 1); secondary and ghost buttons declare color-related transitions of .15s with the same easing.
- The opening product stage declares rise for 0.7s cubic-bezier(0.2,0.8,0.2,1), with 0.15s delay and both fill mode.
- Diagram tile corner borders declare color transitions of 75ms cubic-bezier(.4, 0, .2, 1); tile opacity declares 0.15s.
- Geometric artwork and letter layouts have kinetic character; their exact playback is not specified here.

**Transfer:**

- Keep controls brisk and tonal, not springy or bouncy.
- Ensure static letter sculpture and geometric drawings still make complete compositions; movement should enrich the instruments rather than supply missing content.

**Unknown:**

- Exact artwork rotation, orbit and scroll choreography.
- Whether every declared animation runs in every context.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 640px, 768px, 1024px, 1280px and 1536px.
- The technical-diagram grid declares two columns by default and five at the large breakpoint.

**Transfer:**

- On narrow screens, stack editorial halves in label-then-narrative order and keep the shared left alignment.
- Scale the 896px letter field as one square unit; do not let individual letters spill into the action below.
- Stack staged interfaces and their caption rails; preserve the silver backing and nested-shell hierarchy while reducing the stage inset.
- Keep technical tiles in two columns while preserving their square ratio and fine corner marks.

**Unknown:**

- Exact mobile navigation behavior, mobile type sizes and stage padding values are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
