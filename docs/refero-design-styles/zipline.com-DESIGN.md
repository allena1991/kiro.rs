# Zipline — skyward human momentum

## Overview

A cinematic, optimistic style that makes advanced technology feel part of everyday life. Warm cream and black alternate beneath tall, compressed sans-serif headlines, with violet reserved for interaction and fleeting graphic accents. Expansive outdoor photography, floating product objects and human-scale films carry most of the color; compact controls and sparse copy keep the experience open and direct. It suits ambitious consumer products and services with a tangible benefit and credible operational proof.

### Essentials

- Headlines behave like tall poster lettering rather than wide interface type: fkScreamer 700, uppercase, normal tracking, 150px/0.85 for monumental statements and 90px/0.85 for chapter headings.
- The opening is a view into a world, not a boxed product pitch: edge-to-edge atmospheric media, an 80px overlay header, cream headline on the left and a small action near the supporting copy, all visible in the first 900px.
- Controls are deliberately small beside the spectacle: 34px-high pills with 14px medium grotesk text, 1px edges and a small northeast arrow; filled cream actions contrast with outlined navigation actions.
- Color belongs chiefly to real scenes: cream #f7f4e8 and black #000000 own the structural bands; violet #643aed is concentrated in interaction, play controls and moving media reveals, not a permanent page-wide wash.
- The product and the promise share a stage: place a floating cutout or rendered object around an oversized sentence on cream, and use 20px-rounded portrait films to explain the experience. If no physical object exists, use a clean cutout of the meaningful interaction rather than a dashboard wall.
- A rounded lens-like graphic interrupts rectangular media: paired tapered image windows on black and a broad convex crest on a photographic band provide a recurring visual signature. Rebuild the device with a new abstract silhouette or lens, not a copied logo.
- The ending remains an image-led event: a roughly 1100px photographic closing band combines 150px uppercase copy, a tiny inline action and compact footer links over the same scene; a proof-led variant centers a giant figure above the product.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#643aed` | `--color-violet` | accent, action | Action hover and focus fills, play controls and animated reveal planes. Large violet planes move away to expose imagery rather than remaining empty cards. |
| Translucent lavender | `#b09aea` | `--color-action-tint` | action, surface | Visible equivalent of violet at 0.486 alpha over cream for the compact navigation conversion action; actual appearance responds to the media beneath it. |
| Lavender edge | `#beb4ea` | `--color-action-edge` | border | Fine edge of the tinted navigation conversion action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background | Light-canvas text and immersive dark chapters. A 20% black overlay subdues hero media without removing natural color. |
| Smoked neutral | `#7f7d77` | `--color-nav-shade` | surface | Visible equivalent of black at 0.486 alpha over cream; the compact floating navigation instead blends this alpha layer with whatever lies beneath. |
| Warm cream | `#f7f4e8` | `--color-canvas` | background, surface, text, border, action | Default light canvas; reverse text, outlines and filled actions over photography or black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light-background navigation | Warm gray | `#6e6d67` | `--color-muted` | text, border | Navigation text and outline color on light editorial backgrounds. |
| light-background navigation | Translucent stone | `#d3d0c5` | `--color-nav-light` | surface | Visible warm-gray navigation backing: rgba(171,169,160,0.48) over cream. |

## Typography

