# Flutterwave — exuberance on a curve

## Overview

A friendly editorial style where chunky, characterful serif headlines meet clean geometric sans-serif text and exuberantly colored artwork. White space and deep inky text keep the surrounding interface restrained, while peach bands, illustrated stories and large photographic galleries carry the personality. It suits creative products, community-led platforms and teams that want to feel accomplished without sounding corporate.

### Essentials

- A greeting feels like a printed masthead: centered Millik at 60px, weight 800 and -0.8px tracking, paired with Moderat at 20px/32px in a 750px text measure.
- The opening bends the gallery rather than the typography: a full-width ribbon of 360×500px image cards is cut by opposing shallow curves, with 100px center deflection across 1440px and neighboring cards clipped at the edges. Recreate it with original illustrated product metaphors when photography is unavailable.
- Color lives mostly inside media: retain a predominantly white canvas, inky headings, one peach #fcd2ba gallery band and a small amber #f5a623 conversion control rather than tinting every section.
- Actions are editorial, not pill-shaped: ordinary navigation is unboxed 18px text; collection links are 14px uppercase with a circled arrow; carousel controls are 50px outlined circles; the joined email action is a 68px-high rectangle with 5px outer corners.
- Media is the proof and the decoration: saturated illustration and tactile 3D sit in minimally rounded 5px frames, while captions remain small and outside the artwork. Include an expansive media-led device, using a simple original geometric scene as the minimum fallback.
- The closing invitation is spacious but domestic: a 32px Millik heading, 16px/26px support line, 550px joined email form and 130px vertical padding precede a faint dashed rule and a spare 60px-padded footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery peach | `#fcd2ba` | `--color-peach` | background | Full-bleed gallery band, separated from white editorial sections. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action amber | `#f5a623` | `--color-amber` | action, surface | Joined newsletter submit control; a small warm focal point rather than a page-wide brand wash. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface | Main page canvas and unfilled form area. |
| Overlay cream | `#fff9f1` | `--color-cream` | text | Readable titles and bylines over darkened opening media. |
| Dashed fog | `#d1d1d1` | `--color-rule` | border | Visible charcoal-at-20% footer separator over white. |
| Charcoal | `#171717` | `--color-ink` | text, border | Body text, navigation, icons and strong outlines; also the source hue for 50% media scrims and 20% dashed rules. |
| Midnight ink | `#12122c` | `--color-heading` | text | Default headings and story titles. |
| Button black | `#000000` | `--color-black` | text | Newsletter action lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| team or capability explainers | Soft lemon | `#ffeeb3` | `--color-lemon` | surface | First explanatory illustrated card. |
| team or capability explainers | Soft sky | `#a8dcea` | `--color-sky` | surface | Second explanatory illustrated card. |
| team or capability explainers | Dusty rose | `#e7b2ad` | `--color-rose` | surface | Third explanatory illustrated card. |
| team or capability explainers | Soft mint | `#a9e5c6` | `--color-mint` | surface | Fourth explanatory illustrated card. |
| people spotlights | Portrait berry | `#bd4355` | `--color-berry` | text | Active portrait surname accent, with first name remaining midnight ink. |
| culture storytelling | Deck apricot | `#eea87c` | `--color-deck-orange` | surface | Rear illustrated card in a rotating deck. |
| culture storytelling | Deck blue | `#2d9cdb` | `--color-deck-blue` | surface | Second illustrated deck layer. |
| culture storytelling | Deck lilac | `#cad0f7` | `--color-deck-lilac` | surface | Third illustrated deck layer. |
| culture storytelling | Deck seafoam | `#6fc3b7` | `--color-deck-teal` | surface | Fourth illustrated deck layer. |
| culture storytelling | Deck citron | `#f2f091` | `--color-deck-yellow` | surface | Fifth illustrated deck layer. |
| culture storytelling | Deck coral | `#f29191` | `--color-deck-coral` | surface | Front illustrated deck backing. |

## Typography

