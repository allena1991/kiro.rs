# Superpower — human warmth, clinical clarity

## Overview

An airy, predominantly white visual language pairs everyday human stories with cinematic amber light. Regular-weight grotesk typography, restrained gray surfaces and translucent controls give complex services an approachable, premium feeling. Photography and real interfaces carry more of the persuasion than decoration, making the style suited to membership products, personal technology and expert-led services.

### Essentials

- Headlines feel conversational rather than monumental: regular grotesk at 56.2px/1 with -0.02em tracking for the opening, and 45px/1.2 with -0.0225em tracking for major chapters.
- The opening is a film still, not a dashboard billboard: an 810px-high image stage below an 83px header, 7.5px outer gutters, 11.2px corners and a left-aligned text block about 555px wide against a dark silhouette and amber halo.
- Actions read as soft capsules: 47px white and translucent pills over imagery, 13.1px by 18.7px padding, paired at a 15px gap; dark capsules take over on white sections.
- Color lives inside the light and the people: most reading sections remain white or #fafafa; amber occupies immersive media, while #fc5f2b is reserved for tiny link or audio accents rather than broad interface fills.
- Explanation proceeds through pictures before paragraphs: four near-square process images, 294px wide at desktop with 7.5px gaps, combine human activity, interface fragments and restrained glass annotations.
- A luminous human scene and a paper-like footer form a signature ending: white 56.2px headlines over warm light, followed by a white 11.2px-radius footer inset 22.5px into the same photographic world. Recreate the amber-lit atmosphere with a silhouette or product still-life when portrait film is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fc5f2b` | `--color-accent` | link, accent | Inline editorial links, footer-link hover and played audio waveform marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Default canvas and paper panels; reversed text and the primary action over photographs. |
| Off-white | `#fafafa` | `--color-band` | background, surface | Alternating proof bands, striped lists and pale portrait backings. |
| Cool stage | `#f4f4f5` | `--color-stage` | background, surface | Immersive product-stage backing and subtle image frames. |
| Hairline gray | `#e4e4e7` | `--color-rule` | border, surface | Card outlines, section separators and pale controls. |
| Input edge | `#cccccc` | `--color-input-edge` | border | Newsletter field outlines. |
| Tertiary gray | `#a1a1aa` | `--color-tertiary` | text | Group labels, metadata and fine print. |
| Secondary gray | `#71717a` | `--color-secondary` | text | Supporting paragraphs and secondary descriptions. |
| Primary ink | `#18181b` | `--color-ink` | text, background | Headings, body copy and dark neutral panels. |
| Action black | `#111111` | `--color-action` | action, background | Solid conversion buttons on light sections. |
| Media black | `#000000` | `--color-black` | background, text | Photographic darkening gradients and purchase-section display copy. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial stories | Reading charcoal | `#3f3f46` | `--color-article-ink` | text | Long-form article paragraphs. |

## Typography

- **Nb international pro webfont** — All marketing headings, copy, numerals and controls. A clean grotesk with open counters, compact widths and an unusually consistent regular weight throughout the hierarchy. If unavailable, use **Inter**. Use weight 400 and retain the tight display tracking; tune line breaks to preserve compact heading widths. Font stack: "Nb international pro webfont", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Nb international pro webfont | 400 | 56.2px | 1 | -0.02em | Opening and cinematic closing headlines. |
| heading | Nb international pro webfont | 400 | 45px | 1.2 | -0.0225em | Major chapter titles, often two lines within a 585px text measure. |
| process-heading | Nb international pro webfont | 400 | 37.5px | 1.2 | normal | Centered process introduction. |
| card-heading | Nb international pro webfont | 400 | 22.5px | 1.4 | -0.0166667em | Process-card titles and substantial proof descriptions. |
| body | Nb international pro webfont | 400 | 16.9px | 1.5 | -0.0074em | Section support paragraphs. |
| compact | Nb international pro webfont | 400 | 15px | 1.4 | normal | Buttons, footer links and short process descriptions. |
| support | Nb international pro webfont | 400 | 15px | 1.5 | -0.013em | Compact hero support and secondary card captions. |
| caption | Nb international pro webfont | 400 | 13.1px | 1.4 | normal | Small eligibility labels, footer supporting copy and metadata. |
| navigation | Nb international pro webfont | 400 | 13.1px | 1.5 | normal | Compact desktop navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified proof sections | stat | Nb international pro webfont | 400 | 65.6px | 1 | -0.0206em | Three-column numerical proof; percent sign is a separate 22.5px element aligned to the bottom. |
| purchase sections | purchase-display | Nb international pro webfont | 400 | 56.2px | 1.07 | -0.025em | Purchase-block title and price. |
| editorial stories | pull-quote | Nb international pro webfont | 400 | 30px | 1.25 | -0.02em | Opening first-person story quote. |
| purchase sections | faq-question | Nb international pro webfont | 400 | 16.9px | 1.25 | -0.009em | Purchase-section accordion questions. |
| editorial stories | article-body | Nb international pro webfont | 400 | 15.9px | 1.4 | normal | Long-form story paragraphs. |
| review collections | review-body | Nb international pro webfont | 400 | 15px | 1.55 | -0.013em | Dense testimonial masonry copy. |

