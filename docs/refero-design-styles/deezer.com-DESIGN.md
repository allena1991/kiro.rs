# Deezer — electric pop stages

## Overview

A black-box stage for exuberant product experiences: tall condensed headlines, small conversational text and vivid purple-led collages make the product feel playful rather than technical. The default is dark and spacious, with color concentrated in interface imagery, cartoon illustration and compact actions. A broader acquisition variant alternates near-white and purple-black bands with chunky grotesk type and oversized social proof. It suits expressive consumer products and feature-rich services that can show their personality in use.

### Essentials

- Headlines act like narrow poster lettering, not conventional software headings: the default display is Deezer Product 80px/1 at 700, with 48px/1 section titles and normal tracking.
- The opening is a centered promise above a fan of product surfaces: an 81px navigation bar, 80px breathing room, 32px text-stack gaps and a 1440×420px collage visible within the first 900px.
- Actions are compact rounded rectangles rather than pills: purple primary buttons are 48px high with 12px corners and 12px 24px padding; outline discovery buttons are 50px high with a 1px gray edge.
- Black remains the dominant field across the ordinary landing page; white titles and #a19fa4 support text leave saturated color to small #ad47ff actions and isolated artwork, not continuous colored section fills.
- Product evidence becomes a pop sculpture: overlapping screens, exaggerated scale and purple graphic shapes float directly on black. Include at least one such staged collage; when finished product media is unavailable, use three purpose-built interface panels and a simple elliptical motif.
- Chapters feel like separate performances: 160px separates sections, 64px separates text from wide media, and split scenes use two equal columns with a 64px gap. Keep the closing resource area expansive rather than ending with an unrelated oversized sales banner.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric purple | `#ad47ff` | `--color-primary` | action, accent | Default primary and compact sign-up actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender link | `#bb73ff` | `--color-active` | link, accent | Active navigation and small selected indicators. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-canvas` | background, text | Default page canvas and dark text on bright proof cards. |
| Control charcoal | `#242326` | `--color-control` | surface | Language selector and dark controls. |
| Navigation hairline | `#38373b` | `--color-nav-edge` | border | Subtle divider below navigation. |
| Control edge | `#4e4c51` | `--color-edge` | border | Outline actions and footer rule. |
| Muted lavender gray | `#a19fa4` | `--color-muted` | text | Support copy and footer links on black. |
| Stage white | `#ffffff` | `--color-foreground` | text, surface | Headings, actions and white speech bubbles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| broad acquisition pages | Acquisition purple | `#a238ff` | `--color-campaign-action` | action | Acquisition buttons, distinct from default feature actions. |
| task-oriented feature pages | Deep purple badge | `#6307a4` | `--color-step` | surface | Numbered step tiles. |
| migration and reassurance stories | Acid yellow | `#e6e951` | `--color-proof` | surface | Single high-contrast expert endorsement panel. |
| broad acquisition pages | Banner lavender | `#d09aff` | `--color-banner` | surface | Floating conversion strip. |
| conversational testimonials | Reaction lilac | `#d9abff` | `--color-reaction` | surface | Small reply bubble beside a customer quotation. |
| broad acquisition pages | Purple black | `#0f0d13` | `--color-campaign-dark` | background, text | Acquisition canvas and ink on light bands. |
| task-oriented feature pages | Purple charcoal band | `#141216` | `--color-band` | background, surface | Instruction and recommendation bands. |
| pricing comparisons | Free-plan charcoal | `#29282d` | `--color-plan-dark` | surface | Lower-tier plan panel. |
| pricing comparisons | Premium-plan white | `#f8f8f9` | `--color-plan-light` | surface | Higher-tier plan panel. |
| broad acquisition pages | Milk white | `#fdfcfe` | `--color-campaign-light` | background, text | Light acquisition bands and text on the purple-black canvas. |

## Typography

