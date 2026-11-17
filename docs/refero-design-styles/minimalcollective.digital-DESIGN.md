# Minimal Collective — gridded cultural circuitry

## Overview

A graphite editorial environment with the atmosphere of an experimental arts publication. Regular grotesk type, exposed ruled grids and looping geometric diagrams frame richly colored documentary photography and a small metallic object. Sparse compositions alternate with dense reading passages, suiting research-led products, creative platforms and portfolios more than conventional sales funnels. The default is gray with black type; long-form stories use a black-and-white variant.

### Essentials

- The opening is a diagram inhabited by type and an object: a 900px viewport stage, overlapping 450×810px ellipses stepping by 225px, a centered 76.5px regular headline and a 324px metallic emblem.
- The page behaves like a ruled publication rather than a stack of cards: four equal 360px columns at 1440px, 1px foreground rules and 13.5px inner gutters; media can span one, two or three columns.
- Headlines combine declarative and discursive voices: 76.5px/1 section leads with -2.3px tracking, then 49.5px/0.9 story titles with -1px tracking and an inline italic continuation.
- Controls are shallow outlined rectangles, not pills: 4.5px corners, 1px black borders and 27px/1 action text; compact category stamps use 13.5px capitals.
- The interface remains achromatic throughout: #5a5a5a canvas, black text and rules, white reversed type. Saturated color belongs inside rectangular photographs and artwork, never in branded interface accents.
- Keep the oval diagram, sculptural emblem and atmospheric image-led storytelling as signature devices. If bespoke media is unavailable, use an original curved two-piece SVG emblem with metallic shading and close-up photographs of the product's materials or working environment.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Graphite canvas | `#5a5a5a` | `--color-canvas` | background, surface | Default marketing canvas and the reversed text color on black hover fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, action, background | Default text, outlines and isolated reversed panels; also the canvas for long-form and organization pages. |
| Graphite rule | `#242424` | `--color-rule` | border | Visible black at 60% opacity over the graphite canvas, used for the structural grid and oval diagram. |
| White | `#ffffff` | `--color-reverse` | text, border | Type over dark photography and on black pages; outlined controls in the dark variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form stories and organization pages | Dark-page rule | `#595959` | `--color-dark-rule` | border | Visible white at 35% opacity over black for structural rules. |
| long-form stories | Muted credit | `#5a5a5a` | `--color-credit` | text | Small image credits on black. |

## Typography

- **PolySans** — All headings, paragraphs, links and metadata. Regular grotesk with open round counters, compact spacing and a distinctive italic used as part of editorial titles. If unavailable, use **DM Sans**. Use regular 400 and its italic; retain tight title tracking. Font stack: "PolySans", "DM Sans", Verdana, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | PolySans | 400 | 76.5px | 1 | -0.0294em | Opening promise, section leads and large media-link titles. |
| story-title | PolySans | 400 | 49.5px | 0.9 | -0.0202em | Editorial titles and portrait tile titles. |
| story-continuation | PolySans | 400 italic | 49.5px | 0.9 | -0.0202em | Inline interpretive continuation after the upright editorial title. |
| navigation | PolySans | 400 | 31.5px | 1 | -0.0317em | Identity, navigation and compact square-media titles. |
| action | PolySans | 400 | 27px | 1 | -0.037em | Full-column outlined collection actions. |
| subscribe | PolySans | 400 | 22.5px | 1 | -0.0444em | Footer subscribe control. |
| body | PolySans | 400 | 18px | 1.2 | normal | Supporting descriptions and long-form prose; inline references are underlined. |
| metadata | PolySans | 400 | 15.8px | 1 | normal, uppercase | Credits, years, social links and compact footer lists. |
| stamp | PolySans | 400 | 13.5px | 1 | normal, uppercase | Editorial category tags and dates. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| long-form stories | chapter-heading | PolySans | 400 | 31.5px | 1.1 | normal | Short sentence-case headings above reading passages. |
| long-form stories and organization pages | intro | PolySans | 400 | 27px | 1 | normal | Dense introductory paragraphs in the middle two columns. |

**Notes:**

- Keep every text role at weight 400; hierarchy comes from scale, placement and roman/italic contrast rather than boldness.
- The large title line height is deliberately compressed; body prose returns to 1.2. Uppercase metadata is not letterspaced.
- Do not apply the -1px action tracking to introductory paragraphs of the same size.

