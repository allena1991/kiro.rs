# North Kingdom — cinematic play at scale

## Overview

A cinematic creative-technology style with near-black stages, white editorial passages and unexpectedly enormous, light grotesk lettering. Saturated game worlds, dimensional objects and candid photography supply the color while the interface stays monochrome. It suits experiential products and ambitious creative platforms, pairing sparse copy with a dense visual portfolio and a monumental typographic sign-off.

### Essentials

- The opening is a typographic stage, not a headline above a picture: a 900px dark scene carries a nearly full-width white name split around a dimensional media object, with an 88px circular play control over it.
- Headlines have the lightness of body text at architectural scale: regular display grotesk at 115px, 0.95 line height and -0.05em tracking; the opening and closing word sculptures expand beyond the editorial heading scale.
- The interface stays black and white while the worlds inside it are vivid: #050311 and #ffffff form essentially all structural surfaces, with saturated color confined to media and a faint atmospheric glow behind the opening.
- Proof is staged as large windows, not boxed cards: two 690px-wide media columns at 1440px, a 20px gutter, 8px corners and two 24.4px caption lines; secondary captions use white at 60% opacity.
- Actions are deliberately unbutton-like except for playback: regular 24.4px text, a trailing ↗ and underline on hover; playback alone uses a solid white 88px disc.
- A giant typographic sign-off is a signature device: a 1400px-wide wordmark artwork occupies a 285px contrasting footer, with small affiliation and return-to-top links beneath. Use a typeset product name fitted to the same width when custom lettering is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight ink | `#050311` | `--color-ink` | background, text, surface | Default dark stage, portfolio backing and footer; primary text on white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-paper` | background, text, surface, action | Editorial bands, primary reversed text and play discs. |
| Light-theme hairline | `#b6b5b9` | `--color-light-rule` | border | Subtle light-theme navigation edge; built with midnight ink at 29.4% opacity. |
| Reversed secondary gray | `#9b9aa0` | `--color-muted-on-dark` | text | Secondary text on midnight ink; the visible result of white at 60% opacity. |
| Cinema black | `#000000` | `--color-media-black` | background, text | Full-width film backing and small editorial labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruitment pages with white footers | Light footer gray | `#696870` | `--color-muted-on-light` | text | Return-to-top text on white, built with midnight ink at 60% opacity. |
| recruitment pages with white footers | Light affiliation gray | `#828188` | `--color-affiliation-on-light` | text | Affiliation link on white, built with midnight ink at 50% opacity. |

## Typography

- **FKGroteskNeue** — Paragraphs, navigation, card labels and actions. Open, neutral grotesk with a large x-height, used almost entirely at regular weight. If unavailable, use **Inter**. Use 400; preserve compact line height and slightly negative tracking. Font stack: "FKGroteskNeue", "Inter", Arial, sans-serif.
- **FKDisplay** — Editorial display headings and the typographic character of oversized name artwork. Light-looking regular grotesk with tight joins and very close tracking. If unavailable, use **Inter**. Use 400 with -0.05em tracking; fit oversized lettering to the available width. Font stack: "FKDisplay", "Inter", Arial, sans-serif.
- **FKGroteskMono** (only for editorial detail and recruitment pages) — Small project credits and utility counts. Widely tracked monospace, contrasting with the close-set grotesk. If unavailable, use **IBM Plex Mono**. Font stack: "FKGroteskMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | FKDisplay | 400 | 115px | 0.95 | -0.05em | size calc(-58.3px + 12.0354vw) | Large editorial headings and secondary-page opening statements; retain regular weight and close word spacing. |
| body | FKGroteskNeue | 400 | 24.4px | 1.15 | -0.01em | size calc(4px + 1.41593vw) | Default paragraph, navigation, action, project name and project subtitle. Color and placement establish hierarchy rather than weight. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| explorable image walls | interaction-prompt | FKGroteskNeue | 400 | 18px | 1.15 | -0.01em | fixed | Compact floating drag instruction. |
| editorial detail and recruitment pages | caption-uppercase | FKGroteskMono | 400 | 14.6px | 1.15 | 0.05em, uppercase | size calc(8.2px + 0.442478vw) | Two-line media credits and brief counts or direction labels. |
| capability detail sections | caption | FKGroteskMono | 400 | 14.6px | 1.15 | 0.05em | size calc(8.2px + 0.442478vw) | Mixed-case project credit below a small capability thumbnail. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep display tracking at -0.05em and text tracking at -0.01em. Monospace credits reverse that logic with +0.05em.
- Do not invent a ladder of bold headings: body, navigation, project names and actions share one recipe. Display headings provide the strong scale contrast.
- Name sculptures are fitted graphic compositions rather than ordinary wrapped headings. The opening letters reach about 180px at 1440px, with space carved out for the central object; the footer name fits a 1400px-wide, 202px-high artwork box.

