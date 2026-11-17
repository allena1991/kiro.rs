# Sublime — ideas growing wild

## Overview

A light, art-led style that makes software feel like a place for human curiosity rather than an efficiency machine. White space and warm gray grotesk type surround tactile natural lettering, found-image collages and small, unassuming controls. It suits creative tools and thoughtful consumer products, with a spare marketing voice and more intimate serif storytelling for editorial pages.

### Essentials

- A blunt headline meets a living object: centered Control Upright at 120px/0.9, weight 400, sits behind a nearly full-width organic word sculpture on white; a small creature and filename pill make the scene feel discoverable. Create an original sculptural name or short verbal emblem when no product object exists.
- The page behaves like a loose exhibition, not a dashboard: 160px section padding frames isolated collages, narrow centered gray explanations and tiny repeated actions. Keep the white canvas continuous through the capability chapters.
- Controls deliberately understate conversion: ordinary actions are 30px high with 5px corners and 14px regular text; only the navigation and footer primary actions use pale lime #cbffa6 with forest-green #38744d text.
- Color belongs to collected things, not large UI panels: the page is overwhelmingly white and neutral, with natural greens in the hero, mixed-color reference media, small lime actions and occasional blue relationship labels.
- Found material forms constellations: unequal rectangular excerpts, photographs and notes orbit a small central message; three overlapping collection collages carry 16px Times New Roman titles and 14px parenthesized counts beneath.
- The invitation becomes the closing monument: a 64px/0.9 regular gray action sits in a 429×125px neutral rounded rectangle with 20px corners, followed by a tiny reassuring line and an inset 975px-wide footer with 40px corners.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale lime | `#cbffa6` | `--color-lime` | action, accent | Compact primary actions and text selection; not section backgrounds. |
| Relationship blue | `#00aaff` | `--color-blue` | accent, link | Small reference label and related-content signup text. |
| Forest action ink | `#38744d` | `--color-green-ink` | text, action | Text on pale-lime actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#181816` | `--color-ink` | text | Opening headline and editorial section headings. |
| Charcoal copy | `#41403e` | `--color-copy` | text | Editorial prose and readable excerpts. |
| Deep gray | `#6a6967` | `--color-action-text` | text, action | Monumental closing invitation and hovered neutral actions. |
| Warm medium gray | `#908f8e` | `--color-muted` | text, action | Marketing support lines, capability headings, collection captions and ordinary action text. |
| Warm soft gray | `#a29e9c` | `--color-subtle` | text | Navigation identity, small support copy and footer links. |
| Soft neutral panel | `#efefef` | `--color-panel` | surface, action | Footer, neutral actions, filename pills and the closing invitation. |
| Frosted neutral | `#f9f9f9` | `--color-search-wash` | surface | Visible pale search overlay, made with neutral gray at 40% opacity over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Continuous marketing canvas and reversed text on the small blue reference marker. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| content detail and collection pages | Blue wash | `#e6f7ff` | `--color-blue-wash` | surface | Visible blue signup wash; rgba(0,170,255,0.1) on white. |
| content detail and collection pages | Excerpt gray | `#e5e5e5` | `--color-excerpt` | surface | Related-content excerpt cards. |
| content detail and collection pages | Reading gray | `#eaeaea` | `--color-reading-card` | surface | Long-form reading card and individual quote cards. |
| content detail and collection pages | Almost-white panel | `#f8f8f8` | `--color-related-panel` | surface | Inset related-content container. |

## Typography