- **fkGroteskNeue** — Body copy, compact navigation, captions and actions. Plainspoken contemporary grotesk with open counters and a restrained, utilitarian texture. If unavailable, use **Inter**. Use 400 and 500 for body and controls, 700 for footer links; preserve compact measures. Font stack: "fkGroteskNeue", "Inter", Arial, sans-serif.
- **fkScreamer** — Poster headlines, chapter titles, statistics and story titles. Extremely condensed, heavy sans-serif with tall vertical strokes and tightly packed uppercase silhouettes. If unavailable, use **Anton**. Use its heavy default cut; tune horizontal width to preserve the very narrow headline silhouette. Font stack: "fkScreamer", "Anton", Impact, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | fkScreamer | 700 | 150px | 0.85 | normal, uppercase | Monumental promise, closing slogan and large standalone figures. |
| heading | fkScreamer | 700 | 90px | 0.85 | normal, uppercase | Chapter-scale statements; keep line breaks short and emphatic. |
| card-heading | fkScreamer | 700 | 40px | 0.85 | normal, uppercase | Compact editorial titles beneath media. |
| body | fkGroteskNeue | 400 | 16px | 1.4 | normal | Default supporting prose and explanatory text. |
| action | fkGroteskNeue | 500 | 14px | 1 | normal | Compact pill labels. |
| navigation | fkGroteskNeue | 500 | 14px | 1.5 | normal | Header links and dropdown labels. |
| footer-link | fkGroteskNeue | 700 | 14px | 1.2 | -0.01em | Small but firm footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and impact indexes | story-heading | fkScreamer | 700 | 60px | 0.85 | normal, uppercase | Longer titles in the large two-column story index. |
| editorial and impact indexes | story-date | fkGroteskNeue | 400 | 14px | 1.4 | normal | Small date immediately between story image and headline. |

**Notes:**

- The display face supplies compression; do not imitate it by tightening an ordinary wide sans. All display roles keep normal tracking and the distinctive 0.85 line-height.
- Grotesk text remains sentence case and visually modest; display lettering takes the emotional work. Hero support is visually larger than ordinary card prose; give it an uncluttered two-line measure.
- Use the display recipe for the opening's very short statement. Long promises should break into a few compact lines, not shrink into an ordinary heading.
- The chapter-scale heading recipe also supports an emphatic centered descriptor under a monumental proof number. Article titles step down to 60px or 40px according to column width.

## Layout

**Density:** Airy cinematic stages with compact controls and tightly packed display lines; large pauses separate stories rather than individual sentences.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Small icon-to-label gaps. | fixed |
| 8px | Navigation action separation and footer list gaps. | fixed |
| 14px | Small filled-button horizontal padding and story metadata separation. | fixed |
| 16px | Inline closing action gap and supporting flex groups. | fixed |
| 18px | Headline offset beneath story media and outlined-button horizontal padding. | fixed |
| 24px | Container side padding, grid gutters and brand-to-footer-navigation spacing. | fixed |
| 40px | Gap between footer link columns. | fixed |
| 60px | Closing section vertical padding and vertical story-index separation. | fixed |
| 80px | Dark-chapter vertical padding and desktop header height. | fixed |
| 120px | Major light-section vertical spacing. | fixed |
| 18.7px | Small proportional inset at the top of the photographic closing content. | 1.3vw |
| 198.9px | Opening content's lower inset within its tall media stage. | 13.8122vw |

### Containers and grids

- **content-container**: max width 1320px · side padding 24px. Centered outer container. At 1440px it begins at 60px, putting ordinary content at 84px after its inset.
- **cinematic-stage**: max width 1440px. Full-width immersive bands; a 900px stage can hold a pinned chapter while its content advances.
- **feature-pair**: 2 columns · gap 24px. Two large image-and-caption columns; permit unequal image heights while keeping text attached to its own image.
- **proof-triptych**: 3 columns · gap 24px. Three near-square photographic metrics on cream.
- **editorial-strip**: 4 columns · gap 24px. Compact image-first news row with short condensed headings.
- **portrait-demonstration**: 3 columns · gap 24px. A narrow portrait film centered between a fixed chapter label and a changing instruction. The center media is 384px wide at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| media | 20px |
| filled-actions | 20px |
| navigation-actions | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default light chapters and the backing for isolated product objects.

**CSS:** `background: #f7f4e8; color: #000000`

**Observed:** A warm untextured field; media and typography provide structure without enclosing every item in a panel.

**Transfer:** Leave space around large letters and objects instead of adding UI chrome.