- **Millik** — Hero, collection titles, section leads and closing invitation. Heavy, soft-edged display serif with jaunty wedge-like terminals and a dense, friendly silhouette. If unavailable, use **Fraunces**. Use 700–800 with a low optical size and restrained softness; preserve the broad silhouette. Font stack: "Millik", "Fraunces", Georgia, serif.
- **Moderat** — Body text, navigation, article titles and small metadata. Geometric sans with open circular forms, compact titles and clear regular-weight prose. If unavailable, use **DM Sans**. Use 400–800; keep the tightly tracked titles distinct from untracked prose. Font stack: "Moderat", "DM Sans", Inter, Arial, sans-serif.
- **Flutterwave** — Newsletter submit label. A small serif-looking action label contrasting with the surrounding sans-serif form. If unavailable, use **Libre Caslon Text**. Regular weight; keep this confined to the joined submit control. Font stack: "Flutterwave", "Libre Caslon Text", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Millik | 800 | 60px | 58px | -0.0133em | Centered two-line opening headline and short collection titles. |
| section-heading | Millik | 700 | 32px | 31px | -0.025em | Editorial section labels, media-overlay titles and closing invitation. |
| story-title | Moderat | 600 | 22px | 26px | -0.0364em | Compact one-to-three-line article titles below images. |
| lead | Moderat | 400 | 20px | 1.6 | normal | Centered introduction below the main headline. |
| navigation | Moderat | 400 | 18px | 22px | normal | Unboxed header links and footer text. |
| body | Moderat | 400 | 16px | 1.625 | normal | Explanatory card prose, bylines and closing support. |
| submit-label | Flutterwave | 400 | 16px | 19px | normal | Label on the joined amber submit control. |
| collection-link | Moderat | 600 | 14px | 17px | normal, uppercase | Right-aligned collection action next to a section lead. |
| category | Moderat | 600 | 12px | 15px | normal, uppercase | Small article category above its title. |
| metadata | Moderat | 500 | 12px | 15px | normal, uppercase | Date and reading duration separated by a small dot. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| people spotlights | person-name | Moderat | 800 | 60px | 72px | -0.0133em | Two-line name beneath an active portrait. |
| team or capability explainers | chapter-heading | Millik | 800 | 50px | 49px | -0.016em | Centered narrative chapter heading. |
| team or capability explainers | capability-title | Moderat | 700 | 32px | 39px | -0.025em | Title inside a pastel explanatory card. |
| standalone inspiration galleries | gallery-credit | Moderat | 500 | 16px | 19px | normal | Medium-weight artwork category and maker credit; regular-weight poster attribution follows a vertical divider. |

**Notes:**

- Keep the chunky serif for statements and section markers; use the sans for article titles even when both appear in the same section.
- Tracking is consistently -0.8px on display and title roles rather than one shared em value; body and metadata retain normal spacing.
- The opening is a compact two-line statement, not a thin oversized word sculpture. Let the media ribbon supply the visual drama.

## Layout

**Density:** Airy around sections and compact inside editorial cards; the large image areas supply richness without dense interface chrome.

### Spacing

**Spacing system:**

- **step** 10px — Dominant layout rhythm for margins and padding; retain the specific editorial exceptions rather than forcing everything onto this step.

| Value | Use |
| --- | --- |
| 12px | Title-to-date spacing and small control separation. |
| 20px | Heading-to-intro gap and article-image-to-text gap. |
| 24px | Editorial grid gutter. |
| 30px | Section-header-to-gallery gap and gallery ribbon gutter. |
| 40px | Support-to-form gap and capability-grid gutter. |
| 60px | Opening offset beneath navigation and footer vertical padding. |
| 70px | Standalone masonry item bottom spacing. |
| 120px | Desktop outer content inset. |
| 130px | Closing invitation vertical padding. |
| 160px | Narrative chapter separation in explanatory pages. |
| 180px | Major editorial-section separation in the default landing composition. |

### Containers and grids

