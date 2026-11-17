# Beings — humanist blockwork and scale

## Overview

A boldly human editorial style that pairs massive, sculptural lettering with intimate portrait photography and candid film. Cream, peach and deep chocolate replace the usual black-and-white minimalism, with dense statements balanced against expansive media stages. Chunky geometric display lettering and sturdy grotesks make it suited to culture-led services, creative platforms and products with a strong point of view.

### Essentials

- Identity becomes architecture: a nearly edge-to-edge word sculpture, about 258px high at a 1440px viewport, incorporates a rectangular live-action image in the opening and returns as a monumental closing mark. Use an original product name and a purpose-made still when film is unavailable.
- Chunky display words contrast with compact declarations: Bonto at 66.2px/1 with -0.03em tracking, versus a black grotesk at 30px/1.175 and bold support at 22px/1.1. Editorial openings use 103.7px/0.98 display lettering with staggered, indented lines.
- The grid reaches the edges instead of floating in a card: 12 columns, 12px gutters and 12px side padding at 1440px, with square portrait media spanning one half or one third of the width.
- Color belongs to entire chapters, not decorative badges: cream #fff4ec is the light base, chocolate supports a substantial inverse editorial chapter, and peach #f6c9a1 carries its text. Saturated color is mostly confined to photography and film; the dark closing field uses #1b0800.
- Actions read like editorial links, not sales pills: 12px uppercase bold navigation and 66.2px display links on marketing sections. Catalog controls alone use compact 38px-high buttons with 3px corners and 6px 12px padding.
- Human media is unboxed and materially real: square corners, no shadows, high-contrast monochrome portraits alongside restrained natural-color images, a thin circular outline crossing the image stage, and full-width behind-the-scenes film with small text overlaid.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Espresso ink | `#1b0800` | `--color-ink` | text, background, action, border | Primary dark lettering, control fills and the closing field. |
| Editorial chocolate | `#3d1801` | `--color-chocolate` | text, background, border | Deep brown editorial chapter backing; also the text and hairline color of the peach editorial variant. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach lettering | `#f6c9a1` | `--color-peach` | text, action, accent | Inverse manifesto text and display links; selected catalog control fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#fff4ec` | `--color-canvas` | background, text | Default light canvas and inverse lettering over film and the closing field. |
| Studio white | `#ffffff` | `--color-white` | background, surface | Clean opening identity stage and the marketing navigation backing; retain warm cream for ordinary content. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and mission stories | Apricot paper | `#ffe2cc` | `--color-editorial-canvas` | background | Continuous warmer backing for long-form editorial storytelling. |

## Typography

- **Die Grotesk B** — Navigation, supporting headings, descriptions, lists and controls. Compact, sturdy grotesk with a high x-height; semibold and bold cuts do most of the work. OpenType features: "kern", "ss01", "ss02", "ss03", "ss04". If unavailable, use **Inter**. Use 600 for semibold and 700 for bold; retain compact line spacing. Font stack: "Die Grotesk B", "Inter", Arial, sans-serif.
- **Die Grotesk C** — Manifesto paragraphs and emphatic section statements. Very heavy, closely packed grotesk that makes prose feel like a headline. OpenType features: "kern", "ss01", "ss02", "ss03", "ss04". If unavailable, use **Inter**. Use 900 for the black cut. Font stack: "Die Grotesk C", "Inter", Arial, sans-serif.
- **Bonto** — Short chapter headings, large editorial headlines and display links. Dense geometric block lettering with circular counters, squared silhouettes and playful cutouts. If unavailable, use **Bowlby One SC**. Use 400 with tight tracking; preserve block mass rather than imitating individual glyphs. Font stack: "Bonto", "Bowlby One SC", Arial Black, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading-display | Bonto | 400 | 66.2px | 1 | -0.03em, features "kern", "ss01" 0, "ss02", "ss03" 0, "ss04" 0 | Chapter headings and large linked words. |
| manifesto | Die Grotesk C | 900 | 30px | 1.175 | normal | Full-width statement paragraphs with headline-like authority. |
| lead | Die Grotesk B | 700 | 22px | 1.1 | normal | Concise opening promise, closing promise and substantial supporting copy. |
| supporter | Die Grotesk B | 600 | 16px | 1.1 | normal | Plain-text proof lists over film. |
| caption | Die Grotesk B | 600 | 12px | 1.4 | normal | Short descriptions adjacent to large media and unobtrusive image captions. |
| navigation | Die Grotesk B | 700 | 12px | 1.4 | normal, uppercase | Compact navigation, utility actions and bottom-edge signatures. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and catalog openings | editorial-display | Bonto | 400 | 103.7px | 0.98 | -0.03em, features "kern", "ss01" 0, "ss02", "ss03" 0, "ss04" 0 | Two- or three-line page-opening statements with indented continuation lines. |
| catalog browsing | filter | Die Grotesk B | 700 | 18px | 1.1 | normal, uppercase | Centered text inside compact filter controls. |
| long-form editorial stories | editorial-body | Die Grotesk B | 600 | 15px | 1.4 | normal | Two compact prose columns alongside a large portrait. |