## Layout

**Density:** Airy in text passages and monumental openings; image-led proof remains closely packed across the width.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Small thumbnail-to-credit spacing and title-to-thumbnail spacing. |
| 16px | Large portfolio image to its two-line caption. |
| 20px | Main horizontal page inset and portfolio column gutter. |
| 24px | Navigation padding and spacing between navigation links. |
| 40px | Paragraph-to-action separation; reusable content-element spacing. |
| 48px | Portfolio item bottom margin, combined with the 20px grid row gap. |
| 60px | Separation between staggered editorial images. |
| 80px | White editorial band top and bottom padding. |
| 160px | Breathing room after the compact opening support paragraph. |

### Containers and grids

- **full-bleed stage**: max width 1440px · side padding 0px. Edge-to-edge film, opening scene and contrasting horizontal bands at the desktop reference width; continue fluidly with the viewport.
- **editorial frame**: max width 1440px · side padding 20px. Nearly full-width content with a 1400px inner span at desktop.
- **portfolio grid**: 2 columns · gap 20px · side padding 20px. Equal 690px columns at desktop. Each large window is followed by two short labels; combined vertical row separation is 68px.
- **split copy**: 2 columns · gap 20px. Labels or a brief statement occupy the left half; paragraphs and actions occupy the right 690px half. A compact left-aligned introductory paragraph can occupy 700px alone.
- **staggered collage** (only for culture and editorial detail pages): side padding 20px. Unequal media widths of 470px, 590px and 230px sit at different heights, with a 60px pause between stacked items and substantial white voids.

## Corner radius

| Element | Radius |
| --- | --- |
| media windows | 8px |
| content sheet lower corners | 12px |
| play disc | 50% |

## Surfaces and depth

### Surfaces

#### Midnight stage · level 0

**Use:** Default opening, visual proof and contrasting footer backing.

**CSS:** `background-color: #050311; color: #ffffff`

**Observed:** Near-black with a slight violet cast. Large media windows sit directly on it without card panels.

**Transfer:** Let rich imagery carry the palette while the surrounding structure stays dark.

#### White editorial sheet · level 1

**Use:** Narrative, partner proof and closing invitation.

**CSS:** `background-color: #ffffff; color: #050311; border-radius: 0px 0px 12px 12px`

**Observed:** White passages read as a continuous sheet; rounding belongs to the lower edge of the content layer rather than every band.

**Transfer:** Use broad light passages to change reading pace and reveal a contrasting footer beneath.

#### Cinema panel · level 1

**Use:** Large playback stage.

**CSS:** `background-color: #000000; border-radius: 8px; overflow: hidden`

**Observed:** Full-width black film stage with a centered play disc and a lower caption/control region.

**Transfer:** Supply a finished poster frame even before playback.

#### Floating glass instruction · level 2

**Only for:** explorable image walls

**Use:** Small interaction instruction over a dense picture field.