**Notes:**

- Keep the main hierarchy at weight 400. Size, line breaks and negative tracking provide emphasis instead of bold cuts.
- Use sentence case even for small labels. Compact navigation and captions remain normally tracked.
- Display sizes here are desktop recipes; preserve their relationships rather than inflating headlines to fill all available width.

## Layout

**Density:** Airy at section scale, compact inside lists and controls; broad media stages alternate with narrow readable content.

### Spacing

**Spacing system:**

- **rhythm** 7.5px — Base rhythm for gutters, media gaps and section multiples; fractional steps also occur in control padding.

| Value | Use |
| --- | --- |
| 7.5px | Tight heading-to-support gaps and process-grid gutters. |
| 15px (2 × 7.5px) | Paired-action gap and small proof-header spacing. |
| 22.5px (3 × 7.5px) | Text stacks, footer frame inset and process-card top padding. |
| 30px (4 × 7.5px) | List-to-title and accordion stack spacing. |
| 45px (6 × 7.5px) | Process header-to-grid gap and substantial internal stack breaks. |
| 60px (8 × 7.5px) | Hero internal inset and heading-to-expert-row separation. |
| 75px | Purchase and value-section vertical padding. |
| 89.9px | Footer vertical padding and alternate section rhythm. |
| 104.9px | Default major-section vertical padding, 14 rhythm units. |
| 112.4px | Broad testimonial-band vertical padding, 15 rhythm units. |

### Containers and grids

- **content**: max width 1199px · side padding 37.5px. Centered desktop content, producing about 120px exterior margins at a 1440px viewport.
- **process-grid**: 4 columns · gap 7.5px. Four equal image-led steps with text below, not enclosed in individual painted boxes.
- **feature-split**: 2 columns · gap 30px. Text beside a tall lifestyle photograph, each roughly 585px wide.
- **value-list**: max width 600px. Centered compact benefit table beneath a centered title.
- **footer-columns**: 3 columns · gap 30px. Three directory columns beside the independent newsletter and app-discovery block.
- **purchase-split** (only for purchase sections): 2 columns · gap 58.1px. A larger visual gallery beside a narrower conversion column, in a 1 to 0.73 width relationship.
- **article-column** (only for editorial stories): max width 585px. Central reading column with a separate author and reviewer rail on the left.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | media-and-panels | 11.2px |
|  | small-media | 7.5px |
|  | striped-rows | 3.7px |
| purchase sections | purchase-gallery | 22.5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| review collections | testimonial-card | `rgba(0, 0, 0, 0.33) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 17px 24px 0px` | Subtle elevation beneath review masonry cards. |

### Surfaces

#### Canvas · level 0

**Use:** Primary reading canvas.

**CSS:** `background: #ffffff; color: #18181b`

**Observed:** Most explanatory content sits directly on the canvas without a surrounding card.

**Transfer:** Let typography and images group information before adding containers.

#### Proof band · level 0

**Use:** Testimonial and detail chapters.

