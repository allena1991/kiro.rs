# SoundCloud — culture in full volume

## Overview

A dark, high-impact style that feels closer to a cultural poster than a software brochure. Heavy grotesk capitals, compact white actions and grainy human photography sit on near-black, with color concentrated inside media rather than spread across the interface. It suits creative platforms and participatory products, balancing spacious image-led statements with dense, useful discovery and capability blocks.

### Essentials

- Poster-like headlines are compressed into loud stacks: Söhne at 65px, weight 800, 0.85 line height and -0.02em tracking, in white uppercase.
- The default opening is an inset photographic billboard, not a centered software pitch: a 1240px-wide, 450px-high stage with 16px corners, left-hand text and a large person occupying the right half.
- Actions look like small, decisive labels against the imagery: the default pill is 32px high with 24px horizontal padding and 17px semibold text; larger standalone actions grow to 46px.
- The interface stays almost entirely near-black and white: #121212 canvas, #303030 utility surfaces and #999999 secondary text. Saturated color lives mainly in photography and object art; orange text accents belong to educational campaign variants.
- Media alternates human presence with a floating product-world assemblage: an oversized, grainy portrait and a roughly 470×436px cutout object composition must carry the visual story. If specialist art is unavailable, use a clean cutout of the new product with two related physical objects on the same black backing.
- Closing persuasion is still editorial: a 620×350px photograph beside another 65px uppercase statement and a compact pill, followed by a low, centered social/link/wordmark footer rather than a giant colored conversion panel.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light blue link | `#699fff` | `--color-link` | link | Inline announcement links and secondary conversion links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-primary` | text, surface, action | Main headings, paragraphs, primary actions and testimonial cards. |
| Soft white action | `#f3f3f3` | `--color-button-soft` | action, surface | Compact hero action. |
| Muted gray | `#999999` | `--color-secondary` | text, link | Secondary navigation, creators and footer links. |
| Translucent white edge | `#363636` | `--color-edge` | border | Visible equivalent of rgba(255,255,255,0.15) on the dark canvas; the same alpha also outlines utility surfaces. |
| Utility charcoal | `#303030` | `--color-utility` | surface, background | Announcement strip, search fields and utility controls. |
| Near-black canvas | `#121212` | `--color-canvas` | background, text | Default page backing and inverse text on white actions. |
| True black | `#000000` | `--color-black` | surface, text, action | Dark action over pale photography and campaign button inversion. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| task-focused acquisition pages | Off-white proof band | `#f8f8f8` | `--color-proof` | background | Large contrasting testimonial band. |
| educational campaigns | Campaign near-white | `#fafafa` | `--color-campaign-white` | text, surface | Campaign section headings and conversion actions. |
| educational campaigns | Campaign soft text | `#dcdcdc` | `--color-campaign-copy` | text | Visible rgba(250,250,250,0.87) over near-black for card descriptions. |
| educational campaigns | Signal orange | `#ff5500` | `--color-orange` | accent, link, text | Short highlighted headline phrases, step titles and learn-more links; not a default full-width fill. |

## Typography