- **page-container**: max width 1920px · side padding 120px. Centered outer shell; at 1440px the inner content is 1200px wide. Full-bleed media bands break outside this shell.
- **intro-measure**: max width 750px. Centered default hero headline and lead.
- **editorial-grid**: 3 columns · gap 24px. Equal 384px media columns across the desktop content area.
- **newsletter-form**: max width 550px · 2 columns · gap 0px. 400px input joined to a 150px submit control.
- **capability-grid** (only for team or capability explainers): 2 columns · gap 40px. Centered 518px illustrated explanatory cards, with 60px vertical row separation.
- **masonry-gallery** (only for standalone inspiration galleries): 2 columns · gap 54px · side padding 50px. Two independent image columns of 523px inside the main shell; variable image heights deliberately desynchronize rows.

## Corner radius

| Element | Radius |
| --- | --- |
| media and cards | 5px |
| carousel controls | 50% |
| joined form outer corners | 5px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing and editorial background.

**CSS:** `background: #ffffff; color: #171717`

**Observed:** Flat and untextured; depth comes from artwork and generous white margins, not elevated interface panels.

**Transfer:** Keep text sections on white and isolate decorative color in media or a gallery band.

#### Peach gallery band · level 0

**Use:** Full-width change of tempo behind an expansive media strip.

**CSS:** `background: #fcd2ba; padding: 82px 0 117px`

**Observed:** The section header follows the main content alignment while the image track extends beyond both viewport edges.

**Transfer:** Use as a visual interlude or proof collection rather than tinting every content block.

#### Media scrim · level 1

**Use:** Legibility layer over the opening illustrated cards.

**CSS:** `background: rgba(23, 23, 23, 0.5); color: #fff9f1; padding: 10px`

**Observed:** A flat dark veil covers the entire image. Centered cream title and byline sit above it; no glass blur or gradient edge.

**Transfer:** Retain saturated artwork beneath the scrim and limit overlay text to a short title and attribution.

#### Pastel explainer · level 1

**Only for:** team or capability explainers

**Use:** Illustration and substantial explanatory text grouped in one flat block.

**CSS:** `background: #ffeeb3; border-radius: 5px; overflow: hidden`

**Observed:** Lemon, sky, dusty rose and mint variants share the same construction. A full-width illustration fills the top; the lower text surface matches its backing.

**Transfer:** Assign one pastel per capability; retain the same component dimensions and text hierarchy.

## Components

### Navigation

**Use:** A spare top-level wayfinding strip.

**CSS:** `display: flex; position: relative; justify-content: space-between; align-items: center; padding: 0px 50px; height: 85px`

**Text style:** `navigation` — Moderat 400 · 18px/22px

**Observed:** A small symbol and bold word label sit left. Four plain text links sit right, separated by 50px margins, followed by two small light/dark mode dots. The navigation is part of the document rather than a floating capsule.

**Transfer:** Use a compact identity lockup and a short set of destinations; do not give every link a button surface.

### Collection link

**Use:** Secondary action aligned opposite an editorial section title.

**CSS:** `display: flex; align-items: center; color: #171717; text-transform: uppercase`

**Text style:** `collection-link` — Moderat 600 · 14px/17px · uppercase

**Observed:** Text is followed by a small outlined circular right-arrow icon; the combined action is about 158×25px.

**Transfer:** Use a short verb phrase naming the destination collection.

### Featured media card

**Use:** Image-led item in the curved opening ribbon.

**CSS:** `width: 360px; height: 500px; position: relative; overflow: hidden`

**Text style:** `section-heading` — Millik 700 · 32px/31px · tracking -0.025em

**Observed:** An edge-to-edge image sits below the Media scrim. Title is centered with a byline below, separated by 30px; neighboring cards repeat horizontally beyond the viewport.

**States:** Declared: hover underlines the linked title; focus-visible styling is unspecified.

**Transfer:** Use product outcomes or stories as the card subject and keep the artwork stronger than the accompanying copy.

### Carousel arrow