- **Control Upright** — Marketing headlines, explanations, controls and navigation. Compact, tightly fitted grotesk with a dense visual presence in the oversized headline despite regular weight. OpenType features: "ss12". If unavailable, use **Inter Tight**. Use weight 400 and preserve the compact line lengths; large text should remain visually dense. Font stack: "Control Upright", "Inter Tight", ui-sans-serif, system-ui, sans-serif.
- **Times New Roman** — Small collection captions and extended editorial storytelling. Familiar high-contrast serif; tightly tracked and closely led for large editorial statements. Font stack: "Times New Roman", Times, ui-serif, Georgia, Cambria, serif.
- **ui-sans-serif** (only for content detail and collection pages) — Reading cards, collection titles and related-content controls. Practical system sans, with medium interface labels and bold inline emphasis. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Control Upright | 400 | 120px | 0.9 | normal, features "ss12" | Centered two-line opening promise. |
| closing-action | Control Upright | 400 | 64px | 0.9 | normal, features "ss09" | Oversized final invitation. |
| heading | Control Upright | 400 | 28px | 1 | normal, features "ss12" | Compact centered capability headings and the three-line support statement beneath the main artwork. |
| small-copy | Control Upright | 400 | 16px | 18px | normal, features "ss12" | Short capability explanations, footer links and reassurance beneath an action. |
| collection-caption | Times New Roman | 400 | 16px | 1.2 | -0.03em, features "ss12" | Titles immediately below overlapping collection collages. |
| action | Control Upright | 400 | 14px | 1 | normal, features "ss09" | Compact actions and filename labels. |
| collection-count | Times New Roman | 400 | 14px | 1.2 | normal, features "ss12" | Parenthesized count on a separate line below a collection title. |
| micro-label | Control Upright | 400 | 12px | 1.16 | 0.008em, features "ss12" | Small relationship marker. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial manifesto pages | editorial-display | Times New Roman | 400 | 130px | 0.82 | -0.05em, features "ss12" | Two-line statement above a cloudlike sculpture. |
| editorial manifesto pages | editorial-turn | Times New Roman | 400 | 106px | 0.82 | -0.0613em, features "ss12" | Exceptional oversized thesis or turning-point statement. |
| editorial manifesto pages | editorial-heading | Times New Roman | 400 | 68px | 0.88 | -0.05em, features "ss12" | Centered chapter statements. |
| editorial manifesto pages | editorial-prose | Times New Roman | 400 | 36px | 1 | -0.03em, features "ss12" | Centered paragraphs, with short lines and paragraph breaks. |
| collection pages | library-title | ui-sans-serif | 500 | 30px | 1.2 | -0.02em, features "ss12" | Modest left-aligned title above a media wall. |
| content detail and collection pages | reading-body | ui-sans-serif | 400 | 18px | 1.5 | -0.01875em, features "ss12" | Excerpts, bullet lists and long-form reading. |
| content detail and collection pages | reading-emphasis | ui-sans-serif | 700 | 18px | 1.5 | -0.01875em, features "ss12" | Inline bold and compact subheadings inside reading cards. |
| content detail and collection pages | signup-label | ui-sans-serif | 500 | 15px | 22px | -0.02em, features "ss12" | Blue signup action beneath related material. |

**Notes:**

- The opening grotesk is visually much denser than the small gray capability headings; keep its regular cut rather than replacing the whole scale with bold text.
- Default marketing headings are short, narrow and centered without an uppercase eyebrow. The editorial variant changes the headline and prose family, not the compact navigation controls.
- Serif tracking tightens to -0.05em for the editorial display and chapter headings; collection captions retain a gentler -0.03em.

## Layout

**Density:** Airy exhibition-like marketing sections surround compact controls and small text clusters; reading-card pages are denser within their inset panels.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight media-caption gap and excerpt padding. |
| 15px | Spacing before small repeated actions and below the final invitation. |
| 20px | Navigation side inset and compact promotional panel padding. |
| 30px | Desktop content-page outer padding and small vertical groups. |
| 50px | Related panel vertical padding and footer navigation top inset. |
| 60px | Footer column spacing. |
| 100px | Separation of collection collages and editorial chapter margins. |
| 160px | Default marketing chapter top and bottom padding. |
| 320px | Expanded white space above and below the closing invitation. |

### Containers and grids

