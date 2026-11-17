# Yung Studio — experiments on black

## Overview

An image-led, restless creative style with a black gallery shell, matter-of-fact grotesk typography and small instrument-like controls. Bright editorial cards, tactile product photography and moving graphic experiments bring color into an otherwise monochrome interface. It suits ambitious product launches, creative tools and portfolios that can show their work rather than surround it with sales language; density shifts from a busy visual feed to almost empty closing statements.

### Essentials

- The promise is a compact introduction, not a billboard: regular grotesk at 40px/1.1, normal tracking, in a 672px column aligned to a 36px page gutter, followed by an 18px semibold arrow link.
- The interface behaves like a gallery frame: black canvas, white text and 1px white rules; saturated color belongs primarily to media and editorial cards, not to full-page navigation or body copy.
- Navigation is a miniature control bank: 50px-high outlined rectangles with 10px corners, 12px semibold uppercase labels, and a 34px-high selected insert with 6px corners. Circular 50px controls are reserved for social destinations.
- A visual feed is part of the identity: use a 20px-gutter, three-column modular composition with occasional two-column media, staggered starts and white caption plates laid over lower-left image corners. If there is no campaign photography, produce close-up object studies and composed interface scenes.
- Proof becomes a paired performance: a half-width stack of 129px result rows faces a large changing image; the selected result gains a muted indigo backing and a right arrow. Preserve this device with genuine outcomes or concrete product capabilities.
- The final invitation has room to breathe: a regular 60px/1.1 two-line heading in a 672px column, a 24px semibold arrow action 40px beneath, and 240px external vertical margins before the ruled utility footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof indigo | `#333766` | `--color-proof` | surface, accent | Muted indigo behind the selected proof row; confined to the proof selector rather than the page canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-foreground` | text, surface, border, action | Default text, 1px control outlines, selected navigation inserts and opaque caption plates. |
| Gallery black | `#000000` | `--color-canvas` | background, text, action | Default page canvas and control fill; reversed text on white caption plates and light editorial chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form case studies | Credits coal | `#1a1a1a` | `--color-coal` | surface | Low-contrast attribution panel on black. |
| culture and people chapters | Network ice | `#e2e9ff` | `--color-network` | background | Initial pale blue field behind a floating people-and-object composition; this chapter also changes through pale green and acid yellow. |

## Typography

- **__polySans_c5b537** — All marketing headings, prose, actions and captions. An open, contemporary grotesk with circular bowls and a slightly idiosyncratic drawing; regular text remains direct rather than luxury-editorial. If unavailable, use **Inter**. Use 400 and 600; preserve normal tracking and tune wrapping to the stated column widths. Font stack: "__polySans_c5b537", "Inter", Helvetica, Arial, sans-serif.
- **__polySansMono_2d6016** — Technical metadata, dates and institutional names. Compact, evenly spaced annotation lettering that contrasts with conversational sans headlines. If unavailable, use **IBM Plex Mono**. Font stack: "__polySansMono_2d6016", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-heading | __polySans_c5b537 | 400 | 60px | 1.1 | normal | Two-line closing invitation; also the centered heading in the people-chapter variant. |
| intro | __polySans_c5b537 | 400 | 40px | 1.1 | normal | Default first-screen promise, constrained to 672px. |
| card-heading | __polySans_c5b537 | 400 | 28px | 1.3 | normal | Title on white image-caption plates; also the heading at the left of a structured archive section. |
| action | __polySans_c5b537 | 600 | 24px | 32px | normal | Closing text action and compact brand-name link. |
| secondary-action | __polySans_c5b537 | 600 | 18px | 28px | normal | Introductory arrow link. |
| card-support | __polySans_c5b537 | 400 | 18px | 1.3 | normal | Short outcome sentence beneath a caption title. |
| utility | __polySans_c5b537 | 400 | 16px | 1.5 | normal | Small utility text and footer information. |
| control-label | __polySans_c5b537 | 600 | 12px | 1 | normal, uppercase | Cap-height-centered label inside navigation controls; the surrounding link provides its own box height. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and culture introductions | manifesto-intro | __polySans_c5b537 | 400 | 60px | 1 | normal | Broad, five-line statement spanning ten of twelve columns. |
| structured recognition and speaking archives | archive-title | __polySans_c5b537 | 400 | 24px | 1.2 | normal | Multiline titles in the right-hand column of an editorial table. |
| structured recognition and speaking archives | archive-meta | __polySansMono_2d6016 | 400 | 16px | 1.3 | 0.02em, uppercase | Dates and organization names beside article or event titles. |

