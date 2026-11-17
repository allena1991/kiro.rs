# Becklyn — italic sparks after dark

## Overview

An expansive dark editorial style with a personable, design-led confidence. White grotesk typography trades phrases with expressive italic serif lettering, while vivid product compositions punctuate a charcoal canvas. It suits ambitious digital products, creative technology and portfolio-led marketing, with sparse openings, dense ruled indexes and an exuberant violet-to-blue closing atmosphere.

### Essentials

- Two voices share one headline: a medium grotesk at 92px/1 with -4px tracking pairs with an italic serif at 92px/1 with -1.2px tracking; smaller chapter pairs use 68px/1.
- The opening is a typographic pause, not a dashboard pitch: a 900px charcoal stage, 40px side margins and a left-aligned two-line statement around the vertical middle, with a small masthead above and a floating navigation dock below.
- Actions feel like editorial annotations: primary calls are unboxed 36px/1.15 text with a tiny underline-start mark; selected navigation uses a white 46px-high capsule inside a 58px-high translucent black dock.
- Color arrives as an event: most of the long page stays #1a1a1a with white type; vivid color belongs to isolated project stages, a tiny 20px gradient badge and the full-width blue–plum–rose closing field, not to every section.
- Proof is staged as artwork: combine 1360×765 wide frames with paired 670×670 frames, 10px corners and 20px gutters. Center or overlap real interface fragments on deliberately colored backings; when finished artwork is unavailable, use a carefully composed real product screen on a flat brand backing.
- Indexes turn breadth into a calm ledger: 66px rows, 1px #606060 rules, 22px/1.15 labels, right-aligned explanations and two-digit numbers at the far edge.
- The page signs off with an oversized invitation: a 92px grotesk line and an equally sized italic line sit beside one plain text action over the saturated closing field, followed by a single low horizontal row of small utility links.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#004eff` | `--color-blue` | accent, background | Blue pole of the closing atmosphere and the small navigation badge gradient; menu hover also uses it. |
| Deep plum | `#710966` | `--color-plum` | accent, background | Dominant warm-violet region in the closing atmosphere and gradient controls. |
| Smoked rose | `#8e2e45` | `--color-rose` | accent, background | Warm lower-left end of the closing gradient and final gradient-control stop. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White ink | `#ffffff` | `--color-text` | text, action, background, border | All primary typography, selected navigation capsules, menu disc and outlined view controls. |
| Black substrate | `#000000` | `--color-black` | background, surface | Underlying page substrate. The floating dock uses this hue at 50% opacity over whatever lies behind it. |
| Charcoal canvas | `#1a1a1a` | `--color-canvas` | background, text, surface | Dominant page canvas, dark tag fill and text on white controls. |
| Graphite card | `#3b3b3b` | `--color-card` | surface | Editorial cards and capability tiles; a backing beneath project media rather than a required visible gray mat. |
| Muted gray and rules | `#606060` | `--color-muted` | text, border | Fine index separators and secondary portrait-role captions. |

## Typography

- **UniversalSans** — Display outcomes, headings, paragraphs, captions and navigation. Medium-weight contemporary grotesk with open, round forms; compact negative tracking keeps large statements conversational rather than corporate. If unavailable, use **Inter**. Use 500 and preserve the size-specific tracking; tune line breaks to match the broad phrases. Font stack: "UniversalSans", "Inter", Helvetica, Arial, sans-serif.
- **Cambon** — Italic phrases inside paired headlines and one italic word in the masthead. Expressive high-contrast serif italic with fluid entry strokes, long descenders and a literary cadence. If unavailable, use **Libre Caslon Display**. Use an italic face where available; otherwise use Libre Caslon Text Italic for the italic construction. Font stack: "Cambon", "Libre Caslon Display", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | UniversalSans | 500 | 92px | 1 | -0.0435em | Main title line and monumental closing invitation. |
| display-italic | Cambon | 400 italic | 92px | 1 | -0.013em | Contrasting phrase in main titles, including the opening's first line and closing's second line. |
| opening-outcome | UniversalSans | 500 | 92px | 1.2 | -0.0435em | Short changing outcome on the second line of the default opening. |
| heading | UniversalSans | 500 | 68px | 1 | -0.0588em | Chapter titles and the sans half of editorial section-name pairs. |
| heading-italic | Cambon | 400 italic | 68px | 1 | -0.0176em | Expressive second line or phrase in section headings. |
| card-title | UniversalSans | 500 | 42px | 1.05 | -0.0238em | Article titles and bottom-anchored capability names. |
| lead | UniversalSans | 500 | 36px | 1.15 | -0.014em | Large explanatory paragraphs, small section headings and unboxed conversion links. |
| index | UniversalSans | 500 | 22px | 1.15 | -0.0227em | Index labels, explanatory row text, row numbers and masthead strapline. |
| masthead-italic | Cambon | 400 italic | 22px | 1.15 | -0.0545em | Short italic finish to the small masthead sentence. |
| body | UniversalSans | 500 | 20px | 1.15 | -0.025em | Supporting paragraphs, navigation, tags, dates, portrait captions and footer utilities. |
| badge | UniversalSans | 500 | 12px | 1 | -0.042em | Tiny count inside the navigation gradient disc. |