**Use:** Small directional control beneath the opening ribbon.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 50px; height: 50px; border: 1px solid #171717; border-radius: 50%; padding: 1px 6px; margin-right: 12px`

**Observed:** A simple 14×12px arrow is centered inside the circle.

**States:** Declared: hover background #171717 and transform scale(1.2); focus-visible styling is unspecified.

**Transfer:** Use this circular geometry for media navigation, not for text conversion actions.

### Editorial card

**Use:** Preview of a story or article.

**CSS:** `display: flex; flex-direction: column; width: 384px; color: #12122c`

**Text style:** `story-title` — Moderat 600 · 22px/26px · tracking -0.0364em

**Observed:** A 384×250px image with 5px corners leads. After 20px comes a category when present, then the title and date/duration line. The card has no surrounding colored panel, border or shadow; title margins are 11px above and 12px below.

**States:** Declared: hover underlines linked titles; focus-visible styling is unspecified.

**Transfer:** Keep a consistent image ratio and permit natural title wrapping rather than forcing all titles to one line.

### Gallery tile

**Use:** Large attributed image in the peach media ribbon.

**CSS:** `width: 400px; color: #171717`

**Observed:** A 400×570px image has 5px corners and an 18px gap to a 14px caption. Caption order is medium/category, maker in parentheses, a vertical divider and poster attribution. Standalone galleries use 523px-wide variable-height images and 16px credit text.

**Transfer:** Give visual authorship a visible place outside the image rather than adding a badge overlay.

### Email input

**Use:** Left half of the joined closing form.

**CSS:** `width: 400px; height: 68px; padding: 20px 32px; border-top: 1px solid #171717; border-bottom: 1px solid #171717; border-left: 1px solid #171717; border-right: 0px; border-radius: 5px 0px 0px 5px`

**Observed:** The input and submit control touch without a gap and read as one outlined rectangle. Placeholder copy is friendly rather than a terse technical field name.

**Transfer:** Use one email field; preserve the outlined joined construction.

### Subscribe button

**Use:** Primary action attached to the email input.

**CSS:** `width: 150px; height: 68px; padding: 1px 6px; background: #f5a623; color: #000000; border-top: 1px solid #171717; border-right: 1px solid #171717; border-bottom: 1px solid #171717; border-left: 0px; border-radius: 0px 5px 5px 0px`

**Text style:** `submit-label` — Flutterwave 400 · 16px/19px

**Observed:** A small centered serif-like label gives the utilitarian form a subtly editorial finish.

**States:** Declared: hover on the form ancestor changes the visible button border to amber with no left border; focus-visible styling is unspecified.

**Transfer:** Reserve this amber filled rectangle for a compact conversion action.

### Footer strip

**Use:** Minimal page ending after the closing invitation.

**CSS:** `display: flex; position: relative; justify-content: space-between; align-items: center; padding: 60px 0px; border-top: 1px dashed rgba(23, 23, 23, 0.2)`

**Text style:** `navigation` — Moderat 400 · 18px/22px

**Observed:** Copyright and a parent-site link form the left group; three dark social glyphs form the right group. There is no multi-column sitemap.

**Transfer:** Keep the ending low-density and horizontal, with a subdued separator.

### Capability card

**Only for:** team or capability explainers

**Use:** Detailed illustrated explanation of a capability.

**CSS:** `max-width: 570px; background: #ffeeb3; border-radius: 5px; overflow: hidden`

**Text style:** `capability-title` — Moderat 700 · 32px/39px · tracking -0.025em

**Observed:** At desktop the card is 518×493px with a 518×232px top illustration. The text area uses 40px top/bottom padding, 36px left and 70px right; a 12px gap separates heading from 16px/26px prose. Pastel variants are defined by Pastel explainer.

**Transfer:** Explain the value of a capability in a short paragraph rather than replacing the illustration with a generic icon.

## Imagery and graphics

### Curved illustrated ribbon

**Use:** Signature expansive media object in the default landing opening.