**Notes:**

- Normal tracking is the default even at 60px; do not manufacture a tightly kerned luxury display style.
- Headings are regular while navigation and text actions are semibold. Small uppercase labels belong to controls and metadata, not to every section heading.
- The root size follows 1.111vw at desktop; rem-based dimensions inherit that proportional behavior. Treat the listed recipes as the 1440px desktop baseline.
- Proof-result lettering is visually comparable to the 40px intro, with small mono context labels; results stay in one typographic phrase rather than separating numerals into giant counters.

## Layout

**Density:** Airy gallery shell with a dense, staggered media feed; compact controls contrast with long pauses around proof and conversion.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Text-to-arrow gap. |
| 10px | Caption internal gap and social-control spacing. |
| 12px | Gap between the navigation control groups. |
| 16px | Caption plate padding and intro action margin. |
| 20px | Grid gutters and image-caption inset. |
| 36px | Desktop page gutters and header padding. |
| 40px | Closing headline-to-action gap and archive row spacing. |
| 80px | Service-chapter vertical padding. |
| 100px | Spacing around long-form explanatory chapters. |
| 240px | External margins around the closing invitation. |

### Containers and grids

- **gallery-container**: max width 1600px · side padding 36px. Centered outer content frame; at 1440px the usable width is 1368px.
- **structural-grid**: 12 columns · gap 20px. Underlying alignment grid; wide introductions span ten columns, archive headings three and their records nine.
- **feed-grid**: 3 columns · gap 20px. Staggered visual feed: roughly 443px single-column items and 905px double-column items at desktop. Mix image-led work, smaller colored editorial cards and outlined future-facing notes.
- **intro-column**: max width 672px. Left-aligned introductory promise and closing headline; leave the remaining width open.
- **proof-split**: 2 columns · gap 60px. Half-width image stage opposite a text selector with a 60px right inset; both sit within the gallery container.
- **related-work** (only for case-study endings): 2 columns · gap 20px. Two equal image-led recommendations with overlaid white caption plates.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-plates | 10px |
| selected-tab | 6px |
| social-controls | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Black gallery · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Content is differentiated by position, media and rules, not by elevated panels.

**Transfer:** Keep the interface monochrome while allowing the work to supply chromatic intensity.

#### White caption plate · level 1

**Use:** An opaque readable patch over an image.

**CSS:** `background: #ffffff; color: #000000; border-radius: 10px`

**Observed:** Sits at the lower left rather than tinting the whole image with a gradient.

**Transfer:** Use a short title, compact category marker and one outcome line.

#### Selected proof backing · level 1

**Use:** Active row in the proof selector.

**CSS:** `background: #333766; border-radius: 10px; color: #ffffff`

**Observed:** A muted blue-violet rectangle distinguishes one result while surrounding rows remain unboxed.

**Transfer:** Highlight the currently illustrated result, not every result.

#### White editorial chapter · level 0

**Only for:** company credibility and recognition chapters

**Use:** Reversed-color testimonial and archive area.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** The light theme continues into the footer; black hairlines replace white ones.

**Transfer:** Use a sustained light chapter for extensive reading rather than alternating every small section.

#### Attribution panel · level 1

**Only for:** long-form case studies

**Use:** Credits, scope and resource links.

**CSS:** `background: #1a1a1a; color: #ffffff; border-radius: 10px; padding: 30px 0px 56px`

**Observed:** Four aligned text groups sit on a subdued panel within the page gutters.

**Transfer:** Use for implementation details after the visual story, not as an ordinary benefit card.

#### People field · level 0

**Only for:** culture and people chapters

**Use:** Floating portrait and studio-art scene.

**CSS:** `background: #e2e9ff; color: #000000`

**Observed:** A pastel field evolves toward pale green and yellow as objects and portraits pass around the centered title.

**Transfer:** Keep this playful, spatial chapter distinct from the default black product story.

## Components

### Outline control