**CSS:** `background: #fafafa`

**Observed:** Very slight tonal contrast across full-width sections.

**Transfer:** Alternate long white chapters with this nearly white band, keeping chromatic color in the media.

#### Cinematic shade · level 1

**Use:** Readable foreground over immersive media.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0) 0%, #000000 100%); opacity: 0.5; mix-blend-mode: darken`

**Observed:** Darkness protects small white text without flattening the amber light. Business-oriented scenes use a horizontal left-darkening gradient.

**Transfer:** Keep image exposure bright at the focal point and dark at the text edge.

#### Product stage · level 0

**Use:** Full-viewport capability demonstration.

**CSS:** `background: #f4f4f5; overflow: hidden`

**Observed:** A photographic scene fills the stage; progressively blurred layers soften the left half behind copy and controls.

**Transfer:** Use the actual working product within a tactile human scene, with a calm light region for copy.

#### Footer paper · level 1

**Use:** Directory and low-pressure final conversion.

**CSS:** `background: #ffffff; border-radius: 11.2px; padding: 89.9px 37.5px`

**Observed:** An inset white panel sits in a continuing amber photographic background on the default marketing ending. Business and gifting variants end on a plain white directory.

**Transfer:** Keep the panel visually grounded in the closing scene rather than changing to a generic dark footer.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; z-index: 9999; display: flex; align-items: center; justify-content: space-between; gap: 22.5px`

**Text style:** `navigation` — Nb international pro webfont 400 · 13.1px/1.5

**Observed:** At the top, a wide white header about 83px high carries left links, a centered wordmark and right login, dark capsule action and nine-dot menu. On scroll it becomes a compact dark translucent floating capsule with a separate round dot-menu control.

**Transfer:** Preserve the centered brand anchor and compact scrolled silhouette, adapting the link count to avoid collisions.

### White button

**Use:** Primary action over photographs.

**CSS:** `background: #ffffff; color: #18181b; border-radius: 9999px; padding: 13.1px 18.7px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact` — Nb international pro webfont 400 · 15px/1.4

**Observed:** A text-only capsule paired with a glass secondary action. Its natural desktop height is 47px.

**States:** Declared: hover background #e4e4e7 with no shadow; focus-visible 3px solid #4a9eff outline with 4px offset; active background #27272a and 0px 2px 8px rgba(0,0,0,0.2) shadow.

### Glass button

**Use:** Secondary action on cinematic media.

**CSS:** `background: rgba(255, 255, 255, 0.1); color: #ffffff; border-radius: 9999px; backdrop-filter: blur(32px); padding: 13.1px 18.7px`

**Text style:** `compact` — Nb international pro webfont 400 · 15px/1.4

**Observed:** Same natural height and visual weight as the white action, with the photograph visible through it.

**States:** Declared: hover background rgba(255,255,255,0.2); focus-visible 3px solid #4a9eff outline with 4px offset; active background #e4e4e7 and text #52525b.

### Dark button

**Use:** Conversion on light sections.

**CSS:** `background: #111111; color: #ffffff; border: 1px solid transparent; border-radius: 9999px; padding: 13.1px 18.7px; display: flex; justify-content: center`

**Text style:** `compact` — Nb international pro webfont 400 · 15px/1.4

**Observed:** Compact width for ordinary calls to action; stretches across the conversion column in the purchase block. Business sections pair it with a white outlined secondary capsule.

**States:** Declared: hover background #3d3d3d; focus-visible 3px solid #4a9eff outline with 4px offset; active background #27272a and 0px 2px 8px rgba(0,0,0,0.2) shadow.

### Process card

**Use:** A short, pictured explanation step.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `card-heading` — Nb international pro webfont 400 · 22.5px/1.4 · tracking -0.0166667em

**Observed:** Square image first, small numbered translucent marker in its upper corner, then a title and gray compact paragraph. Text begins 22.5px beneath the media and has 22.5px right inset; cards have no outer box.

**Transfer:** Mix object, interaction and outcome imagery across the row; do not substitute four unrelated stock icons.

### Benefit row

**Use:** Compact value or inclusion list.

