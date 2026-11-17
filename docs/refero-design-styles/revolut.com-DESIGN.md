# Revolut — everyday life, sculpted

## Overview

An expansive, aspirational product style that makes practical services feel like premium physical objects. Clean geometric grotesk typography sits between sunlit lifestyle photography and dramatic black stages with metallic, glass and softly glowing objects. White, charcoal and silver carry most of the interface, while sky blue and restrained cool light give the imagery its atmosphere. It suits broad consumer launches and focused product stories, with sparse cinematic chapters above a deliberately dense utility ending.

### Essentials

- A short promise takes over a human-scale scene: the default opening fills 900px with sky-backed photography, white display lettering around 88px, a compact left-aligned support line and a 42px dark action.
- Useful things become luxury sculptures: every new landing page needs an oversized product-object stage with brushed metal, glass edges or sculpted light, occupying more space than its 51.8px heading. When there is no physical product, turn one meaningful interface panel into a dimensional object.
- Typography is rounded and close-set, not loud or heavy: Aeonik Pro at weight 500, section headings 51.8px/1 with -0.6px tracking, and card headings 24px/28px with -0.01em tracking.
- Actions are small capsules against monumental media: 16px/22px medium labels, 10px 24px padding and 9999px radius; dark on light or photographic skies, white on black.
- Color belongs to the scene rather than the furniture: black and white chapters alternate with a charcoal footer; blue appears as a full atmospheric opening or a small technical accent, never as a repeated rainbow of feature-card fills.
- The ending changes scale rather than disappearing: a centered conversion line has 32px to its pill action, then the #191c1f utility band introduces black 20px-radius plan tiles, six compact link columns and a thin social-row divider.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue lower | `#3991d8` | `--color-sky-bottom` | background | Lower blue of the photographic opening's backing gradient. |
| Sky blue upper | `#4c8acc` | `--color-sky-top` | background | Upper blue of the photographic opening's backing gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#1f1f1f` | `--color-ink` | text, action | Primary lettering and dark capsule actions on white or bright media. |
| Stage black | `#000000` | `--color-black` | background, surface, text | Cinematic product stages and plan tiles; also lettering on white reverse actions. |
| Utility charcoal | `#191c1f` | `--color-footer` | background | Full-width footer band, visually distinct from pure black stages. |
| Utility hairline | `#303336` | `--color-edge` | border | Visible white at 10% over utility charcoal; the social-row separator. |
| Secondary grey | `#717173` | `--color-muted` | text, border | Supporting card text, eyebrows and accordion rules. |
| Footer silver | `#c9c9cd` | `--color-footer-text` | text, link | Dense footer links and legal paragraphs. |
| Soft grey | `#f7f7f7` | `--color-card` | surface | Instruction and editorial cards on light sections. |
| White | `#ffffff` | `--color-white` | background, surface, text, action, border | Default light canvas, reverse lettering, white actions and outlined controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark utility and business content | Light action blue | `#6fa0ff` | `--color-link-blue` | link, accent | Dark-theme story links and focus-ring hue. |
| technical reassurance and help content | Technical blue | `#234fa6` | `--color-technical-blue` | text, accent, link | Emphasised words in explanatory proof panels and light-theme link interaction. |
| interactive feature explanations | Smoked white | `#1a1a1a` | `--color-glass` | surface | Visible white at 10% over a black stage; use the alpha recipe when laid over imagery. |
| business-oriented product pages | Business graphite | `#1c1c1e` | `--color-dark-card` | surface | Raised stat and plan tiles on black. |

## Typography