**Observed:** Bright conceptual editorial illustrations mix rendered objects, expressive hands, abstract planes and simplified interface fragments. The track is darkened for cream overlaid text and clipped into a concave upper edge with an opposing lower edge; the center is shorter than the sides. Cards fill the viewport width and continue off-screen.

**Transfer:** Create original visual metaphors for the new product's benefits. A minimum viable treatment is three vivid collages of simple SVG shapes and product-related objects beneath the same dark scrim and curved mask.

**Build:** Place 360×500px image cards in a horizontal track with about 25px gaps. Apply a full-track SVG mask with viewBox 0 0 1440 500 and preserveAspectRatio none: path M 0 0 C 275 100 445 100 720 100 C 995 100 1165 100 1440 0 V 500 C 1165 400 995 400 720 400 C 445 400 275 400 0 500 Z. Keep the cards rectangular beneath the shared mask; layer rgba(23,23,23,0.5) over each artwork before adding text. Use a white mask path and transparent exterior.

### Editorial concept illustrations

**Use:** Article thumbnails and illustrated explanatory cards.

**Observed:** Scenes favor saturated greens, purples, yellows and coral, with soft gradients, paper-like grain and occasional softly lit 3D. Hands, floating interface fragments, stationery and playful objects tell a concept in a single wide composition. Images are rectangular, sharply readable and minimally rounded, without external shadows.

**Transfer:** Commission or assemble a coherent set of original concept scenes. If complex rendering is unavailable, use a few bold vector silhouettes, one contrasting background shape and restrained grain rather than unrelated stock icons.

### Attributed inspiration collection

**Use:** Peach gallery interlude; expanded as a standalone visual archive.

**Observed:** Portrait paintings, expressive character illustration, interiors, architecture, travel photos and pastel 3D scenes mix freely. Color stays native to the media. Wide white gutters and tiny maker/poster credits let the pictures occupy far more area than text; the archive uses variable heights rather than uniform crops.

**Transfer:** Curate media that communicates the new product's sensibility or community. Keep the range intentional and the credit structure consistent; do not apply one blanket tint to every image.

### Orbiting portrait spotlight

**Only for:** people spotlights

**Use:** Human-centered opening on team-oriented pages.

**Observed:** The active square portrait is 432px wide, front-facing and in full color, with two large centered name lines beneath. Tilted grayscale neighboring portraits are clipped at the left and right edges; the active surname is colored and a small role line follows.

**Transfer:** Use genuine portraits and a personal name/role treatment, reserving this carousel as a human-centered alternative to the default illustrated opening.

**Build:** Center a square 5px-rounded portrait in a white stage. Place the previous and next portraits partly outside the viewport, tilted away in opposite directions and filtered grayscale(1). Keep the center at grayscale(0); put the two-line 60px sans name below with the second line in an accent. The simplified layout should preserve the active-versus-neighbor contrast without requiring a full orbital engine.

### Fanned illustrated deck

**Only for:** culture storytelling

**Use:** A compact tactile device following a centered narrative introduction.

**Observed:** Six square illustrated cards share a 430px base size and 5px corners, stacked at rotations of 20, 16, 12, 8, 4 and 0 degrees. The visible art is a grainy, colorful miniature world with foliage, a central pedestal and floating objects; colored edges peek from beneath.

**Transfer:** Use an original sequence of benefit, principle or process illustrations. A minimum version uses a simple geometric vignette per card while retaining the rotating colored stack.

**Build:** Use a 430×430px relative wrapper and six absolutely positioned equal-size squares. Rotate successive layers 20deg down to 0deg in 4deg steps around their centers. Use apricot, blue, lilac, seafoam, citron and coral deck backings. Render the foreground vignette in SVG with a central ellipse-topped pedestal, curving stems, simple leaves and a few floating symbols; add a faint SVG noise layer inside the artwork, not across the page.

### Icons

**Observed:** Most interface symbols are charcoal silhouettes or very simple arrows. Social glyphs are about 24–25px; the carousel arrow is 14×12px. Collection arrows have thin circular outlines. The light/dark switches are paired 21px circular swatches with dotted contrasting edges.