- **Deezer Product** — Default hero and section headings. Very tall, narrow, heavy sans with lively condensed proportions. If unavailable, use **Barlow Condensed**. Use 700; preserve the narrow measure rather than replacing with a wide grotesk. Font stack: "Deezer Product", "Barlow Condensed", Tahoma, Arial, sans-serif.
- **Inter** — Paragraphs, navigation, buttons and question labels. Neutral, compact grotesk that stays unobtrusive beside the display face. OpenType features: "kern". Font stack: "Inter", Arial, sans-serif.
- **Deezer Brand** (only for broad acquisition pages) — Chunky campaign headlines, plan statements and oversized proof. Heavy tightly packed grotesk with less extreme condensation than the default display. If unavailable, use **Roboto Condensed**. Use 700–800 and preserve deliberate multiline blocks. Font stack: "Deezer Brand", "Roboto Condensed", Tahoma, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Deezer Product | 700 | 80px | 1 | normal, features "kern" | Centered first-screen promise; sentence case. |
| heading | Deezer Product | 700 | 48px | 1 | normal, features "kern" | Section leads, FAQ title and expert-panel heading. |
| question | Inter | 700 | 20px | 1.2 | normal, features "kern" | FAQ questions and compact benefit headings. |
| body | Inter | 400 | 16px | 1.5 | normal, features "kern" | Support text and resource links. |
| action | Inter | 700 | 16px | 1.5 | normal, features "kern" | Primary actions, discovery actions and main navigation. |
| footer-heading | Inter | 600 | 16px | 1.5 | normal, features "kern" | Resource-column labels. |
| compact-action | Inter | 600 | 14px | 20px | normal, features "kern" | Navigation authentication controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| broad acquisition pages | campaign-display | Deezer Brand | 800 | 140px | 0.9 | normal, uppercase | Monumental stacked text-only opening. |
| broad acquisition pages | proof-ticker | Deezer Brand | 700 | 120px | 1 | 0.0021em | Oversized single-line community proof running beyond both viewport edges. |
| pricing comparisons | plan-statement | Deezer Brand | 700 | 46px | 48px | 0.0054em, uppercase | Two-line introductory offer within each plan. |

**Notes:**

- Keep the default heading system condensed and sentence case. The uppercase 140px campaign face is a separate visual mode, not a larger step of the ordinary page scale. Acquisition section headings use Deezer Brand at 56px, weight 700, normal line height and 0.3px tracking.
- Body copy stays at 16px even beside large artwork; visual hierarchy comes from weight, width and black space rather than many intermediate sizes.
- Default heading and body tracking is normal; do not introduce editorial letterspacing or mono eyebrows.

## Layout

**Density:** Airy at chapter scale, compact within controls and resource lists; large black intervals give the colorful objects room to perform.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact heading-icon alignment and small internal gaps. |
| 12px | Action vertical padding and small benefit text gaps. |
| 16px | Resource-link intervals and navigation gaps. |
| 24px | Action horizontal padding, footer heading-to-links gap and plan padding. |
| 32px | Title-to-support and support-to-action gaps. |
| 64px | Text-to-media separation and split-column gutter. |
| 80px | Space after navigation before the hero and between footer tiers. |
| 112px | Desktop outer text and navigation inset. |
| 160px | Chapter separation and space before footer. |
| 28px | Only for broad acquisition pages: content spacing and side padding. |
| 140px | Only for broad acquisition pages: hero padding and major light-band breathing room. |

### Containers and grids

- **desktop rails**: side padding 112px. Text, navigation and footer align on 1216px of usable width at a 1440px viewport; artwork can break out to the edges.
- **centered copy**: max width 1000px. Centered support paragraphs and feature headings.
- **split stage**: 2 columns · gap 64px. Equal-width tracks with media on one side and a vertically centered text stack on the other; reverse sides between chapters.
- **wide media**: max width 1440px. Full-stage collage bands, typically 420px or 506px high; no enclosing card.
- **faq column**: max width 900px · side padding 16px. Compact question list with an 868px inner measure; wider feature variants align to the desktop rails.
- **benefit trio** (only for task-oriented feature pages): max width 930px · 3 columns · gap 48px. Compact benefit summaries below a task-oriented opening.
- **acquisition content** (only for broad acquisition pages): max width 1120px · side padding 28px. Main campaign sections; central conversion and FAQ copy narrow to 880px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | ordinary actions | 12px |
|  | compact actions and select | 8px |
|  | proof panels and speech bubbles | 16px |
|  | circular controls | 50% |
| broad acquisition pages | acquisition actions | 16px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default uninterrupted canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Artwork floats directly on the field with no general-purpose card system.