- **hero-stage**: max width 1366px. Nearly edge-to-edge centered sculpture, 426px high on desktop, overlapping the headline.
- **footer-island**: max width 975px · side padding 25px. Centered footer with its own softly rounded perimeter, detached from both page edges.
- **collection-triptych**: 3 columns · gap 100px. Three unequal collage previews, approximately 265–290px wide; center preview drops lower than the outer two.
- **related-grid** (only for content detail and collection pages): max width 890px · 2 columns · gap 90px. Two columns of roughly 388–400px excerpt cards with independent vertical pacing.
- **reading-column** (only for content detail pages): max width 600px. Single centered long reading card with a compact activity row above it.
- **editorial-column** (only for editorial manifesto pages): max width 672px · side padding 16px. Centered prose column with 640px of inner text width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact-actions | 5px |
|  | closing-invitation | 20px |
|  | footer-and-related-islands | 40px |
|  | filename-and-relationship-labels | 9999px (pill) |
| content detail and collection pages | reading-cards | 15px |
| content detail and collection pages | signup-action | 8px |

## Surfaces and depth

### Surfaces

#### White exhibition canvas · level 0

**Use:** All default marketing sections.

**CSS:** `background: #ffffff; box-shadow: none`

**Observed:** No alternating colored bands or visible dividing rules; artwork creates the section boundaries.

**Transfer:** Separate chapters through open space and changes in media composition.

#### Neutral island · level 1

**Use:** Footer and closing action backing.

**CSS:** `background: #efefef; border-radius: 40px; box-shadow: none`

**Observed:** Large islands float inside white margins without borders. The closing action uses its smaller 20px corner variant.

**Transfer:** Use tonal contrast rather than elevation.

#### Search glass · level 2

**Use:** Search demonstration over a single piece of content.

**CSS:** `background: rgba(239,239,239,0.4); backdrop-filter: blur(40px); border-radius: 9999px`

**Observed:** A pale horizontal search field crosses the foreground of a vertically oriented saved item.

**Transfer:** Keep the overlay light enough that the item behind it remains legible as an object.

#### Related reading tray · level 1

**Only for:** content detail and collection pages

**Use:** Discovery section at the end of reading or browsing.

**CSS:** `background: #f8f8f8; border-radius: 40px; padding: 50px 80px; box-shadow: none`

**Observed:** The tray surrounds darker excerpt cards. The collection variant uses 60px side padding.

**Transfer:** Let the panel end with an invitation to explore rather than adding a marketing footer.

#### Excerpt paper · level 2

**Only for:** content detail and collection pages

**Use:** Text-heavy quote and related-content cards.

**CSS:** `background: #e5e5e5; border-radius: 15px; padding: 10px; box-shadow: none`

**Observed:** Some reading cards use the slightly lighter #eaeaea. Long previews fade into their own gray fill above metadata.

**Transfer:** Retain a paper-like flat surface and light metadata; do not add hairline decoration.

## Components

### Fixed navigation

**Use:** Persistent identity and two compact access actions.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; z-index: 20; display: flex; align-items: center; justify-content: space-between; padding: 17.5px 20px 0px`

**Observed:** Muted symbol and wordmark sit at the far left; login and the lime primary action sit at the far right with a 10px gap. No enclosing colored bar.

**Transfer:** Keep product navigation subordinate to the opening artwork.

### Primary button

**Use:** Main compact conversion action in navigation and footer.

**CSS:** `display: inline-flex; align-items: center; height: 30px; padding: 0px 17.5px; border-radius: 5px; background: #cbffa6; color: #38744d; border: 0px`

**Text style:** `action` — Control Upright 400 · 14px/1

**Observed:** A small soft rectangle, not a capsule. The footer variant is 29px high with 7.5px 15px padding.

**States:** Declared: hover background-color #bbee96 and color #22603a; focus-visible box-shadow 0 0 #0000,0 0 #0000,0 0 #0000,0 0 #0000,0 0 #0000.

### Neutral button

**Use:** Repeated low-pressure chapter action and login.

**CSS:** `display: inline-flex; align-items: center; height: 30px; padding: 0px 17.5px; border-radius: 5px; background: #efefef; color: #908f8e; border: 0px`

**Text style:** `action` — Control Upright 400 · 14px/1

**Observed:** Centered below the small support paragraph; repeats without growing in emphasis.

**States:** Declared: hover background-color #e1e1e1 and color #6a6967; focus-visible box-shadow 0 0 #0000,0 0 #0000,0 0 #0000,0 0 #0000,0 0 #0000.