**CSS:** `background-color: rgba(255, 255, 255, 0.2); border-radius: 8px; backdrop-filter: blur(40px); padding: 16px`

**Observed:** A translucent rectangle picks up nearby image colors. It is not a general card treatment.

**Transfer:** Keep glass localized to an interaction hint; let surrounding images remain sharp.

## Components

### Navigation

**Use:** Persistent top-level wayfinding.

**CSS:** `position: fixed; height: 80px; width: 100%; padding: 24px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** A compact 33px by 43px emblem sits left, with four plain text links right and 24px spacing between them. On a dark opening both are white; light contexts reverse to ink and may add a translucent white backing with a fine lower rule. Current-page text is subdued.

**States:** Declared: hover underline on text links.

**Transfer:** Use a compact product emblem rather than a large header wordmark.

### Text action

**Use:** Primary editorial conversion and onward navigation.

**CSS:** `color: #050311; position: relative; margin-top: 40px`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** An unboxed sentence-case link ends with an inline northeast arrow. Dark variants reverse to white.

**States:** Declared: hover text-decoration underline.

**Transfer:** Keep a single concise action at the end of a paragraph block.

### Play disc

**Use:** Primary action within the opening object and full-width film.

**CSS:** `width: 88px; height: 88px; border-radius: 50%; background-color: #ffffff; color: #000000; padding: 1px 6px; transition: transform 350ms cubic-bezier(0.2,0,0,1)`

**Observed:** A small solid triangular play symbol sits centrally within a much larger white circle. The opening disc is attached to the object, not to the page center.

**States:** Declared: hover transform scale(1.1); focus-visible behavior unknown; active transform scale(0.93).

### Portfolio media window

**Use:** Large visual proof item.

**CSS:** `border-radius: 8px; overflow: hidden; object-fit: cover`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** One linked media window carries a project or client name 16px below it, then a secondary project title immediately below. Both labels use the body recipe, the second in white at 60% opacity. There is no separate card backing.

**Transfer:** Use moving or still product scenes with a consistent 690px by 435px frame at desktop.

### Monumental footer

**Use:** Signature closing identity after the final editorial passage.

**CSS:** `position: sticky; background-color: #050311; padding: 52px 20px 24px`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** A giant white wordmark spans the available width above a low-contrast affiliation link left and return-to-top control right. The desktop footer is 285px high and its wordmark artwork is 1400px by 202px. Recruitment reverses it to white with dark lettering.

**Transfer:** Fit the new product's name as a single typographic artwork to the width, preserving the small bottom utility row and broad contrast.

### Return to top

**Use:** Closing-page navigation beside the affiliation link.

**CSS:** `position: relative; padding: 1px 6px; color: rgba(255, 255, 255, 0.6)`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** Plain text with an upward arrow; right-aligned at the foot of the giant wordmark. The white-footer variant uses ink at 60% opacity.

**States:** Declared: hover text-decoration underline.

### Capability row

**Only for:** capability detail sections

**Use:** Explain a capability while anchoring it in visible work.

**CSS:** `display: flex; padding-top: 14px; padding-bottom: 64px`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** A fine horizontal divider precedes the row. Left half: modest title, 333px by 186px thumbnail and a small monospace credit. Right half: a substantial paragraph. The thumbnail group is sticky; successive rows maintain the same split.

**Transfer:** Translate each capability into one clear benefit and one small proof image.

### Opportunity row

**Only for:** recruitment and directory pages

**Use:** Compact actionable listings beneath an oversized heading.

**CSS:** `position: relative; padding-top: 14px; padding-bottom: 14px; color: #ffffff`

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

**Observed:** A thin pale divider spans the row. The title occupies the left half; location starts at the midpoint and the action aligns right. A secondary sentence can continue under the right-hand metadata.

**Transfer:** Use this architecture for positions, availability or other short directories rather than converting them into cards.

### Drag instruction

**Only for:** explorable image walls