**Use:** Navigation destinations and short utility actions.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #ffffff; border-radius: 10px; padding: 19.6px 20px; height: 50px; box-sizing: border-box; text-align: center`

**Text style:** `control-label` — __polySans_c5b537 600 · 12px/1 · uppercase

**Observed:** Cap-height-centered label sits inside a broader link box. On the light editorial theme the colors reverse; the selected destination is filled.

**States:** Declared: hover background-color #fff and color #000; focus-visible not specified.

**Transfer:** Keep these compact and architectural; conversion can remain a text link.

### Segmented navigation

**Use:** A compact set of content categories, repeated in header and footer.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 7px; height: 50px; box-sizing: border-box; background: #000000; border: 1px solid #ffffff; border-radius: 10px`

**Text style:** `control-label` — __polySans_c5b537 600 · 12px/1 · uppercase

**Observed:** Five short category links share one enclosing frame. A separate white insert follows the current category, with black label text, 6px corners and a 34px height. The group sits 12px from standalone Outline controls.

**Transfer:** Use a small, stable category vocabulary; do not turn it into a wide navigation bar.

### Intro arrow link

**Use:** A modest next step beneath the opening promise.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; color: #ffffff`

**Text style:** `secondary-action` — __polySans_c5b537 600 · 18px/28px

**Observed:** Unboxed text is followed by a small right-pointing line arrow.

**Transfer:** Use a concrete verb phrase, not a filled hero button.

### Closing arrow link

**Use:** Primary invitation at the end of the story.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #ffffff`

**Text style:** `action` — __polySans_c5b537 600 · 24px/32px

**Observed:** The arrow is larger than in the introductory link, around 21px; the action stays aligned to the headline’s left edge.

**Transfer:** Let scale and isolation establish priority without adding a colored button.

### Social circle

**Use:** Footer contact and social destinations.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 50px; height: 50px; border: 1px solid #ffffff; border-radius: 9999px; color: #ffffff`

**Observed:** Three icon-only circles sit 10px apart. The glyphs are only 14px, leaving unusually generous internal space. Light-theme circles reverse the ink and border.

**States:** Declared: hover background-color #fff and color #000; focus-visible not specified.

**Transfer:** Keep the circle size even when the destination icon is small; provide accessible names.

### Project caption

**Use:** Readable title and outcome laid over a media tile.

**CSS:** `background: #ffffff; color: #000000; padding: 16px; border-radius: 10px; max-width: 500px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `card-heading` — __polySans_c5b537 400 · 28px/1.3

**Observed:** The title shares its first row with a small outlined category tag. The card-support sentence comes next. A 20px inset positions the plate inside the image’s lower-left corner; its width follows the text up to the maximum.

**Transfer:** Name the offering and describe its effect in one sentence; keep the rest of the image unobstructed.

### Proof result row

**Use:** A text-led selector tied to a changing proof image.

**CSS:** `position: relative; display: block; height: 129px; color: #ffffff`

**Observed:** A small uppercase mono context line precedes a much larger regular result phrase. The active row uses Selected proof backing and an arrow at its right; other rows remain directly on black. Rows are separated by 16px.

**Transfer:** Pair each outcome with a relevant photograph, object study or interface scene. Keep units and descriptions in the same result line.

### Ruled footer

**Use:** The common ending after the invitation or editorial archive.

**CSS:** `background: #000000; color: #ffffff; border-top: 1px solid #ffffff`

**Text style:** `utility` — __polySans_c5b537 400 · 16px/1.5

**Observed:** An inner wrapper uses 50px top padding, 36px side padding and 24px bottom padding. Social circles occupy the upper left; the full navigation group repeats on the right. A second row 40px below holds copyright at left and the underlined policy link at right. The light-theme variant reverses all ink and fill.

**Transfer:** Finish with working navigation, not a huge brand illustration or multi-column sitemap.

### Credits grid

**Only for:** long-form case studies

**Use:** Final project attribution and hand-off details.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 20px; background: #1a1a1a; border-radius: 10px; padding: 30px 0px 56px`

**Observed:** Four three-column groups present scope tags, external links, contributor roles and client credits. The low-contrast surface keeps this information subordinate to the media story.

**Transfer:** Replace the groups with equivalent implementation, partner and resource information appropriate to the product.

## Imagery and graphics