**Transfer:** Let negative space separate chapters.

#### Instruction band · level 0

**Only for:** task-oriented feature pages

**Use:** Differentiate how-to and related-feature material.

**CSS:** `background: #141216; padding: 48px 0`

**Observed:** A slight purple lift rather than a strong contrasting stripe.

**Transfer:** Use sparingly for practical support content.

#### Expert panel · level 1

**Only for:** migration and reassurance stories

**Use:** Make a human explanation feel like a bright editorial insert.

**CSS:** `background: #e6e951; color: #000000; border-radius: 16px; padding: 32px; max-width: 500px`

**Observed:** A solid acid-yellow block set beside conversational proof, with no shadow.

**Transfer:** Reserve this color for one concentrated reassurance moment.

#### Acquisition light band · level 0

**Only for:** broad acquisition pages

**Use:** Text-led opening and community proof island.

**CSS:** `background: #fdfcfe; color: #0f0d13`

**Observed:** Broad near-white fields alternate with purple-black. Some band boundaries form shallow convex arcs rather than square cuts.

**Transfer:** Use an oversized elliptical pseudo-element at the bottom edge to create a shallow curved boundary; keep the center nearly flat.

## Components

### Navigation

**Use:** Compact global orientation above the opening.

**CSS:** `height: 81px; border-bottom: 1px solid #38373b; padding: 0 112px; display: flex; align-items: center; gap: 16px`

**Text style:** `action` — Inter 700 · 16px/1.5

**Observed:** Small 107×30px logo on the left; three text destinations and two authentication controls on the right. The active destination is lavender. A 64px separation distinguishes the authentication group.

**Transfer:** Keep the logo compact so the opening headline remains dominant.

### Primary button

**Use:** Main conversion in the opening or a practical instruction band.

**CSS:** `background: #ad47ff; color: #ffffff; border-radius: 12px; padding: 12px 24px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 700 · 16px/1.5

**Observed:** Text-only centered control with content-sized width; not stretched across the hero.

**States:** Declared: hover changes the purple fill and accent text tokens; focus-visible uses a light neutral outline with no box shadow; active changes to the pressed accent tokens.

### Discovery button

**Use:** Low-pressure action repeated through feature chapters.

**CSS:** `color: #ffffff; background: transparent; border: 1px solid #4e4c51; border-radius: 12px; padding: 12px 24px; height: 50px`

**Text style:** `action` — Inter 700 · 16px/1.5

**Observed:** Outline action sits below support text in split scenes or beneath the artwork in centered scenes.

**States:** Declared: hover fills with a dark neutral and changes border and text tokens; focus-visible changes outline and border to purple with no box shadow; active uses the next darker neutral surface.

### Compact signup

**Use:** Authentication action in the navigation.

**CSS:** `background: #ad47ff; color: #ffffff; border-radius: 8px; padding: 4px 16px; height: 32px`

**Text style:** `compact-action` — Inter 600 · 14px/20px

**Observed:** Paired with an outlined login control of the same height and corner shape; login uses the control-edge color.

**Transfer:** Keep authentication smaller than the page conversion.

### FAQ row

**Use:** Resolve practical objections without a heavy card grid.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 8px 0; color: #ffffff; background: transparent`

**Text style:** `question` — Inter 700 · 20px/1.2

**Observed:** Question heading on the left, 24px chevron on the right; first answer is expanded beneath it, followed by 16px-separated questions. Answers use body text; the question itself is not the smaller inherited button text.

**States:** Declared: hover reduces opacity to 0.7; focus-visible uses a purple outline, a 3px blue alpha ring and opacity 0.7.

### Resource footer

**Use:** Close the story with useful destinations and download access.