- **Aeonik Pro** — Marketing headings, support lines, navigation and buttons. Rounded geometric grotesk with open counters, broad circular forms and a restrained medium weight. If unavailable, use **DM Sans**. Use 400 and 500; preserve tight heading tracking and check line breaks. Font stack: "Aeonik Pro", "DM Sans", Arial, sans-serif.
- **Inter** — Explanatory paragraphs, small descriptions and utility navigation. Neutral, compact sans with high small-size legibility. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display-art | Aeonik Pro | 500 | 88px | 1 | -0.02em | size 6.11111vw | White, single-line aspirational opening headline over photography; keep sentence case. |
| heading | Aeonik Pro | 500 | 51.8px | 1 | -0.0116em | size clamp(3rem, 2.41667rem + 0.911111vw, 3.75rem) | Main section promises and closing conversion line. |
| footer-heading | Aeonik Pro | 500 | 40px | 1.2 | -0.01em | fixed | Plan-selection introduction in the utility band. |
| card-heading | Aeonik Pro | 500 | 24px | 28px | -0.01em | fixed | Tile titles, large eyebrows and accordion questions. |
| support | Aeonik Pro | 400 | 18px | 24px | normal | fixed | Brief supporting lines under marketing headings; also plan prices. |
| action | Aeonik Pro | 500 | 16px | 22px | normal | fixed | Buttons, navigation and image-award captions. |
| body | Inter | 400 | 16px | 1.5 | -0.01em | fixed | Longer explanatory copy and instructions. |
| caption | Inter | 400 | 14px | 22px | -0.005em | fixed | Plan descriptions and supporting stat annotations. |
| utility | Inter | 400 | 12px | 1.5 | 0.015em | fixed | Footer links and the dense utility ending. |
| utility-heading | Inter | 600 | 12px | 1.5 | 0.01em | fixed | Small footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| rate or single-metric product storytelling | monumental-number | Aeonik Pro | 500 | 240px | 1 | -0.02em | size 16.66667vw | One oversized number with smaller qualifiers aligned to its baseline. |
| focused product pages | product-hero | Aeonik Pro | 500 | 58.1px | 1 | -0.0207em | size clamp(3rem, 1.44444rem + 2.42963vw, 5rem) | Left-hand headline beside a sculptural object. |
| quantified proof and technical explanation | stat | Aeonik Pro | 500 | 48px | 1 | -0.01em | fixed | Large figures in compact proof tiles and headings inside wide proof panels. |
| technical reassurance panels | stat-emphasis | Aeonik Pro | 700 | 48px | 1 | -0.01em | fixed | A blue key phrase embedded in a proof-panel heading. |
| customer or expert proof | quote | Aeonik Pro | 500 | 32px | 38px | -0.01em | fixed | Testimonial statements, below a small circular portrait. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display and number artwork use the same geometric spirit as live headings. Their surrounding copy remains small; do not scale every element up with the hero.
- Medium weight carries ordinary headings. Bold is reserved for the technical blue phrase, not applied globally.
- Large headings have close tracking and nearly solid leading; paragraphs relax to 24px leading. Headings remain sentence case, including short section labels.

## Layout

**Density:** Airy cinematic chapters with compact internal cards and a dense utility ending.

### Spacing

**Spacing system:**

- **rhythm** 8px — Primary declared spacing rhythm; 10px button padding and 20px section-list margins are explicit exceptions.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Tight title-to-price and title-to-description gaps. | fixed |
| 16px | Instruction-grid gaps, paragraph spacing and portrait-to-caption breathing room. | fixed |
| 24px | Default tile padding, heading-support separation and media-grid gaps. | fixed |
| 32px | Closing headline-to-action gap and editorial-grid gaps. | fixed |
| 40px | Footer vertical padding and separation between utility subregions. | fixed |
| 48px | Proof-panel column gap and heading-to-feature-grid separation. | fixed |
| 56px | Introductory proof line to award imagery. | fixed |
| 64px | Proof-panel padding and stage interior breathing room. | fixed |
| 80px | Major chapter margins and accordion section padding. | fixed |
| 220px | Desktop utility band's side inset at 1440px. | calc((100vw - 1000px) / 2) |

### Containers and grids

- **content**: max width 1000px · side padding 0px. Centered desktop text, proof and tile region; at 1440px the edges sit 220px in from the viewport.
- **stage**: max width 1440px · side padding 0px. Edge-to-edge 810px or 900px tall media chapters; images may continue below the fold.
- **support-copy**: max width 720px. Limit centered supporting copy so the heading remains the dominant horizontal line.
- **tile-grid**: 3 columns · gap 24px. Default proof and plan rows. A 12-column underlying grid lets a lower pair each span half the width.
- **footer-columns**: 6 columns · gap 16px. Compact link categories across the 1000px utility region.
- **instruction-grid** (only for focused product education): 3 columns · gap 16px. Equal-width light instruction or benefit cards.
- **editorial-grid** (only for help and education pages): 3 columns · gap 32px. Image-led resource cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | tiles | 20px |
| help and education pages | editorial-cards | 24px |