#### Black chapter · level 0

**Use:** High-contrast benefit demonstrations and editorial stories.

**CSS:** `background: #000000; color: #f7f4e8`

**Observed:** A full band rather than a dark card floating on cream.

**Transfer:** Use a dark chapter to change narrative tempo while retaining the same typography.

#### Media window · level 1

**Use:** Photographs and explanatory videos within grids.

**CSS:** `border-radius: 20px; overflow: hidden`

**Observed:** Media has a soft rectangular edge but no border, shadow or enclosing card background.

**Transfer:** Round only the image window; let titles and prose sit directly on the page.

#### Smoked navigation · level 2

**Use:** Compact floating header backing over varied media.

**CSS:** `background: rgba(0, 0, 0, 0.486); border-radius: 9999px`

**Observed:** The opening navigation is visually transparent and expanded; the compact state uses a smoked, highly rounded backing. A light-background version uses rgba(171,169,160,0.48).

**Transfer:** Keep the expanded header light over the scene and use a compact neutral backing where legibility requires it.

#### Media shade · level 1

**Use:** Text legibility on atmospheric openings.

**CSS:** `background: rgba(0, 0, 0, 0.2)`

**Observed:** A transparent black layer above the photograph or film but below cream copy.

**Transfer:** Retain the scene's natural blue, green and skin tones.

#### Violet reveal · level 1

**Use:** Moving cover during media entry.

**CSS:** `background: #643aed; border-radius: 20px`

**Observed:** A solid rounded plane translates away from the media window; it is not its final content.

**Transfer:** Use as a brief reveal accent, always resolving to meaningful imagery.

## Components

### Overlay navigation

**Use:** Persistent wayfinding above immersive media.

**CSS:** `position: fixed; height: 80px; display: flex; align-items: center; z-index: 1000`

**Observed:** Brand left, a centered group of four links and two small actions right, aligned to the content container. The first screen uses an expanded transparent presentation; a compact smoked version appears during navigation.

**Transfer:** Use a small proprietary mark rather than oversized header branding.

### Navigation link

**Use:** Top-level navigation and dropdown triggers.

**CSS:** `display: flex; align-items: center; gap: 6px; color: #f7f4e8`

**Text style:** `navigation` — fkGroteskNeue 500 · 14px/1.5

**Observed:** Dropdown triggers end in a tiny downward chevron; groups use 24px separation. The light-background version changes text to warm gray.

**States:** Declared: hover text-decoration none, color currentcolor and opacity 0.7; focus-visible color currentcolor and opacity 0.7. Opacity transition 0.25s.

### Cream action

**Use:** Primary action inside a scene or a dark chapter.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 34px; padding: 0px 14px; border: 1px solid #f7f4e8; border-radius: 20px; background: #f7f4e8; color: #000000`

**Text style:** `action` — fkGroteskNeue 500 · 14px/1

**Observed:** Short label followed by a small northeast arrow. The action is subordinate in size to the headline; the closing action sits beside the first headline line. Index expansion uses a downward arrow instead.

**States:** Declared: hover background-color #643aed, color #f7f4e8 and border-color #643aed; transition 0.35s.

### Outline action

**Use:** Secondary partnership or contact action in navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 34px; padding: 0px 18px; gap: 6px; border: 1px solid #f7f4e8; border-radius: 9999px; background: transparent; color: #f7f4e8`

**Text style:** `action` — fkGroteskNeue 500 · 14px/1

**Observed:** Sits immediately before the conversion action. The light-background variant uses warm-gray text and edge.

**States:** Declared: hover text-decoration none, background-color #643aed, border-color #643aed and color #f7f4e8; focus-visible uses the same fill, edge and text colors. Background, border and color transition 0.25s.

### Tinted navigation action