**Notes:**

- The display face is not an oversized version of the text grotesk: preserve its sculptural mass, circular counters and -0.03em tracking.
- Large prose is deliberately heavy. Keep manifesto paragraphs at the black weight rather than substituting regular body copy.
- Wordmark artwork is a separate identity treatment, not the Bonto heading style. Use an original extra-bold grotesk outline fitted to the available width.
- Use normal tracking for the grotesks; the hierarchy comes from weight, width and the sharp jump between 12px marginal text and large image or letter forms.

## Layout

**Density:** Airy media stages with compact prose and marginal controls; empty space separates editorial moments rather than padding repeated cards.

### Spacing

**Spacing system:**

- **gutter** 12px — Primary grid gap, page inset and local paragraph spacing; half-gutters are 6px.

| Value | Use |
| --- | --- |
| 6px | Half-gutter between controls and proof-list rows. |
| 12px | Page inset, grid gaps, navigation padding and paragraph spacing. |
| 24px | Two gutters between introductory prose and editorial media. |
| 36px | Three-gutter spacing for grouped editorial content. |
| 48px | Four-gutter bottom breathing room in the main editorial media stage. |
| 84px | Top allowance for the opening identity artwork. |
| 135px | Top and bottom padding of editorial opening statements. |
| 180px | Breathing room before editorial and catalog endings. |

### Containers and grids

- **edge grid**: max width 1440px · 12 columns · gap 12px · side padding 12px. Desktop marketing composition; all large media and small text align to this broad edge grid.
- **paired portrait stage**: max width 1440px · 2 columns · gap 12px · side padding 12px. Two 702px-wide vertical media fields, with a short lead over the right field and a circular line crossing the center.
- **three-part editorial stage**: max width 1440px · 3 columns · gap 12px · side padding 12px. A large display link at left, 464px-wide portrait gallery at center and a caption up to 420px wide at right.
- **editorial prose columns** (only for company and mission stories): max width 708px · 2 columns · gap 12px. Two approximately 297px-wide prose columns beside a half-width portrait.
- **catalog grid** (only for catalog browsing): max width 1440px · 4 columns · gap 0px · side padding 0px. Four 360px-wide cells; media is inset generously within each cell rather than stretched edge-to-edge.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media | 0px |
| catalog browsing | filter buttons | 3px |
| catalog browsing | search control | 50% |
| catalog browsing | density slider | 24px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default content background.

**CSS:** `background: #fff4ec`

**Observed:** Continuous flat backing without card elevation or texture.

**Transfer:** Let content and media share the same canvas.

#### Identity stage · level 0

**Use:** Clean backing for the enormous opening word sculpture.

**CSS:** `background: #ffffff`

**Observed:** The image insert and dark letters have crisp, square edges against a clean studio field.

**Transfer:** Keep the identity artwork legible and the image insert visually integrated.

#### Chocolate chapter · level 0

**Use:** Inverse editorial stage.

**CSS:** `background: #3d1801; color: #f6c9a1`

**Observed:** A sustained dark-brown field holds large statements and the three-part editorial stage, rather than a small inset card.