## Surfaces and depth

### Surfaces

#### Light canvas · level 0

**Use:** Default resting canvas and text-led closing regions.

**CSS:** `background: #ffffff; color: #1f1f1f`

**Observed:** Untextured and borderless; depth comes from media rather than floating container shadows.

**Transfer:** Keep the space surrounding artwork visually empty.

#### Black stage · level 0

**Use:** Immersive object demonstrations.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The media fills the entire chapter, with no outer rounded wrapper.

**Transfer:** Let a dark render dissolve naturally into the page edge.

#### Sky backing · level 0

**Use:** Bright photographic opening.

**CSS:** `background: linear-gradient(#4c8acc, #3991d8)`

**Observed:** Atmospheric sky texture and the subject cover this simple blue backing.

**Transfer:** Use a believable open-air scene, not a smooth blue dashboard background.

#### Utility band · level 0

**Use:** Plan selection and the full footer ending.

**CSS:** `background: #191c1f; padding: 40px 0px`

**Observed:** Runs continuously behind the plan tiles, link columns, social row and legal tail.

**Transfer:** Treat the ending as one coordinated dark area.

#### Soft tile · level 1

**Use:** Instruction, benefit and resource content on white.

**CSS:** `background: #f7f7f7; border-radius: 20px; padding: 24px`

**Observed:** Flat, borderless, with a small icon above a title and concise copy.

**Transfer:** Group practical details without competing with the cinematic imagery.

#### Black plan tile · level 1

**Use:** Plans inside the charcoal utility band.

**CSS:** `background: #000000; border-radius: 20px; padding: 24px 24px 0px`

**Observed:** Light headings and prices sit above muted descriptions; a small arrow sits near the bottom right.

**Transfer:** Make the entire tile a destination.

#### Smoked feature panel · level 1

**Only for:** interactive feature explanations

**Use:** Feature explanations flanking a central device.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 20px; padding: 24px`

**Observed:** Active content is fully visible while other feature panels are dimmed; panels can overlay a large hardware render.

**Transfer:** Preserve one clearly active explanation and a strong central object.

#### White proof panel · level 1

**Only for:** technical reassurance panels

**Use:** A bright interruption in a black chapter.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 64px; gap: 48px; display: flex`

**Observed:** 1000px-wide panel splits into a large statement and an explanatory paragraph; a blue phrase provides emphasis.

**Transfer:** Use for one decisive piece of reasoning, not a grid of unrelated benefits.

## Components

### Primary button

**Use:** Default conversion action on white or bright photography.

**CSS:** `background: #1f1f1f; color: #ffffff; border-radius: 9999px; padding: 10px 24px; height: 42px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Aeonik Pro 500 · 16px/22px

**Observed:** A short label only, without a trailing arrow; width follows its content.

**States:** Declared: hover background-color #1f1f1f and opacity 0.85; focus-visible inset blue ring with a white inner ring, 2px blue outline and 2px outline-offset; active opacity 0.75.

**Transfer:** Keep the action visually smaller than the promise.

### Reverse button

**Use:** Primary conversion on black stages.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; padding: 10px 24px; height: 42px`

**Text style:** `action` — Aeonik Pro 500 · 16px/22px

**Observed:** Same capsule construction as Primary button, with reversed contrast. Paired business closing actions use 46px height.

**States:** Declared: hover background-color #ffffff and opacity 0.85; focus-visible 2px blue outline with 2px outline-offset plus inset blue and black rings; active opacity 0.75.

### Navigation

**Use:** Low-profile header over the opening scene.

**CSS:** `position: sticky; height: 72px; z-index: 3`

**Text style:** `action` — Aeonik Pro 500 · 16px/22px

**Observed:** A centered 1000px row places the small wordmark first, broad audience links next, and login plus a white capsule at the right. Navigation links have 8px 20px padding. White lettering overlays bright or dark media; light product pages reverse to dark lettering.