**Transfer:** Choose recognizable compact social silhouettes and plain directional arrows. Avoid turning content cards into icon grids or adding multicolor interface pictograms.

## Section recipes

How recurring sections are built.

### First screen: Greeting and curved gallery opening

**Observed:** A White canvas carries the 85px Navigation, then a centered two-line 60px serif headline beginning about 60px below it. The headline spans about half the viewport, with the second line wider; a greeting and inline hand emoji make it personal. A 750px-wide 20px/32px lead follows with 20px separation. Beneath the text, the Curved illustrated ribbon reaches both viewport edges, showing roughly three complete cards plus clipped neighbors. Layer order is white canvas, vivid artwork, Media scrim, centered cream titles and bylines, then the shared curved mask. Carousel arrow controls sit near the lower center. Within the first 900px the navigation, headline, lead, large ribbon and its controls are visible; the next editorial grid falls below the fold. There is no separate filled hero CTA.

**Transfer:** Replace the greeting with a warm concise product promise and create original benefit illustrations for the ribbon. Preserve the shared curved silhouette even with simpler SVG collage media. Editorial collections instead open with one centered 60px title and a short lead before the grid; human-centered pages use Orbiting portrait spotlight.

**Avoid:** Do not replace this composition with a left-aligned SaaS headline, two pill CTAs and a single floating dashboard. Do not curve each card independently or remove the edge-to-edge continuity of the mask.

**Text style:** `display` — Millik 800 · 60px/58px · tracking -0.0133em

### Editorial section and card row

**Observed:** A 32px serif section label sits left and Collection link sits right on one baseline. After 30px, a three-column Editorial card grid fills the 1200px inner width with 24px gutters. The default composition leaves 180px between major sections.

**Transfer:** Use this structure for related resources, proof stories or educational content; let each illustration explain one idea.

**Text style:** `section-heading` — Millik 700 · 32px/31px · tracking -0.025em

### Peach media interlude

**Observed:** Peach gallery band contains the same aligned heading/action pair but a full-width horizontal track of Gallery tile items. Portrait-oriented 400×570px images have 30px gutters, captions below and clipped neighboring images at both edges.

**Transfer:** Use an expansive visual collection as a pacing device between white text-led regions; content can be customer work, applications or community imagery.

### Closing invitation and spare footer

**Observed:** On white, a centered 32px serif invitation is followed by a 16px/26px support line after 15px and a joined 550×68px email form after 40px. The block has 130px top and bottom padding. Footer strip follows with a faint dashed separator, copyright and parent-site link on the left, and three social icons on the right.

**Transfer:** Offer a continuing relationship rather than ending with an oversized sales slogan. Use the same construction for a concise update list or community invitation.

**Text style:** `section-heading` — Millik 700 · 32px/31px · tracking -0.025em

### Centered chapter and pastel explainers

**Only for:** team or capability explainers

**Observed:** A centered 50px serif heading is paired with a 20px/32px paragraph in a 780px measure, separated by 20px. Two-column Capability card groups begin about 50px below the introduction. Subsequent chapters are separated by 160px.

**Transfer:** Use for a small family of capabilities or disciplines that deserve prose, not just labels.

**Text style:** `chapter-heading` — Millik 800 · 50px/49px · tracking -0.016em

### Standalone visual archive

**Only for:** standalone inspiration galleries

**Observed:** A single centered 60px serif title sits above a 20px/32px introduction up to 900px wide. The gallery begins 100px after the introduction. Two independent columns of 523px images retain varied proportions, captions underneath and 70px item separation. The last image leads directly toward the shared closing invitation.

**Transfer:** Use when browsing imagery is itself the purpose. Keep the low text density and natural image heights rather than imposing the editorial article grid.

**Text style:** `display` — Millik 800 · 60px/58px · tracking -0.0133em

### Fanned story object

**Only for:** culture storytelling

**Observed:** A centered chapter-heading and lead introduce a large white stage; the Fanned illustrated deck sits centrally with 140px separation from its introductory block. It has presence as one layered object rather than a multi-column list.