- **Söhne** — All marketing headings, prose and actions; campaign cuts use the unaccented Sohne family spelling. Compact contemporary grotesk with very heavy display cuts, open small text and a blunt, direct character. If unavailable, use **Inter**. Use 400–800; preserve the unusually tight display leading and tracking. Font stack: "Söhne", "Inter", system-ui, -apple-system, 'Segoe UI', Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Söhne | 800 | 65px | 0.85 | -0.02em, uppercase | Default opening and major promotional statements. |
| lead | Söhne | 600 | 19px | 1.1 | -0.01em | Compact supporting text beside display statements. |
| action | Söhne | 600 | 17px | 24px | 0.012em | Default marketing pills. |
| ui-label | Söhne | 600 | 14px | 20px | normal | Navigation and media tile labels. |
| caption | Söhne | 400 | 14px | 20px | normal | Secondary links and footer text. |
| announcement | Söhne | 700 | 14px | 18px | normal | Single-line announcement copy and its inline link. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| educational campaigns | campaign-display | Söhne | 800 | 80px | 0.9 | -0.0125em, uppercase | Centered three-line hero promise using the Extrafett cut. |
| educational campaigns | campaign-heading | Söhne | 800 | 68px | 0.9 | -0.02em, uppercase | Carousel chapter heading. |
| educational campaigns | faq-heading | Söhne | 600 | 60px | 80px | normal | Centered sentence-case FAQ section label. |
| educational campaigns | campaign-subheading | Söhne | 800 | 48px | 1 | normal, uppercase | Large multi-line guide title with a short orange phrase. |
| task-focused acquisition pages | task-heading | Söhne | 600 | 36px | 1 | normal | Sentence-case opening and section headings. |
| educational campaigns | faq-question | Söhne | 600 | 24px | 1 | -0.02em | Spacious accordion question labels. |
| task-focused acquisition pages | task-action | Söhne | 600 | 22px | 28px | normal | Rectangular conversion buttons. |
| educational campaigns | campaign-card-heading | Söhne | 800 | 21px | 1.02 | normal, uppercase | Titles under portrait video cards. |
| task-focused acquisition pages | feature-heading | Söhne | 600 | 20px | 28px | normal | Three-column capability labels. |
| educational campaigns | campaign-lead | Söhne | 600 | 19.2px | 1.3 | normal | Centered hero support using the Halbfett cut. |
| task-focused acquisition pages | body-large | Söhne | 400 | 18px | 22px | normal | Section introductions. |
| task-focused acquisition pages | body | Söhne | 400 | 16px | 1.25 | normal | Capability descriptions. |
| educational campaigns | campaign-action | Söhne | 600 | 16px | 1.5 | normal | White hero conversion pill. |
| educational campaigns | campaign-caption | Söhne | 400 | 14.7px | 1.25 | -0.011em | Descriptions under portrait videos. |
| task-focused acquisition pages | quote | Söhne | 400 | 14px | 1.24 | normal | Compact testimonials below portraits. |

**Notes:**

- The display leading is tighter than the font size: short uppercase statements form dense blocks, while paragraphs remain small and compact.
- Use the default 65px recipe for ordinary marketing; do not average it with the 36px sentence-case acquisition variant or 80px centered campaign variant.
- Campaign font files named Buch, Halbfett, Dreiviertelfett and Extrafett are cuts of the same family. Their visual weights, not a regular-weight file declaration, define the hierarchy.

## Layout

**Density:** Airy around major media statements, compact inside controls and text groups; utilities and discovery rows retain product-like density.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Media-to-caption and feature-title-to-description separation. |
| 16px | Hero text grouping, media tile gaps and common content separation. |
| 20px | Campaign card gaps and announcement vertical padding. |
| 24px | Compact pill horizontal padding. |
| 32px | Hero inner side padding and common flex gaps. |
| 48px | Gap after the opening stage before the discovery actions; capability row offset. |
| 64px | Lower padding of large promotional bands. |
| 65px | Acquisition section inner side padding. |
| 80px | Default footer top padding. |
| 130px | Top padding of the light proof band. |

### Containers and grids

- **marketing container**: max width 1240px · side padding 32px. Center the main stage; at a 1440px window the outer gutters are 100px. The padding belongs inside the photographic stage.
- **support measure**: max width 560px. Short supporting paragraphs under left-aligned display headlines.
- **split promotion**: 2 columns · gap 0px. Half-width photo paired with a similarly sized text area; photo can be 620×350px.
- **acquisition grid** (only for task-focused acquisition pages): max width 1110px · 3 columns · gap 45px · side padding 65px. Three 340px proof or capability columns inside the main container.
- **campaign container** (only for educational campaigns): max width 1200px · side padding 0px. Wider campaign chapters with 120px desktop outer gutters; centered opening text uses a 640px measure.
- **portrait rail** (only for educational campaigns): 3 columns · gap 20px. 370px-wide slides with the next slide partially visible; overflow is clipped, not squeezed into four columns.
- **faq measure** (only for educational campaigns): max width 900px · gap 18px. Single-column list of roomy questions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | hero stage | 16px |
|  | media tile | 12px |
|  | utility panels | 4px |
| task-focused acquisition pages | task buttons | 4px |
| educational campaigns | faq rows | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media edge | `inset 0px 0px 0px 1px rgba(18,18,18,0.1)` | Barely visible internal edge of artwork tiles; no raised-card shadow. |