**Transfer:** Use a whole chapter of dark color to change the emotional register.

#### Closing field · level 0

**Use:** Monumental closing identity and repeated promise.

**CSS:** `background: #1b0800; color: #fff4ec; padding: 12px`

**Observed:** Flat near-black brown with no gradient, shadow or rounded container.

**Transfer:** Give the closing statement architectural weight.

#### Apricot editorial field · level 0

**Only for:** company and mission stories

**Use:** Warmer long-form editorial canvas.

**CSS:** `background: #ffe2cc; color: #3d1801`

**Observed:** Continuous backing across prose, collage, portrait letter and quote chorus.

**Transfer:** Use this variant to distinguish deeper editorial reading from the main marketing experience.

#### Ruled editorial band

**Only for:** company and mission stories

**Use:** Personal letter or human-author chapter.

**CSS:** `border-top: 1px solid #3d1801; border-bottom: 1px solid #3d1801`

**Observed:** Only horizontal rules frame the chapter; no enclosing box.

**Transfer:** Separate a sustained personal statement with hairlines, not a card.

## Components

### Navigation rail

**Use:** Persistent site orientation.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 12px; padding: 12px; background: #ffffff`

**Text style:** `navigation` — Die Grotesk B 700 · 12px/1.4 · uppercase

**Observed:** A 41px rail with identity at left, two widely spaced main destinations and a tightly grouped utility cluster flush right. The wrapper is fixed; editorial variants match the canvas instead of using white.

**Transfer:** Keep the ordinary navigation sparse and utility labels compact.

### Navigation link

**Use:** Primary destinations and small utility actions.

**CSS:** `color: #1b0800; text-transform: uppercase; text-decoration: none`

**Text style:** `navigation` — Die Grotesk B 700 · 12px/1.4 · uppercase

**Observed:** Current destination is underlined. Text links carry the marketing actions; there is no dominant filled conversion pill.

**States:** Declared: hover text-decoration underline 1px; focus-visible outline blue solid 2px, outline-offset 2px.

### Display chapter link

**Use:** A large editorial entry point.

**CSS:** `color: #f6c9a1; font-size: 66.2px; line-height: 1; letter-spacing: -0.03em`

**Text style:** `heading-display` — Bonto 400 · 66.2px/1 · tracking -0.03em

**Observed:** A short sculptural word sits in the left column beside a central vertical gallery, serving as both heading and navigation.

**States:** Declared: hover text-decoration underline 1px.

### Supporter name

**Use:** Plain-language proof over full-bleed film.

**CSS:** `color: #fff4ec; font-size: 16px; line-height: 1.1`

**Text style:** `supporter` — Die Grotesk B 600 · 16px/1.1

**Observed:** Names are stacked in two widely spaced columns near the upper left; they are text, not a logo strip or boxed badges.

**States:** Declared: hover text-decoration underline 1px.

### Closing identity panel

**Use:** Brand-scale closing statement.

**CSS:** `background: #1b0800; color: #fff4ec; display: flex; flex-direction: column; justify-content: flex-end; padding: 12px`

**Text style:** `lead` — Die Grotesk B 700 · 22px/1.1

**Observed:** Two parallel promise lines sit above enormous cream identity artwork. Three small uppercase signatures occupy the bottom edge: motto, short companion phrase and visitor-count copyright treatment. The image-like wordmark is about 250px tall and covers roughly four fifths of the desktop width.

**Transfer:** Repeat the central promise, with a meaningful second-language line only when appropriate; finish with an original monumental identity and compact factual metadata.

### Filter button

**Only for:** catalog browsing

**Use:** Category selection.

**CSS:** `background: #1b0800; color: #fff4ec; border-radius: 3px; padding: 6px 12px; height: 38px`

**Text style:** `filter` — Die Grotesk B 700 · 18px/1.1 · uppercase

**Observed:** A compact row of short uppercase labels. The selected option reverses to peach with dark text; controls sit 6px apart.

**States:** Declared: hover background-color #f6c9a1 and color #1b0800; focus-visible unspecified; active transform scale(0.9).

### Catalog control bar