**Transfer:** Use a deck to make a small set of ideas feel tangible and collectible; preserve the artwork-rich front face.

**Text style:** `chapter-heading` — Millik 800 · 50px/49px · tracking -0.016em

## Page flow

**Storyline:** warm introduction → expansive visual proof → browsable editorial or capability material → continuing-relationship invitation → spare utility ending

### Brand-led landing page balancing personality and discovery

1. **promise** — Centered greeting and short self-description above the curved illustrated ribbon.
2. **editorial proof** — A three-card selection with small metadata and a collection link.
3. **visual breadth** — Peach-backed, edge-clipped image gallery with external credits.
4. **closing call** — Centered email invitation and joined amber action.
5. **utility ending** — Dashed rule, copyright, parent link and social icons.

**Transfer:** Make the opening product promise specific, then demonstrate breadth through media and a compact resource collection. Preserve the visual devices without requiring the same subject matter.

### Editorial archive for learning and deeper product stories

1. **orientation** — Single centered serif title and two-line explanatory lead.
2. **browse** — Long three-column article grid of colorful thumbnails, category, title and date/duration.
3. **closing call** — The grid ends before the shared email invitation.
4. **utility ending** — The same minimal dashed-rule footer.

**Transfer:** Use the card grammar for guides, release stories or case studies; do not replace a substantial archive with a short landing-page strip.

### Human and capability narrative

1. **human introduction** — Active color portrait in a tilted grayscale orbit, with a large two-line name.
2. **context** — Centered serif chapter title and concise team description.
3. **capability chapters** — Two-column pastel illustration-and-prose cards.
4. **principles** — Centered heading and a fanned illustrated deck.
5. **closing call** — Shared spacious email invitation.
6. **utility ending** — Shared low-density footer strip.

**Transfer:** Use genuine people and original capability explanations. Treat the portrait orbit and deck as scoped storytelling devices, not required product modules.

### Image-first archive of taste and community

1. **orientation** — Centered serif title and a longer conversational explanation of the collection.
2. **visual exploration** — Long, staggered two-column image gallery mixing photography, art and rendered scenes with credits.
3. **closing call** — The final image gives way to the shared email invitation.
4. **utility ending** — Minimal footer with a dashed separator and social glyphs.

**Transfer:** Curate a visual universe connected to the new product, retain image authorship and let the archive's length follow the material.

## Writing

Warm, self-aware and enthusiastic about making things. Confidence is expressed through concrete work and conversational explanations rather than grandiose market claims.

**Do not copy:** Do not reuse the Flutterwave identity, team names, artwork, maker attributions, article claims, proprietary product facts or source-specific slogans. Source examples illustrate voice only; write new claims grounded in the new product.

- **Addressing the reader:** The organization speaks as we and our; use you or your for invitations. People and their work are named rather than hidden behind institutional language.
- **Rhythm:** Short noun-like collection headings, a compact two-line opening, then one or two conversational support sentences. Article titles can be full questions or explanatory phrases; emoji appear sparingly in welcomes and personal introductions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Direct friendly introduction with an occasional personal gesture. | 6–12 words | “Hello! 👋🏾 We’re the [Brand] Design team” |
| Supporting introduction | Name what the group does, then add a human interest or motive. | 20–45 words | “We are the designers at [Brand], aka FWDT. We enjoy creating beautiful product experiences, writing, photography and just general vibes.” |
| Section heading | Short literal name for the material that follows. | 1–4 words | “Latest Stories”<br>“Our disciplines” |
| Article title | A useful question or an explicit learning outcome, occasionally with a colon. | 5–13 words | “UX KPIs: What, Why, and How”<br>“Do Design systems Limit Creativity?” |
| Primary action | One familiar verb with no promotional qualifier. | 1–3 words | “Subscribe” |
| Input invitation | Treat an administrative step as a friendly welcome. | 8–12 words | “We saved a nice spot for your email” |
| Secondary action | View all plus the collection name. | 3–4 words | “View all stories” |