**Notes:**

- Use the sans family’s medium cut even when the font file is registered at CSS weight 400; avoid adding a separate bold tier.
- The serif contrast is italic, not a second upright display face. Keep both halves white and let the change of construction carry the emphasis.
- Tracking is most compressed in 68px chapter headings at -4px; do not apply that value to 36px prose.
- Large prose is a principal compositional object: 36px/1.15 text can occupy up to 1020px of width; reserve 22px and 20px for quieter explanations and labels.
- Keep the serif substitute genuinely italic. If Libre Caslon Display lacks an italic in the available font delivery, use Libre Caslon Text for that family instead.

## Layout

**Density:** Airy between chapters, compact within indexes: long charcoal intervals alternate with closely stacked media and ruled rows.

### Spacing

**Spacing system:**

- **chapter rhythm** 20px, vertical — Underlying vertical rhythm for section padding, ordinary gaps and media spacing.

| Value | Use |
| --- | --- |
| 6px | Floating dock inner inset and view-control horizontal inset. |
| 10px | Tag gaps and image-to-caption spacing. |
| 20px | Media gutters, ordinary flex gaps, card inset and index row vertical padding. |
| 40px | Desktop page margins, paragraph-to-action spacing and capability-card bottom inset. |
| 60px | Chapter-heading-to-index gap and portrait-grid row gap. |
| 80px | Spacious multi-column proof-grid separation. |
| 100px | Detail-title-to-lead gap. |
| 120px | Closing invitation-to-utility-row gap. |
| 160px | Opening-stage vertical padding. |
| 240px | Closing section top padding. |
| 260px | Standard section bottom breathing room: 13 × 20px. |

### Containers and grids

- **main container**: max width 1361px · side padding 40px. Centered desktop container; at 1440px the visible content span is 1360px.
- **prose measure**: max width 1020px. Left-aligned lead prose occupies about three quarters of the main container, leaving a quiet right side.
- **paired project grid**: 2 columns · gap 20px. Two 670px square stages across the main desktop span; alternate these with full-width 16:9 stages.
- **editorial rail**: gap 20px. A title occupies roughly one third of the width at left; 443px-wide article cards extend horizontally to the right with continuation beyond the edge.
- **capability rail** (only for capability catalogs and related-offering sections): gap 20px. 325px square cards in a horizontally continuing rail; four full cards and a glimpse of the next fill the desktop span.
- **portrait grid** (only for people directories): 4 columns · gap 20px. Four 325px-wide portraits per desktop row, with a separate 60px vertical row gap.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | page shell | 20px |
|  | media and cards | 10px |
|  | navigation dock | 31px |
|  | active navigation | 23px |
|  | tags | 100px |
|  | menu disc | 50% |
| capability catalogs and related-offering sections | view switch | 26px |

## Surfaces and depth

### Surfaces

#### Charcoal shell · level 0

**Use:** Continuous page material beneath type, indexes and imagery.

**CSS:** `background: #1a1a1a; color: #ffffff; border-radius: 20px; box-shadow: none`

**Observed:** A softly rounded outer page layer lies over black. Individual chapters are not separated by alternating colored bands.

**Transfer:** Let typography and unusually deep spacing distinguish chapters.