### Gallery media and editorial cards

**Use:** The primary content and color system of the default landing page.

**Observed:** A large pale peach scientific-object close-up sits beside a narrower collage. Later tiles combine stage photography, identity objects, handheld devices, candid travel photographs and experimental renderings. Work images are edge-to-edge inside gently rounded rectangles, with bright detail and no uniform color filter. Smaller editorial cards carry saturated periwinkle, vivid green or neutral gray backings, inset photographs, dates and tiny tags. Some future-facing notes use a dashed outline directly on black.

**Transfer:** Create a varied but well-lit set of real product contexts, detailed object studies and experimental illustrations. Preserve varied tile spans and start heights rather than making every item an identical feature card. The minimum is one dominant close-up, one contextual scene and several smaller process or editorial tiles.

**Build:** Lay out a three-column grid with 20px gutters; let selected images span two columns and use offset starts for smaller cards. Clip media to 10px corners. For an experimental tile without artwork, compose cropped interface fragments, one brightly lit product shape and a few enlarged material details on a colored backing; do not fill the feed with generic gradients.

### Paired proof image

**Use:** The required visual companion to the result selector.

**Observed:** A tall photograph occupies the right half of the page: a metallic spiral award against a black-and-white portrait, then a softly lit product box held by hands. The selected text backing is muted indigo; the image changes the emotional register without changing the black shell.

**Transfer:** Use tangible proof—an output, a real customer context, a physical object or an editorial product image. If no photography exists, render a single output at convincing scale and directional light on a restrained backing.

### Case-study material sequence

**Only for:** long-form case studies

**Use:** Deep explanation of how a system works across touchpoints.

**Observed:** Full-width product studies alternate with equal split images: transparent laboratory trays in warm light, dark teal stationery on textured stock, framed posters with long shadows, screens in real hardware, lab portraits and saturated scientific motion graphics. Text interludes are narrow and left-aligned; media takes most of the page.

**Transfer:** Follow a product concept across physical use, digital interface, making process and people. Preserve the alternation between full-width and paired scenes rather than adopting the displayed client’s visual identity.

### Atmospheric manifesto

**Only for:** company and culture storytelling

**Use:** Full-screen values chapters following a broad textual introduction.

**Observed:** Huge white words stack at the left over red-orange diagonal light smears, prismatic architectural distortion and blue-violet soft terrain. A small explanatory paragraph sits low at the right. The lettering is roughly 200px with a close line step at the desktop baseline, substantially larger than normal marketing headings.

**Transfer:** Use short behavioral statements and a visual metaphor tied to the new organization. This is a culture-story variant, not the default hero.

**Build:** For a minimum equivalent, fill a 1440px by 900px SVG with black; layer diagonal blurred crimson and amber ribbons with broad dark cuts, then add a fine grain filter. Use white regular sans text around 200px, three short lines on the left, and an 18px paragraph in the lower-right third. Scale the entire composition proportionally; an equivalent CSS size rule is 13.889vw for the large lettering.

### Floating people constellation

**Only for:** culture and people chapters

**Use:** A playful social portrait scene.

**Observed:** Circular portraits and rectangular candid photographs orbit a centered black title on changing pale fields. A vivid pink inflated, soft-edged star-like object floats in front, with small black markings wrapping its faces. It is glossy and tactile, not a flat sticker.

**Transfer:** Use authentic people and process images around a stable central phrase; simplify the inflated object to a single soft 3D form rather than reproducing its specific silhouette or markings.

**Build:** Build the floating object as an SVG path with five rounded bulges, filled with a pink radial gradient, a darker magenta lower edge and a broad white highlight at low alpha. Add a soft internal shadow and a small rotated black label. Place it off-center among circular portraits and rounded rectangular photos; keep enough empty field for the central title.

### Highlighted testimonial

**Only for:** company credibility chapters

**Use:** A reading-led pause before structured proof archives.

**Observed:** On white, a large italic black quotation occupies about two thirds of the width. A short phrase is highlighted with a flat purple marker strip. Attribution and an active circular portrait sit on the right, with other portrait options blurred above and below.

**Transfer:** Use a real, permissioned quotation and highlight only a meaningful fragment. Keep the reader focused on the quote rather than turning the section into a row of testimonial cards.