**Only for:** catalog browsing

**Use:** Sticky filter, search and density controls above the image collection.

**CSS:** `display: flex; position: sticky; flex-wrap: wrap; justify-content: space-between; align-items: center; padding: 12px 0px; border-bottom: 1px solid #1b0800`

**Observed:** Category buttons and a 38px circular search action occupy the left; a compact view control and elongated dark density slider sit at right. The bar is 63px high at desktop.

**Transfer:** Keep browsing controls in one low horizontal rail rather than a large sidebar.

### Portrait catalog cell

**Only for:** catalog browsing

**Use:** Media-first catalog entry.

**CSS:** `position: relative; padding: 86.4px; overflow: hidden`

**Text style:** `caption` — Die Grotesk B 600 · 12px/1.4

**Observed:** A 360px-wide cell contains an approximately 187px by 282px monochrome portrait. Under it, a first name aligns left and a one-letter identifier aligns right; the image has no border or radius.

**Transfer:** Keep captions minimal and let each image float within ample cream space.

### Minimal signature strip

**Only for:** catalog browsing

**Use:** Understated ending after a long image collection.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 12px; padding: 12px; color: #3d1801`

**Text style:** `navigation` — Die Grotesk B 700 · 12px/1.4 · uppercase

**Observed:** Three widely distributed text groups share the bottom edge directly on cream. Unlike the marketing ending, there is no dark band or giant identity mark.

**Transfer:** Use this compact ending for utilitarian browse pages.

## Imagery and graphics

### Identity with a human insert

**Use:** Signature opening word sculpture, repeated as pure lettering at the close.

**Observed:** Huge dark extra-bold grotesk letters span nearly the entire width. A square-ish studio photograph or moving portrait replaces a letter-width slot near the middle; the person is shown dynamically against pale studio backing. The composition is flat and crisp, not a 3D logo.

**Transfer:** Use the new product's own name or a short defining word with an image of someone using it. Minimum acceptable version: original extra-bold SVG lettering and a carefully art-directed still in a rectangular interruption.

**Build:** Compose original extra-bold uppercase letter outlines in an SVG or flex row. At 1440px, fit the composition within 12px side insets and about 258px of height; reserve a roughly 248px-wide image slot within the word, aligning its top and bottom to the letter cap edges. Use #1b0800 letters on white, then cream letters without an insert for the closing version. Fit by width rather than distorting the glyphs.

### Editorial portrait galleries

**Use:** Large paired media stage and narrow central gallery.

**Observed:** Fashion-editorial portraits, gestural bodies, close facial details and lived-in rooms alternate between high-contrast black-and-white and muted natural color. Images use square corners and tall proportions near 2:3. Paired panels occupy almost the whole width; the central gallery occupies about one third, with small text on either side.

**Transfer:** Photograph the real makers, users or physical context of the product. For a nonhuman product, use tactile close-ups and real working environments with the same deliberate lighting and vertical framing.

### Circular outline overlay

**Use:** Signature line device connecting large portraits.

**Observed:** A fine peach circular outline crosses the seam between paired images; a smaller dark circle frames a personal portrait in the editorial variant. It sits above the media without a filled disc.

**Transfer:** Carry the unfilled circle into a photographic or product-detail stage, preserving its light visual touch.

**Build:** Place an absolutely positioned SVG circle above the media with fill none, a 1px stroke in #f6c9a1 and a centered origin on the panel seam. Start with a 566px viewBox and scale with the media stage, allowing parts of the circumference to extend outside the visible image. For the editorial portrait variant, use a 288px square circle and #3d1801 stroke.

### Behind-the-scenes film

**Use:** Immersive social proof chapter.

**Observed:** Full-width 1440px by 900px film shows a working portrait session: camera, real bodies, studio equipment and ambient room light. Warm cream names sit at upper left and a tiny support statement floats around the right-center. The film is candid and slightly dark, not glossy animation.

**Transfer:** Use documentary process footage showing people making or using the product. A strong still of that process is the fallback; maintain readable cream lettering against naturally darker areas.

### Monochrome catalog portraits

**Only for:** catalog browsing