**CSS:** `display: flex; align-items: center; gap: 52.5px; background: #fafafa; border-radius: 3.7px; padding: 8.4px 11.2px 7.5px`

**Text style:** `body` — Nb international pro webfont 400 · 16.9px/1.5 · tracking -0.0074em

**Observed:** Alternating lightly tinted and unpainted 600px-wide rows, with dark feature names at left and gray clarifications at right; about 40px high.

**Transfer:** Keep the left labels short so the table remains scannable.

### Newsletter field

**Use:** Low-pressure footer signup.

**CSS:** `background: #ffffff; border: 1px solid #cccccc; border-radius: 99px; padding: 8px 12px; height: 45px`

**Text style:** `caption` — Nb international pro webfont 400 · 13.1px/1.4

**Observed:** A long pill input and separate dark Sign up pill share one horizontal row with a 7.5px gap, beneath a compact explanatory sentence.

**Transfer:** Offer a useful resource rather than duplicating the main sales pitch.

### Footer directory

**Use:** Final navigation, signup and trust.

**CSS:** `background: #ffffff; border-radius: 11.2px; padding-top: 89.9px; padding-bottom: 89.9px`

**Text style:** `compact` — Nb international pro webfont 400 · 15px/1.4

**Observed:** Left block holds a modest wordmark, newsletter, app QR and store badge, then five muted AI-discovery icon tiles. Three right columns group product, company, comparisons, partnerships, social and research links. A fine top rule separates the final legal row; muted group names are not bold.

**Transfer:** Retain the asymmetry, practical discovery tools and low-contrast legal row; adapt categories to the new offering.

### Review card

**Only for:** review collections

**Use:** Mixed-media first-person proof.

**CSS:** `background: #ffffff; border: 0.5px solid #e4e4e7; border-radius: 11.2px; box-shadow: rgba(0, 0, 0, 0.33) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 17px 24px 0px`

**Text style:** `review-body` — Nb international pro webfont 400 · 15px/1.55 · tracking -0.013em

**Observed:** Three masonry columns of roughly 343px cards mix text-only, audio and vertical video stories. Copy has about 30px side insets; attribution and a tiny outlined status chip finish the card. Audio has a black circular play button, faint waveform and small duration.

**Transfer:** Let real content set card heights while retaining consistent widths and metadata placement.

### FAQ row

**Only for:** purchase sections

**Use:** Objection handling alongside conversion.

**CSS:** `padding-top: 22.5px; border-top: 1px solid rgba(24, 24, 27, 0.1); display: flex; flex-direction: column`

**Text style:** `faq-question` — Nb international pro webfont 400 · 16.9px/1.25 · tracking -0.009em

**Observed:** Question and small disclosure icon share a line. Rows are separated by 30px; answers use gray body copy. The first row lacks the visible rule.

**States:** Declared: focus-visible 2px solid #18181b outline with 2px offset.

## Imagery and graphics

### Amber human light

**Use:** Signature opening and closing immersive scenes.

**Observed:** A person in profile is silhouetted against a large soft amber circle on near-black; the closing scene brings the face closer and exposes warm skin and curls beside an intense yellow-orange light. These images cover almost the entire stage, while text occupies the darker left portion.

**Transfer:** Photograph a real user or a product held in human hands with a warm circular spotlight. The minimum equivalent is a carefully cut-out silhouette over a soft amber disc, with natural edge light and deep brown-black surroundings.

**Build:** Layer a dark near-black field, a large radial-gradient ellipse centered slightly right using rgba(255,190,70,0.95), rgba(224,127,24,0.8) and transparent edges, and a foreground silhouette. Blur the ellipse edge by about 24px; add a low-opacity dark linear gradient beneath the text. For the closing scene use a closer subject and a brighter warm light. Match the soft glow; exact stops are not essential.

### Human-scale product scenes

**Use:** Process cards and immersive feature chapters.

**Observed:** Hands hold phones and tablets; warm outdoor activity alternates with bright neutral interiors. Real interface screens and translucent appointment, plan or progress annotations connect the image to a concrete action. The large tablet scene is diagonal and fills the right side, with a softly blurred continuation behind left copy.