#### Graphite panel · level 1

**Use:** Article cards, capability cards and media backing.

**CSS:** `background: #3b3b3b; border-radius: 10px; overflow: hidden; box-shadow: none`

**Observed:** Flat fill without a raised shadow or outline; media can cover the entire backing.

**Transfer:** Use tonal separation rather than simulated elevation.

#### Floating smoked glass · level 2

**Use:** Persistent compact navigation.

**CSS:** `background: rgba(0, 0, 0, 0.5); backdrop-filter: blur(10px); border-radius: 31px; padding: 6px`

**Observed:** The same dock reads near-black over charcoal and tinted over colorful imagery or the closing field.

**Transfer:** Limit glass to this small fixed utility, not every card.

#### Closing color field · level 0

**Use:** The signature full-width final invitation.

**CSS:** `background: linear-gradient(235deg, #004eff 0%, #710966 75%, #8e2e45 100%); color: #ffffff`

**Observed:** Broad, soft regions of blue at right, violet/plum through the middle and muted rose at lower left fill the entire closing area; white type remains crisp above it.

**Transfer:** Match the broad soft color balance; exact stops are not essential. Keep this atmospheric treatment concentrated in the closing invitation.

## Components

### Floating navigation dock

**Use:** Persistent global orientation.

**CSS:** `display: inline-flex; align-items: center; height: 58px; padding: 6px; border-radius: 31px; background: rgba(0, 0, 0, 0.5); backdrop-filter: blur(10px)`

**Text style:** `body` — UniversalSans 500 · 20px/1.15 · tracking -0.025em

**Observed:** A compact five-destination rail floats centered near the bottom edge, 30px above it, above every page section. Links are evenly centered; one carries a tiny gradient count badge.

**Transfer:** Use short destination labels and retain the low central placement instead of expanding into a top navigation bar.

### Selected navigation capsule

**Use:** Current destination inside the navigation dock.

**CSS:** `height: 46px; padding: 0px 20px; background: #ffffff; color: #1a1a1a; border-radius: 23px; display: flex; align-items: center; justify-content: center`

**Text style:** `body` — UniversalSans 500 · 20px/1.15 · tracking -0.025em

**Observed:** The white capsule sits behind the current label while other labels remain white on the glass rail; its width follows the label.

**Transfer:** Reserve white-filled pills for selected state and compact controls rather than the main conversion.

### Service menu disc

**Use:** Secondary navigation access independent of the dock.

**CSS:** `width: 46px; height: 46px; border-radius: 50%; background: #ffffff; color: #1a1a1a; display: flex; align-items: center; justify-content: center`

**Observed:** A separate lower-right fixed disc holds three small dark dots in a horizontal line. Dots are 5px circles; the group is about 21px wide.

**States:** Declared: hover changes color to #ffffff and background to linear-gradient(235deg, #004eff 0%, #710966 75%, #8e2e45 100%); focus-visible and active are unknown.

**Transfer:** Keep it visually distinct from the main conversion links.

### Editorial call link

**Use:** Principal next step after prose or a media section, and the final conversion.

**CSS:** `color: #ffffff; background: transparent; display: inline-block`

**Text style:** `lead` — UniversalSans 500 · 36px/1.15 · tracking -0.014em

**Observed:** Unboxed text stands alone. A short white dash begins the underline beneath the label rather than a permanent full-width button border. Actions follow prose after 40px; gallery actions often align right.

**Transfer:** Use one clear conversational verb phrase, not a row of filled CTA pills.

### Project stage

**Use:** Large visual proof of the product or delivered work.

**CSS:** `background: #3b3b3b; border-radius: 10px; overflow: hidden; position: relative`

**Observed:** Whole clickable stages alternate wide landscape and square formats; the composed image fills the stage. Some dark interface scenes visually merge into the canvas while other stages provide saturated or pale contrasting backdrops.

**Transfer:** Keep the outer frame simple and put visual complexity inside the artwork, not into extra surrounding card chrome.

### Ruled index row

**Use:** Compact overview of capabilities, process steps or additional proof.

**CSS:** `border-bottom: 1px solid #606060; color: #ffffff`

**Text style:** `index` — UniversalSans 500 · 22px/1.15 · tracking -0.0227em