## Layout

**Density:** Airy at the section scale, with compact tags and dense reading blocks inside a thin ruled grid.

### Spacing

| Value | Use |
| --- | --- |
| 4.5px | Small tag vertical padding and top padding on collection buttons. |
| 9px | Chapter heading-to-paragraph spacing and subscribe button vertical padding. |
| 13.5px | Persistent cell padding, media insets, metadata offsets and footer padding. |
| 18px | Title-to-description spacing, control horizontal padding and credit-row gaps. |
| 36px | Separation after a lead paragraph before narrative body text. |
| 72px | Credit section top spacing. |
| 144px | Main long-form section breathing room and separation between large images. |
| 216px | Expanded editorial media chapter padding. |

### Containers and grids

- **Quarter-page grid**: 4 columns · gap 0px · side padding 0px. Full-width structural grid; 360px cells at 1440px. Foreground vertical rules remain visible through media.
- **Cell inset**: side padding 13.5px. Inset content within each ruled cell; one-column images are 333px wide.
- **Opening promise**: max width 1094px · side padding 0px. Centered promise spanning roughly three quarters of the desktop stage.
- **Reading column** (only for long-form stories and organization pages): max width 720px · side padding 13.5px. Middle two quarters of the desktop grid with a 693px inner text or portrait-media width.
- **Wide media** (only for long-form stories): max width 1080px · side padding 0px. Three-quarter-width landscape images aligned alternately to the left or right edge.

## Corner radius

| Element | Radius |
| --- | --- |
| Outlined controls | 4.5px |
| Media frames | 0px |
| Oval diagram | 50% |

## Surfaces and depth

### Surfaces

#### Graphite canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #5a5a5a; color: #000000`

**Observed:** A continuous gray field rather than alternating colored sections.

**Transfer:** Keep the field continuous through editorial content and footer.

#### Ruled cell · level 0

**Use:** Structural columns and section divisions.

**CSS:** `border-right: 1px solid rgba(0,0,0,0.6)`

**Observed:** Rules overlay the layout, including photographs; horizontal rules separate major bands.

**Transfer:** Draw a pointer-events-free foreground grid aligned with actual content columns.

#### Reversed inset · level 1

**Use:** Compact registration panel within a gray grid cell.

**CSS:** `background: #000000; color: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** Portrait-shaped panel, title at top and email controls at bottom.

**Transfer:** Reserve the black inset for a focused notification or access action.

#### Black canvas · level 0

**Only for:** long-form stories and organization pages

**Use:** Dark editorial page variant.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Same quarter-page structure, with white 35% rules instead of black rules.

**Transfer:** Change the whole page's neutral polarity, not each narrative chapter.

## Components

### Persistent navigation

**Use:** Identity at left and menu at right.

**CSS:** `height: 45px; padding: 0px 13.5px`

**Text style:** `navigation` — PolySans 400 · 31.5px/1 · tracking -0.0317em

**Observed:** Small filled emblem precedes the wordmark. The identity and three-line menu stay at opposite upper corners while content scrolls; the emblem remains recognizable when the wordmark retracts. Difference blending reverses the mark across imagery.

**Transfer:** Use an original compact symbol and short product name; do not replace the sparse header with a full link bar.

### Collection button

**Use:** Browse a collection or request notification.

**CSS:** `color: #000000; background: transparent; border: 1px solid #000000; border-radius: 4.5px; padding: 4.5px 18px 6.8px; text-align: center`

**Text style:** `action` — PolySans 400 · 27px/1 · tracking -0.037em

**Observed:** Spans the 333px content width of one quarter-column; often anchored at the foot of an introduction cell.

**States:** Declared: hover background-color black, color #5a5a5a, outline 0px; focus-visible unknown; active outline 0px.

**Transfer:** Use a short collection label or restrained access action.

### Category stamp

**Use:** Classify stories beside their date.

**CSS:** `color: #000000; border: 1px solid #000000; border-radius: 4.5px; padding: 4.5px 6.3px; overflow: hidden`

**Text style:** `stamp` — PolySans 400 · 13.5px/1 · uppercase

**Observed:** Small outlined stamps appear in pairs followed by an unboxed uppercase date; the tag wrapper supports duplicated sliding text.