### Closing invitation

**Use:** Final conversion statement.

**CSS:** `display: inline-block; position: relative; overflow: hidden; background: #efefef; color: #6a6967; border-radius: 20px; padding: 30px 70px 35px`

**Text style:** `closing-action` — Control Upright 400 · 64px/0.9

**Observed:** The action reads as a large typographic object, centered alone with a small two-line reassurance beneath.

**Transfer:** Use an equally short lowercase verb-and-product invitation.

### Filename pill

**Use:** Playful contextual link beneath a small creature in the opening art.

**CSS:** `display: inline-flex; align-items: center; height: 30px; padding: 0px 12.5px; border-radius: 9999px; background: #efefef; color: #908f8e`

**Text style:** `action` — Control Upright 400 · 14px/1

**Observed:** The small filename sits near one side of the sculpture, aligned with a butterfly or bird rather than with the headline.

### Relationship marker

**Use:** Reference label attached to an isolated piece of media.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 85px; height: 25px; background: #00aaff; color: #ffffff; border-radius: 9999px`

**Text style:** `micro-label` — Control Upright 400 · 12px/1.16 · tracking 0.008em

**Observed:** Overlaps the lower edge of the reference image; surrounding related items use much paler blue markers.

**Transfer:** Name the relationship, not the file format.

### Search overlay

**Use:** Demonstrate retrieval without a full browser frame.

**CSS:** `display: flex; align-items: center; width: 585px; height: 60px; padding-left: 20px; column-gap: 10px; background: rgba(239,239,239,0.4); backdrop-filter: blur(40px); border-radius: 9999px`

**Observed:** Magnifier, typed fragment and caret traverse the middle of a single saved excerpt. The field is substantially wider than the content behind it.

**Transfer:** Use a short plausible query and one recognizable result object, not an entire results dashboard.

### Inset footer

**Use:** Utility navigation after the final invitation and a personal team note.

**CSS:** `max-width: 975px; margin: 0px auto; padding: 20px 20px 30px 25px; background: #efefef; border-radius: 40px; box-shadow: none`

**Text style:** `small-copy` — Control Upright 400 · 16px/18px

**Observed:** Top row separates a small symbol, wordmark and login/action pair. Below, four unheaded link groups occupy the right side with 60px column gaps; copyright stays low on the left. Links are muted and closely stacked.

**States:** Declared: hover text-decoration-line underline on footer text links.

**Transfer:** Group download, resource, company and social links without introducing bold category headings.

### Reading card

**Only for:** content detail and collection pages

**Use:** Single long document or short testimonial excerpt.

**CSS:** `max-width: 600px; background: #eaeaea; padding: 10px; border-radius: 15px; color: #41403e; overflow: hidden`

**Text style:** `reading-body` — ui-sans-serif 400 · 18px/1.5 · tracking -0.01875em

**Observed:** Long card begins directly with bold inline title text. Same-size bold subheads divide bullet lists; no oversized editorial title inside the card. A small avatar and activity count sit above the card.

**Transfer:** Apply to an actual document or customer note rather than converting every capability into a card.

### Related discovery tray

**Only for:** content detail and collection pages

**Use:** Ending for browsing and reading pages.

**CSS:** `max-width: 1050px; padding: 50px 80px; background: #f8f8f8; border-radius: 40px; overflow: hidden`

**Observed:** Centered Related/filter controls lead into two staggered excerpt columns. Metadata sits at card bottoms and tiny counts float near upper-right edges. The tray ends with a centered exploration prompt and blue signup action.

**Transfer:** Use relevant reading or examples, not a generic feature grid.

### Exploration signup

**Only for:** content detail and collection pages

**Use:** Final action below related cards.

**CSS:** `background: rgba(0,170,255,0.1); color: #00aaff; border-radius: 8px; padding: 7.5px 30px; border: 0px`

**Text style:** `signup-label` — ui-sans-serif 500 · 15px/22px · tracking -0.02em

**Observed:** Sits immediately below a soft gray one-line exploration prompt. It does not replace the lime global access action.