**Use:** Conversion action in the compact navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 34px; padding: 0px 14px 0px 18px; gap: 6px; background: rgba(100, 58, 237, 0.486); color: #f7f4e8; border: 1px solid #beb4ea; border-radius: 9999px`

**Text style:** `action` — fkGroteskNeue 500 · 14px/1

**Observed:** Text followed by a 14px northeast arrow. The expanded opening presentation reads as a restrained outline; the compact presentation brings in the violet tint.

### Editorial media card

**Use:** Image-first news and evidence stories.

**CSS:** `display: flex; flex-direction: column`

**Text style:** `card-heading` — fkScreamer 700 · 40px/0.85 · uppercase

**Observed:** A linked 20px-rounded photograph above an uppercase condensed headline with an 18px top offset. No enclosing painted card. Compact strips use four columns; editorial indexes use two columns, dates and the story-heading recipe.

**Transfer:** Use actual project photography with informative, tightly wrapped titles.

### Portrait step film

**Use:** A focused explanation of a simple product workflow.

**CSS:** `position: relative; width: 384px; border-radius: 20px; overflow: hidden`

**Observed:** A 634px-tall vertical film at desktop, flanked by a fixed chapter title and a changing action phrase. A thin segmented vertical progress marker sits near the outer lower edge.

**Transfer:** Show the user's point of view and one action at a time; use a sequence of portrait stills if film is unavailable.

### Footer link

**Use:** Compact institutional and legal navigation at the page ending.

**CSS:** `display: inline-flex; align-items: center; color: #f7f4e8`

**Text style:** `footer-link` — fkGroteskNeue 700 · 14px/1.2 · tracking -0.01em

**Observed:** Two left-aligned lists beneath a small brand mark, 40px apart, with 8px internal gaps. Solid social icons align separately at the lower right.

**States:** Declared: hover text-decoration none and opacity 0.7; transition 0.35s.

### Monumental figure

**Use:** One striking proof value or closing slogan.

**CSS:** `color: #f7f4e8; text-transform: uppercase`

**Text style:** `display` — fkScreamer 700 · 150px/0.85 · uppercase

**Observed:** Numbers and abbreviated units use the same tall display silhouette as the slogan. On cream, the figure becomes black; over photographic proof cards, the figure sits near the lower left with a short uppercase descriptor.

**Transfer:** Keep units inside the typographic object and place the explanation outside it.

## Imagery and graphics

### Atmospheric human scenes

**Use:** The first screen, benefit chapters and photographic closing bands.

**Observed:** Outdoor scenes use low viewpoints, wide skies, saturated green foliage and warm natural skin tones. People are caught looking up, receiving something or enjoying ordinary life. Media fills most or all of the stage; copy occupies a small clear area rather than a separate white panel.

**Transfer:** Photograph the product's result in a real environment with a large calm sky or wall for type. A strong single still with a human gesture is the minimum alternative to cinematic film.

### Floating object and word sculpture

**Use:** A signature product-promise moment on cream.

**Observed:** A softly lit pale product cutout floats around a black uppercase multiline sentence, with a tiny rounded lifestyle inset embedded in the sentence. The object overlaps the lettering and moves vertically; the scene has little surrounding chrome.

**Transfer:** Pair an isolated object or meaningful interaction cutout with one compact benefit statement; use a high-quality still if a 3D scene is impractical.

**Build:** Set two or three short uppercase lines on a cream stage. Position a transparent-background object across the right third, around 300px wide at desktop, with no hard bounding box. Insert one small 20px-rounded image into an intentional gap in the type. Keep the object in front of some letters but never obscure the entire promise.

### Rounded lens motif

**Use:** A recurring signature device for image transitions, benefit windows and the entrance to the closing band.

**Observed:** On black, two broad tapering lens windows reveal one continuous human scene, with a narrow black waist between them. Elsewhere a broad convex central crest rises into the cream canvas at the top of a full-width photograph. The testimonial uses a cream outline version behind and in front of the person.