### Surfaces

#### Dark canvas · level 0

**Use:** Continuous backing for most of the page.

**CSS:** `background: #121212; color: #ffffff`

**Observed:** Sections are separated primarily by composition and space, not alternating colored panels.

**Transfer:** Keep the page visually continuous behind independent media blocks.

#### Utility strip · level 1

**Use:** Announcements and dense utility surfaces.

**CSS:** `background: #303030; border: 1px solid rgba(255,255,255,0.15); border-radius: 4px`

**Observed:** A shallow outlined strip sits above the main stage.

**Transfer:** Confine important notices to a thin neutral band.

#### Photographic stage · level 1

**Use:** Default opening image container.

**CSS:** `border-radius: 16px; overflow: hidden; background-size: cover; background-position: 100% 0%`

**Observed:** An edge-to-edge photograph supplies all visible material within the rounded stage.

**Transfer:** Choose imagery with enough tonal separation to carry white text without an additional text card.

#### Slanted proof band · level 0

**Only for:** task-focused acquisition pages

**Use:** High-contrast human proof chapter.

**CSS:** `background: #f8f8f8; color: #121212; padding: 130px 65px 100px`

**Observed:** Top and bottom edges rise toward the right, using 63px-high diagonal masks across a 1240px band. Cards remain upright.

**Transfer:** Use SVG triangles in the canvas color at both edges; do not rotate the text or cards.

#### Transparent FAQ row · level 1

**Only for:** educational campaigns

**Use:** Objection-handling list.

**CSS:** `border-radius: 20px; backdrop-filter: blur(5px); padding: 20px 44px 32px 0px`

**Observed:** The row is visually almost indistinguishable from the dark background, not a visibly frosted tile.

**Transfer:** Preserve the unboxed appearance even when retaining the blur declaration.

## Components

### Primary pill

**Use:** Default action over a media-led statement.

**CSS:** `background: #f3f3f3; color: #121212; border-radius: 9999px; height: 32px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Söhne 600 · 17px/24px · tracking 0.012em

**Observed:** A short light label sits at the lower left of the opening content. Secondary actions can be plain text alongside it.

**Transfer:** Use a short verb phrase rather than a promotional sentence.

### Standalone pill

**Use:** Larger action in an open dark area.

**CSS:** `background: #ffffff; color: #121212; border-radius: 9999px; height: 46px; padding: 13px 23px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — Söhne 600 · 17px/24px · tracking 0.012em

**Observed:** Centered below a broad search field with a small alternative connector between them.

### Announcement banner

**Use:** Short contextual notice above the hero.

**CSS:** `background: #303030; border: 1px solid rgba(255,255,255,0.15); border-radius: 4px; padding: 20px 30px; height: 68px; display: flex; align-items: center`

**Text style:** `announcement` — Söhne 700 · 14px/18px

**Observed:** Centered bold sentence with an inline light-blue link, tiny leading symbol and a close control pinned to the right.

### Media tile

**Use:** Horizontal discovery rail with artwork and two text rows.

**CSS:** `width: 190px; border-radius: 12px; background-size: cover; background-position: 50% 50%; box-shadow: inset 0px 0px 0px 1px rgba(18,18,18,0.1)`

**Text style:** `ui-label` — Söhne 600 · 14px/20px

**Observed:** Square artwork above a white truncated title and muted creator line; caption begins 8px below the artwork. Tiles are separated by 16px, without surrounding card fill.

**Transfer:** Show actual items made or available through the new product, keeping the two-level title treatment.

### Compact footer

**Use:** Low-contrast ending after the last promotional statement.

**CSS:** `color: #999999; padding-top: 80px; padding-bottom: 15px; text-align: center`

**Text style:** `caption` — Söhne 400 · 14px/20px