**Build:** Use semantic blockquote text with an italic sans face; wrap one short phrase in a span with a translucent purple background and no padding beyond the text’s line box. Place the author and one sharp circular portrait in the adjacent column; blur only inactive portrait choices, never the active attribution.

### Icons

**Observed:** Small monochrome symbols: 14px social glyphs inside 50px circles, a 14px right arrow with a 2px butt-ended stroke beside the intro link, and a 21px right arrow beside the closing action. External references use a compact diagonal arrow.

**Transfer:** Choose plain line arrows and recognizable monochrome destination marks. Keep icons subordinate to type and avoid decorative icon bubbles in benefit sections.

## Section recipes

How recurring sections are built.

### First screen: Compact promise and visual feed

**Observed:** Black fills the first screen. A 122px header places a compact brand-name link at left and the miniature navigation bank at right, both within 36px gutters. Below it, the regular 40px/1.1 intro occupies a 672px left column over about three lines, leaving the right half empty. A small Intro arrow link follows with a 16px margin. Around 360px down the page, a large two-column image and a narrower collage tile begin the feed; their upper portion and the large image’s lower-left white caption are visible within the first 900px. More staggered cards continue below the fold. Layers are canvas, clipped media and opaque caption plates; no giant text sits over the main object.

**Transfer:** Write one direct sentence that identifies the product’s character and value, keep the short arrow action, then introduce an arresting close-up and a contrasting process collage. Without existing media, make a lit product-output study and an arranged interface composition. A project-detail opening can instead lead with full-width media and follow with a white explanatory panel; an archive can open immediately with large stacked media and a slim year rail; a culture introduction uses the manifesto-intro recipe before immersive art.

**Avoid:** Do not center a giant slogan above two filled CTA pills, or postpone all visual material until after the first screen.

**Text style:** `intro` — __polySans_c5b537 400 · 40px/1.1

### Staggered editorial gallery

**Observed:** Gallery media and editorial cards use Feed-grid alignment. Larger work tiles carry Project captions; narrow notes and editorial posts interrupt the rhythm with dates and small categories. The black gaps are visible and uneven rather than filled by a uniform card surface.

**Transfer:** Mix product use, outputs, process and relevant editorial proof. Use span and offset to establish importance, not a separate colored heading for every card.

### Sticky proof duet

**Observed:** A 900px-tall sticky stage pairs Proof result rows in the left half with Paired proof image in the right half. The text stack is inset from the image by 60px, with a small introductory line above the results. The active row receives Selected proof backing and a large arrow; an all-recognition text link follows the sequence.

**Transfer:** Use a small set of genuine outcomes or capability claims that can each support a visual. A static paired composition is the minimum acceptable version when a changing scene is not practical.

### Open closing invitation

**Observed:** On Black gallery, a Closing-heading wraps over two lines in a 672px column. Closing arrow link follows after 40px. External margins of 240px isolate the invitation before Ruled footer; the right side stays empty.

**Transfer:** Close on an open, collaborative invitation appropriate to the product. Keep the line short and the action unboxed rather than adding a form or another media panel.

**Text style:** `closing-heading` — __polySans_c5b537 400 · 60px/1.1

### Explanatory media chapter

**Only for:** long-form case studies

**Observed:** A full-width opening image is followed by a white rounded project introduction with a broad narrative column and narrower partnership area. Later black text interludes use a short heading and one or two paragraphs within a narrow left column, separated from the next large media panel by substantial space around 100px. Full-width and equal paired imagery alternate.

**Transfer:** Introduce the problem and contribution, then explain each important design or product decision immediately next to a tangible demonstration.

### Case-study tail

**Only for:** long-form case studies

**Observed:** Press references precede Credits grid. Three related editorial cards follow, then a two-column set of related work with Project captions. Open closing invitation and Ruled footer complete the page.

**Transfer:** Offer attribution and useful next reading before the final action; preserve the difference between related articles and related product stories.

### Service taxonomy

**Only for:** company capability chapters

**Observed:** A black section uses an introductory heading, 1px white horizontal rules and rows pairing a service-family label on the left with wrapped small outlined mono tags on the right. The section has 80px vertical padding and 36px side gutters.

**Transfer:** Use for a genuine taxonomy of capabilities or supported workflows; keep each row’s tags terse and consistently shaped.