**Use:** Signal that the picture field can be moved.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; padding: 16px; background-color: rgba(255, 255, 255, 0.2); border-radius: 8px; backdrop-filter: blur(40px); color: #ffffff`

**Text style:** `interaction-prompt` — FKGroteskNeue 400 · 18px/1.15 · tracking -0.01em

**Observed:** A compact instruction plus a four-direction move symbol floats near the lower center of the wall.

**Transfer:** Only show a drag prompt on a genuinely draggable surface.

## Imagery and graphics

### Dimensional name stage

**Use:** Signature opening artwork for a new landing page.

**Observed:** A nearly full-width white name is interrupted by an upright faceted object carrying vivid landscape/interface imagery. The object is roughly 260px wide and 340px high at desktop, centered slightly left of the page midpoint. Dark teal diagonal faces cut through its warm sunset imagery. A very soft olive light field extends behind it across the black stage.

**Transfer:** Replace the emblem-like object with a product-specific prism, folded plane or sculptural interface window. Minimum acceptable version: a crisp static polygonal image montage interrupting oversized live text, with a softly lit backing and the play disc on the object.

**Build:** Create a 900px-high #050311 stage. Layer two broad radial gradients using rgba(132,139,40,0.18) fading to transparent around 30% 25% and 62% 55%; blur the light layer by 70px. Place an upright clipped hexagonal prism about 260px by 340px between the two text groups. Use polygon faces, one image texture and dark teal rgba(10,45,43,0.9) diagonal planes. Fit white name lettering across the stage at about 12.5vw and overlay the Play disc on the object. Match the soft glow; exact gradient stops are not essential.

### Vivid proof windows

**Use:** Dominant media language for project or product demonstrations.

**Observed:** High-saturation 3D scenes, game characters, rendered worlds, branded interfaces and event photographs fill wide rounded frames. Mint, purple, cobalt and cyan vary freely inside the images while the surrounding page stays monochrome. Frames are large relative to their two-line labels.

**Transfer:** Use finished product worlds or strong staged demonstrations, not tiny screenshots on decorative colored cards. When motion is unavailable, use one art-directed still per window.

### Monochrome partner field

**Use:** Social proof in the white portion of the page.

**Observed:** Black partner marks occupy generous 288px by 140px image slots in three horizontal rows that extend beyond the viewport. The field is typographic and open, with no card borders.

**Transfer:** Use authorized partner marks normalized optically, not equal visual heights; preserve the spacious black-on-white rhythm.

**Build:** Use three horizontally clipped flex tracks, with each logo centered in a 288px by 140px cell. Render vector marks in #000000 against #ffffff. Offset track starts so the field feels continuous beyond both edges.

### Atmospheric landscape and candid collage

**Only for:** culture and company-story pages

**Use:** Secondary-page opening panorama and irregular editorial media.

**Observed:** A full-bleed panorama follows the large dark statement: luminous green and violet aurora for the company story, a silhouetted treeline under a dusky sky for recruitment. Lower images are candid, naturally lit rooms, people and trips, arranged in staggered rounded windows rather than a uniform portrait grid.

**Transfer:** Choose a real landscape tied to the team's environment and authentic activity photographs. Preserve original color and casual framing; contrast these with carefully art-directed product proof.

### Explorable archive wall

**Only for:** culture and company-story pages

**Use:** Immersive archive of creative output before a closing invitation.

**Observed:** Many varied photographs, posters, sketches and renders float in a dark, subtly perspectival field. Roughly 215px image objects occupy 240px cells; several rows and partial edge items make it feel larger than the viewport. The backing is midnight, with a Floating glass instruction near the bottom center.

**Transfer:** Use genuine process artifacts and product experiments, not a repeated stock-photo grid. A static overflow-hidden collage with a few shifted image planes is the minimum visual equivalent; reserve the drag prompt for an interactive implementation.