## Imagery and graphics

### Living word sculpture

**Use:** Signature opening artwork for marketing pages.

**Observed:** An irregular lowercase word is rendered as one continuous gray stone formation with moss, tiny white flowers and rounded upright protrusions. It spans nearly the entire stage, overlaps the lower headline and is isolated on white without a plinth, room or enclosing card. A small orange butterfly hovers at the right.

**Transfer:** Create an original name or short emblem as a tactile natural object. Minimum acceptable version is a clean outlined word silhouette filled with convincing stone texture, moss patches and tiny flower details, not plain green text.

**Build:** Create a wide SVG mask from custom rounded lowercase lettering connected by a low irregular baseline. Fill with mottled gray stone texture using layered noise and directional light, darker along lower edges. Scatter small olive-green textured patches on upward-facing regions and tiny white flower dots within those patches. Keep the object about 1366×426px on a white stage and add a small isolated creature near its right upper edge; give that creature a neutral filename pill.

### Reference constellations

**Use:** Capability demonstrations throughout the marketing page.

**Observed:** Found book passages, highlighted quotations, photographs, album art and notes remain unequal in size and aspect ratio. They orbit a centered gray heading and support line or create a loose row that extends beyond the viewport. Some overlap, but large white channels remain between clusters. Individual pieces range from about 140px to 310px wide.

**Transfer:** Collect real material relevant to the new product's use, mixing text and image fragments rather than uniform mockups. With no media library, compose original short typeset notes, one photograph and one diagram.

**Build:** Use an approximately 1090×662px relative stage; reserve a narrow central text column, then position 6–10 rectangular image and note objects in loose left and right arcs. Vary widths around 140–220px, let two or three objects overlap lightly, and preserve white space around the central text. Use pale green or pale yellow only within selected notes, not as a stage fill.

### Collection collages

**Use:** Three public collection previews with serif captions.

**Observed:** Each preview is a layered pile of two or three rectangular clippings, book covers or posters with irregular overlap. The three groups differ in shape and color; the middle group sits lower. Titles and parenthesized counts are centered beneath each group, not overprinted on imagery.

**Transfer:** Show three meaningful bodies of work or example collections; vary their content instead of repeating one mockup.

**Build:** Within three roughly 275px-wide groups, overlap three aspect-ratio-preserving images with small horizontal offsets. Keep them upright rather than rotating every piece. Offset the center group downward, add a 10px gap to its 16px serif title, and place the 14px parenthesized count underneath.

### Human proof video

**Use:** Social proof near the later marketing chapters.

**Observed:** A 750×422px video shows a real working context with a small circular speaking portrait overlaid near the lower-left. A white 85px circular play control floats centrally. The scene is contained, not full bleed.

**Transfer:** Show a person explaining a real use case over relevant work, keeping the media itself the colorful object on white.

### Cloud word sculpture

**Only for:** editorial manifesto pages

**Use:** Opening symbolic artwork beneath a large serif statement.

**Observed:** The word silhouette becomes soft white cloud volume with pale gray internal shading, fading softly into the white canvas. A dove and filename pill occupy the upper-right edge.

**Transfer:** Reinterpret the same emblem in an airy material to distinguish reflective editorial content from the default stone-and-moss marketing look.

**Build:** Reuse an original connected-word silhouette; assemble overlapping soft white ellipsoids within it, shade undersides with translucent gray and feather its perimeter with soft noise. Keep the white background and add a small white bird beside the filename label.

### Unpolished proof wall

**Only for:** testimonial collection pages

**Use:** Long-form social proof archive.

**Observed:** Two staggered columns preserve messages, emails, social posts, highlighted excerpts, short videos and occasional gray text cards. They retain their native colors and proportions, with ample irregular white gaps and no uniform testimonial treatment.

**Transfer:** Use genuine, permissioned customer material in its natural format. Preserve readable framing and variety rather than rebuilding everything as identical quote cards.

### Icons

**Observed:** Small monochrome filled symbols rather than a pervasive outlined feature-icon system. Identity symbol is 35px; a magnifier anchors the search overlay and a solid triangle sits in the central white play circle.