**Transfer:** Keep audience navigation distinct from in-page chapters; the opening artwork must still own the screen.

### Plan tile

**Use:** Clickable plan-summary destination in the footer.

**CSS:** `background: #000000; border-radius: 20px; padding: 24px 24px 0px`

**Text style:** `card-heading` — Aeonik Pro 500 · 24px/28px · tracking -0.01em

**Observed:** Title, price and short description stack with 8px gaps; description uses Caption and a small right arrow closes the tile. Three equal tiles sit above two wider tiles.

**Transfer:** Use tiers appropriate to the new offering, keeping the summaries short rather than adding full comparison tables.

### Footer link

**Use:** Dense categorized utility navigation.

**CSS:** `color: #c9c9cd; padding: 8px 0px`

**Text style:** `utility` — Inter 400 · 12px/1.5 · tracking 0.015em

**Observed:** Small left-aligned links sit below semibold Utility-heading labels; categories stack within six columns.

**States:** Declared: hover color #ffffff; active color rgba(255, 255, 255, 0.8).

### Outline button

**Only for:** dark stages with a secondary destination

**Use:** Secondary action beside a reverse action or alternate media choice.

**CSS:** `background: transparent; color: #ffffff; border: 2px solid #ffffff; border-radius: 9999px; padding: 10px 24px; height: 46px`

**Text style:** `action` — Aeonik Pro 500 · 16px/22px

**Observed:** An empty capsule instead of a grey filled secondary button.

**States:** Declared: hover transparent background and opacity 0.85; focus-visible 2px blue outline and 2px outline-offset with inset blue and black rings; active opacity 0.75.

### Instruction tile

**Only for:** focused product education

**Use:** A small set of actionable steps or practical benefits.

**CSS:** `background: #f7f7f7; border-radius: 20px; padding: 24px; display: flex; flex-direction: column; gap: 8px`

**Text style:** `card-heading` — Aeonik Pro 500 · 24px/28px · tracking -0.01em

**Observed:** A 24px icon leads the title; longer instruction text uses Body in secondary grey. Three equal columns use a 16px gutter.

**Transfer:** Keep one task per tile and write a complete instruction.

### Stat tile

**Only for:** business-oriented quantified proof

**Use:** A compact quantified claim.

**CSS:** `background: #1c1c1e; border-radius: 20px; padding: 24px; text-align: center`

**Text style:** `stat` — Aeonik Pro 500 · 48px/1 · tracking -0.01em

**Observed:** Large number, 24px contextual title and a 14px grey qualifier; three tiles occupy one row with 24px gaps.

**Transfer:** Use comparable evidence-backed figures and include the period or condition in the qualifier.

### Accordion row

**Only for:** objection handling and practical help

**Use:** Questions beneath a centered heading and grey eyebrow.

**CSS:** `border-bottom: 1px solid #717173; margin-bottom: 24px; min-height: 81px`

**Text style:** `card-heading` — Aeonik Pro 500 · 24px/28px · tracking -0.01em

**Observed:** Full-width 1000px question row with a compact circular plus at the far right; the same pattern appears in light and black themes.

**Transfer:** Use a real button for each question and disclose the answer in place.

### Feature panel

**Only for:** interactive feature explanations

**Use:** Explain a selected capability beside a central device.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 20px; padding: 24px; display: flex; flex-direction: column; gap: 8px`

**Text style:** `card-heading` — Aeonik Pro 500 · 24px/28px · tracking -0.01em

**Observed:** Icon, short title and compact description; four panels frame a tall phone in a three-column composition. The active panel is highlighted by opacity rather than a bright border.

**Transfer:** Dim only inactive explanatory cards, not the whole page.

### Editorial card

**Only for:** help and education pages

**Use:** Related resources near the end of an educational story.

**CSS:** `background: #f7f7f7; border-radius: 24px; overflow: hidden; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — Aeonik Pro 500 · 24px/28px · tracking -0.01em

**Observed:** 312px-wide card begins with a 240px-high image, then category label, title and small date. Three cards have 32px gaps.

**Transfer:** Use related stories as a calm bridge into the dark utility ending.

## Imagery and graphics

### Sky portrait with floating utility

**Use:** Signature default opening, with related portraits in later product chapters.