**Observed:** A flex inner row uses 20px vertical padding, 20px gaps and space-between alignment. Titles sit left, explanations toward the right and two-digit numbers flush to the outer right. A matching top rule caps the entire list; rows are about 66px high.

**Transfer:** Remove the description column for a simpler numbered approach list; remove numbers for a project archive.

### Editorial article card

**Use:** Linked thought-leadership or update content.

**CSS:** `background: #3b3b3b; border-radius: 10px; overflow: hidden; padding: 20px; display: flex; flex-direction: column`

**Text style:** `card-title` — UniversalSans 500 · 42px/1.05 · tracking -0.0238em

**Observed:** Tags wrap across the top, a substantial headline follows after 48px, and a small date anchors the bottom. Cards are about 443px wide and 434px high in a continuing horizontal rail.

**Transfer:** Keep the date and category metadata quiet; let the title be the main visual rather than adding decorative images to every article.

### Category tag

**Use:** Compact category metadata inside editorial cards.

**CSS:** `background: #1a1a1a; color: #ffffff; border-radius: 100px; padding: 8px 24px; display: flex; align-items: center`

**Text style:** `body` — UniversalSans 500 · 20px/1.15 · tracking -0.025em

**Observed:** Dark capsules wrap with 10px gaps across the top of the lighter graphite panel.

**Transfer:** Use a few meaningful categories rather than dense keyword clouds.

### Masthead signature

**Use:** Small opening identity opposite the wordmark.

**CSS:** `display: flex; align-items: flex-end; color: #ffffff`

**Text style:** `index` — UniversalSans 500 · 22px/1.15 · tracking -0.0227em

**Observed:** A short sans sentence ends with an italic serif word using masthead-italic. It sits at upper left while a small white script-style identity mark sits at upper right; the line is not a navigation menu.

**Transfer:** Keep a compact verbal signature and the new product's own identity; do not enlarge them into a second headline.

### Navigation count disc

**Use:** Small live count attached to a destination label.

**CSS:** `width: 20px; height: 20px; border-radius: 50%; background: linear-gradient(200deg, #004eff 0%, #710966 75%, #8e2e45 100%); display: flex; align-items: center; justify-content: center; color: #ffffff`

**Text style:** `badge` — UniversalSans 500 · 12px/1 · tracking -0.042em

**Observed:** The colored badge overlaps the upper-right end of the destination word like a superscript.

**Transfer:** Use only for a real count; keep the visual size tiny.

### Capability tile

**Only for:** capability catalogs and related-offering sections

**Use:** Large navigable overview of distinct offerings.

**CSS:** `background: #3b3b3b; border-radius: 10px; padding: 20px 20px 40px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `card-title` — UniversalSans 500 · 42px/1.05 · tracking -0.0238em

**Observed:** A square 325px tile puts its title at the bottom with generous quiet space above. An overview tile can carry a small category tag at its top. A horizontal rail shows continuation off the right side.

**Transfer:** Use short two-line names, not descriptions competing with the title.

### View switch

**Only for:** capability catalogs and related-offering sections

**Use:** Switch between tile and list presentations.

**CSS:** `display: inline-flex; align-items: center; width: 130px; height: 52px; padding: 0px 6px; border: 1px solid #ffffff; border-radius: 26px`

**Observed:** Two equal icon targets show grid and list; the selected target has a white 58×38px capsule with 20px corners, dark icon and no text label.

**Transfer:** Retain accessible names even though the visible control is icon-only.

## Imagery and graphics

### Composed product proof

**Use:** Major visual punctuation between text-led chapters.

**Observed:** Interfaces are presented as designed compositions, not raw edge-to-edge browser dumps: a centered dark dashboard, overlapping editorial cards with forest and landscape photographs on acid yellow, tall mobile interfaces beside a rendered physical product, or paired smaller screens on pale and dark backings. Objects sit front-on or in restrained perspective with substantial surrounding air. Wide 16:9 and square stages carry far more area than captions.

**Transfer:** Use real product flows, a small cluster of interface fragments and, where relevant, a physical product rendering. Preserve deliberate overlap and generous negative space. Minimum version: one high-resolution interface screen centered at roughly two thirds of the stage width on a flat contrasting product color.