**Observed:** Centered social icons precede one wrapping line of small dot-separated resource and legal links, then a language selector and a small wordmark. The task-page variant reduces this to links and language; the campaign variant uses an isolated small symbol and a horizontal legal row.

**Transfer:** Finish with a modest identity mark rather than oversized footer navigation.

### Utility navigation link

**Only for:** task-focused acquisition pages

**Use:** Dense navigation in a persistent 46px header.

**CSS:** `color: #999999; padding: 13px 8px; display: flex; margin-right: 8px`

**Text style:** `ui-label` — Söhne 600 · 14px/20px

**Observed:** Wordmark, a short navigation group, rectangular search, account actions and an overflow control share one horizontal line. Active navigation has a white underline.

### Testimonial card

**Only for:** task-focused acquisition pages

**Use:** Human proof on the light diagonal band.

**CSS:** `background: #ffffff; color: #121212; width: 340px; padding: 12px 16px 14px; margin-top: 60px`

**Text style:** `quote` — Söhne 400 · 14px/1.24

**Observed:** Small name and audience count sit above a 308×235px portrait, followed immediately by a compact quote. Three upright cards step upward by 60px each; they have square corners and no drop shadow.

**Transfer:** Use real customers or contributors; the count should measure something meaningful rather than serve as decoration.

### Task conversion button

**Only for:** task-focused acquisition pages

**Use:** Large-label conversion below image or capability proof.

**CSS:** `background: #ffffff; color: #121212; border-radius: 4px; height: 40px; padding: 6px 12px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `task-action` — Söhne 600 · 22px/28px

**Observed:** The light-band variant inverts to a dark fill. A blue secondary link can share the closing action row.

### Campaign pill

**Only for:** educational campaigns

**Use:** Centered conversion over a full-width photographic hero.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid rgba(255,255,255,0.5); border-radius: 200px; padding: 8px 32px; height: 42px`

**Text style:** `campaign-action` — Söhne 600 · 16px/1.5

**Observed:** One white action follows centered support text; the carousel heading also carries a right-aligned pill.

**States:** Declared: hover background-color #000000, color #ffffff, border-color #ffffff; active outline 0px and color #43464d. Focus-visible treatment is unknown.

### FAQ row

**Only for:** educational campaigns

**Use:** Quiet accordion under the guide chapter.

**CSS:** `border-radius: 20px; backdrop-filter: blur(5px); padding: 20px 44px 32px 0px; width: 900px`

**Text style:** `faq-question` — Söhne 600 · 24px/1 · tracking -0.02em

**Observed:** Each question sits at the left of a roomy transparent row, with a small gray plus immediately after the question group rather than against the far page edge. Collapsed rows read as text in open space.

## Imagery and graphics

### Grainy human billboard

**Use:** Primary identity-bearing opening and human promotional panels.

**Observed:** An oversized portrait fills the stage. The opening figure is off-center to the right, with raised arms extending through the frame; muted green-gray clothing, deep shadows and visible grain give the image an analog cultural tone. Text occupies the quieter left side. Later photography shows a person at work, lit by direct flash against a dark studio curtain.

**Transfer:** Photograph a real practitioner in the new product's context. Favor a bold gesture, imperfect texture and a dark face-to-background range over a polished stock-office scene. Preserve negative space for the headline.

### Floating object assemblage

**Use:** Required visual counterpart to the human imagery, in a major dark promotional chapter.

**Observed:** A roughly 470×436px composition of phone, headphones, looping keyboard, chain and glossy fragments floats directly on black. Orange and lavender lacquered objects mix with white keys, metallic outlines and grain; there is no enclosing card.

**Transfer:** Assemble the new product's core object with two or three adjacent tools. The minimum version is a crisp transparent product cutout with a looping ribbon and two accessory cutouts; maintain a strong colored center and a dark empty surround.

**Build:** Layer transparent cutouts or SVG shapes in a 470×436px relative wrapper. Place a tilted central device across the middle, a looping strip behind it and two overlapping accessories near opposing corners. Use black outlines, pale specular patches and a restrained grain mask clipped to each object; leave the wrapper transparent. Shape colors should echo the new product rather than tinting the whole page.