**States:** Declared: hover outline 0px, with black background and #5a5a5a text on the category variant; focus-visible unknown; active outline 0px.

**Transfer:** Use one content category and one format label rather than feature badges.

### Editorial story

**Use:** Image-led feature within the open grid.

**CSS:** `padding: 0px 13.5px; color: #000000`

**Text style:** `story-title` — PolySans 400 · 49.5px/0.9 · tracking -0.0202em

**Observed:** Rectangular image first, stamp/date row next, upright title followed directly by italic continuation, then a body description. No outer card fill, outline or corner treatment; widths span two or three grid cells.

**Transfer:** Write a compact subject phrase and a longer interpretive subtitle; let the image establish the atmosphere.

### Portrait project tile

**Use:** Compact visual entry into deeper work.

**CSS:** `padding: 13.5px; color: #ffffff; position: relative`

**Text style:** `story-title` — PolySans 400 · 49.5px/0.9 · tracking -0.0202em

**Observed:** A 333×500px portrait photograph fills the cell inset, with the title overlaid near its top edge. Three image tiles sit beside a quarter-column introduction.

**Transfer:** Show original work or product-in-context photography instead of interface feature icons.

### Subscription control

**Use:** Footer email conversion.

**CSS:** `border: 1px solid #000000; border-radius: 4.5px; padding: 9px 18px; color: #000000`

**Text style:** `subscribe` — PolySans 400 · 22.5px/1 · tracking -0.0444em

**Observed:** Sits to the right of a long underlined email field. The dark-page variant reverses text and border to white.

**Transfer:** Keep this action compact even when the input spans two columns.

### Email underline

**Use:** Newsletter entry without a boxed input.

**CSS:** `border-bottom: 1px solid #000000; background: transparent; border-radius: 0px`

**Text style:** `navigation` — PolySans 400 · 31.5px/1 · tracking -0.0317em

**Observed:** Footer field occupies the remaining width beside Subscription control; registration panels use a smaller underlined input with white rule.

**Transfer:** Use a descriptive placeholder without a floating label or filled input shell.

### Four-column footer

**Use:** Contact, subscription and utility navigation at the page ending.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr 1fr 1fr; position: relative`

**Text style:** `metadata` — PolySans 400 · 15.8px/1 · uppercase

**Observed:** 234px-tall desktop footer. First row has two large text links in the first two quarters and the subscription form across the last half; bottom row has copyright, social and policy lists aligned to the same four columns. The dark variant has white text on black.

**Transfer:** Preserve the two-scale hierarchy and widely separated rows rather than adding a monumental sales CTA.

### Credit ledger

**Only for:** long-form stories

**Use:** Attribute contributors and summarize roles.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; row-gap: 18px`

**Text style:** `metadata` — PolySans 400 · 15.8px/1 · uppercase

**Observed:** A two-column ledger inside the middle half of the page. Dim labels introduce white names and roles; it appears both near the opening and near the end.

**Transfer:** Use for collaborators, production roles, technical partners or project metadata.

### Related-work banner

**Only for:** long-form stories

**Use:** Continue exploration before the footer.

**CSS:** `height: 360px; position: relative; overflow: hidden`

**Text style:** `display` — PolySans 400 · 76.5px/1 · tracking -0.0294em

**Observed:** Full-bleed landscape image with large white title at the left; consecutive banners touch, with hairline division and foreground grid continuing over the image.

**Transfer:** Offer a small number of deep next steps as cinematic horizontal strips.

## Imagery and graphics

### Metallic emblem

**Use:** Central object in the opening diagram.

**Observed:** A dark blue-gray, reflective two-part curved emblem is framed in a 324px square, centered behind the promise. Thin bright rims and soft internal reflections give it a glassy metal quality; overlapping letters change polarity over it.

**Transfer:** Create an original product glyph with a curved or folded silhouette, not a photorealistic device mockup. Minimum version: a sharply drawn SVG with restrained metallic shading.

**Build:** Use two opposing curved ribbon paths inside a 324×324px SVG. Fill each with a dark cool-gray to translucent white linear gradient, add a thin black outer stroke and a narrow white inner highlight at low opacity; offset one ribbon downward. Keep a transparent backing and place headline text above it with difference blending where appropriate.

### Oval circuitry

**Use:** Signature opening background and recurring diagram cell.