**Observed:** A low-angle, sunlit portrait fills the screen against saturated blue sky. The person occupies the center-right and extends beyond the bottom edge; an oversized white headline crosses above the face. A thin rounded account frame overlays the torso, with a compact balance and white capsule, while trust badges sit low in the frame.

**Transfer:** Photograph a user in a believable moment with open space to the left. Add one useful UI result over the person, not a full dashboard. Without bespoke photography, use one strong editorial portrait on a sky-blue backing with a simple outlined result card.

**Build:** Layer a full-bleed sky photo over the Sky backing; place the portrait toward the right, add a rounded transparent panel roughly 440px wide using a 2px rgba(255,255,255,0.6) border, then one white numeric result and a small capsule. Keep the headline above these layers.

### Sculptural product objects

**Use:** Required signature device within the product story.

**Observed:** Cards, coins, shields, safes and phones become oversized studio objects. Brushed silver, ribbed graphite, reflective glass edges and soft specular highlights are staged on black or pale reflective ground. Perspective is dramatic but materials remain realistic; the object often fills the lower two-thirds of a chapter.

**Transfer:** Choose a shape that expresses the new product's function. Use a carefully lit 3D render or, at minimum, a high-resolution product cutout with a glass plinth and restrained metallic edge treatment.

**Build:** For a minimum graphic, stack two rounded rectangles in perspective, with a black-to-silver linear gradient, a 1px translucent white rim and a darker duplicate offset below for thickness. Back with a broad, low-opacity cool radial glow and keep only one dominant object. Use SVG geometry rather than adding many decorative symbols.

### Soft cool light

**Use:** Atmospheric backing for dark device chapters.

**Observed:** A diffuse blue-grey or green-grey light pool rises from the bottom of black, behind a centered device; edges disappear gradually into darkness. The effect is luminous fog, not a neon ring.

**Transfer:** Carry the soft glow into product-object stages even when the original object has no illumination.

**Build:** On black, place a wide elliptical radial gradient centered near the lower middle: rgba(150,190,198,0.5) at the center, rgba(100,148,154,0.2) midway and transparent at the edge. Blur a separate elliptical layer by 64px and let it extend below the section. Match the soft glow; exact stops are not essential.

### Lifestyle proof cards

**Use:** Split chapters and goal galleries.

**Observed:** Portrait-format photos show people at a café, at home or travelling, with warm natural light and subdued surroundings. Rounded imagery stands beside left-aligned text; a dark notification strip or small chat bubbles show a single outcome. Galleries use three tall photographs, with the middle card slightly taller.

**Transfer:** Show the product acting in ordinary life rather than people smiling at the camera. Overlay only the one result explained by the adjacent copy.

### Monumental metric field

**Only for:** rate or single-metric product storytelling

**Use:** A large numerical benefit between practical chapters.

**Observed:** A huge dark number dominates the lower half of a pale cool field. Small lead-in and unit text align to its baseline, with a centered promise and tiny qualifier well above.

**Transfer:** Make a single meaningful metric the object of the section; keep qualifications nearby.

**Build:** Use a white canvas with a bottom-up rgba(111,160,255,0.24) wash fading through rgba(111,160,255,0.08) to transparent. Center a flex row aligned to baseline; apply Monumental-number only to the numeral and Heading to its short qualifiers.

### Ambient campaign title

**Only for:** AI or technology reveal campaigns

**Use:** Minimal reveal before the product explanation.

**Observed:** A small widely spaced white title floats near the middle of an almost black screen, with a blue-grey light bloom below. The opening is about anticipation rather than immediate feature copy.

**Transfer:** Use only for a deliberate campaign reveal; follow with a clear promise and visible action.

**Build:** Reuse Soft cool light with the bloom centered below the title; render a short custom typographic title in thin white lettering with expanded tracking. Keep the rest of the stage black.

### Icons

**Observed:** Small monochrome solid or mask-style icons rather than colorful illustrations: 24px in feature tiles and accordions, 16px social marks within 32px targets. Plus and arrow symbols are compact and high-contrast.

**Transfer:** Use a consistent solid icon family with simple geometry. Place icons above tile titles and keep arrows at destination edges rather than decorating every label.

## Section recipes