**Build:** Build an oversized 1920px square field of 240px cells behind a 1440px by 900px clipped stage. Center diverse images within cells at a maximum of about 215px. Use contain fitting, modest individual rotation and slight perspective on the whole field to separate the planes. Keep the backing #050311 and allow edge images to be cut off.

### Icons

**Observed:** Mostly solid monochrome symbols: a 33px by 43px header emblem, 24px play/move icons, 18px media controls and inline text arrows. Icons switch between white and dark with the backing.

**Transfer:** Use filled triangles for playback and typographic ↗ or ↑ arrows for navigation. Keep custom pictograms out of editorial headings.

## Section recipes

How recurring sections are built.

### First screen: Cinematic name opening

**Observed:** The first 900px is one full-bleed Midnight stage. Navigation sits at its top edge. A near-full-width white name crosses the central band; its left word ends at a dimensional object and its right word runs toward the far right edge. Rendered letters are about 180px high in type size, exceeding the ordinary 115px display scale. The 260px by 340px object interrupts the name and carries an 88px Play disc. Layers run from dark backing through diffuse olive light, vivid faceted image object and oversized lettering to the white play control and navigation. Within the first screen there is no supporting paragraph or conventional CTA row; the compact support paragraph starts below the fold.

**Transfer:** Retain the name-as-scene composition for a product landing page. Without dimensional artwork, use a polygon-clipped product montage and large fitted live text, not a generic centered hero. Editorial or recruitment pages instead open with a two-line 115px statement after a deep dark upper pause; a full-width landscape begins about 644px down and continues below the first screen.

**Avoid:** Do not turn the opening into a standard headline, paragraph and two pill buttons stacked over a small screenshot. Do not add explanatory copy into the carefully empty top half.

**Text style:** `display` — FKDisplay 400 · 115px/0.95 · tracking -0.05em

### Compact promise bridge

**Observed:** A 700px-wide body paragraph sits at the left edge of the Midnight stage immediately after the opening, followed by 160px breathing room before proof windows.

**Transfer:** Use one compact positioning statement as a bridge between visual identity and concrete demonstrations.

**Text style:** `body` — FKGroteskNeue 400 · 24.4px/1.15 · tracking -0.01em

### Two-column proof field

**Observed:** Portfolio media windows form equal columns with 20px side insets and gutters. Each 690px by 435px image has 16px before its two-line caption; a 48px item margin plus 20px row gap separates rows.

**Transfer:** Show enough varied examples to establish breadth while preserving identical framing and unembellished labels.

### Full-width film pause

**Observed:** A Cinema panel spans the full page at 780px high. The Play disc is centered; a short title and restrained player controls sit low on the stage.

**Transfer:** Use a single film or visually strong demonstration as a change of pace between grids and editorial text.

### Light proof and split invitation

**Observed:** A White editorial sheet introduces social proof with a half-width paragraph and 80px vertical padding, then a Monochrome partner field. A later split block sets a short statement left and body copy right, with a Text action 40px below the paragraph.

**Transfer:** Use the left side for a concise anchor and the right for a useful explanation or invitation. The partner field can sit wherever external proof best supports the narrative.

### Contrasting name sign-off

**Observed:** The final sheet reveals the Monumental footer: midnight with white lettering after a light ending. The wordmark is almost edge-to-edge, with muted affiliation and Return to top beneath. Recruitment reverses the palette after its dark ending.

**Transfer:** Include an oversized fitted name treatment on every page, choosing the inverse of the last content surface rather than repeating its color.

### Staggered editorial proof

**Only for:** culture and company-story pages

**Observed:** An introductory body paragraph sits in the right half of a white band with 80px vertical padding. Below it the staggered collage distributes unequal rounded image windows across white space. Small uppercase mono credits identify selected work.

**Transfer:** Mix context, people and product output in an asymmetric field while keeping captions brief.

### Capability chapters

**Only for:** capability detail sections