**Transfer:** Use a few functional silhouettes in warm gray or near-black; let artwork and text carry the feature narrative.

## Section recipes

How recurring sections are built.

### First screen: Living-object opening

**Observed:** A white first screen holds Fixed navigation at its upper edge, then a centered two-line near-black promise spanning almost the full width in the display recipe. Behind-to-front layers are white canvas, headline, then a 1366×426px living word sculpture overlapping the headline's lower edge by about 90px. The small butterfly and Filename pill perch to the right. A narrow three-line gray support statement sits beneath the sculpture in the heading recipe. Within the first 900px the whole headline, artwork, support line and navigation actions are visible; the next chapter begins below the fold. There is no separate large hero button beneath the support line.

**Transfer:** Write a short paradox or tension the product resolves, then give it a tactile sculptural emblem. If there is no physical product, make the new name or an original short word into the object. Editorial stories open with the cloud material and editorial-display recipe; collections instead start with a modest left-aligned title and a media wall, while document pages begin with a readable card.

**Avoid:** Do not replace this with a left-aligned SaaS split hero, full browser screenshot or gradient background; do not place the artwork in a rounded card.

**Text style:** `display` — Control Upright 400 · 120px/0.9

### Reflective pause

**Observed:** A short centered gray statement occupies a largely white chapter with 160px top and bottom padding. Its role is emotional reframing rather than another feature list.

**Transfer:** Use one candid sentence that changes how the reader thinks about the problem; keep it short enough to read as a single thought.

### Capability constellation

**Observed:** A compact centered heading, small support paragraph and Neutral button sit within or beside Reference constellations. Related media spread widely across the page, with no section rule or colored backing. One variant stacks a reference image above the text and distributes related images around it.

**Transfer:** Build each capability as one memorable visual idea. Alternate a loose row, an orbit and a single-item demonstration to avoid a repeated grid.

**Text style:** `heading` — Control Upright 400 · 28px/1

### Remembered fragment demonstration

**Observed:** A short centered capability heading leads to one vertical excerpt crossed by Search overlay. A narrow support line and Neutral button follow on white.

**Transfer:** Demonstrate the user's uncertain language as a small human interaction rather than listing search specifications.

**Text style:** `heading` — Control Upright 400 · 28px/1

### Collection triptych

**Observed:** Centered heading and support precede three Collection collages on a wide white stage. The outer two sit higher, the center lower; serif collection titles and separate parenthesized counts are the only metadata.

**Transfer:** Use it to present example outputs or collections, preserving the collage treatment even if the product's objects are not documents.

**Text style:** `collection-caption` — Times New Roman 400 · 16px/1.2 · tracking -0.03em

### Contained human proof

**Observed:** A centered capability-scale heading introduces Human proof video. Narrow gray paragraphs below extend the emotional case instead of adding a quantitative stat banner.

**Transfer:** Use a real narrative of use, with a few human observations beneath the video.

**Text style:** `heading` — Control Upright 400 · 28px/1

### Monumental invitation and footer island

**Observed:** Closing invitation stands alone with 320px of white space above; small reassurance follows after 15px. A personal two-line team note with an archive link appears before Inset footer. The footer is detached from the viewport edges, contains grouped links and ends with a small copyright line.

**Transfer:** Keep the invitation, reassurance and inset footer device even on shorter landing pages, adjusting the surrounding narrative rather than adding a full-width closing band.

**Text style:** `closing-action` — Control Upright 400 · 64px/0.9

### Centered editorial argument

**Only for:** editorial manifesto pages

**Observed:** A 672px outer column alternates editorial-heading statements and editorial-prose paragraphs. Chapter headings have 100px margins; the oversized editorial-turn has 120px margins. Text remains centered, with short lines and large white breaks. The ending turns personal, then returns to Closing invitation and Inset footer.

**Transfer:** Develop a point of view through short chapters and a genuine welcome at the end; reserve the oversized turn for the argument's pivot.

**Text style:** `editorial-heading` — Times New Roman 400 · 68px/0.88 · tracking -0.05em