**CSS:** `border-top: 1px solid #4e4c51; padding: 40px 112px 120px; display: flex; flex-direction: column; gap: 80px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Centered store badges precede five link columns. White semibold column labels contrast with gray regular links spaced 16px apart. Bottom tier places social icons left, compact identity centered, copyright and an 170×48px charcoal language select right. No giant closing headline.

**Transfer:** Replace store badges with equivalent distribution or access links when the product is not an app.

### Speech bubble

**Only for:** conversational testimonials

**Use:** Present a customer's unpolished first-person proof.

**CSS:** `background: #ffffff; color: #000000; border-radius: 16px; padding: 12px 16px; position: relative`

**Text style:** `action` — Inter 700 · 16px/1.5

**Observed:** Wide white quotation bubble with a small triangular lower-left tail and the person's name immediately below; a tiny lilac response bubble sits lower and to the right.

**Transfer:** Use a 10px CSS border triangle for the tail; keep the statement short enough to feel like a message.

### Expert endorsement

**Only for:** migration and reassurance stories

**Use:** Pair practical authority with conversational customer proof.

**CSS:** `background: #e6e951; color: #000000; border-radius: 16px; padding: 32px; max-width: 500px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Large condensed heading, regular explanation, small circular portrait with name and role, then a black action with white lettering. The heading uses the ordinary heading recipe.

**Transfer:** Explain one anxiety in plain language, not a second marketing manifesto.

### Plan comparison card

**Only for:** pricing comparisons

**Use:** Contrast entry and upgraded offers.

**CSS:** `background: #f8f8f9; color: #000000; padding: 24px; border-radius: 12px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `plan-statement` — Deezer Brand 700 · 46px/48px · tracking 0.0054em · uppercase

**Observed:** Upgraded plan is light and appears left of the dark entry plan, despite reverse reading order in the markup. A skewed capsule label tops the offer; small price detail, full-width action and checkmarked benefit list follow. Cards are about 350–370px wide and 465px tall, separated by 14px. Dark plan uses a white action; light plan uses purple.

**Transfer:** Keep the contrast and matched heights; use actual product terms and restrained benefit counts.

### Acquisition button

**Only for:** broad acquisition pages

**Use:** Conversion within text-led campaigns and plan comparisons.

**CSS:** `background: #a238ff; color: #ffffff; border: 1px solid transparent; border-radius: 16px; padding: 8px 32px; height: 42px`

**Text style:** `action` — Inter 700 · 16px/1.5

**Observed:** Softer and shorter than the default feature-page button; secondary versions are white on dark bands or dark on light bands.

### Floating conversion strip

**Only for:** broad acquisition pages

**Use:** Persistent conversion reminder during long campaign browsing.

**CSS:** `background: #d09aff; border-radius: 16px; padding: 14px 28px; position: fixed; max-width: 1064px; display: flex; align-items: center; justify-content: space-between; gap: 28px`

**Observed:** A small playful illustration precedes a compact heading and one-line support. A dark compact action sits at the opposite edge. It appears after scrolling rather than replacing the initial global navigation.

**Transfer:** Keep this to acquisition campaigns; do not cover every feature scene with a banner.

## Imagery and graphics

### Interface pop sculpture

**Use:** Hero and major capability demonstrations; a signature visual device on ordinary landing pages.

**Observed:** Five overlapping upright app panels form a shallow fan in the opening, tallest in the center. Bright magenta, purple, white and blue screens are cropped cleanly along one baseline; no realistic phone hardware is needed. Later scenes use two or three panels, overscale notification cards, circular controls and small decorative sparkles. Large media bands are 420–506px high against black.

**Transfer:** Use real interface content from the new product. Minimum acceptable version: three convincing panels, one light, one dark and one saturated, with varied heights and a prominent center panel.

**Build:** Use a full-width relative container 420px high with overflow hidden. Layer five rounded-top rectangular panels at widths around 280px on desktop; center one in front, lower its neighbors by 48px and outer panels by another 32px. Show cropped UI, not empty blocks. Back selected scenes with two or three purple ellipses and keep the canvas black.

### Playful flat illustration