How recurring sections are built.

### First screen: Immersive human opening

**Observed:** A 900px full-bleed scene starts behind a 72px navigation row. From back to front: Sky backing, lightly textured sky, large sunlit center-right portrait, transparent account frame, then white copy and navigation. The display-art headline spans roughly two-thirds of the content width near the upper left; the support line occupies a much narrower measure beneath it, followed by Primary button. The person and UI frame continue to the bottom edge. The first 900px includes the headline, support, action, face, torso, result UI and trust badges; the proof strip is below the fold.

**Transfer:** For an ordinary new landing page, retain a human scene plus one floating useful result. Without portrait media, create a photographic object-in-use composition on the same bright blue stage. Focused product pages instead use Product-hero on the left beside a large sculpture, dark for premium or technical stories and white for straightforward utility. Reveal campaigns use Ambient campaign title before their explanatory promise.

**Avoid:** Do not substitute a centered SaaS dashboard inside a white rounded hero card, or reduce the person to a small thumbnail beside the headline.

**Text style:** `display-art` — Aeonik Pro 500 · 88px/1 · tracking -0.02em

### Promise above object

**Observed:** An edge-to-edge Black stage places a centered Heading, a short Support line and Reverse button above a large metallic object or phone. Objects take most of the lower viewport; paired capsule choices sit near the bottom of some scenes.

**Transfer:** Give each chapter one capability, one outcome and one object metaphor.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

### Proof strip

**Observed:** On white, a small muted introductory line precedes a row of four award marks with 56px breathing room; captions sit 16px below imagery. A second row can contain three wider marks. Black-theme proof uses restrained customer logos and compact ratings.

**Transfer:** Use actual endorsements or partner marks, with visual weight kept below the product story.

### Split lifestyle chapter

**Observed:** Within the 1000px content region, one portrait-oriented media block and one vertically centered text block share a white or black chapter. The text uses a short Heading, concise support and a capsule. Media sides alternate; a dark notification strip may sit near the bottom of the photograph.

**Transfer:** Explain a practical outcome beside its human context; let the scene do the emotional work.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

### Closing conversion and utility ending

**Observed:** A centered Heading and Primary button form a short light closing block with 32px separation and 80px outer margins. Necessary qualifications follow before Utility band. Inside the band, a 40px plan heading introduces Plan tiles arranged three above two; then six link columns, the wordmark/social divider, locale and policy links, compact legal paragraphs and a final wrapped utility-link tail. Business variants put their plan choice and FAQ on black before a shorter utility footer; focused product variants may transition directly from their last product chapter into plans.

**Transfer:** Keep the close decisive, then provide a useful smaller-scale ending. Adapt plan count to the offering; retain the tonal shift, compact category navigation and separated legal area.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

### Heading and practical grid

**Only for:** focused product education

**Observed:** Centered Heading and Support are separated by 24px. After 80px breathing room, three Instruction tiles use equal columns and 16px gutters. Icons and text are left-aligned even though the section introduction is centered.

**Transfer:** Use for setup, benefits or conditions that need fast comparison.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

### Phone and active explanations

**Only for:** interactive feature explanations

**Observed:** A centered Heading sits over a three-column composition: a tall phone in the middle, two Feature panels stacked on each side. The selected explanation has full opacity; inactive panels recede. The phone extends down to the chapter edge.

**Transfer:** Map each explanation to one state of the device, keeping the center visually dominant.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

### Bright reasoning panel

**Only for:** technical reassurance panels

**Observed:** White proof panel sits centrally within a 900px Black stage. The left column pairs a small blue icon with a 48px statement and bold blue key phrase; the right column carries an 18px explanation.

**Transfer:** Interrupt immersive storytelling with one clear reason to believe.

**Text style:** `stat` — Aeonik Pro 500 · 48px/1 · tracking -0.01em

### Quantified proof and voice

**Only for:** business-oriented product pages

**Observed:** A centered Heading introduces a three-column Stat tile row, followed by compact award marks. A separate testimonial places a 76px circular portrait above a 32px quote, then attribution and a story link.

**Transfer:** Mix measurable outcomes with a credible human explanation, using only substantiated claims.

**Text style:** `quote` — Aeonik Pro 500 · 32px/38px · tracking -0.01em