### Culture to editorial proof

**Only for:** company and culture pages

**Observed:** Manifesto-intro is followed by Atmospheric manifesto, a service taxonomy and Floating people constellation. A White editorial chapter then holds Highlighted testimonial and structured recognition records. The ending is a speaking archive directly above a light Ruled footer, not the black invitation used elsewhere.

**Transfer:** Separate expressive beliefs and people imagery from the more documentary credibility material; let the surface reversal signal the change in reading mode.

### Recognition ledger

**Only for:** structured recognition and speaking archives

**Observed:** A 1px black top rule introduces a twelve-column grid: section title spans three columns, while date, organization and title occupy the remaining nine. The records use 20px column gaps and 40px row spacing. Archive-meta contrasts with Archive-title; linked feature titles can be bold and end in a diagonal arrow.

**Transfer:** Reuse for press, releases, talks or compatibility records with meaningful dates and institutions. Maintain clear column roles instead of placing each record inside a card.

**Text style:** `archive-title` — __polySans_c5b537 400 · 24px/1.2

## Page flow

**Storyline:** Direct introduction → visual demonstrations → selective proof → open invitation or documentary ending → compact repeated navigation.

### A general marketing landing page that introduces character through a varied feed

1. **Promise** — Short left-aligned introduction and a small arrow link above the visual content.
2. **Product demonstration** — Staggered large and small tiles mix finished outcomes, process experiments and editorial notes.
3. **Quantified proof** — A result selector faces a large relevant image.
4. **Closing call** — An isolated two-line invitation and text arrow action lead to the ruled utility footer.

**Transfer:** Lead with a clear proposition and let a curated feed show how the product lives in the world; adapt the selection and quantity of tiles to the available story.

### A work or product archive organized for visual browsing

1. **Product demonstration** — Large stacked landscape media with white caption plates; a narrow year rail marks groups at the left.
2. **Breadth** — Repeated wide images carry different project contexts without extra section headlines.
3. **Social proof** — The same paired proof selector gives context to the archive’s outcomes.
4. **Closing call** — The spacious black invitation and ruled footer end the browse experience.

**Transfer:** Use for an archive of releases, outputs or customer stories; metadata is secondary to the image, and the proof device prevents an endless undifferentiated list.

### A deep product or customer story connecting an idea to its applications

1. **Hook** — Edge-to-edge hero media opens without a superimposed marketing headline.
2. **Context** — A white rounded panel explains the offering, contribution and partnership.
3. **Capability chapters** — Narrow explanatory interludes punctuate full-width and paired material, interface and real-world imagery.
4. **Credibility** — Press references and a coal credits panel document the project.
5. **Discovery** — Related editorial cards and related work provide two kinds of onward exploration.
6. **Closing call** — The shared black invitation and utility footer finish the story.

**Transfer:** Expand only the chapters necessary to explain the product; show the system in multiple contexts without copying a particular client’s visual language.

### A company narrative that moves from beliefs to people to public credibility

1. **Promise** — A wider, 60px statement introduces the working philosophy.
2. **Capability chapters** — Immersive atmospheric statements give way to a ruled taxonomy of services.
3. **Human proof** — A floating portrait-and-object field presents the people behind the work.
4. **Social proof** — A white chapter presents a large highlighted quotation and author selector.
5. **Documentary proof** — Awards, features and speaking records use a structured editorial ledger.
6. **Utility ending** — The final ledger runs directly into the light footer, without a separate invitation.

**Transfer:** Use this as a scoped company-story structure, not as the default product landing page. Retain the contrast between expressive scenes and documentary records.

## Writing

Confident, curious and collaborative. It sounds like designers describing what they made and why, with warmth but little overt sales pressure.