**Transfer:** Stage the new interface in use rather than floating it alone. For non-screen products, pair a real object interaction with one compact explanatory overlay.

**Build:** Place an object-fit cover photograph across the stage. Duplicate it beneath the copy region, apply blur(40px), and mask the duplicate toward the image side. Set compact annotation panels in rgba(24,24,27,0.5), backdrop-filter blur(24px), white text and 7.5px corners.

### Everyday proof portraits

**Use:** Testimonials, story carousels and expert credibility.

**Observed:** Members appear in naturally lit homes or outdoors, often looking away rather than posing. Testimonial media is wide and shallow, about 645px by 300px; expert portraits use pale backings and appear beside names, muted institutional marks and short credentials. Social proof uses edge-to-edge portrait reels mixing phone footage and editorial cards.

**Transfer:** Combine honest user environments with cleaner expert portraits; keep natural skin tones and avoid forcing every image into an identical color filter.

### Gifting portrait arc

**Only for:** gifting campaigns

**Use:** Emotional campaign opening.

**Observed:** Rounded portrait cards run beyond both viewport edges. A central couple image sits highest, adjacent cards lower, and outer cards lower still; the rising arc sits below a centered promise and small delivery reassurance.

**Transfer:** Use relationships appropriate to the new offering, retaining the stepped arc and generous white separation from the headline.

### Personal story collage

**Only for:** editorial stories

**Use:** Intimate long-form storytelling.

**Observed:** Family and personal photographs sit within a narrow reading column. Some compositions combine two candid photos, or a small photo with handwritten quotation artwork; related-story thumbnails place smaller images on pale neutral fields.

**Transfer:** Use genuinely personal materials and brief handwritten excerpts as artwork, not as the default text font. Minimum equivalent: a candid photo beside a short handwritten SVG quotation.

### Audience ruler

**Only for:** business audience sections

**Use:** Connect multiple audience columns with an instrument-like shared baseline.

**Observed:** Three centered audience descriptions sit above a very faint horizontal ruler, with dense short ticks and one tall marker below each audience.

**Transfer:** Use this single restrained technical motif to suggest breadth or scale, not a full decorative graph.

**Build:** Create a 24px-tall repeating-linear-gradient in rgba(24,24,27,0.12), with approximately 0.9px strokes on a 20px interval and a 0.5px baseline. Place three 94px vertical gradient markers above the baseline; fade each from transparent to dark neutral.

### Icons

**Observed:** Small utility glyphs accompany eligibility, checks, playback and disclosure. Most inline marks are 15–22px; outline controls use about 1.5px strokes. The dot-menu is a compact nine-dot square, while numbered process markers are translucent rounded squares.

**Transfer:** Prefer simple monochrome checks and thin disclosure marks. Reserve filled circles for playback or compact verification rather than making every feature a large icon.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** An 83px white navigation zone sits above a nearly full-width 810px media stage with 7.5px outer gutters and 11.2px corners. Back to front: dark film scene, giant amber disc, human profile concentrated in the center-right, darkening gradients, then white left-aligned copy. The headline uses display, wraps to two lines and occupies less than half the stage width within a 555px group; a small checked eligibility line precedes it, a compact one-line factual support follows, then White button and Glass button. A three-part benefit strip sits along the lower-left edge with thin vertical dividers. Within the first 900px the full media scene, headline, support, both actions and benefit strip are visible; the credibility strip begins below.

**Transfer:** Use one strong person, object or silhouette against warm light and put the promise in the dark negative space. Keep a clear main object visible without hiding it under text. Business variants use a real collaborative interior photograph and a checklist. Review-led variants use a shorter photographic stage and rating. Gifting variants open on white with a centered promise above the portrait arc; editorial stories use a two-column title and cover image.

**Avoid:** Do not replace the film-like scene with a centered oversized slogan, a busy dashboard collage or a flat orange hero.

**Text style:** `display` — Nb international pro webfont 400 · 56.2px/1 · tracking -0.02em

### Process introduction

**Observed:** A centered process-heading and compact gray support sit above Process card in four equal columns. The content container is 1199px wide, the title-to-grid break is 45px, and the square media has numbered corners.