**Transfer:** Use a new simple silhouette with the same broad center, narrow ends and soft turning points. Keep meaningful faces visible rather than treating the mask as random decoration.

**Build:** Create an SVG clipPath in a 1000 by 600 viewBox: two wide rounded diamonds or lenses, each roughly 1000 by 240, separated by about 40. Use cubic curves at the upper and lower center peaks and rounded tips, not sharp polygon corners. Clip a single photograph through both. For the full-width band use one shallow convex arc rising about 180px at its center across 1440px. For the portrait outline, stroke two analogous paths in cream at about 10px with round joins, then layer the person cutout above the rear stroke.

### Photographic proof tiles

**Use:** A compact quantified-proof interlude.

**Observed:** Three near-square rounded photographs sit in a cream band: a close human encounter, a product-in-use detail and a clean object against sky. Large cream numbers and condensed descriptors sit low in each photograph.

**Transfer:** Select a different image for each metric and retain a readable lower corner. The subject should explain the metric without an added pictogram.

### Documentary evidence

**Only for:** trust, operational proof and editorial pages

**Use:** Capability grids and reported stories.

**Observed:** Unvarnished photographs and films show laboratory work, field tests, communities and real infrastructure. Two-column layouts permit both shallow landscape and taller frames; rounded edges unify the varied footage.

**Transfer:** Show the actual process and people behind the new product. Keep documentary color and imperfect real environments rather than replacing every image with a polished render.

### Sky proof closing

**Only for:** trust and reliability pages

**Use:** An evidence-led alternative to the human photographic slogan ending.

**Observed:** A softly blurred blue-sky background supports a centered giant cream figure, a floating product object beneath it, a 90px uppercase descriptor and a small cream action. Footer navigation remains within the same scene.

**Transfer:** Center a verified cumulative result and a relevant isolated object; keep the background soft so the stacked proof remains dominant.

**Build:** Use a full-bleed sky photograph with shallow depth of field. Center the display figure in the upper half, overlap a transparent product render between the figure and descriptor, then place the pill below. Add a subtle black alpha gradient only at the footer edge if required for contrast.

### Icons

**Observed:** Small solid SVGs rather than a large line-icon library: 10px dropdown chevrons, 14px action arrows and 18px social glyphs. They usually inherit cream or black from their control.

**Transfer:** Use a consistent tiny chevron and northeast arrow; reserve solid recognizable brand glyphs for social links. Do not decorate capability headings with unrelated icons.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric opening

**Observed:** A 1099px-tall full-width media stage extends beyond the first 900px. Behind everything is a softly textured blue-green sky film; a 20% black shade supports cream text. The 80px Overlay navigation sits at the top. A very short 150px uppercase statement anchors the left about one third down the visible screen, taking roughly a quarter of the width. Two lines of supporting prose sit near the lower left with a Cream action beneath. A small distant human figure enters along the lower edge, leaving the sky dominant. The first 900px contains navigation, full headline, support and action, plus the bottom-edge human gesture; the curved transition and the next chapter remain below the fold.

**Transfer:** Open a new landing page with one expansive real-world scene and a short imperative or benefit. Without film, use a carefully composed still with generous environmental space and a human-scale cue. A lead-generation page can instead open on black with image, promise and support left and an underlined form right. Trust-oriented openings anchor a two-line promise at the lower left over documentary photography, with support and a small action alongside.

**Avoid:** Do not center a long paragraph over a generic stock backdrop or replace the scene with an ordinary software card and giant conversion button.

**Text style:** `display` — fkScreamer 700 · 150px/0.85 · uppercase

### Object and promise stage

**Observed:** Cream canvas holds Floating object and word sculpture. The statement becomes a compact composition rather than a heading above a card; the isolated object and small human inset create depth around the letters.

**Transfer:** Give one main benefit a memorable typographic and object composition. Resolve the full sentence clearly even if revealed in stages.