**Use:** Add human character beside interface proof and in conceptual feature scenes.

**Observed:** Expressive cartoon faces and exaggerated hands, lilac hair, purple clothing, pink skin and mint or yellow details. Thin dark outlines, flat fills and tiny white highlights create a sticker-like vector finish without photographic texture.

**Transfer:** Commission or draw product-relevant gestures, tools and people. A simple smiling avatar and one exaggerated interaction are sufficient; avoid generic isometric business people.

**Build:** Use SVG organic paths with dark 1–2px outlines, solid purple and lilac masses, rounded pink hand shapes, small pale highlight paths and a few short motion strokes. Layer in front of the interface only where it explains the interaction.

### Elliptical transfer sculpture

**Use:** Conceptual connector between capabilities or platforms.

**Observed:** A horizontal sequence of purple ellipses changes width and tilt between two circular endpoints. It reads as elastic movement or a waveform, with black space around it.

**Transfer:** Translate a before-and-after relationship into a chain of abstract shapes; replace endpoint symbols with the new product's own inputs and outputs.

**Build:** In an 800×181px SVG, draw about twelve vertical ellipses on one centerline. Vary horizontal radii from 12px to 38px and rotate neighboring ellipses slightly in opposite directions. Progress from deep purple to electric purple. Use circular endpoint medallions instead of a literal arrow.

### Fine luminous wave

**Use:** Premium-quality or performance chapter.

**Observed:** A thin gold ribbon of parallel sine-like strands stretches nearly edge to edge on black, crossing itself around the center and fading at both ends. The scene is delicate and luminous rather than a solid gradient slab.

**Transfer:** Use abstract light to make an invisible quality tangible; preserve fine line density and the large black field.

**Build:** Create 24–32 SVG cubic Bézier paths over a 1440×420px viewBox with 1px strokes in rgba(226,199,128,0.55). Vary control-point heights so the ribbon expands, contracts and crosses twice. Place a blurred low-opacity duplicate behind the lines; mask both ends with transparent-to-opaque-to-transparent alpha. Exact glow stops are not essential.

### Angled editorial mosaics

**Use:** Catalog breadth and personalized content chapters.

**Observed:** Square cover art and editorial portraits form tilted, overlapping grids; center imagery remains bright while black edge fades merge the composition into the canvas.

**Transfer:** Use the new product's outputs, projects or content tiles rather than unrelated stock art. Preserve the tight tile collage and softened edges.

**Build:** Rotate a tightly spaced tile grid roughly 25 degrees, scale it beyond its 420px container and apply a radial alpha mask that keeps the middle bright and dissolves the perimeter into black.

### Circular proof constellation

**Only for:** social and collaborative product stories

**Use:** Show playful quantified outcomes, not financial dashboards.

**Observed:** Different-sized lavender disks carry huge condensed black figures with small centered captions. Overlapping oval portraits anchor the center, while tiny stat circles drift toward or beyond the page edges. A dominant percentage is much larger than the supporting totals.

**Transfer:** Use only substantiated figures; for a product without metrics, replace numbers with short outcomes while retaining the scale contrast.

**Build:** Arrange an overlapping pair of portrait ovals in the central half of a black 506px media band. Add four lavender circles of markedly different diameters; put the largest in front of one portrait and one small circle partly outside the right edge. Keep labels inside disks, figures dominant, and avoid connector lines.

### Immersive event photography

**Only for:** community and access campaigns

**Use:** Show the emotional experience beyond the application.

**Observed:** Crowds holding phones, close candid faces and venue objects under saturated violet light. A wide hero photograph sits within a black media band; alternating chapters use rectangular images or photos masked into adjacent vertical ovals, with warm flash-lit faces against the black page.

**Transfer:** Choose genuine moments of participation relevant to the new product, mixing intimate human detail with environmental color.

**Build:** For the masked treatment, clip one continuous photo through a row of overlapping SVG ellipses with varying heights, largest in the center. Keep narrow gaps at the outer slices and let black show around the silhouette.

### Icons