**Observed:** Tall overlapping hairline ellipses on gray, intersected by horizontal rules. The opening ellipses are 450×810px, repeated at a 225px step, cropped by the viewport. Smaller panels compress the same motif into a portrait cell.

**Transfer:** Rebuild this diagram for every new landing-page system; it provides identity without requiring proprietary artwork.

**Build:** In an overflow-hidden layer, position repeated 450×810px ellipses with border:1px solid rgba(0,0,0,0.6) and border-radius:50%, stepping each by 225px. Add three evenly spaced horizontal 1px rules within the stage. Scale the geometry to a 333×500px cell for an inset diagram.

### Editorial atmosphere

**Use:** Feature images, proof sections and project entries.

**Observed:** Architecture, furniture, spatial installations and abstract cover artwork are shown in square, portrait and 16:9 rectangles. Interiors are often dim, with warm wood, stained glass, projected light or reflections; colors are rich inside the picture while the surrounding interface stays gray.

**Transfer:** Photograph the product's material context, working spaces and human use with directional available light. For a digital-only product, use a compelling close detail of work in progress or an abstract material study rather than a generic floating dashboard.

### Documentary photo essay

**Only for:** long-form stories

**Use:** Primary narrative proof throughout case studies.

**Observed:** Grainy, candid images alternate natural greenery and raw concrete with dark indoor silhouettes, amber or cyan light, glass reflections and crowds. Central 693×1040px portraits alternate with 1080×608px edge-aligned landscapes; 333×500px images form two- or four-up strips. The grid remains visible in front.

**Transfer:** Commission a coherent essay around users, process, spaces and outcomes. Preserve natural color variation and deep shadows; use imperfect observational framing rather than polished stock portraits.

### Organizational image stage

**Only for:** organization pages

**Use:** Large mission image and oversized identity graphic.

**Observed:** A three-quarter-width performance photograph begins one column in from the left. Bright blue projected texture and a dark human silhouette back white large text and a flat white emblem below.

**Transfer:** Use one photograph showing the organization in action; place a large original monochrome symbol beneath a multi-line mission rather than a team headshot grid.

**Build:** Use a wide rectangular photo, align it to the right three grid columns, overlay a two-column white mission and an original solid SVG mark of about one cell width below. Keep the first column open.

### Icons

**Observed:** Tiny filled abstract identity mark around 25×23px, a 35×18px three-line menu glyph, and thin directional arrows on the photo carousel. Colors reverse between black and white.

**Transfer:** Keep UI iconography minimal and monochrome; use thin arrows and simple horizontal menu lines rather than a full decorative icon library.

## Section recipes

How recurring sections are built.

### First screen: Diagram stage opening

**Observed:** The first 900px is a single sticky viewport composition: 45px identity/menu rail above, gray Oval circuitry across the field, a 324px Metallic emblem at center and a two-line centered promise in the display recipe spanning roughly three quarters of the width. The headline and emblem overlap, with lettering reversing where it crosses the object. About and Contact text links sit at the lower left and lower right along the bottom rail. A portrait story teaser is partially visible at the right edge, in front of the diagram. During the extended 2700px scroll region, more rectangular image teasers move across the stage; the first editorial grid sits below that opening sequence. There is no supporting paragraph or boxed primary button in the first screen.

**Transfer:** Write one clear cross-disciplinary product promise and stage it against the original emblem and rebuilt ellipses. Use product-context images as the moving teasers; a static presentation can preserve the same overlap and edge-peeking image composition. Organization pages instead open with a left title above a three-column mission image; case-study pages use a title-led black introduction and a credit ledger.

**Avoid:** Do not convert this into a left-aligned SaaS hero with a right-side device mockup, gradient canvas or two filled CTA buttons.

**Text style:** `display` — PolySans 400 · 76.5px/1 · tracking -0.0294em

### Split editorial spread

**Observed:** A full-width display section lead sits on a horizontal rule. Two half-page Editorial story components occupy separate vertical positions within an airy ruled area; the action lives in the bottom right quarter.

**Transfer:** Use for essays, insights or product narratives with unequal image positions and complementary titles.

**Text style:** `story-title` — PolySans 400 · 49.5px/0.9 · tracking -0.0202em

### Quarter-column offer band