### Questions and resources

**Only for:** help and education pages

**Observed:** An 80px-padded section stacks a grey 24px eyebrow, Heading and Accordion rows. Light-theme follow-up can offer two Soft tiles and a three-column Editorial card grid before the footer.

**Transfer:** Resolve specific concerns, then offer deeper reading rather than another promotional collage.

**Text style:** `heading` — Aeonik Pro 500 · 51.8px/1 · tracking -0.0116em

## Page flow

**Storyline:** Aspirational promise → visible product experience → proof and capability chapters → practical reassurance → conversion or plan choice → dense utility ending.

### Broad consumer landing page

1. **Promise** — Immersive human opening with an account result over the portrait.
2. **Social proof** — White award and rating rows.
3. **Capability chapters** — Alternating lifestyle, metallic-object and phone stages with one promise each.
4. **Closing call** — Centered conversion line and dark capsule on white.
5. **Utility ending** — Qualifications, charcoal plan tiles, categorized navigation, social row, locale, legal and wrapped utility links.

**Transfer:** Show the breadth of an offering through distinct single-purpose scenes, not a dense feature inventory.

### Business product landing page

1. **Promise** — Dark sculptural hero with left-hand copy and white action.
2. **Product overview** — A horizontal carousel of object-led capability cards with a larger central item and visible adjacent cards.
3. **Social proof** — Customer logo strip.
4. **Capability chapters** — Alternating split photo and object chapters with direct, practical copy.
5. **Quantified proof** — Three stat tiles, ratings and a portrait-led testimonial.
6. **Plan choice and objections** — Centered paired actions, four dark plan summaries and accordion questions.
7. **Utility ending** — Qualifications and a shorter charcoal footer with six columns, social row, locale and legal paragraphs.

**Transfer:** Keep the art premium while making copy more operational and the proof more quantitative.

### Trust and technical reassurance page

1. **Promise** — Exploded metallic-object hero on black followed by an expert quote.
2. **Capability demonstration** — Full-screen scenes alternate with device-centered active feature panels and bright reasoning panels.
3. **Human reassurance** — Light split chapters show help and verification in everyday situations.
4. **Objection handling** — Light accordion, practical resource cards and editorial links.
5. **Utility ending** — Charcoal plans, six-column links, social and locale rows, legal and utility tail.

**Transfer:** Alternate mechanism, explanation and human support; do not make the entire story feel like an alarm.

### Technology reveal campaign

1. **Reveal** — Sparse white title over a dark cool glow.
2. **Product demonstration** — Full-screen contextual scene with an overlaid result and bottom capsule choices.
3. **Activation** — Centered promise and action above a large phone.
4. **Reassurance** — Split photo chapter with a short protection explanation.
5. **Closing call** — Centered white conversion statement and action on black.
6. **Utility ending** — Disclosures, then the shared charcoal plans and complete utility footer.

**Transfer:** Use atmosphere to create anticipation, then quickly explain what the technology actually does.

### Focused benefit-led product page

1. **Promise** — White hero with left-hand copy, dark action and a large metallic object to the right.
2. **Practical setup** — Conditions followed by a centered heading and three light instruction cards.
3. **Quantified benefit** — Monumental number against a pale cool field.
4. **Capability proof** — Three benefit tiles, split lifestyle examples and a tall photo gallery.
5. **Activation** — Final split photograph with a notification strip, action and capsule choices.
6. **Utility ending** — Direct transition into charcoal plan tiles and the full navigation, social, locale, legal and utility tail.

**Transfer:** Make the benefit obvious, show how to begin, then connect it to real situations before plan choice.

## Writing

Confident and conversational, mixing short aspirational promises with plain explanations of useful actions. Technical detail is reassuring rather than intimidating; small wordplay makes serious products feel approachable.

**Do not copy:** Do not reuse Revolut names, logos, product artwork, partner marks, customer counts, rates, award claims, regulatory claims or testimonials. Source phrases illustrate voice, not reusable claims.