### Closing atmosphere

**Use:** Full-bleed signature graphic behind the final invitation.

**Observed:** A continuous soft blend shifts from rose/plum at lower left through violet to electric blue on the right. There are no hard facets, grain or illustrated objects; the saturation provides the finale after the long neutral body.

**Transfer:** Keep the field broad and simple so the two-line white invitation remains the dominant object.

**Build:** Cover the section with a linear-gradient at 235deg using #004eff at 0%, #710966 at 75%, and #8e2e45 at 100%. If needed for the softer broad balance, layer a very large radial-gradient of rgba(0,78,255,0.25) fading to transparent at the upper-right. Do not add small glowing blobs or a star field.

### Monochrome trust marks

**Use:** Compact visual social proof between larger chapters.

**Observed:** Small white client and partner marks sit directly on charcoal in a loose multi-row grid, with markedly more breathing room than a dense sponsor strip. A 36px heading introduces the field.

**Transfer:** Use authorized customer, integration or certification marks in monochrome white; keep their apparent visual weights balanced rather than forcing identical widths.

### Everyday portrait wall

**Only for:** people-led stories and directories

**Use:** Human proof and culture sections.

**Observed:** Natural-color 5:7 portraits mix seated, standing and casual environmental views: offices, travel, outdoor walls and personal settings. People are not cut out or standardized onto studio backgrounds. Frames have square corners, with a white 20px name and muted-gray 20px role below. The directory uses four columns; the shorter people rail runs beyond both viewport edges.

**Transfer:** Request individual environmental photographs with varied candid framing but a consistent portrait ratio. Keep natural light and authentic color; use 10px caption separation and 60px between directory rows.

### Luminous brand vignette

**Only for:** project proof with abstract brand identities

**Use:** A self-contained square project-art variant.

**Observed:** A translucent cyan-green orbital ring floats on a deep navy backing around a centered white identity. Soft overlapping edge loops and a bright lower rim create a glassy, luminous depth; the scene stays inside one project stage.

**Transfer:** Use an abstract identity vignette only when it genuinely represents the product's brand. Keep it out of the default typographic opening.

**Build:** Inside a square stage, center a circular SVG occupying about 70% of the frame. Layer three slightly offset elliptical strokes in rgba(255,255,255,0.12), rgba(0,78,255,0.35) and rgba(255,255,255,0.3), blur the broad back strokes by 12px, and add a narrower pale highlight along the lower-left arc. Place the product mark above the loops. Match the soft luminous depth; exact hues belong to the project identity.

### Icons

**Observed:** Utility glyphs are minimal outlines: white directional arrows around 32px with 3px butt-ended strokes; the view switch uses 18px dark grid and 24px white list symbols with 2px rounded strokes. The service-menu icon is three filled dots, not a hamburger.

**Transfer:** Choose simple outline arrows, grid and list glyphs without decorative containers. Preserve the white/dark inversion inside selected capsules.

## Section recipes

How recurring sections are built.

### First screen: Typographic pause opening

**Observed:** A 900px charcoal stage holds a two-line left-aligned statement around the vertical middle, spanning about three fifths of the desktop width rather than centering across it. The first line is display-italic; the short second-line outcome is opening-outcome. Both are white. Layers run from Charcoal shell to type, the small Masthead signature at upper left and compact identity at upper right, then the fixed Floating navigation dock near the lower center and Service menu disc at lower right. No product object or filled conversion button competes with the statement. Within the first 900px the masthead, both headline lines and both navigation devices are visible; the 36px introductory paragraph and first proof stage begin below the fold. The changing outcome stays in a clipped text slot, but the resting line sits directly beneath the italic phrase.

**Transfer:** Write a compact transformative premise followed by one concrete outcome, using the type contrast as the main artwork; this needs no hero media. Inner category and detail pages reverse the pairing to sans first and italic second, add a small back arrow, and can place a 36px support paragraph 100px below the title. Portfolio openings use a short title pair with a small asterisk note; people-led openings use a concise identity statement.

**Avoid:** Do not replace this pause with a centered SaaS headline, two bright CTA pills and a giant dashboard above the fold; do not preserve displaced letters from a changing-text transition.

**Text style:** `display-italic` — Cambon 400 italic · 92px/1 · tracking -0.013em