**Observed:** Small solid SVG symbols, usually 24×24px in actions; 20px control chevrons and larger muted down arrows support navigation. Social controls have 48px circular hit areas and 12px gaps. Cartoon illustration is distinct from this utility icon set.

**Transfer:** Use compact filled symbols and simple directional chevrons; keep utility icons white or muted gray, leaving full color to media and platform marks.

## Section recipes

How recurring sections are built.

### First screen: Centered pop-stage opening

**Observed:** Black field begins with Navigation. After 80px, a centered 80px condensed white headline spans about three quarters of the viewport, remaining one line for a short promise and wrapping for longer ones. Body support sits 32px below, then Primary button after another 32px. After 64px the Interface pop sculpture fills a 1440×420px band: colorful screens rise from a shared clipped baseline, with the central screen foremost. Within 900px the entire title, support, action and main object are visible; the next capability chapter falls below the fold. Layers are black canvas, rear panels, front center panel, then the text and action area above rather than over the artwork.

**Transfer:** Create a bold single promise and stage the new product's most varied outputs as a panel fan. A task-specific opening can use a compact conceptual illustration between title and support; collaboration pages add a three-benefit strip before the large scene. Broad acquisition campaigns instead use the scoped uppercase text-only light opening.

**Avoid:** Do not turn this into a left-text/right-dashboard SaaS hero, add an eyebrow above the title or place text over a noisy full-bleed photograph.

**Text style:** `display` — Deezer Product 700 · 80px/1

### Centered capability stage

**Observed:** Heading and gray support center over a large picture, with 32px between text roles and 64px before media. Discovery button sits another 64px below artwork in the overview; focused feature stories place it just above the image. Media is usually 420px high, expanding to 506px for more theatrical scenes.

**Transfer:** Give each stage one specific benefit and one clear demonstration; vary the artistic medium without changing the type hierarchy.

**Text style:** `heading` — Deezer Product 700 · 48px/1

### Alternating split scene

**Observed:** Split stage pairs a roughly 482×435px product illustration with a left-aligned heading, gray paragraph and Discovery button. Text-stack gaps remain 32px. Larger photography variants reach the page edge while text holds to the desktop rails.

**Transfer:** Alternate text and image sides for contrasting benefit chapters; allow the picture to explain the claim instead of enclosing every chapter in a card.

**Text style:** `heading` — Deezer Product 700 · 48px/1

### Questions to resources ending

**Observed:** Where needed, a centered FAQ heading leads an open first answer and compact FAQ rows. The ordinary overview and focused collaboration story end directly after their last media-and-action stage. All resolve into Resource footer after 160px, with app badges, five columns and a quiet identity row rather than a monumental sign-off.

**Transfer:** Finish with the last meaningful capability or objection, then practical access and navigation. Do not append every possible closing module.

**Text style:** `heading` — Deezer Product 700 · 48px/1

### Practical steps band

**Only for:** task-oriented feature pages

**Observed:** Instruction band pairs a multiline heading and Primary button on the left with a vertical three-step list on the right. Each step has a 40px deep-purple tile with 12px corners, 16px to its label and 24px between rows.

**Transfer:** Reduce the task to a few meaningful actions; keep numbering visually small relative to the heading.

**Text style:** `heading` — Deezer Product 700 · 48px/1

### Conversational reassurance close

**Only for:** migration and reassurance stories

**Observed:** Two adjacent proof columns near the ending: a Speech bubble with a name, small lilac reply and outline community action on the left; an Expert endorsement on the right. The bright panel is about 500×448px, padded 32px, while the conversation remains unboxed on black.

**Transfer:** Pair lived experience with an accountable explanation when users fear change. This is a distinctive closing proof option, not a universal final CTA.

**Text style:** `heading` — Deezer Product 700 · 48px/1

### Community proof island

**Only for:** broad acquisition pages

**Observed:** A light band contains a centered campaign heading and support, a horizontal row of playful avatar heads, then the 120px proof ticker clipped beyond both edges. Content-art collages and a centered two-action conversion block follow; the bottom band boundary has a shallow curve.

**Transfer:** Turn credible adoption or a shared outcome into oversized prose rather than a standard three-stat grid.