**Text style:** `heading` — fkScreamer 700 · 90px/0.85 · uppercase

### Image and benefit chapters

**Observed:** A large 20px-rounded portrait photograph occupies about half the screen on the left; a short uppercase benefit aligns toward the upper right with ample cream below. Subsequent scenes replace the image and heading within the same visual frame.

**Transfer:** Pair each audience benefit with one real use scene; preserve the asymmetrical text placement rather than filling the open half with extra cards.

**Text style:** `heading` — fkScreamer 700 · 90px/0.85 · uppercase

### Human testimonial stage

**Observed:** A full-width environmental portrait places a person in the left half against blurred dark greenery, with a short cream quotation in the right half and small name and location below. The Rounded lens motif loops around the portrait as an outline.

**Transfer:** Use one believable firsthand experience, a real portrait and restrained attribution. Preserve the separation between expressive photograph and quiet quote.

### Portrait workflow stage

**Observed:** Portrait step film sits between a chapter label on the left and a short changing instruction on the right. The stage is cream, the type black and the three columns vertically centered across a 900px view.

**Transfer:** Translate a product journey into a few observable actions, letting the portrait media carry the detail.

**Text style:** `heading` — fkScreamer 700 · 90px/0.85 · uppercase

### Dark masked benefit chapter

**Observed:** Black chapter uses a small contextual label above a condensed heading at upper left and a short explanatory line low on the same side. Rounded lens motif occupies the right two thirds. A segmented progress line marks the current benefit near the lower outer edge. Vertical padding is 80px.

**Transfer:** Use one distinct outcome per scene and change both image and text together. Keep the masked image large enough to show people clearly.

**Text style:** `heading` — fkScreamer 700 · 90px/0.85 · uppercase

### Proof interlude

**Observed:** Photographic proof tiles form a three-column row after 120px of top breathing room. A separate commercial variant puts two black 150px figures beneath a wide rounded lifestyle image. The editorial variant uses a cream two-by-two grid with giant figures, uppercase descriptors, low learn-more links and thin gray lower rules.

**Transfer:** Choose the proof format that matches the page's purpose: emotional photographic metrics for a broad pitch, plain figures for business outcomes, ruled evidence cells for reports.

**Text style:** `display` — fkScreamer 700 · 150px/0.85 · uppercase

### Capability evidence grid

**Observed:** A short heading introduces a two-column cream layout. Rounded landscape media appears first, then a condensed benefit title and brief grotesk explanation. Media aspect ratios vary without turning each item into a boxed card.

**Transfer:** Use concrete capabilities and their user consequences. For lead generation, follow the opening form with this grid; for reliability, use tests and process footage.

**Text style:** `card-heading` — fkScreamer 700 · 40px/0.85 · uppercase

### Photographic closing event

**Observed:** A roughly 1100px full-width human photograph enters through the broad crest of Rounded lens motif. A two-line 150px cream slogan sits near the center; a 34px Cream action nests beside the first line. People overlap the lower lettering against vivid blue sky. Footer link lists sit at lower left beneath the brand, with social glyphs at lower right. The trust variant uses Sky proof closing instead.

**Transfer:** End a marketing page with one memorable benefit and a small action integrated into the image, not a separate oversized CTA box. Use the new product's real users or the proof-led variant where evidence is the appropriate final note.

**Text style:** `display` — fkScreamer 700 · 150px/0.85 · uppercase

### Editorial story index

**Only for:** editorial and impact indexes

**Observed:** A black band begins with a film-and-headline showcase, then two independent story columns. Rounded documentary images are followed by a 14px date and 60px uppercase title. Vertical story spacing is 60px. A centered Cream action expands the list, followed by a plain black footer with 60px vertical padding rather than another photographic slogan.

**Transfer:** Use this variant when the reader is browsing reports or stories, preserving the visibly editorial ending.

**Text style:** `story-heading` — fkScreamer 700 · 60px/0.85 · uppercase