### Editorial explanation

**Observed:** A left-aligned heading uses heading, sometimes followed by heading-italic; lead prose begins 40px later within the 1020px Prose measure. An Editorial call link can follow after another 40px. Standard chapter bottom space is 260px.

**Transfer:** Use one developed idea per block and let the right side remain empty. Longer low-priority explanation can use index rather than lead.

### Proof stage sequence

**Observed:** A lead-sized section label sits 20px above Project stage frames. A full-width 1360×765 stage can be followed by a pair of 670×670 stages and another wide stage, with 20px gutters. An Editorial call link follows with 40px separation, often aligned right.

**Transfer:** Vary frame scale to give flagship proof more weight than supporting examples; the media composition itself should explain the work.

### Ruled breadth index

**Observed:** A heading introduces a full-width list after 60px. Ruled index row repeats beneath a top hairline with no enclosing panel. The desktop default has title, right-aligned description and two-digit number; process variants keep only the title and number, archives omit the number.

**Transfer:** Use the same structure for features, outcomes, integrations or process steps without turning every item into a raised card.

**Text style:** `index` — UniversalSans 500 · 22px/1.15 · tracking -0.0227em

### Trust-mark field

**Observed:** A lead-sized heading introduces small monochrome marks arranged across roughly the left three quarters of the container, in several spacious rows on bare charcoal. The surrounding chapter keeps the 260px lower breathing room.

**Transfer:** Use a curated, visually balanced set of legitimate proof marks rather than a full-width noisy logo conveyor.

### Editorial reading rail

**Observed:** A two-line sans/italic section title occupies the left third, vertically centered against an extending row of Editorial article cards. Cards sit 20px apart and can continue beyond the right edge; previous/next arrow controls appear above the rail.

**Transfer:** Give news or educational content a compact literary identity distinct from product proof; use Category tag and a bottom-aligned date.

### Monumental final invitation

**Observed:** Closing color field fills the full width. A two-line display/display-italic invitation sits at left, occupying roughly three fifths of the content span, with a single Editorial call link centered vertically in the remaining area. Top padding is 240px and bottom padding 140px. After 120px, one body-sized utility row places copyright left, legal/social links near the middle, and an editorial destination right. The navigation dock and menu disc remain floating in front.

**Transfer:** Close with an inviting, product-specific next step that fits in two lines and one short link. Keep the signature colorful material even if the body contains little visual proof.

**Text style:** `display` — UniversalSans 500 · 92px/1 · tracking -0.0435em

### People rail and directory

**Only for:** people-led stories and directories

**Observed:** The short version places a lead heading above a horizontally overflowing row of portrait images about 345×483px, with 20px gaps and two lines of body-sized captions. The directory version uses four 325×455px images per row, 20px horizontal gutters and 60px vertical row gaps. Captions remain outside the pictures.

**Transfer:** Choose a rail for a small supporting team introduction and a grid for a dedicated directory. Let individual photographs carry personality.

### Capability explorer

**Only for:** capability catalogs and related-offering sections

**Observed:** A heading and optional lead paragraph introduce the View switch. A Capability tile rail begins 40px below the control. Four square tiles plus a continuation hint fill the desktop span; the alternative presentation uses the ruled index language.

**Transfer:** Offer two genuinely useful views of the same content rather than unrelated tabs; keep tile names short.

### Topic current

**Only for:** long-form capability detail pages

**Observed:** Three full-width rows of 36px keywords interleaved with occasional colorful emoji move beyond the page edges, separated vertically by about 8px. The words repeat in opposing horizontal directions, directly on charcoal without a panel.

**Transfer:** Use a restrained topic vocabulary to convey breadth and energy; substitute relevant simple emoji rather than building a branded sticker library.

**Text style:** `lead` — UniversalSans 500 · 36px/1.15 · tracking -0.014em

## Page flow

**Storyline:** A spacious typographic promise opens into explanation, tangible proof and indexed breadth; trust or human perspective supports the argument before an oversized colorful invitation.

### Broad marketing landing page