**Do not copy:** Do not reuse the studio name or identity, client names, campaign titles, proprietary artwork, quotes, awards, funding totals, audience metrics or other source-specific claims. Replace them with truthful product-specific content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use “we” for the maker’s point of view and “together” for invitations. Most descriptions state what a product or project does rather than repeatedly addressing “you.”
- **Rhythm:** A conversational introductory sentence gives way to short titles, one-sentence outcome captions and terse control labels. Long-form explanations use compact paragraphs; closing copy is brief enough to wrap deliberately over two lines.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Introductory promise | A first-person identity statement linked to an energetic way of working. | One sentence, about 12–20 words. | “We’re a creative studio powered by curiosity, momentum, and fast-moving ideas.” |
| Outcome caption | A gerund-led statement that explains a concrete effect, not a list of services. | About 6–12 words. | “Building the first instant hormone monitoring for everyday, everywhere”<br>“Expanding access to modern obesity care” |
| Closing invitation | An inclusive invitation that makes collaboration feel exploratory. | About 3–5 words. | “Let’s Experiment Together” |
| Action | A familiar, direct destination or verb phrase without promotional qualifiers. | 1–3 words. | “About Us”<br>“Contact Us” |
| Explanatory heading | A concrete process or tension expressed as a short phrase. | About 4–8 words. | “Encoding cellular connection”<br>“Balancing scientific precision with biological warmth” |

**Words and phrasing to use:** curiosity; momentum; experiment; build; make; together; signal; ideas; iteration

**Avoid:** revolutionary solution; world-class excellence; unlock limitless potential; industry-leading innovation; frictionless synergies

**Rules:**

- Let images show ambition while captions explain the practical effect.
- Use measured outcomes only when they are substantiated; never invent impressive-looking counters.
- Keep uppercase for controls, tags and metadata; sentence-case prose remains conversational.
- In long-form storytelling, explain the connection between a design decision and what someone experiences.

## Do's and Don'ts

### Do

- Keep the default opening at 40px regular in a 672px column rather than competing with the first image.
- Align intro, closing and footer information to the same 36px desktop gutters.
- Use 20px grid gutters even when tile spans and vertical offsets vary.
- Keep control corners at 10px and selected inserts at 6px.
- Give caption plates opaque white fills with 16px padding so image detail never compromises reading.
- Pair proof text with a large image and reserve indigo selection backing for one result at a time.
- Leave 240px of external space around the black closing invitation.
- Reverse the full utility system to black on white when a sustained editorial chapter ends in the light theme.

### Don't

- Do not turn the default canvas into charcoal gradients; the gallery background is true black.
- Do not apply negative tracking or heavy weights to the regular 40px and 60px headings.
- Do not make every tile the same width or start every card on the same horizontal baseline.
- Do not turn rectangular navigation controls into capsule buttons; circles belong to social destinations.
- Do not add drop shadows to caption plates or controls; separation comes from opacity and 1px rules.
- Do not flood body text, navigation and dividers with the colors seen inside the media.
- Do not separate proof numerals into oversized dashboard counters detached from their descriptions.
- Do not replace the repeated footer navigation with an expansive conventional sitemap.

## Motion and responsive

### Motion

**Observed:**

- Color, background-color, border-color, text-decoration-color, fill and stroke transitions are declared at 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- The fixed header declares a transform transition of 0.3s cubic-bezier(0.4, 0, 0.2, 1).
- The proof scene uses a sticky viewport-height composition; immersive culture scenes also use viewport-height sticky layers.
- Text-link arrows declare a hover translation of 8px; color-inverting hover treatments distinguish outlined controls.

**Transfer:**

- Use the declared short color inversion for control feedback; do not add bouncy button physics.
- Keep proof text and its companion image synchronized in a shared stage.
- Let atmospheric material supply motion in culture storytelling while the ordinary gallery remains easy to browse.

**Unknown:**

- Exact scroll thresholds, scene interpolation, media playback timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px, 1440px and 1600px.
- The root font-size is 1.111vw; desktop rem-based dimensions scale with it.
- Intro classes distinguish 24px small-screen and 40px large-screen type; closing headings distinguish 30px and 60px. The media feed uses a single-column flex layout before its wider breakpoint.
- Project caption placement changes from normal flow to an absolute lower-left overlay at wider widths; footer rows switch between stacked and horizontal layouts.

**Transfer:**

- On narrow screens, preserve the compact text-first opening but stack the feed and keep captions in normal flow so they do not hide the image.
- Replace the desktop proof split with readable paired results and imagery rather than shrinking a 900px sticky scene into a narrow column.
- Retain rectangular control construction when navigation stacks; do not compress all category labels into an unreadable desktop-sized strip.

**Unknown:**

- Exact narrow-screen gutters, mobile menu interaction and observed mobile composition remain unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