**Observed:** A 528px-high band divides into four equal cells: heading, support and bottom-aligned Collection button in the first; portrait artwork or release information in the next; Oval circuitry in another; Reversed inset with registration form at the end.

**Transfer:** Use this construction for an upcoming release or notification program. Replace release facts with real product information while retaining the diagram cell and contrasting form.

**Text style:** `display` — PolySans 400 · 76.5px/1 · tracking -0.0294em

### Isolated editorial image

**Observed:** A large image and roman/italic title occupy a half- or three-quarter-page width while other grid cells remain open. Expanded editorial sections use 216px vertical padding.

**Transfer:** Give a major product story one dominant image and a long interpretive title without wrapping it in a separate panel.

**Text style:** `story-title` — PolySans 400 · 49.5px/0.9 · tracking -0.0202em

### Utility ending

**Observed:** Four-column footer closes the gray landing layout as well as both black page types; no separate colored conversion slab. Its upper row is active and conversational, its lower row small and administrative.

**Transfer:** Make the newsletter or contact route the understated final action, maintaining the page's neutral polarity.

**Text style:** `navigation` — PolySans 400 · 31.5px/1 · tracking -0.0317em

### Narrative chapter

**Only for:** long-form stories

**Observed:** Reading column on Black canvas; chapter-heading followed by body prose after 9px. Chapters breathe with 144px top separation and lead to portrait images, edge-aligned landscapes or photo strips.

**Transfer:** Organize evidence around meaningful phases, methods and consequences rather than a repetitive feature-card grid.

**Text style:** `chapter-heading` — PolySans 400 · 31.5px/1.1

### Mission and closing assertion

**Only for:** organization pages

**Observed:** Organizational image stage leads into a middle-half intro block with 144px above and below. A separate ruled ending gives a short multi-line display assertion in that same reading width with substantial space beneath before the footer.

**Transfer:** Finish an organization story with a specific durable position or verified longevity statement rather than a generic invitation.

**Text style:** `display` — PolySans 400 · 76.5px/1 · tracking -0.0294em

### Attribution and onward viewing

**Only for:** long-form stories

**Observed:** Closing prose is followed by Credit ledger, 144px breathing room, a display heading and touching Related-work banner components. Four-column footer follows directly.

**Transfer:** Let the reader understand authorship and find adjacent work before encountering utility navigation.

**Text style:** `display` — PolySans 400 · 76.5px/1 · tracking -0.0294em

## Page flow

**Storyline:** Positioning → visual exploration → focused narrative or offer → deeper proof → attribution or ongoing relevance → onward exploration and contact.

### Marketing landing page and editorial index

1. **Positioning** — Diagram stage with centered promise, reflective emblem and passing image teasers.
2. **Exploration** — Ruled editorial spread mixing large images, tags and roman/italic headlines.
3. **Focused action** — Quarter-column offer bands with a single outlined action and reversed registration panel.
4. **Proof** — Alternating square, landscape and portrait story entries with generous open cells.
5. **Closing action** — Compact contact and newsletter footer.

**Transfer:** Interleave product stories, use cases and release invitations without making every block a sales pitch.

### Organization or company profile

1. **Identity** — Page label followed by a three-column photo, white mission text and oversized flat symbol.
2. **Explanation** — Dense intro paragraphs in the central half.
3. **Lasting position** — Monumental multiline assertion above the footer.
4. **Closing action** — Contact and subscription utilities.

**Transfer:** Explain the organization's practice, then leave the reader with one grounded statement of purpose.

### Single-project case study

1. **Orientation** — Title-led introduction on black and an uppercase contributor ledger.
2. **Context** — Large lead paragraph followed by a historical or problem-setting chapter.
3. **Method and experience** — Alternating narrative passages, tall central photos, wide landscapes and photo strips.
4. **Reflection** — Outcome discussion, quotation and acknowledgment.
5. **Attribution and continuation** — Repeated credit ledger, related-work image banners and utility footer.

**Transfer:** Develop one detailed product implementation through context, intent, process and consequences; keep citations within the prose.

### Long-running partnership case study

1. **Orientation** — Title-led black opening and compact metadata ledger.
2. **Context** — Introductory statement followed by a sequence of tall documentary images.
3. **Evolution** — Short chapter headings describe successive phases; prose alternates with edge-aligned landscapes and portrait strips.
4. **Demonstration** — Four-up photo carousel documents people, spaces and activities.
5. **Synthesis** — Reflective closing prose, credit ledger and related-work banners.
6. **Closing action** — Shared black utility footer.