**Transfer:** Show the user's progression from first action through understandable feedback to improved outcome; keep each support line short.

**Text style:** `process-heading` — Nb international pro webfont 400 · 37.5px/1.2

### Immersive capability chapter

**Observed:** A 900px sticky Product stage carries a narrow left text-and-controls column and a large working-product scene on the right. Small numbered capsule tabs precede a compact heading, support and dark translucent question bars near the bottom-left. The scroll chapter spans 2700px while retaining the viewport-height scene.

**Transfer:** Use a few distinct product capabilities as scene changes, with consistent left copy placement and one dominant image per state.

### Value ledger

**Observed:** A centered heading contrasts former complexity with an accessible offer. A 600px Benefit row list below it alternates pale stripes, followed by a compact Dark button. The surrounding section has 75px vertical padding.

**Transfer:** Translate value into a concise inventory with plain-language clarifications rather than many pricing cards.

**Text style:** `heading` — Nb international pro webfont 400 · 45px/1.2 · tracking -0.0225em

### Expert and member proof

**Observed:** A left-aligned two-line heading leads either a horizontal row of portrait-and-bio expert modules or a Proof band with wide testimonial media. Expert media is about 206px by 248px; testimonial slides pair 645px by 300px images with name, quotation and muted summary. Adjacent slides remain partially visible and lower contrast; a segmented progress line sits below.

**Transfer:** Use credible people and actual outcomes. Maintain a contrast between restrained professional credentials and candid first-person stories.

**Text style:** `heading` — Nb international pro webfont 400 · 45px/1.2 · tracking -0.0225em

### Social proof reel

**Observed:** A 45px chapter heading is followed by a full-bleed horizontal strip of tall rounded media tiles, mixing editorial headlines, portrait footage and product use. The strip extends beyond the content container and clips at viewport edges.

**Transfer:** Use heterogeneous proof formats with consistent tile height, not a uniform logo wall alone.

**Text style:** `heading` — Nb international pro webfont 400 · 45px/1.2 · tracking -0.0225em

### Luminous closing and paper directory

**Observed:** A 750px immersive amber scene returns the display scale in white, alongside a rating, three short reassurances and paired White button and Glass button. The photograph continues around Footer paper, inset 22.5px from the page edges. Footer directory contains newsletter and discovery tools on the left, three directory columns on the right and a final legal rule. Business-oriented endings instead finish with a dark testimonial paired with a communication collage and a plain white directory; gifting uses its relationship photograph and plain white directory.

**Transfer:** End the sales narrative with a simple human promise, not another dense explanation. Retain the warm-light device and framed white directory on ordinary marketing pages; use the scoped alternatives only for the matching page purpose.

**Text style:** `display` — Nb international pro webfont 400 · 56.2px/1 · tracking -0.02em

### Purchase and objections

**Only for:** purchase sections

**Observed:** A two-column gallery and offer layout uses a 660px square main visual with 22.5px corners and 88px thumbnail controls below. The narrower column stacks rating, purchase-display title, support, price, a six-line check list, full-width Dark button, small reassurances, compact stats and FAQ row.

**Transfer:** Keep all decision-critical information beside the product visual and use the FAQs for practical friction rather than another feature list.

**Text style:** `purchase-display` — Nb international pro webfont 400 · 56.2px/1.07 · tracking -0.025em

### Quantified proof

**Only for:** quantified proof sections

**Observed:** Three equal text groups pair stat numerals with much smaller percent signs, then 22.5px explanatory lines. Fine vertical rules fade toward their ends; the disclosure spans beneath the row.

**Transfer:** Show a small set of defensible metrics, attach each to a readable outcome, and keep methodology caveats nearby.

**Text style:** `stat` — Nb international pro webfont 400 · 65.6px/1 · tracking -0.0206em

### Editorial story

**Only for:** editorial stories

**Observed:** A pale split opening pairs breadcrumb, 45px title and share tools with a cover graphic. Below, a 585px reading column begins with pull-quote and subject metadata; a separate left rail carries author, reviewer and a small promotion. Paragraph chapters alternate with candid images, ending with a story invitation, related-story rail, cinematic closing scene and Footer directory.