**Use:** Repeated browseable entries.

**Observed:** Consistent small vertical monochrome portraits sit within much wider cream cells; expressions and environments remain varied and individual. Fine name-and-initial captions sit immediately below.

**Transfer:** Normalize framing and tonal treatment without making every person or item look identical.

### Press-fragment collage

**Only for:** company and mission stories

**Use:** Visceral context or problem proof.

**Observed:** Ragged rectangular article headlines and social-message fragments overlap across the apricot field. Mostly white and black paper strips, occasional original media color, slight rotation, varied widths near 300px and clipping at page edges create a messy editorial wall.

**Transfer:** Assemble genuine problem statements, relevant press or primary research fragments for the new product. Minimum version: a handful of real typographic excerpts with clear attribution rather than invented press coverage.

**Build:** Use independently positioned rectangular image or text fragments over #ffe2cc, varying widths around 300px and rotating approximately -4 to 4 degrees. Layer in two or three loose rows with modest overlap, uneven baselines and no shadows, radii or tape embellishments. Keep the fragments readable enough to convey the conflict without turning them into a uniform card grid.

### Icons

**Observed:** Very sparse iconography: a cream outline search symbol, approximately 19px by 20px with 2px butt-ended strokes, inside a 38px dark circular control. Other decoration is typographic or circular line art.

**Transfer:** Use a small functional outline set only where text alone cannot explain a control; do not add icons to editorial headings.

## Section recipes

How recurring sections are built.

### First screen: Identity-stage opening

**Observed:** A clean white field carries a nearly full-width dark word sculpture beginning around 84px below the top. Letter and embedded image cap heights are about 258px, making identity—not explanatory copy—the dominant first impression. The media insert interrupts the word rather than sitting beneath it. In the first 900px the identity and human insert are the visible focal points; the settled content composition continues into paired tall media with a 22px lead at the right, while the manifesto and large chapter link belong below. Actions are compact text navigation and utility labels, not a hero button stack. Layers are flat backing, letter artwork, rectangular media insert and marginal navigation.

**Transfer:** Create a custom-width original word sculpture and embed a portrait or tactile product still. Preserve the identity-first impression without depending on a loading sequence. Editorial and catalog page types instead open with the editorial-display recipe in staggered lines, 135px top padding and a bold explanatory paragraph.

**Avoid:** Do not substitute a centered SaaS headline with two rounded buttons and a tiny product mockup, or make a blank screen part of the experience.

**Text style:** `lead` — Die Grotesk B 700 · 22px/1.1

### Inverse manifesto and gallery

**Observed:** Chocolate chapter holds a full-width manifesto paragraph with a 12px inset. A short companion statement sits underneath; the three-part editorial stage places Display chapter link left, a 464px-wide portrait gallery centrally and caption text on the right. The small text remains subordinate to images and heavy prose.

**Transfer:** State a strong product belief, show a real result or use context, then attach a concise explanation to the right. Preserve the contrast between very heavy prose and tiny marginal copy.

**Text style:** `manifesto` — Die Grotesk C 900 · 30px/1.175

### Immersive proof stage

**Observed:** Behind-the-scenes film fills a desktop viewport. Supporter name components form two columns at upper left; a caption-sized sentence sits near the right-center, directly on the image.

**Transfer:** Use credible collaborators or customers as plain names over documentary imagery, not a separate logo carousel.

**Text style:** `supporter` — Die Grotesk B 600 · 16px/1.1

### Monumental closing

**Observed:** Closing identity panel changes to near-black brown. Two compact lead paragraphs form parallel columns above a huge cream wordmark; the lower edge holds three tiny uppercase signatures. Its revealed composition feels close to a full screen rather than a conventional link-heavy footer.

**Transfer:** End with an original word sculpture and a repeated product promise. Preserve a generous dark interval around the promise and let the identity occupy the lower field.

**Text style:** `lead` — Die Grotesk B 700 · 22px/1.1

### Editorial declaration and columns

**Only for:** company and mission stories

**Observed:** Apricot editorial field opens with 103.7px block lettering in three staggered lines; continuation lines are indented by roughly one grid column. After 135px of breathing room, three dense black-grotesk paragraphs span the width. A 696px by 1043px portrait follows beside two small prose columns.