### Document and related discovery

**Only for:** content detail pages

**Observed:** A centered Reading card opens immediately below the compact top area. An activity row sits above it, bold inline headings organize bullets, then an 80px gap leads to Related discovery tray. The page ends inside that tray with the exploration prompt and Exploration signup, not the marketing footer.

**Transfer:** Use for a substantive document or saved item; related content should extend the reader's path rather than interrupt it.

**Text style:** `reading-body` — ui-sans-serif 400 · 18px/1.5 · tracking -0.01875em

### Proof archive ending

**Only for:** testimonial collection pages

**Observed:** A modest library-title, small description and count introduce a long two-column Unpolished proof wall. At its end a small centered creation credit appears in white space, followed by Related discovery tray and Exploration signup. A compact access panel remains at the lower-left while browsing.

**Transfer:** Make the wall as long as the quality and diversity of real proof supports; close with a discovery path rather than a duplicate marketing CTA stack.

**Text style:** `library-title` — ui-sans-serif 500 · 30px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Emotional tension → reframing → concrete encounters with the product → human resonance → low-pressure invitation or continued discovery.

### Art-led product landing page

1. **Promise** — Oversized compact headline with living word sculpture and a tiny support statement.
2. **Reframing** — A blunt human-centered statement alone in white space.
3. **Capability chapters** — Loose media row, reference constellation, single-item search overlay, creative collage and collection triptych, each with a small repeated action.
4. **Social proof** — Contained human demonstration video with reflective copy beneath.
5. **Closing call** — Monumental neutral invitation, small reassurance, personal team note and inset footer.

**Transfer:** Choose the capability scenes that best make the new product tangible; retain the sculpture, collage language and closing monument without requiring the same chapter count.

### Readable document detail

1. **Primary content** — Activity row above one centered gray reading card with inline subheads and bullets.
2. **Continued discovery** — Inset related-content tray with staggered excerpts.
3. **Closing call** — Exploration prompt and blue signup action at the tray bottom.

**Transfer:** Lead with actual reading content and keep marketing access compact, rather than adding a landing-page hero.

### Browsable testimonial collection

1. **Orientation** — Small left-aligned collection heading, description and item count.
2. **Social proof** — Extended two-column wall of native-format customer messages, posts and videos.
3. **Attribution** — Small centered creation credit after the last collection item.
4. **Continued discovery** — Related-content tray ending with exploration signup.

**Transfer:** Let the diversity of real voices build trust; avoid turning the archive into a handful of polished identical cards.

### Editorial story and point of view

1. **Vision** — Large serif opening statement and cloud-material word sculpture.
2. **Argument** — Centered serif chapters describe an ideal, its loss and a possible alternative.
3. **Narrative turn** — An exceptional oversized serif statement resets the argument.
4. **Belonging** — A familiar everyday analogy and direct personal welcome.
5. **Closing call** — Shared oversized invitation, small serif sign-off, team note and inset footer.

**Transfer:** Use the serif variant for an actual argument or origin story, not as a random alternate landing-page theme.

## Writing

Candid, idealistic and a little irreverent. The voice treats the reader as a creative person, uses human metaphors and makes its case through recognition rather than productivity superlatives.

**Do not copy:** Do not reuse Sublime's name, symbol, distinctive word sculpture, filename labels, quoted customer statements, customer identities, collection names, counts or brand-specific product and pricing claims. Source examples illustrate cadence only; create truthful material for the new product.

- **Addressing the reader:** Speak directly to you in capabilities and invitations; use we or ours for convictions and origin stories. Marketing copy often uses lowercase, while editorial prose and reading content use conventional sentence case.
- **Rhythm:** Short, conversational headings can break over two to four very narrow lines. Support copy is usually one compact paragraph; editorial prose stacks brief paragraphs with deliberate turns, contrasts and occasional fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar condition followed by a contradiction. | 5–8 words | “inspiration is everywhere. and nowhere.” |
| Supporting line | Product name plus one human outcome, stated plainly. | 8–12 words | “sublime gives your ideas one place to grow.” |
| Capability heading | An ordinary verb and recognizable emotional reaction, not a feature category. | 5–10 words | “save anything that makes you go "whoa”<br>“find the thing, however you remember it” |
| Primary action | A short lowercase invitation with no urgency. | 2 words | “try now” |
| Reassurance | A lightly humorous sentence that lowers commitment. | 7–12 words | “it's free until you can't live without it.” |
| Editorial thesis | A simple hopeful statement with room to breathe. | 4–8 words | “Another world is possible.” |
| Human sign-off | A small wordplay that names a kind of person, not a persona segment. | 7–10 words | “Built for minds that wander. And wonder.” |