## Page flow

**Storyline:** Atmospheric promise → tangible experience → human validation → practical explanation → differentiated benefits → quantified or reported proof → image-led invitation or editorial continuation.

### Broad consumer or product landing page

1. **Promise** — Full-bleed environmental film with a short imperative and modest action.
2. **Product demonstration** — A floating product object interacts with an oversized sentence, then human-use scenes make the benefit concrete.
3. **Social proof** — Environmental portrait with a short first-person quotation.
4. **Practical explanation** — Portrait step films between chapter and action labels.
5. **Differentiation** — A cinematic product scene leads into black masked benefit chapters.
6. **Quantified and editorial proof** — Three photographic metrics and a four-column news strip.
7. **Closing invitation** — Photographic slogan and integrated compact footer.

**Transfer:** Use the cinematic scene and graphic lens vocabulary to connect the product to daily life; choose the amount of explanation the new product actually needs.

### Business lead-generation page

1. **Conversion** — Black two-column opening: lifestyle media, condensed promise and support left; an underlined multi-field form right.
2. **Capability chapters** — Cream section with a centered promise followed by a two-by-two media-and-benefit grid.
3. **Commercial proof** — Wide lifestyle photograph over two giant black figures with brief explanations.
4. **Closing invitation** — The shared photographic slogan and compact footer.

**Transfer:** Make the offer and form visible immediately, then prove business value with concrete benefits and verified figures.

### Evidence report and story collection

1. **Mission and outcome** — Documentary full-bleed hero with bottom-aligned promise and adjacent support.
2. **Quantified proof** — Cream two-by-two highlights with giant figures and understated research links.
3. **Narrative proof** — Black film showcase with a small play accent and large condensed title.
4. **Editorial continuation** — Black two-column dated story index and centered expansion action.
5. **Utility ending** — Plain black footer, without a second photographic slogan.

**Transfer:** Make evidence browsable and keep the ending utilitarian so the story collection remains the focus.

### Trust and reliability explainer

1. **Reassurance** — Real engineering photography with an emphatic lower-left promise, support and small film action.
2. **Objection handling** — Cream heading followed by two columns of tests and operational process footage with short explanations.
3. **Cumulative proof** — Sky-backed central figure, floating product and descriptor with a fact-sheet action.
4. **Utility ending** — Small footer links and social glyphs integrated into the proof scene.

**Transfer:** Show observable mechanisms before giving the cumulative result; let a verified measure carry the closing reassurance.

## Writing

Optimistic, direct and grounded in useful outcomes. The emotional tone is expansive, but the explanation stays concrete and makes advanced engineering feel ordinary and helpful.

**Do not copy:** Do not reuse Zipline names, logos, product artwork, customer identities, quotations, locations, delivery records, health outcomes, regulatory claims or promotional offers. Replace every claim with facts and permissions belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for everyday benefits; use we for responsibility and operational reassurance. Refer to the product plainly rather than through ornate category language.
- **Rhythm:** Short imperative or benefit headlines, often split into two fragments. Support is one or two straightforward sentences; practical instructions start with verbs. Longer editorial titles remain informative rather than slogan-like.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An imperative or direct benefit that the image makes tangible. | 2–7 words | “LOOK UP”<br>“DELIVER FASTER. WIN MORE ORDERS.” |
| Benefit heading | Two compressed fragments, or a benefit plus a timing consequence. | 2–6 words | “YOUR FAVORITES, FRESHER”<br>“LESS WAITING. MORE LIVING.” |
| Supporting line | State what happens in everyday terms; connect the mechanism to convenience or confidence. | 1–3 short sentences | “The fastest way to get what you need. Delivered by drone.”<br>“Hot stays hot. Cold stays cold. Everything arrives as it should.” |
| Trust heading | Firm, compact reassurance that points to an actual method. | 4–7 words | “NO SHORTCUTS. JUST SMART DESIGN.” |
| Primary action | Verb-led invitation, short and literal. | 2–5 words | “Try it today”<br>“See more”<br>“View our safety fact sheet” |
| Closing line | A brief emotional consequence, not a new feature list. | 2–5 words | “Moments matter.” |