**Transfer:** Use a short declaration and a human image to introduce the product's purpose, then keep deeper explanation compact and asymmetrical.

**Text style:** `editorial-display` — Bonto 400 · 103.7px/0.98 · tracking -0.03em

### Personal letter and quote chorus

**Only for:** company and mission stories

**Observed:** Ruled editorial band places a two-line 66.2px display heading at upper left, a centered 288px square portrait with a circular line overlay, and a full-width 22px personal letter near the bottom. The following chapter uses a staggered display heading above dense continuous testimonial prose separated by double slashes, with informal punctuation and occasional emoji.

**Transfer:** Use an accountable human voice for a founder, maker or practitioner statement. For a chorus of proof, assemble authentic short quotes into a dense editorial texture instead of identical testimonial cards.

**Text style:** `heading-display` — Bonto 400 · 66.2px/1 · tracking -0.03em

### Browse collection

**Only for:** catalog browsing

**Observed:** Cream opening uses three lines of editorial-display lettering and a 22px bold support paragraph. Catalog control bar follows at the fold. Four-column Portrait catalog cell entries continue for a long browse experience, ending with Minimal signature strip rather than the dark marketing footer.

**Transfer:** Apply this variant to collections where the user needs to compare real people or visual artifacts, keeping filtering secondary to imagery.

**Text style:** `editorial-display` — Bonto 400 · 103.7px/0.98 · tracking -0.03em

## Page flow

**Storyline:** Identity or declaration → lived-context demonstration → conviction and explanation → human proof → repeated promise and identity; browse experiences replace the middle with a sustained visual collection.

### Media-led marketing landing experience

1. **Identity hook** — Monumental word sculpture with a moving human insert.
2. **Context demonstration** — Paired tall portraits connected by a circular line and a compact promise.
3. **Conviction and offering** — Inverse heavy manifesto followed by a display link, central gallery and small description.
4. **Social proof** — Names and a support statement over behind-the-scenes film.
5. **Closing promise** — Parallel promise lines, dark field, giant cream identity and bottom signatures.

**Transfer:** Use the product's own human or physical context as the demonstration, and make brand conviction tangible through imagery rather than a list of feature cards.

### Long-form company or mission story

1. **Declaration** — Staggered block-type statement on apricot paper.
2. **Explanation** — Dense bold introductory prose then a half-width portrait beside small columns.
3. **Problem context** — Overlapping press and social fragments across the canvas.
4. **Accountability** — Personal letter with a centered portrait and ruled band.
5. **Social proof** — Continuous chorus of supporter quotes.
6. **Closing promise** — Shared dark identity ending.

**Transfer:** Replace mission-specific material with the new product's reason to exist, a credible human voice and genuine external response.

### Visual catalog and discovery experience

1. **Promise** — Large staggered display statement and compact bold explanation.
2. **Browsing controls** — Low sticky filter rail with search and density adjustment.
3. **Collection** — Long four-column monochrome portrait grid with minimal captions.
4. **Closing signature** — Cream bottom strip with motto, companion phrase and visitor copyright.

**Transfer:** Make the collection itself the proof and reduce the ending to a minimal signature, without importing the marketing footer into a utility browse page.

## Writing

Confident, human and values-led, with direct assertions rather than polished corporate hedging. The tone is warm but willing to challenge the reader; informal personal testimony can be blunt and emotionally specific.

**Do not copy:** Do not reuse the BEINGS name, logo artwork, portraits, personal names, collaborator lists, quotes, visitor totals, founding claims, cultural slogans or community-representation claims as assets or facts for another product. Source examples below illustrate voice only.