**Observed:** A full-width display heading leads into repeated Capability rows. Each row combines a modest body-sized title and thumbnail left with explanatory copy right; horizontal rules and long breathing spaces replace raised cards.

**Transfer:** Organize complex capabilities into a few benefit-led chapters with a visible example attached.

**Text style:** `display` — FKDisplay 400 · 115px/0.95 · tracking -0.05em

### Archive and monumental invitation

**Only for:** company-story pages

**Observed:** The Explorable archive wall occupies a 900px dark stage, followed by a white closing band with 80px vertical padding. A broad 115px heading spans most of the width, while the supporting paragraph and Text action sit in the right half. The content sheet's lower corners round into the contrasting Monumental footer.

**Transfer:** Pair an abundance of tangible artifacts with one simple invitation; let the final name artwork provide the last visual statement.

**Text style:** `display` — FKDisplay 400 · 115px/0.95 · tracking -0.05em

### Recruitment ending

**Only for:** recruitment and directory pages

**Observed:** A dark closing band uses a 115px display heading with 115px top padding and 36px below. Opportunity rows follow with fine rules and body-sized text. The band retains a substantial dark lower pause, rounds at its lower corners and yields to a white Monumental footer.

**Transfer:** End a recruitment narrative with a usable directory and an open invitation, not a generic sales conversion panel.

**Text style:** `display` — FKDisplay 400 · 115px/0.95 · tracking -0.05em

## Page flow

**Storyline:** immersive identity → concise promise → tangible visual proof → editorial context or external validation → invitation → monumental identity sign-off

### Image-led marketing landing page

1. **identity** — Cinematic name stage with object-linked playback.
2. **promise** — Compact left-aligned paragraph on dark.
3. **product proof** — Two-column visual field with paired labels.
4. **demonstration** — Full-width film pause.
5. **social proof** — White paragraph and moving monochrome partner field.
6. **closing invitation** — Split editorial statement and text action, followed by a dark giant-name footer.

**Transfer:** Lead with a memorable product identity and prove it visually before explaining it at length.

### Recruitment and culture landing page

1. **invitation** — Deep dark opening with large two-line statement above a dusk panorama.
2. **context** — Small count/direction label left and welcoming paragraph right on white.
3. **culture proof** — Candid staggered photo collage.
4. **conversion** — Dark opportunity directory and open-application invitation.
5. **identity sign-off** — White giant-name footer with subdued utility links.

**Transfer:** Exchange product demonstrations for lived evidence, and make the final action a useful listing.

### Company or capability story

1. **positioning** — Large two-line statement on dark with an atmospheric panorama below.
2. **expertise proof** — Right-aligned introduction and irregular media collage with mono credits.
3. **capability chapters** — Oversized heading followed by split ruled rows and small proof images.
4. **breadth proof** — Explorable dark archive wall.
5. **closing invitation** — Large editorial closing line, right-hand paragraph and text action.
6. **identity sign-off** — Dark giant-name footer.

**Transfer:** Explain breadth through concrete examples and concise chapters, then return to a simple invitation.

## Writing

Confident creative practitioners speaking plainly about ambitious work. Warmth and playfulness come through human verbs and invitations rather than jokes or technical bravado.

**Do not copy:** Do not reuse North Kingdom's name, emblem, wordmark artwork, project names, partner marks, founding year, anniversary claims, recruitment details or proprietary copy as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the makers; address the reader as you or your in invitations and outcomes. Project labels can remain neutral names.
- **Rhythm:** Short, speakable headings contrast with compact multi-sentence explanatory paragraphs. Actions are brief sentence-case phrases; occasional exclamation marks belong to warm invitations, not every headline.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Display statement | A simple declarative identity or welcoming phrase, broken for typographic impact. | 4–7 words | “Become a part of our kingdom”<br>“It's all about the play” |
| Support paragraph | State what the team does, then connect it to a human outcome. | 25–60 words | “[Brand] is the creative agency for the world of gaming. We connect players and brands through unforgettable experiences and engaging platforms.” |
| Capability label | Verb plus tangible benefit, or a short craft category. | 2–4 words | “Elevate brand experience”<br>“Engage communities”<br>“Creative tech” |
| Action | Direct verb-led phrase with a directional arrow. | 1–4 words | “See our work ↗”<br>“Apply ↗” |
| Closing invitation | An inclusive, low-pressure welcome after evidence. | One short sentence | “We always welcome applications from talented individuals.” |