1. **Promise** — A two-line italic-to-sans transformative statement on an otherwise empty charcoal stage.
2. **Positioning** — A large left-aligned paragraph with a plain conversational next-step link.
3. **Product proof** — Mixed-scale composed project stages introduced by a modest label.
4. **Capability breadth** — Large chapter heading and a fine-ruled numbered index, then a quieter explanatory paragraph.
5. **Trust and human context** — Monochrome trust-mark grid and a candid portrait rail.
6. **Continuing conversation** — Editorial title pair beside graphite article cards.
7. **Closing call** — Full-width saturated gradient, monumental invitation and low utility row.

**Transfer:** Use the spacious default opening, then choose proof and breadth blocks that support the new product's strongest argument; retain the contrasting final invitation.

### Focused capability or product-detail page

1. **Specific promise** — Back arrow, sans/italic title pair and 36px explanatory prose within the opening stage.
2. **Topic breadth** — Three keyword-and-emoji currents on bare charcoal.
3. **Method** — A four-row numbered approach index.
4. **Use-case explanation** — Paired heading and a substantial large-type paragraph, followed by a small tool-mark field.
5. **Conversion prompt** — A question heading, support paragraph and conversational text link.
6. **Relevant proof** — Two square project stages with a link to the larger archive.
7. **Related pathways** — A capability rail with grid/list switch.
8. **Closing call** — The shared colorful monumental invitation and utility footer.

**Transfer:** Develop one focused promise through method, application and specific proof; use related pathways only after the reader understands the subject.

### Portfolio or customer-story index

1. **Editorial hook** — Sans/italic two-line statement, then a small asterisk note.
2. **Visual proof** — An extended sequence of wide and paired square composed project stages.
3. **Archive breadth** — A large heading above compact title-and-description index rows.
4. **Social proof** — White trust marks directly on charcoal.
5. **Capability connection** — The numbered service index and editorial reading rail.
6. **Closing call** — The shared gradient invitation and utility row.

**Transfer:** Prioritize compelling visual examples, then use the ruled archive for breadth instead of giving every example an equally large frame.

### Offering catalog

1. **Orientation** — Back arrow above a spare sans/italic category title.
2. **Breadth** — Large explanation, view switch and square capability-tile rail.
3. **Method and detail** — Quiet support paragraph and long ruled service index.
4. **Product proof** — Two square selected project stages.
5. **Trust** — Industry-spanning explanation and monochrome marks.
6. **Point of view** — A large paragraph with a conversational editorial link.
7. **Closing call** — The shared gradient invitation and utility footer.

**Transfer:** Pair a visual entry into the catalog with a compact index for practical scanning; use proof to connect the catalog to outcomes.

### People and company story

1. **Identity** — A short sans/italic declaration on a spacious charcoal opening.
2. **Introduction** — Large prose introduces the people behind the work.
3. **Human proof** — An extensive four-column candid portrait grid with name and muted role captions.
4. **Operating perspective** — Large explanatory prose about how the organization works.
5. **Capability connection** — The same numbered index used elsewhere.
6. **Continuing conversation** — Editorial title pair and article-card rail.
7. **Closing call** — The shared colorful invitation and low utility row.

**Transfer:** Let real people and their environments carry this page type; link their perspective back to useful capabilities rather than adding generic culture slogans.

## Writing

Confident and thoughtful, but warmly collaborative rather than triumphalist. It connects creative ambition to usefulness through clear explanations and inviting next steps.

**Do not copy:** Do not reuse the brand name, wordmark, strapline, customer names, project artwork, staff identities, proprietary claims, dates or project counts. Source examples illustrate voice and structure only, not reusable product copy.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Together is a recurring bridge between the two; utility labels can remain neutral.
- **Rhythm:** Short headline phrases contrast with developed multi-sentence explanatory paragraphs. Lists compress information into labels and slash-separated concepts; actions read as natural spoken invitations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A short premise and a contrasting outcome or completion, often split across sans and italic lines. | 3–8 words | “We transform ideas into”<br>“We love,”<br>“what* we do” |
| Section heading | Direct editorial label or a plain question; no forced cleverness in functional indexes. | 2–7 words | “Our Approach”<br>“Partners, Clients, Friends.”<br>“Ready for the next step?” |
| Supporting line | Explain the human or business purpose before naming the implementation; use balanced phrases and an occasional dash. | 25–65 words | “Our work is based on strategies and concepts that equally prioritize the needs of businesses and users. This results in customised solutions that impact people – and drive companies forward.” |
| Primary action | A short conversational invitation or a literal destination rather than a hard sell. | 1–4 words | “Curious? Let's talk.”<br>“More about us”<br>“All cases” |
| Index description | Concrete scope in a short noun phrase, or a slash-separated trio of activities. | 3–10 words | “Vision / Objectives / Scaling”<br>“Workshops / Scoping / Specifications” |
| Closing invitation | A collective invitation with an expressive second line. | 6–10 words | “Join us on this exciting journey.” |