### Staggered proof portraits

**Only for:** task-focused acquisition pages

**Use:** Portraits inside testimonial cards.

**Observed:** Three closely framed portraits use distinct treatments: muted natural green-gray, saturated red side lighting and monochrome. Their rectangular framing stays consistent despite varied lighting.

**Transfer:** Keep human variety and a documentary feel; unify dimensions rather than forcing a single artificial duotone.

### Portrait video rail

**Only for:** educational campaigns

**Use:** Capability education through short creator-led video.

**Observed:** Tall portrait media is staged in a clipped horizontal rail. One visible tile is a casually dressed presenter against a plain gray wall; others use dark branded title frames. Descriptions sit outside the media, with uppercase white titles and orange learn-more links.

**Transfer:** Use actual vertical explainers with poster frames and ordinary human presenters. Keep the platform's player controls inside the media rather than turning their colors into marketing tokens.

### Layered product demonstration

**Only for:** task-focused acquisition pages

**Use:** Closing feature proof before conversion.

**Observed:** A large white desktop interface overlaps two smaller phone views on a continuous dark background. Fine orange edges and orange chart bars are confined to the demonstration; the montage is centered and much wider than its action row.

**Transfer:** Show one legible desktop result in front with mobile contexts behind. Preserve the bright-on-dark silhouette, without rebuilding every interface detail.

### Icons

**Observed:** Most utility and social icons are solid monochrome SVGs at 16px, 22px or 24px. The educational guide uses larger gray outline pictograms beside short orange titles, visually distinct from navigation symbols.

**Transfer:** Choose compact filled symbols for utilities and social actions; reserve thin outlined pictograms for instructional lists. Keep icons subordinate to the heavy text.

## Section recipes

How recurring sections are built.

### First screen: Inset human billboard opening

**Observed:** A shallow Announcement banner spans the centered 1240px container, followed by a 32px gap and a 450px-high Photographic stage. The stage occupies half of the first 900px viewport. Back to front: full-bleed grainy portrait, a logo at upper left and small account pills at upper right, then the left-aligned two-line 65px uppercase display and tightly led support in a 560px measure. The face and gesture dominate the right half. Primary pill sits lower left, a small subject credit lower right, and three 12px circular slide indicators sit at the bottom center. Below the stage, the first screen also reveals a centered 600×46px pill search, an alternative action and a discovery heading; the artwork rail starts at the fold and its captions fall below it. There is no separate utility header above this default opening.

**Transfer:** Use a striking practitioner portrait or a tightly framed product-in-use image with clear left-side text space. Keep logo and short navigation inside the image stage. A task-oriented acquisition page instead uses a 36px sentence-case headline over a photographic collage with three benefits beneath; an educational campaign opens full-width with a centered 80px uppercase statement over a close-up human image.

**Avoid:** Do not replace the first impression with a centered white SaaS dashboard, an abstract gradient or a separate boxed text panel over the photograph.

**Text style:** `display` — Söhne 800 · 65px/0.85 · tracking -0.02em · uppercase

### Discovery invitation

**Observed:** A centered search and Standalone pill form a compact vertical fork. Below them, a small centered heading introduces a horizontally overflowing row of Media tiles on Dark canvas. The rail uses real square artwork rather than uniform marketing feature cards.

**Transfer:** Offer two immediate modes of participation, then expose actual content or outputs. Let the content breadth extend beyond the container.

### Object-led availability statement

**Observed:** A broad dark split chapter pairs a two-line display headline on the left with Floating object assemblage on the right. A 152px square QR code and short availability copy sit side by side below the heading. The chapter has substantial breathing room, with 64px lower padding.

**Transfer:** Keep the combination of heavy text, a practical access mechanism and expressive object art; replace the QR with a relevant access action when appropriate.

**Text style:** `display` — Söhne 800 · 65px/0.85 · tracking -0.02em · uppercase

### Human closing invitation

**Observed:** A 620×350px documentary photograph occupies the left half. On the right, a short uppercase display stack is followed by compact lead copy and a small white pill. Compact footer follows without changing the page background.