**Text style:** `proof-ticker` — Deezer Brand 700 · 120px/1 · tracking 0.0021em

## Page flow

**Storyline:** Promise → tangible product experience → benefit chapters → practical reassurance or proof where needed → resource-rich ending.

### Rich capability overview

1. **Promise** — Centered condensed headline, short support, purple action and multi-screen fan.
2. **Capability chapters** — Alternating split explanations and wide centered demonstrations; colorful UI, illustration and abstract light vary the pace.
3. **Closing capability** — A final playful product scene and outline discovery action complete the tour.
4. **Resources** — Store badges, five link columns and a small identity row close on black.

**Transfer:** Use this as the default for a new product landing page; select a smaller set of genuinely distinct benefits rather than reproducing the length.

### Broad consumer acquisition and plan selection

1. **Promise** — Near-white text-only poster opening with uppercase display, purple action and compact ratings proof.
2. **Pricing** — Contrasting light and dark plan panels with an introductory offer and benefit lists.
3. **Product breadth** — Abstract waveform statement and three tall colorful capability tiles.
4. **Social proof** — Light community island with avatars and a giant clipped proof sentence.
5. **Reassurance** — Low-friction switching block followed by a topical product explanation.
6. **Objection handling** — Compact FAQ and subdued offer terms.
7. **Resources** — Five-column footer on purple-black; conversion strip persists above content.

**Transfer:** Use the scoped campaign type and light/dark bands when selling an entire service, not for every focused feature.

### Remove friction around a specific transition task

1. **Promise** — Centered title, compact cartoon transfer illustration, support and primary action.
2. **Benefits** — Three concise icon-led explanations.
3. **Product demonstration** — Three-part carousel composition with heading and controls left, portrait demonstration center and support right.
4. **Process** — Dark raised band with numbered steps and conversion.
5. **Objection handling** — FAQ and support action.
6. **Discovery** — Related-feature carousel on a charcoal panel.
7. **Human proof** — Conversation paired with a bright expert explanation.
8. **Resources** — Shared badge-and-column footer.

**Transfer:** For onboarding or migration, make the practical task legible before introducing broader product breadth.

### Explain a collaborative capability through joyful outcomes

1. **Promise** — Two-line condensed title, purple action and three circular benefit icons.
2. **Product demonstration** — Large collage introduces the shared experience.
3. **Capability chapters** — Centered titles, repeated outline action and wide scenes: graphic platform medallions, portrait statistics, exaggerated illustration and paired interface screens.
4. **Closing capability** — Co-creation screen pair completes the story with an action above the media.
5. **Resources** — Shared black footer without an extra closing slogan.

**Transfer:** Keep one action label repeated while changing the proof scene for each outcome.

### Sell emotional access and community participation

1. **Promise** — Centered two-line title, support, primary download action and violet-lit crowd photograph.
2. **Experience** — Alternating text/photo chapters, including a sliced-oval photo mask and a venue detail.
3. **Product demonstration** — Centered access benefit with an in-app event-card collage.
4. **Objection handling** — Four practical questions, first expanded.
5. **Resources** — Shared footer with no additional hero-scale conversion.

**Transfer:** Use the scoped photographic treatment when the product connects digital utility to real-world participation.

## Writing

Friendly, confident and culturally fluent. Benefits sound like an invitation from someone who uses the product, with concrete explanations balancing occasional jokes and energetic claims.

**Do not copy:** Do not reuse Deezer names, feature names, proprietary illustrations, logos, artist imagery, customer quotes, adoption figures, performance claims, prices or trial terms. Source examples illustrate cadence only; substitute verified product-specific content.