**Transfer:** Center the narrative on one person and preserve enough space for full paragraphs and authentic media instead of converting the story into a card grid.

**Text style:** `article-body` — Nb international pro webfont 400 · 15.9px/1.4

### Campaign comparison

**Only for:** gifting campaigns

**Observed:** A centered heading sits above a narrow two-column comparison. The offered product's column has a white backing over the off-white band; each paired row is about 116px high with faint dashed separators and small checks. The closing campaign scene is a full-bleed couple photograph, with white promise left and support, bullets and a wide action right.

**Transfer:** Compare existing behavior to the offered improvement using direct practical contrasts, then close emotionally rather than repeating the table.

**Text style:** `heading` — Nb international pro webfont 400 · 45px/1.2 · tracking -0.0225em

## Page flow

**Storyline:** Promise → understandable process → immersive capability proof → value and credibility → human outcomes → practical decision support → emotional closing → useful directory.

### Broad product or membership landing page

1. **Promise** — Cinematic opening with concise benefit and action pair.
2. **Product explanation** — Compact credibility strip, four pictured steps and immersive capability chapter.
3. **Value** — Centered inclusion ledger makes the offer legible.
4. **Social proof** — Expert profiles, wide member stories and mixed-format social reel.
5. **Decision support** — Gallery, offer details, compact metrics and FAQs.
6. **Closing call** — Amber human scene continues behind the inset paper footer.

**Transfer:** Balance emotional introduction with tangible process and purchase clarity; adapt the number of chapters to the offering.

### Business or organizational service page

1. **Promise** — Collaborative workplace photograph with left headline, checklist and two actions.
2. **Audience fit** — Three centered audience descriptions joined by a ruler motif.
3. **Capability proof** — Split image-and-checklist chapter.
4. **Risk reduction** — Short security section with compliance marks.
5. **Social proof** — Dark testimonial beside a collage of authentic communications.
6. **Directory** — Plain white footer with newsletter and navigation.

**Transfer:** Give procurement concerns their own concise chapter without losing human photography.

### Review and testimonial collection

1. **Social promise** — Short portrait hero with rating and white action.
2. **Social proof** — Category tabs above mixed text, audio and video masonry.
3. **Participation** — Story invitation beside a portrait mosaic.
4. **Quantified proof** — Social reel, three large metrics and expert profiles.
5. **Process reassurance** — Large image beside a step-by-step journey and action.
6. **Closing call** — Amber scene and inset paper directory.

**Transfer:** Allow evidence to lead; keep multiple proof formats and a path back to the product decision.

### Gift or relationship-led campaign

1. **Emotional promise** — Centered white opening with a rising portrait arc.
2. **Product explanation** — Four square feature images with plain benefits.
3. **Breadth** — Pale category grid with small illustrative symbols and fine column rules.
4. **Social proof** — Member story carousel and expert profiles.
5. **Comparison** — Narrow paired comparison table.
6. **Closing call** — Full-bleed relationship photograph with promise and checklist, then plain white directory.

**Transfer:** Lead with the recipient's experience, then answer what the gift includes and how it improves existing behavior.

### Long-form customer story

1. **Orientation** — Breadcrumb and title beside editorial cover.
2. **Human hook** — First-person pull quote, subject profile and candid photo.
3. **Narrative proof** — Narrow paragraph chapters with photographs and handwritten quotation art.
4. **Participation** — Story invitation and related-story rail.
5. **Closing call** — Warm cinematic scene and inset white directory.

**Transfer:** Keep the editorial reading experience distinct from a conversion landing page while sharing the same typography, atmosphere and ending.

## Writing

Warm, assured and plain-spoken. Technical detail becomes personal agency rather than a demonstration of expertise; emotional claims are anchored by concrete process, numbers and real people.