**Transfer:** Close on participation or an attainable outcome, using a human image rather than repeating the opening photo.

**Text style:** `display` — Söhne 800 · 65px/0.85 · tracking -0.02em · uppercase

### Slanted testimonial chapter

**Only for:** task-focused acquisition pages

**Observed:** Slanted proof band uses 130px top and 100px bottom padding. A 36px sentence-case heading and 18px introduction sit above three Testimonial cards. Each card rises 60px relative to the previous one, echoing the diagonal band. A dark Task conversion button anchors the lower left.

**Transfer:** Use the diagonal and stagger to energize genuine proof, not to distort the reading surface.

**Text style:** `task-heading` — Söhne 600 · 36px/1

### Capability grid and demonstration close

**Only for:** task-focused acquisition pages

**Observed:** A 36px heading and support introduce a three-column text grid, with 20px labels and compact 16px descriptions. A centered layered desktop-and-phone montage fills the next wide area. The action row pairs Task conversion button with a blue text link; a slim legal and language footer ends the page.

**Transfer:** Explain three useful outcomes, substantiate them in one clear product image, and make the final action small relative to the proof.

**Text style:** `task-heading` — Söhne 600 · 36px/1

### Campaign video chapter

**Only for:** educational campaigns

**Observed:** A 68px uppercase chapter title and right-aligned pill sit above a portrait video rail with 60px separation. Slides are 370px wide and separated by 20px; three fit with a glimpse of the next. Bold uppercase titles, small soft-white descriptions and orange links sit below media.

**Transfer:** Organize explainers around benefits rather than generic resource categories.

**Text style:** `campaign-heading` — Söhne 800 · 68px/0.9 · tracking -0.02em · uppercase

### Instruction and objections

**Only for:** educational campaigns

**Observed:** A 48px uppercase heading fills the left column while a five-item pictogram guide occupies the right. A short phrase in the headline and guide labels are orange. Below this, a centered 60px sentence-case FAQ heading introduces five transparent FAQ rows. A long dark release of space separates the questions from the small centered footer symbol and legal links; there is no added conversion banner.

**Transfer:** Pair an emphatic guide title with concise actionable steps, then answer practical objections. End with restraint, allowing the legal footer to remain small.

**Text style:** `campaign-subheading` — Söhne 800 · 48px/1 · uppercase

## Page flow

**Storyline:** participation promise → tangible content or capability proof → human or product-world persuasion → practical next action → restrained utility ending

### Broad participation and discovery landing page

1. **Promise** — Inset human billboard with a short reciprocal headline and compact action.
2. **Product discovery** — Search-or-contribute choice followed by a square-artwork rail.
3. **Access proof** — Heavy availability statement, QR access and floating object collage.
4. **Closing invitation** — Human photo paired with a second bold statement and small action.
5. **Utility ending** — Social row, inline resources, language and a small wordmark.

**Transfer:** Make the product feel inhabited before listing specifications; show its content, then the people and tools around it.

### Task-focused acquisition page

1. **Promise** — Image collage with sentence-case outcome, large-label action and a three-benefit row.
2. **Social proof** — Light diagonal band with staggered portrait testimonials.
3. **Capability proof** — Three text columns followed by layered device interfaces.
4. **Closing action** — Trial action and secondary plan link above a slim legal footer.

**Transfer:** Reduce headline theatrics for a specific task, but preserve photography, contrast and the diagonal proof treatment.

### Educational campaign landing page

1. **Promise** — Full-width close-up human image, centered uppercase promise and one pill.
2. **Capability education** — Portrait-video rail with bold external captions and orange links.
3. **Practical guidance** — Split guide headline and five illustrated action steps.
4. **Objection handling** — Large centered FAQ heading and quiet transparent rows.
5. **Utility ending** — Small isolated identity symbol, then a restrained legal line.

**Transfer:** Use the stronger centered type and orange text accents only for a campaign or education context; let questions, not another sales panel, finish the argument.

## Writing

Direct, culturally fluent and encouraging, with confident outcomes grounded in participation. It sounds like an invitation from a scene, not a technical specification or luxury manifesto.