**Transfer:** Tell the development of an ongoing product or partnership using distinct phases and photographic evidence, not identical timeline cards.

## Writing

Curatorial, reflective and culturally literate. Claims are explained through context, process and relationships rather than competitive superlatives.

**Do not copy:** Do not reuse the brand name, identity artwork, project names, artist names, founding dates, attendance claims, quotations or source-specific achievements. Replace them with original assets and verified product facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person descriptions and occasional first-person plural accounts of work; direct reader address is reserved for short invitations and actions.
- **Rhythm:** Short section nouns contrast with long interpretive titles and substantial explanatory paragraphs. Sentence case dominates, metadata is uppercase, and exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Present-tense positioning statement connecting complementary areas. | 8–14 words | “Operating at the intersection of music, art and technology” |
| Editorial title | Short conceptual subject and colon, followed by an italic how-statement. | 12–20 words | “The sound of memory: How listening connects people and places across time” |
| Supporting description | Explain the experience or scope without a hard sell. | 12–30 words | “Immerse yourself in a joint exploration of music and art.” |
| Action | Collection noun or restrained access verb. | 1–3 words | “All projects”<br>“Pre-register” |
| Chapter heading | Brief conceptual phrase that names a phase or intent. | 3–6 words | “Shaped by intention”<br>“Documenting emergence” |

**Words and phrasing to use:** explore; practice; context; collaboration; research; experience; dialogue; shaped by; intersection

**Avoid:** game-changing; supercharge; crush it; ultimate solution; unlock your potential

**Rules:**

- Pair abstract positioning with concrete people, methods, spaces or outcomes in the supporting prose.
- Use a colon and italic continuation to turn a story title into a question of meaning, not a slogan.
- Name real contributions in compact credit lists; keep interpretation in the narrative.
- Keep collection actions literal and calm.

## Do's and Don'ts

### Do

- Use the 13.5px cell inset consistently for text and media.
- Keep four equal grid quarters and 1px rules visible across major sections.
- Set the primary promise at 76.5px/1, weight 400, with -2.3px tracking.
- Use 4.5px radii only on outlined controls and tags.
- Let photographs carry cyan, green, amber or magenta while the interface stays neutral.
- Use 144px chapter breathing room and 216px for expanded editorial features.
- Preserve roman/italic title continuity at 49.5px/0.9.
- Keep the footer's large contact row separate from its 15.8px uppercase utility lists.

### Don't

- Do not turn the 333×500px project images into rounded floating cards.
- Do not introduce accent-colored CTA fills into the grayscale control system.
- Do not replace the persistent diagram with a generic soft mesh gradient.
- Do not use bold weights to distinguish adjacent editorial title phrases.
- Do not center every narrative block; keep prose in the middle two columns and landscapes edge-aligned.
- Do not add drop shadows or glass panels around editorial content.
- Do not enlarge compact stamps into pill-shaped feature labels.
- Do not impose uniform image ratios across the essay; preserve square, 16:9 and tall portrait roles.

## Motion and responsive

### Motion

**Observed:**

- Opening stage is sticky inside a 2700px scroll region; images traverse the diagram and editorial content has scroll-linked vertical displacement.
- Identity uses difference blending and changes from wordmark to compact emblem while scrolling.
- Opacity transitions of 0.2s are declared for some actions and surfaces.
- Category stamps have duplicated text layers; buttons declare black hover fills with gray text.

**Transfer:**

- Preserve the opening's layered diagram and image procession when implementing scroll motion.
- Keep editorial motion subordinate to the four-column alignment; use static layered artwork when motion is unavailable.

**Unknown:**

- Exact scroll choreography, emblem rotation timing and easing assignments are not established.
- Menu-open appearance, form success behavior and focus-visible styling are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px, 1440px and 1920px.

**Transfer:**

- On narrow screens, retain the oval field and central emblem while shortening the headline to preserve the overlap.
- Collapse the quarter-grid into fewer columns, keeping media flush to its cell and the footer subscription form readable.
- Treat these as adaptation guidance: preserve the hierarchy between isolated image moments and dense narrative passages.

**Unknown:**

- Narrow-screen type sizes, exact column changes and mobile scroll behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