**Words and phrasing to use:** create; connect; craft; play; experiences; people; ideas; bring to life; from concept to execution

**Avoid:** revolutionary; best-in-class; synergy; disrupt everything; guaranteed success; excessive acronym chains

**Rules:**

- Let visual examples carry the boldest claims; support them with concrete verbs and outcomes.
- Keep project labels descriptive rather than adding promotional subtitles.
- Use an informal phrase for a major heading, then a more specific explanatory paragraph.
- Write conversion links as natural language, not as all-capital button commands.

## Do's and Don'ts

### Do

- Use #050311 rather than generic charcoal for the main dark stage.
- Keep editorial display text at weight 400 with -0.05em tracking and 0.95 line height.
- Carry 20px page insets through proof grids and editorial sections.
- Use 8px media corners and reserve 12px rounding for the bottom of the continuous content sheet.
- Keep project names and subtitles at the same 24.4px scale, separating them through white versus 60% white.
- Use 80px vertical padding for light editorial bands and 40px before their onward links.
- Include a fitted giant-name footer with a small opposing utility row.
- Use the 88px white disc consistently for opening and film playback.

### Don't

- Do not introduce a persistent accent hue into navigation, buttons or editorial surfaces; vivid color belongs inside media.
- Do not replace regular-weight typography with bold display or semibold card titles.
- Do not center every paragraph; preserve the left-half introduction and right-half explanatory patterns.
- Do not add drop shadows, raised panels or borders around portfolio windows.
- Do not turn the monochrome partner field into a grid of bordered logo cards.
- Do not use 9999px pill styling for ordinary conversion links; they are plain text.
- Do not apply the floating glass material to general content panels.
- Do not shrink the closing name into a conventional small logo with many footer columns.

## Motion and responsive

### Motion

**Observed:**

- Play discs declare transform 350ms cubic-bezier(0.2,0,0,1), with hover scale(1.1) and active scale(0.93).
- Featured work declares an 800ms fade-up using cubic-bezier(0,0,0,1).
- Horizontal image marquees declare 80s, 60s and 40s linear infinite animation variants.
- Navigation declares background-color .25s, opacity .25s, border-color .25s and transform .35s cubic-bezier(0.645,0.045,0.355,1). Footer theme colors transition over 0.3s.

**Transfer:**

- Preserve slow continuous horizontal partner movement rather than turning the field into a slide carousel.
- Tie the play-disc scale response to the disc itself, leaving the surrounding giant typography stable.
- Let visual proof arrive through restrained upward reveals; keep text labels attached to their media.

**Unknown:**

- Exact opening WebGL choreography, scroll-trigger timing and complete drag-wall behavior are unspecified.

### Responsive

**Observed:**

- Viewport-relative font formulas govern body, display and mono caption sizes.
- Styles declare width breakpoints near 480px, 768px, 850px, 1024px, 1440px and 1980px.

**Transfer:**

- On narrow screens, retain the huge fitted name and object relationship, allowing a deliberate two-line name rather than reducing it to a small logo.
- Stack split editorial copy and proof windows when necessary, preserving media-to-caption attachment and the monochrome surface contrast.
- Keep irregular media variation on editorial pages, but reduce overlapping planes before sacrificing legibility.

**Unknown:**

- Exact mobile navigation, column-collapse rules and mobile artwork compositions are unspecified; narrow-screen arrangements are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