**Words and phrasing to use:** faster; fresh; your; get; minutes; built; tested; real; more living; right when you need it

**Avoid:** revolutionary ecosystem; synergize; next-generation platform; unparalleled; seamlessly leverage; magical disruption

**Rules:**

- Put the human benefit in the headline and the mechanism in support.
- Pair very short claims with specific observable proof elsewhere in the story.
- Use punctuation and line breaks for cadence rather than exclamation marks.
- Keep action labels literal even when the surrounding headline is emotional.
- Use abbreviated units beside giant numerals, then explain the measure in a separate short line.

## Do's and Don'ts

### Do

- Keep monumental type at 150px with 0.85 line-height on desktop and let the condensed face control width.
- Use the 1320px container and 24px inset for ordinary content alignment.
- Keep small conversion pills at 34px high beside large photographs and headlines.
- Carry the rounded lens device into a meaningful media moment, not merely a decorative divider.
- Use 20px-rounded media without a raised surrounding card.
- Separate light proof bands with 120px-scale breathing room while keeping metadata close to its image.
- Keep footer navigation compact: 14px type, 8px list gaps and 40px between columns.
- Use actual human scenes and a clean isolated product object to balance warmth with engineering credibility.

### Don't

- Do not replace the compressed display face with a wide geometric headline font.
- Do not turn the palette into a violet website; black, cream and photographic color provide the large fields.
- Do not leave violet reveal planes as permanent feature tiles.
- Do not inflate compact 34px actions into oversized rectangular sales buttons.
- Do not add drop shadows or outlined containers around every photograph.
- Do not apply 20px rounding to whole page bands; round image windows and use the broad crest for image-led transitions.
- Do not make all story images the same shallow aspect ratio; the two-column editorial treatment supports varied heights.
- Do not add a giant sitemap footer; the ending uses small link columns and a separate line of social glyphs.

## Motion and responsive

### Motion

**Observed:**

- Long cinematic chapters pin a 900px scene while successive media and text states advance with scrolling.
- Rounded violet covers translate away to reveal media. Text and media can enter with opacity and translation.
- Cream actions declare 0.35s transitions. Outlined navigation actions declare background-color, border-color and color transitions of 0.25s; navigation links declare opacity 0.25s.
- Media figures declare 0.85s transitions. Social glyph hover declares scale(1.2), with a 0.18s ease-out transform transition.

**Transfer:**

- Keep moving media coupled to the benefit or instruction currently shown; the chapter should resolve to a complete readable scene.
- Use the violet reveal as a momentary accent, with photography as its destination.
- For a reduced-motion implementation, present complete still scenes and all instructions without requiring a long pinned journey.

**Unknown:**

- Exact scroll timelines and the easing of each cinematic scene are not established.
- Video playback and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width thresholds include 576px, 768px, 992px, 1200px and 1400px.
- Desktop uses an 80px header; a 60px small-header token is declared.
- The proof grid has full-width columns below its large-screen three-column state; the compact editorial strip includes two-column classes below the large-screen four-column state.
- The elaborate desktop benefit composition has a separate narrower-layout treatment.

**Transfer:**

- On narrow screens, preserve the tall display silhouette with shorter line measures, not horizontal overflow.
- Stack paired media and prose while keeping the portrait demonstration tall and its instruction adjacent in reading order.
- Retain the lens silhouette with a focal crop that keeps the human subject readable, and allow the compact footer lists to wrap.

**Unknown:**

- Mobile renderings, exact mobile type sizes and the alternate benefit layout are not established.
- Fluid headline formulas are not established; preserve the desktop hierarchy while tuning smaller layouts deliberately.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