**Do not copy:** Do not reuse the brand name, wordmark, proprietary assistant names, photography, personal quotations, customer identities, membership prices, medical claims or outcome statistics. Write new claims only when the new product can substantiate them. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the provider's commitments. First-person language belongs mainly to testimonials.
- **Rhythm:** Short sentence-case headlines, often four to nine words and broken into two lines. Support usually fits one or two sentences; checklists use compact noun phrases and practical benefits.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the reader's new possibility in direct, familiar language. | 4–9 words | “Your new health membership”<br>“Give your team control over their health” |
| Section heading | Turn an abstract feature into an understandable promise or change. | 3–12 words | “How it works”<br>“Changing outcomes and lives across the nation” |
| Support | Provide a specific mechanism, scope or practical reassurance immediately after the promise. | 1–2 sentences | “Members get 150+ lab tests across 2 blood draws. $199 per year.” |
| Action | A short verb-led next step; distinguish committing from exploring. | 2–5 words | “Become a member”<br>“See what we test”<br>“Talk to our team” |
| Process label | A verb and an understandable user outcome. | 3–4 words | “Build your baseline”<br>“See what matters” |
| Invitation | Welcome ordinary experiences, not only spectacular transformations. | 1–2 short sentences | “Every story matters, from small victories to big changes. We want to hear about your path to wellness.” |

**Words and phrasing to use:** your; understand; see; clear; personalized; support; starts with; what matters; take control

**Avoid:** revolutionary ecosystem; biohacking superlatives; guaranteed transformation; fear-driven urgency; dense technical jargon in headlines

**Rules:**

- Follow a broad promise with a concrete mechanism or next step.
- Keep product inclusion lists factual and scannable.
- Let testimonials retain personal uncertainty and conversational texture.
- Distinguish measured aggregate outcomes from individual expectations.
- Use fine print for real qualifications, not to reverse the headline promise.

## Do's and Don'ts

### Do

- Keep primary display type at weight 400 and -0.02em tracking.
- Maintain the 7.5px outer hero frame and 11.2px media corners.
- Use about 105px vertical padding for ordinary major chapters.
- Keep most content within the 1199px centered container.
- Pair 47px white and glass actions on dark photographs, with about 15px separation.
- Use pale #fafafa bands to separate proof chapters without introducing extra hues.
- Show the actual product at human scale in at least one image-led explanation.
- Retain the 22.5px inset paper footer and continuing warm scene on default marketing endings.

### Don't

- Do not turn the regular grotesk hierarchy into bold, all-caps advertising typography.
- Do not use orange as the default button or card fill; it is a tiny interface accent and a photographic light.
- Do not add heavy shadows to ordinary process cards; elevation belongs chiefly to review masonry.
- Do not turn the 600px value ledger into an oversized multi-plan pricing grid.
- Do not make all supporting copy as dark as headings; use #71717a for explanatory paragraphs.
- Do not center every chapter heading; centered process and value blocks contrast with left-aligned proof chapters.
- Do not replace authentic portrait media with a wall of generic outline illustrations.
- Do not use the handwritten editorial artwork as a site-wide font.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, transform and box-shadow transitions of 0.25s cubic-bezier(0.4,0,0.2,1).
- Value rows declare opacity 0.6s and transform 0.6s transitions.
- The immersive capability scene is sticky across a 2700px chapter; tabs expand into capsules and the media changes between stages.
- A marquee is declared at 28s linear infinite for a business-page strip.

**Transfer:**

- Keep the image-led capability stage stable while its tabs and scene change; use a still poster with the same framing when motion is unavailable.
- Use the declared brief button transitions rather than adding bouncy pill interactions.

**Unknown:**

- Exact reveal sequencing, scroll thresholds, video timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare breakpoints around 479/480px, 767/768px, 991/992px, 1024px and 1439/1440px, with additional component-specific widths.

**Transfer:**

- On narrow screens, preserve the amber focal object and dark text-safe region; stack the image and text when they can no longer share that separation.
- Reduce process columns and stack purchase columns while retaining image-first reading order; keep the testimonial rail horizontally clipped rather than shrinking portraits beyond legibility.
- Collapse footer groups without removing the newsletter-to-directory distinction.

**Unknown:**

- Exact mobile type sizes, navigation arrangement and breakpoint-specific layouts are not established; these transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