**Do not copy:** Do not reuse SoundCloud names, wordmarks, artist identities, photography, quotes, audience counts, platform claims or proprietary program names. The source examples illustrate rhythm only; write truthful claims for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for the service's role and active verbs for the reader's next move.
- **Rhythm:** Short headline fragments, often two balanced clauses, followed by one or two compact explanatory sentences. Actions are usually two to five words. Display capitals provide emphasis without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A terse opportunity, a reciprocal contrast or a concrete progression. | 3–7 words | “Discover. Get Discovered.”<br>“First upload to first album” |
| Supporting line | Address the reader's aspiration and explain the product's useful role. | 15–35 words | “[Brand] is where you define what's next in music. Just hit upload.”<br>“Uploading is just the beginning: [Brand] gives you the tools to level up your career.” |
| Primary action | Plain verb plus immediate object or next step. | 2–5 words | “Get started”<br>“Upload your first track”<br>“Try it free” |
| Closing headline | A brief rallying invitation or continuing benefit. | 3–4 words | “Calling all creators”<br>“Never stop listening” |
| Instruction label | Imperative tied to one practical behavior. | 2–5 words | “Nail your profile”<br>“Connect with your scene” |

**Words and phrasing to use:** discover; connect; your; first; next; share; get started; community; grow

**Avoid:** revolutionary ecosystem; synergize; best-in-class solution; unleash infinite potential; luxurious experience

**Rules:**

- Make the headline emotionally legible before explaining mechanisms.
- Use specific actions to make aspirational copy credible.
- Keep feature labels useful and benefit-led; use everyday verbs rather than technical category names.
- Let proof carry numerical claims; keep the main headlines short and human.

## Do's and Don'ts

### Do

- Keep the default display at 65px/0.85 with -0.02em tracking and uppercase.
- Center the 1240px stage within dark outer gutters and clip its photo at 16px corners.
- Use 32px compact hero pills and 46px standalone pills as distinct action sizes.
- Keep supporting marketing copy close to 19px/1.1 and limited to a 560px measure.
- Use real square media at 190px with 12px corners and 16px rail gaps.
- Include both grainy human presence and a floating object composition somewhere in the new page.
- Use square white proof cards with 16px side padding inside the acquisition variant.
- Finish with small centered links and identity rather than enlarging the legal area.

### Don't

- Do not turn orange into the default button fill; the ordinary marketing action is light on dark.
- Do not apply the campaign's 80px centered headline to every section.
- Do not soften all corners to 20px: hero, tile, task button and pill radii have different jobs.
- Do not elevate every tile with a drop shadow; artwork uses only a faint inset edge.
- Do not wrap discovery captions in filled charcoal cards; they sit directly on the canvas.
- Do not skew testimonial text to follow the diagonal section edges; cards stay upright.
- Do not spread the floating collage across a colored full-width backdrop; its silhouette belongs on near-black.
- Do not substitute outline icons for all utility symbols; navigation uses compact filled marks.

## Motion and responsive

### Motion

**Observed:**

- Actions and surfaces declare opacity 0.2s, background 0.2s, border-color 0.3s, transform 0.2s ease-out and background-color 0.25s transitions.
- The opening supports slide indicators; the educational media rail has previous and next controls.
- Campaign pill declares a white-to-black hover inversion.

**Transfer:**

- Keep interaction emphasis local to actions and media rails rather than animating the entire dark canvas.
- Use the declared 0.25s background-color transition for the campaign pill inversion.

**Unknown:**

- Carousel autoplay timing, slide easing and video playback sequencing are unknown.
- FAQ expansion behavior and its exact timing are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 768px, 1024px and 1280px; the campaign also declares 991px, 1440px and 1920px rules.

**Transfer:**

- On narrow layouts, preserve the portrait as the dominant opening material and reframe it so the face does not collide with the headline.
- Stack split promotional sections and reduce outer gutters before shrinking the heavy headline into ordinary body scale.
- Retain horizontal media rails with partial next-item visibility instead of compressing portrait videos into narrow columns.

**Unknown:**

- Only desktop composition is established; exact mobile font sizes, navigation collapse and section stacking rules are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