- **Addressing the reader:** Speak directly to you and your; use we for a helpful product team. Questions and contractions keep the tone conversational.
- **Rhythm:** Headlines range from punchy two-word declarations to roughly ten-word benefit promises. Support uses one to three plain sentences; occasional fragments, repeated words and a parenthetical aside add bounce.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct promise, often combining a personal outcome with product distinction. | 5–10 words | “A unique experience, only on [Brand]” |
| Benefit heading | A compact personal benefit or question-and-answer fragment. | 2–10 words | “Always authentic”<br>“No internet? No problem!”<br>“Your month. Your year. Your music.” |
| Supporting line | Tell the reader what they can do and why it matters; keep it approachable. | 12–45 words | “We never gatekeep good taste. Share your favorite tracks with your friends and they can listen on any platform they choose.” |
| Primary action | An invitation built from a simple verb; add free only when true. | 2–5 words | “Sign up for free”<br>“Transfer now” |
| Discovery action | Low-pressure exploration rather than repeated purchase language. | 2–4 words | “Find out more”<br>“Discover more” |
| FAQ | Ask the exact practical question in the user's language. | 6–14 words | “Why can't I see [Brand] Club on the desktop page?” |

**Words and phrasing to use:** your; discover; get; friends; in seconds; tastes; vibe; we got you

**Avoid:** enterprise-grade synergy; leverage; revolutionary ecosystem; unlock unparalleled potential; impersonal feature inventories

**Rules:**

- Lead with an outcome, then explain the mechanism only as far as needed to believe it.
- Keep humorous idioms occasional; the practical support copy must still answer a real question.
- Use specific evidence for factual promises; present statistics as human outcomes rather than anonymous metrics.
- Choose one short discovery verb for repeated focused-feature actions.

## Do's and Don'ts

### Do

- Keep ordinary display and section headings at 80px/1 and 48px/1 with normal tracking.
- Use 16px/24px gray support copy even beside theatrical media.
- Maintain 32px within text stacks and 64px between the text and a large object.
- Let artwork occupy full 1440px media bands while text holds the 112px desktop rails.
- Use 12px corners for ordinary actions and 8px for compact navigation actions.
- Make at least one product scene an overlapping collage rather than a solitary flat screenshot.
- Preserve the five-column resource ending, including a small identity row and generous 80px tier gaps.
- Use the 16px-corner acid-yellow panel as a concentrated reassurance variant, paired with human proof.

### Don't

- Do not replace the condensed display with a standard-width Inter headline; Inter belongs to body and controls.
- Do not apply a purple gradient to every black section; most of the default page is unpainted black.
- Do not turn the 48–50px action rectangles into fully round pills.
- Do not add shadows to every card or button; surface distinction comes from fill and fine borders.
- Do not use the 140px uppercase acquisition recipe for ordinary feature headings.
- Do not render the circular outcome art as a conventional equal-width KPI dashboard.
- Do not move tiny UI-label typography into the marketing type scale; keep product details inside the demonstration.
- Do not collapse the footer into a narrow centered legal strip or replace it with a giant wordmark.

## Motion and responsive

### Motion

**Observed:**

- Feature controls declare 200ms transitions across background, border, outline, color, fill, stroke, opacity, shadow and transform; other control rules declare 150ms cubic-bezier(0, 0, 0.2, 1).
- The acquisition proof sentence repeats beyond the viewport with a translated banner; its full travel timing is unspecified.
- Portrait-format product demonstration media appears in the task carousel.

**Transfer:**

- Use the declared short color and border transitions on discovery and authentication controls.
- For an oversized proof sentence, retain the clipped horizontal continuation; do not introduce unrelated bouncing or zooming effects.

**Unknown:**

- Exact scene entrance choreography, banner loop timing and media playback behavior are not established.

### Responsive

**Observed:**

- Styles declare width thresholds at 575px, 724px, 767px, 991px, 1024px, 1200px, 1535px and 1800px; the acquisition variant uses 575px, 767px, 991px and 1200px.

**Transfer:**

- Recommended adaptation: stack split scenes on narrow screens, retaining title/support/action hierarchy and letting staged media bleed to the viewport edge.
- Recommended adaptation: reduce outer rails, keep the center panel dominant in the hero fan and clip the outer panels rather than shrinking every UI label to illegibility.
- Recommended adaptation: retain distinct scale differences in the proof constellation while moving peripheral circles away from captions.

**Unknown:**

- Mobile layouts, exact type reductions, navigation replacement and footer collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