**Words and phrasing to use:** grow; wonder; make; save; discover; ideas; a place; labor of love; however you remember it

**Avoid:** 10x productivity; unlock your potential; enterprise-grade; game-changing solution; act now; dominate; AI-powered everything

**Rules:**

- Make the benefit feel lived: describe the imperfect moment a person recognizes.
- Use wit sparingly and matter-of-factly; avoid relentless jokes or exclamation marks.
- Keep capability headings in everyday language and explanations below them short enough for a narrow centered column.
- On editorial pages, state a belief and develop it with contrasts and concrete metaphors instead of bullet-point sales claims.
- Let customer language remain recognizably human, including its informal rhythm, when quoting with permission.

## Do's and Don'ts

### Do

- Use the 120px/108px regular grotesk recipe for the desktop opening promise.
- Keep the main sculpture nearly full width while its support statement stays about 217px wide.
- Repeat 30px-high neutral actions inside chapters; save lime for global access actions.
- Allow 160px above and below capability scenes so each reads as its own exhibit.
- Mix text clippings with photos and notes, preserving varied aspect ratios.
- Set collection captions in 16px Times New Roman, with separate 14px parenthesized counts.
- Close marketing pages with the 64px typographic invitation and detached 975px footer.
- Use flat neutral fills and no drop shadows on cards and footer islands.

### Don't

- Do not spread the pale-lime accent across large section backgrounds; it is a tiny action signal.
- Do not normalize every button into a capsule: ordinary controls use 5px corners, filename labels are pills.
- Do not make every heading black and bold; the later capability text is regular warm gray.
- Do not turn collection counts into oversized numeric statistics; they belong under serif captions.
- Do not replace irregular reference clusters with six identical icon cards.
- Do not add dark full-bleed bands to create chapter separation; the canvas stays white.
- Do not use the 36px centered serif prose style for everyday interface labels; it belongs to editorial storytelling.
- Do not add elevation shadows or strong outlined card edges where tonal gray surfaces already define the grouping.

## Motion and responsive

### Motion

**Observed:**

- Compact action transitions declare 0.15s cubic-bezier(.4, 0, .2, 1) for color and related surface properties.
- The blue exploration action declares transform transitions of 0.2s cubic-bezier(.4, 0, .2, 1).
- The final invitation's label declares a white hover text treatment. A search scene presents a typed fragment and caret.

**Transfer:**

- Keep small action feedback restrained and preserve the sculptural composition when animating it.
- Use a typed fragment only where it helps explain remembered-language search, rather than adding typewriter effects to every heading.

**Unknown:**

- Exact choreography and timing of artwork and scroll reveals are not established.
- Active scale serialization does not establish a reliable visual scale change.

### Responsive

**Observed:**

- Declared spacing distinguishes 30px desktop content padding from 15px mobile content padding.
- Responsive classes change the footer from a horizontal navigation arrangement to a vertical one and reduce its maximum width to 500px.
- Declared viewport breakpoints include 640px, 768px, 1024px and 1280px.

**Transfer:**

- On narrow screens, preserve the overlapping headline-and-sculpture idea but fit the emblem to the available width and keep its small creature clear of the text.
- Reflow collection and related-content groups into a readable narrow sequence; maintain image aspect ratios rather than shrinking text clippings to illegibility.
- Keep the compact access controls and detached rounded footer, while stacking utility groups vertically.

**Unknown:**

- Exact mobile type sizes and the mobile arrangement of collage scenes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