- **Addressing the reader:** Use you when challenging a habit or inviting discovery, and we for a collective point of view. Describe the product plainly and name the people affected by it.
- **Rhythm:** Short display phrases contrast with substantial compact paragraphs. Use sequences of parallel sentences for emphasis; navigation stays at one or two words. Testimonials retain natural speech rather than being normalized into slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Direct discovery verb plus the real subject or benefit. | Approximately 7–12 words | “Discover Aotearoa’s POC, Rainbow and Disabled talent.” |
| Support paragraph | A concrete claim developed through parallel clauses, not a generic adjective stack. | Approximately 25–40 words | “Here you’ll find experience that can’t be begged, borrowed, stolen, or schooled. Perspectives that can’t be practised. Insights that can’t be rehearsed. And instincts earnt through grit.” |
| Manifesto | Declare why the outcome matters before explaining the system. | A short assertion leading into a substantial paragraph | “What we put on stage and screen matters.” |
| Challenge | Address a shallow alternative head-on, then define the right audience. | Two sentences | “If you’re looking to tick a box, you’ve come to the wrong place. Our talent directory is for those bold enough to choose authenticity over imitation.” |
| Action | Plain verb or short destination, without benefit inflation. | 1–2 words | “Join”<br>“Talent” |

**Words and phrasing to use:** discover; real; show up; perspectives; instincts; bold enough; without imitation; plain descriptions of people and outcomes

**Avoid:** unlock your potential; revolutionary solution; seamless ecosystem; best-in-class; frictionless journey; unsupported superlatives

**Rules:**

- Say what the product does in ordinary language even when the surrounding design is expressive.
- Let strong beliefs earn their space through concrete consequences, not moral posturing.
- Use parallel clauses and short declarative sentences to create momentum.
- Use bilingual copy only with authentic relevance and competent translation; parallel lines should have equal visual respect.
- Preserve the natural texture of genuine quotes; do not invent a community response.

## Do's and Don'ts

### Do

- Align media, small labels and heavy prose to a 12-column desktop grid with 12px gaps.
- Use 66.2px display chapter words with -0.03em tracking and 1 line height.
- Keep manifesto text at 30px and black weight, with 1.175 line height.
- Make tall paired media about 702px wide each at a 1440px desktop viewport.
- Reserve 12px uppercase bold type for navigation and bottom-edge signatures.
- Keep catalog filters 38px high with 3px corners and 6px separation.
- Use a full dark-brown chapter with peach lettering instead of isolated accent cards.
- Carry both a monumental original identity treatment and a fine circular line across media into a new marketing page.

### Don't

- Do not turn editorial chapters into white elevated cards with shadows.
- Do not give portraits rounded corners or a framed app-window treatment.
- Do not replace warm espresso text with cool slate or neutral charcoal throughout.
- Do not set the manifesto in lightweight 16px body copy; its heavy 30px texture is structural.
- Do not spread 3px catalog-button styling into oversized marketing CTA pills.
- Do not enlarge the 12px marginal descriptions until they compete with the central media.
- Do not render the press collage as a tidy three-column testimonial grid.
- Do not add a dashboard-style icon to every feature or heading.

## Motion and responsive

### Motion

**Observed:**

- Catalog filter buttons declare a 0.1s transition and active scale(0.9).
- The catalog control rail declares a 0.3s transition.
- Other action and media rules include 0.3s ease-out; header rules include top 0.3s.
- Large media stages are scroll-pinned and the closing field is revealed with a translated panel; imagery changes within the galleries.

**Transfer:**

- Keep gallery motion confined to the media panels while small text remains anchored to the grid.
- Preserve a strong still composition for every pinned chapter and the original identity insert; motion should not be needed to understand the product.

**Unknown:**

- Exact scroll progress mappings, gallery durations and footer reveal choreography.
- No verified timing for the identity opening beyond the declared CSS transitions.

### Responsive

**Observed:**

- Width breakpoints are declared at 812px, 1380px, 1512px and 1800px.
- Desktop composition uses 12 columns and square-corner media.

**Transfer:**

- On narrow screens, retain the strong word sculpture by fitting it to width, then stack the paired media and editorial side captions in reading order.
- Keep the distinction between display block lettering and compact grotesk copy instead of shrinking the entire desktop composition uniformly.
- Allow the catalog control rail to wrap and reduce catalog columns before making portraits too small to recognize.

**Unknown:**

- Mobile type sizes, column counts, navigation behavior and scroll-pinning changes were not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