**Words and phrasing to use:** we; our; beautiful; delightful; building; experiences; stories; things we love

**Avoid:** revolutionary; industry-leading; unlock unprecedented; synergy; dominate; guaranteed transformation

**Rules:**

- Lead with what people make or experience, not abstract corporate positioning.
- Keep action labels familiar; save the warmth for headings and support copy.
- Use a concrete analogy to explain a broad capability, as with a multifunctional tool, without turning every sentence into a metaphor.
- Keep attribution factual and visually secondary; distinguish maker from poster.
- Use sentence case in prose; reserve uppercase for small collection actions, categories and dates.

## Do's and Don'ts

### Do

- Keep default hero type at 60px with -0.8px tracking and a centered 750px measure.
- Preserve the shared 100px-deflection curved media mask as a recognizable opening device.
- Use 384×250px editorial thumbnails with 5px corners and 24px grid gutters.
- Keep media overlay text cream and use the charcoal 50% scrim for legibility.
- Let a peach #fcd2ba band carry the broadest interface color field while most text sections stay white.
- Maintain the 550×68px joined email form and its 150px amber action.
- End with the 1px dashed separator and 60px footer padding rather than adding dense utility columns.
- Keep human and culture treatments scoped: 60px sans names for portraits, 50px serif headings for explanatory chapters.

### Don't

- Do not convert all actions into rounded pills; the filled action has 5px outer corners only.
- Do not add drop shadows or blurred glass to flat editorial cards.
- Do not put article titles in the display serif; their default is 22px Moderat, weight 600.
- Do not extend negative heading tracking into 20px/32px body introductions.
- Do not replace the rich illustration palette with monochrome blue interface mockups throughout.
- Do not make amber a full-page background or a color for every navigation link.
- Do not overlay gallery credits on images; reserve overlay type for the featured ribbon.
- Do not impose equal-height thumbnail crops on the standalone masonry archive.

## Motion and responsive

### Motion

**Observed:**

- Declared media transitions use 1.2s cubic-bezier(0.16, 1, 0.3, 1).
- Declared circular-control hover uses 0.8s cubic-bezier(0.16, 1, 0.3, 1), darkens the background and scales to 1.2.
- Declared form borders transition over 0.2s ease-out.
- Declared portrait filters transition over 0.5s ease-out; portrait text transforms use 0.7s cubic-bezier(0.16, 1, 0.3, 1), including 90ms staggering.
- Declared illustrated-deck transforms use 0.36s cubic-bezier(0.16, 1, 0.3, 1) with successive 72ms delay increments.
- The opening support line has a declared 0.6s linear fade and 1s slide using the main easing, both delayed 2s.

**Transfer:**

- Use the long decelerating movement for image tracks and object arrangements, and the much shorter border transition for the form.
- Keep portrait emphasis tied to active color versus grayscale neighbors, with staggered name motion.
- Preserve readable text and a complete curved silhouette in a reduced-motion version rather than depending on an entrance to reveal essential content.

**Unknown:**

- Autoplay behavior, drag physics and exact sequencing of the orbital portrait carousel are not established.
- Focus-visible designs and reduced-motion source behavior are unspecified.

### Responsive

**Observed:**

- Width breakpoints are declared at 480px, 600px, 750px, 768px, 900px, 980px, 1024px, 1200px, 1280px, 1400px, 1440px and 1920px.

**Transfer:**

- On narrow screens, reduce shell padding before sacrificing image presence. Keep edge-clipped tracks and a shared curved mask instead of shrinking five cards into one viewport.
- Stack explanatory and editorial cards when their text measures become cramped; retain natural-height imagery in an image archive.
- Allow the joined form to shrink as one unit while retaining its rectangular outer corners and readable action.

**Unknown:**

- Narrow-screen navigation, exact type reductions and breakpoint-specific column counts are not established.
- No source viewport-relative typography formula is available; desktop type sizes are the defined reference.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