**Words and phrasing to use:** together; thoughtful; people; experience; ideas; concepts; relevance; from idea to implementation; real needs

**Avoid:** crush the competition; 10x everything; revolutionary game-changer; unlock limitless potential; hurry, act now

**Rules:**

- Explain how the product connects people, intent and outcomes, not just which technology it uses.
- Use compact literal names for catalog items, and reserve more expressive wording for editorial titles.
- Use questions sparingly at decision points; follow them with an answer and one action.
- Keep source-language mixtures out of new copy; maintain one coherent language and spelling convention.
- Do not turn the friendly tone into exclamation-heavy enthusiasm.

## Do's and Don'ts

### Do

- Keep the default hero at 92px, with a serif italic premise and a short medium-sans outcome.
- Preserve 40px desktop side margins and 20px image gutters.
- Separate major chapters with 260px of lower breathing room while keeping their internal content tightly related.
- Use 1px #606060 rules and 22px/1.15 text for breadth indexes.
- Use 10px corners on composed media and graphite editorial cards.
- Keep the navigation dock compact at 58px high with a 46px selected capsule.
- Give article headlines 42px/1.05 type and place dates at the bottom.
- Retain the saturated closing field and the 92px two-font invitation even on text-led pages.

### Don't

- Do not use pure black as the main visible reading canvas; the body is #1a1a1a.
- Do not introduce 700-weight headline typography; contrast comes from family and italics, not boldness.
- Do not turn every capability row into a rounded box; the 66px ruled ledger is the default breadth treatment.
- Do not apply glass blur to article cards or media; blur belongs to the small floating navigation.
- Do not add drop shadows around graphite cards; their tonal fill provides separation.
- Do not round candid portrait photographs to 10px or circles; people imagery keeps straight corners.
- Do not scatter the blue/plum gradient through every section or every text link.
- Do not force project artwork into one identical mockup template; mix wide and square stages with intentional composition.

## Motion and responsive

### Motion

**Observed:**

- Declared tag transitions use color and background-color over 0.1s ease.
- Declared card transitions use transform and color over 0.2s ease; view-switch selection uses transform over 0.2s ease.
- The active navigation layer declares a 0.3s ease fade-in.
- Three-dot utility animation is declared as a 15s ease infinite jumping-dots loop.
- Detail-page keyword currents declare linear marquee and reversed-marquee animations with periods around 83.1s–83.6s.
- The opening outcome changes within an overflow-hidden text slot.

**Transfer:**

- Keep the default opening's dynamic word confined to its own line so changing copy does not move the whole composition.
- Keep keyword motion specific to the topic-current variant, with opposing directions and a slow continuous speed.
- Preserve short control feedback rather than giving ordinary tags and cards theatrical entrances.

**Unknown:**

- Exact outcome-cycle timing, scroll-entry choreography and three-dot keyframe geometry are not specified.
- No custom easing curve or focus-visible behavior is established.

### Responsive

**Observed:**

- Declared width breakpoints are 524px, 768px, 1024px, 1250px and 1441px.
- Portrait-directory CSS uses repeat(auto-fill, minmax(300px, 1fr)).

**Transfer:**

- On narrow screens, preserve the typographic two-line contrast and left alignment; reduce headline size enough to avoid unintended third-line fragments.
- Stack the paired proof stages while retaining their square framing; allow capability and article rails to remain horizontally browsable.
- Let the closing invitation and action stack, and wrap utility links without competing with the fixed dock.
- Keep index titles readable by moving descriptions under their labels when three columns no longer fit.

**Unknown:**

- Exact narrow-screen type sizes, side insets, dock adaptation and breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