- **Addressing the reader:** Speak directly to you and your; use we or our when explaining the service's responsibility. Product benefits are framed around what the reader can do.
- **Rhythm:** Usually 3–8-word headlines, one or two brief support sentences and 2–5-word actions. Use occasional em dashes and conversational repetition; keep conditions in separate, precise sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar need reframed in a short, memorable phrase. | 3–6 words | “Banking & Beyond”<br>“Savings, on demand”<br>“This is business banking” |
| Chapter headline | Outcome-led sentence fragment with light wordplay or rhythm. | 3–9 words | “Elevate your spend”<br>“Your money’s safe space”<br>“Interest paid day after day after day” |
| Supporting line | Concrete verbs turn the promise into a useful sequence. | 15–35 words | “Spend smartly, send quickly, sort your salary automatically, and watch your savings grow — all with a [Brand] bank account.”<br>“Take your finances further with the account designed for efficiency, and built for business.” |
| Primary action | An uncomplicated imperative naming the next step. | 2–5 words | “Download the app”<br>“Get started”<br>“Open a bank account” |
| Reassurance | State the protection or practical response directly, then qualify it carefully. | Short headline plus factual explanation | “Safe, even when you’re sleeping”<br>“No withdrawal fees. No minimums. Instant access anytime.” |

**Words and phrasing to use:** your; get started; on demand; in seconds; every day; keep; take control; simple; built for

**Avoid:** revolutionary ecosystem; synergise; unparalleled excellence; hustle harder; guaranteed returns; fear-based urgency

**Rules:**

- Lead with the benefit before explaining the mechanism.
- Use concrete action verbs and one useful outcome per chapter.
- Keep numbers and their qualifying conditions close together.
- Allow a playful heading, but make the supporting line unambiguous.
- Keep button labels about the next action, not the marketing proposition.

## Do's and Don'ts

### Do

- Use 51.8px medium section headings with 1 line-height and -0.6px tracking.
- Give object chapters 810px or 900px of stage height at desktop.
- Keep content grids centered within 1000px while media runs edge to edge.
- Use 20px tile radii and 24px padding rather than pronounced card shadows.
- Keep capsule actions at 42px with 10px 24px padding on ordinary sections.
- Place one floating result over lifestyle media to connect aspiration to use.
- Preserve the #191c1f ending and compact 12px/18px utility navigation.
- Use 48px numbers in compact proof tiles and reserve the monumental numeral for a single-metric chapter.

### Don't

- Do not make every chapter a pale rounded bento grid; black full-width object stages carry the brand's weight.
- Do not use 700-weight headlines throughout; ordinary marketing headings are 500.
- Do not turn the interface blue just because the opening sky is blue; actions remain monochrome.
- Do not apply drop shadows to all 20px-radius tiles; their separation is primarily tonal.
- Do not replace the six-column utility ending with only a logo and a copyright line.
- Do not enlarge ordinary buttons to match the scale of the hero art; their 42px height is intentionally restrained.
- Do not set descriptions in the display face everywhere; longer explanation uses 16px/24px Inter.
- Do not use bright outlines to indicate active feature cards; use the smoked surface and controlled opacity.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use 300ms cubic-bezier(0.15,0.5,0.5,1) for background, color and opacity, with 200ms cubic-bezier(0.4,0.3,0.8,0.6) for box-shadow.
- Feature panels declare opacity 300ms cubic-bezier(0.15,0.5,0.5,1). Footer navigation links declare color 0.15s.
- Media chapters include video, carousel pagination and capsule selectors; the art and UI can change while the chapter stays composed.

**Transfer:**

- Keep selected states in the same visual stage: vary the object or overlaid result rather than changing the whole layout.
- Use the declared opacity transition for interactive explanatory panels.

**Unknown:**

- Video playback timings, scroll-pinning behavior and complete chapter transition choreography are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 720px, 839px, 840px, 1200px, 1600px and 1920px; some themes also include 1199px.
- Live section and focused-product headline recipes use the stated clamp formulas.

**Transfer:**

- As adaptation guidance, preserve the human subject or product object's focal point while shortening headline lines. Stack split chapters and reduce tile columns before sacrificing the 24px internal padding.
- Keep the selected result visible when simplifying a device-centered chapter; move inactive explanations below rather than shrinking the device to an icon.

**Unknown:**

- Exact mobile navigation, column counts, side insets and media art direction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
